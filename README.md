<<<<<<< HEAD
# Introduction

**Ultrahigh_kappa_Carbon_Supplementary** is the repository for article "Generative Deep Learning for Discovering Ultrahigh Lattice Thermal Conductivity Materials" (npj Comput. Mater. 11, 1–10 (2025); doi: [https://doi.org/10.1038/s41524-025-01592-8](https://doi.org/10.1038/s41524-025-01592-8)). It included all **POSCAR** files of 34 carbon allotropes with ultrahigh lattice thermal conductivity (> 800 W/mK on one direction).

|Id|kappa (RTA, max) [W/mK]|kappa (RTA, tensor) [W/mK]|Prototype|
|---|---|---|---|
| 5     | 2573.37   | [**2573, 2573, 2573**, 0, 0, 0        ] | Diamond<br>[SACADA-1](https://www.sacada.info/ca_data.php?id=1)|
| 15<br>(i.e. C~18~-cfe-15) | 1783.97   | [**1784, 1462, 1454**, 8, 40, 67      ] | [SACADA-447](https://www.sacada.info/ca_data.php?id=447)|
| 94    | 1796.32   | [**1796, 1796, 1543**, 0, 0, 0        ] | Lonsdaleite<br>[SACADA-37](https://www.sacada.info/ca_data.php?id=37)|
| 172<br>(i.e. C~16~-cag-172) | 1102.62   | [**911, 910, 1103**,   0, 0, -5       ] | [SACADA-81](https://www.sacada.info/ca_data.php?id=81)|
| 208<br>(i.e. C~8~-sra-208) | 1163.57   | [**1009, 1006, 1164**, 16, -17, -132  ] | [SACADA-67](https://www.sacada.info/ca_data.php?id=67)|
| 224   | 1481.56   | [**1073, 1482, 993**,  0, 0, 198      ] | Bct-C4<br>[SACADA-60](https://www.sacada.info/ca_data.php?id=60)|
| 445   |  841.84   | [**723, 842, 840**,    0, 0, 28       ] | [SACADA-213](https://www.sacada.info/ca_data.php?id=213)|
| 532   | 1301.35   | [**784, 1301, 445**,   0, -13, 0      ] | C-80160-4880-28<br>(in CDVAE's dataset)|
| 637   |  963.70   | [**690, 964, 760**,    26, -90, 85    ] | C-113078-2193-39<br>(in CDVAE's dataset)|
| 659<br>(i.e. C~8~-cfc-659) | 1771.03   | [**1771, 1771, 1349**, 0, 0, 0        ] | [SACADA-111](https://www.sacada.info/ca_data.php?id=111)|
| 828   | 1450.68   | [**834, 852, 1451**,   0, 0, 12       ] | Z-carbon<br>[SACADA-141](https://www.sacada.info/ca_data.php?id=141)|
| 855   | 1180.36   | [**1180, 749, 474**,   0, 0, 0        ] | [SACADA-256](https://www.sacada.info/ca_data.php?id=256)|
| 877   |  822.61   | [**742, 809, 823**,    5, -29, 13     ] | [SACADA-262](https://www.sacada.info/ca_data.php?id=262)|
| 1212  | 1120.39   | [**840, 883, 1120**,   0, 0, 9        ] | [SACADA-188](https://www.sacada.info/ca_data.php?id=188)|
| 2050  |  966.59   | [**842, 838, 967**,    29, -34, 16    ] | [SACADA-570](https://www.sacada.info/ca_data.php?id=570)|
| 2643  | 1033.72   | [**799, 1034, 776**,   0, 0, 109      ] | [SACADA-619](https://www.sacada.info/ca_data.php?id=619)|
| 3099  | 1012.14   | [**1012, 754, 865**,   168, -49, 81   ] | [SACADA-568](https://www.sacada.info/ca_data.php?id=568)|
| 3546  | 1677.17   | [**1677, 1308, 1302**, 5, 33, 57      ] | [SACADA-209](https://www.sacada.info/ca_data.php?id=209)|
| 6804  | 852.06   | [**852, 852, 542**, 0, 0, 0      ] | AA T12-carbon<br>[SACADA-102](https://www.sacada.info/ca_data.php?id=102)|
| 9191<br>(i.e. C~16~-pcl-9191) | 1050.82   | [**871, 864, 1051**,   0, 0, -132     ] | [SACADA-82](https://www.sacada.info/ca_data.php?id=82)|
| 9335  | 1009.84   | [**884, 1009, 1010**,  -1, -9, -15    ] | C-176648-5645-7<br>(in CDVAE's dataset)|
| 12050 | 1345.86   | [**427, 427, 1346**,   0, 0, 0        ] | C-145335-4867-32<br>(in CDVAE's dataset)|
| 15979 |  841.69   | [**235, 206, 842**,    0, 0, -7       ] | [SACADA-514](https://www.sacada.info/ca_data.php?id=514)|
| 17469 |  838.57   | [**839, 769, 612**,    0, 0, -14      ] | -|
| 18604 | 1218.56   | [**753, 592, 1219**,   0, 0, -105     ] | [SACADA-616](https://www.sacada.info/ca_data.php?id=616)|
| 20585 |  879.76   | [**812, 805, 880**,    -2, 2, -139    ] | [SACADA-588](https://www.sacada.info/ca_data.php?id=588)|
| 31148 | 1135.06   | [**1135, 519, 478**,   0, 0, 0        ] | -|
| 62216 |  823.78   | [**824, 239, 239**,    0, 0, 0        ] | -|
| 70214 |  971.59   | [**746, 972, 784**,    8, -21, 105    ] | -|
| 84157 | 1738.54   | [**1739, 1707, 1621**, -1, 1, -23     ] | -|
| 86432 | 1130.27   | [**1130, 1067, 1066**, 1, 5, 8        ] | C-141053-1510-43<br>(in CDVAE's dataset)|
| 89645 | 1052.47   | [**311, 1052, 453**,   0, 0, 0        ] | -|
| 89688 |  931.12   | [**931, 665, 744**,    105, -40, 118  ] | -|
|C-130507-2037-23<br>(i.e. C~10~-hccch-C13)|1776.98|[**1777, 1777, 1375**, 0, 0, 0]|-|
|C-9612-1722-33|879.57|[**880, 874, 862**, -71, 57, 12      ] | [SACADA-142](https://www.sacada.info/ca_data.php?id=142)|
=======
## Introduction

Supplementary materials for article "Generative Deep Learning for Predicting Ultrahigh Lattice Thermal Conductivity Materials" (npj Comput. Mater. 11, 97 (2025). [https://doi.org/10.1038/s41524-025-01592-8](https://doi.org/10.1038/s41524-025-01592-8))
>>>>>>> 5d44fc024da5cddd37faf198b1d87db23a8bcf8e
