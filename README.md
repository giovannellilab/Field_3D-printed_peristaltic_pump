# Field_3D-printed_peristaltic_pump
Plans for the portable 3D printed peristaltic pump for field use developed in the Giovannelli Lab


# 3D printed field peristaltic pump for fluid sampling

[![forthebadge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNDUuMzc1MDE5MDczNDg2MzMiIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAyNDUuMzc1MDE5MDczNDg2MzMgMzUiPjxyZWN0IHdpZHRoPSIxNzguMjk2ODkwMjU4Nzg5MDYiIGhlaWdodD0iMzUiIGZpbGw9IiNkMWQyZDMiLz48cmVjdCB4PSIxNzguMjk2ODkwMjU4Nzg5MDYiIHdpZHRoPSI2Ny4wNzgxMjg4MTQ2OTcyNyIgaGVpZ2h0PSIzNSIgZmlsbD0iIzAwMDAwMCIvPjx0ZXh0IHg9Ijg5LjE0ODQ0NTEyOTM5NDUzIiB5PSIxNy41IiBmb250LXNpemU9IjEyIiBmb250LWZhbWlseT0iJ1JvYm90bycsIHNhbnMtc2VyaWYiIGZpbGw9IiNGRkZGRkYiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGFsaWdubWVudC1iYXNlbGluZT0ibWlkZGxlIiBsZXR0ZXItc3BhY2luZz0iMiI+Q1JFQVRJVkUgQ09NTU9OUzwvdGV4dD48dGV4dCB4PSIyMTEuODM1OTU0NjY2MTM3NyIgeT0iMTcuNSIgZm9udC1zaXplPSIxMiIgZm9udC1mYW1pbHk9IidNb250c2VycmF0Jywgc2Fucy1zZXJpZiIgZmlsbD0iI0ZGRkZGRiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZm9udC13ZWlnaHQ9IjkwMCIgYWxpZ25tZW50LWJhc2VsaW5lPSJtaWRkbGUiIGxldHRlci1zcGFjaW5nPSIyIj5CWSBOQzwvdGV4dD48L3N2Zz4=)](https://creativecommons.org/licenses/by-nc/4.0/deed.en)
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com)
[![forthebadge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMTcuODQzNzY1MjU4Nzg5MDYiIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAyMTcuODQzNzY1MjU4Nzg5MDYgMzUiPjxyZWN0IHdpZHRoPSIxMDYuNTc4MTMyNjI5Mzk0NTMiIGhlaWdodD0iMzUiIGZpbGw9IiNkMDAyMWIiLz48cmVjdCB4PSIxMDYuNTc4MTMyNjI5Mzk0NTMiIHdpZHRoPSIxMTEuMjY1NjMyNjI5Mzk0NTMiIGhlaWdodD0iMzUiIGZpbGw9IiNlMmRmZGYiLz48dGV4dCB4PSI1My4yODkwNjYzMTQ2OTcyNjYiIHk9IjE3LjUiIGZvbnQtc2l6ZT0iMTIiIGZvbnQtZmFtaWx5PSInUm9ib3RvJywgc2Fucy1zZXJpZiIgZmlsbD0iI2ZmZmZmZiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgYWxpZ25tZW50LWJhc2VsaW5lPSJtaWRkbGUiIGxldHRlci1zcGFjaW5nPSIyIj5NQURFIFdJVEg8L3RleHQ+PHRleHQgeD0iMTYyLjIxMDk0ODk0NDA5MTgiIHk9IjE3LjUiIGZvbnQtc2l6ZT0iMTIiIGZvbnQtZmFtaWx5PSInTW9udHNlcnJhdCcsIHNhbnMtc2VyaWYiIGZpbGw9IiMwMDAwMDAiIHRleHQtYW5jaG9yPSJtaWRkbGUiIGZvbnQtd2VpZ2h0PSI5MDAiIGFsaWdubWVudC1iYXNlbGluZT0ibWlkZGxlIiBsZXR0ZXItc3BhY2luZz0iMiI+M0QgUFJJTlRFUjwvdGV4dD48L3N2Zz4=)](https://forthebadge.com)
[![forthebadge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOTkuMTg3NTE1MjU4Nzg5MDYiIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAxOTkuMTg3NTE1MjU4Nzg5MDYgMzUiPjxyZWN0IHdpZHRoPSI5OS4yNjU2MzI2MjkzOTQ1MyIgaGVpZ2h0PSIzNSIgZmlsbD0iIzk2OTY5NiIvPjxyZWN0IHg9Ijk5LjI2NTYzMjYyOTM5NDUzIiB3aWR0aD0iOTkuOTIxODgyNjI5Mzk0NTMiIGhlaWdodD0iMzUiIGZpbGw9IiM3ZWQzMjEiLz48dGV4dCB4PSI0OS42MzI4MTYzMTQ2OTcyNjYiIHk9IjE3LjUiIGZvbnQtc2l6ZT0iMTIiIGZvbnQtZmFtaWx5PSInUm9ib3RvJywgc2Fucy1zZXJpZiIgZmlsbD0iI2ZmZmZmZiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgYWxpZ25tZW50LWJhc2VsaW5lPSJtaWRkbGUiIGxldHRlci1zcGFjaW5nPSIyIj5NQURFIEZPUjwvdGV4dD48dGV4dCB4PSIxNDkuMjI2NTczOTQ0MDkxOCIgeT0iMTcuNSIgZm9udC1zaXplPSIxMiIgZm9udC1mYW1pbHk9IidNb250c2VycmF0Jywgc2Fucy1zZXJpZiIgZmlsbD0iIzAwMDAwMCIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZm9udC13ZWlnaHQ9IjkwMCIgYWxpZ25tZW50LWJhc2VsaW5lPSJtaWRkbGUiIGxldHRlci1zcGFjaW5nPSIyIj5USEUgRklFTEQ8L3RleHQ+PC9zdmc+)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://forthebadge.com)

[![giovannellilab](https://img.shields.io/badge/BY-Giovannelli_Lab-blue)](http:s//www.donatogiovannelli.com)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/giovannellilab/Field_3D-printed_peristaltic_pump/graphs/commit-activity)
[![giovannellilab](https://img.shields.io/badge/Mark-II-darkred)]()


DThis GitHub repository provides the 3D printing STL files for a portable peristaltic pump. The original design of this pump is credited to PattysLab and can be found on Thingiverse [here](https://www.thingiverse.com/thing:4653708).

A peristaltic pump is a type of positive displacement pump that moves fluids through a flexible tube by squeezing and releasing it in a rolling motion. While there are several model commercially available on the web, we were looking for a compact, portable and reliable design. We made some minor mopdification to the design found on Thingiverse by Pattyslab and mounted it on a battery powered drill.

Thge entire design is very small and lightweight, and can be used to filter several liters of water (or gorup routinely filters 6 liters of hydrothermnal fluids in 3 sterivex filters) while in the field.

A new version of the pumop is currently under design (mark III).

### Credits
- Adaptation: Matteo Selci and Luciano di Iorio / Giovannelli Lab ©2022
- Original Design: [PattysLab on Thingiverse]((https://www.thingiverse.com/thing:4653708))


### License
[Creative Commons 4.0 BY NC](https://creativecommons.org/licenses/by-nc/4.0/deed.en)


Please cite as:

Selci Matteo, di Iorio Luciano, Giovannelli Donato. 2022. Field portable 3D printed peristaltic pump for fluid sampling. https://github.com/giovannellilab/Field_3D-printed_peristaltic_pump
