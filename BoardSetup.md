# Design Rules

## Constraints

| Setting                       | Value   | OSH Park  | PCBWay    |
|-------------------------------|--------:|----------:|----------:|
| Copper                        |         |           |           |
|   Minimum clearance           | 0.20 mm | 0.1524 mm | 0.1016 mm |
|   Minimum clearance         † | 0.15 mm | 0.1524 mm | 0.1016 mm |
|   Minimum track width         | 0.20 mm | 0.1524 mm | 0.1016 mm |
|   Minimum connection width    | 0.20 mm |      -    |      -    |
|   Minimum annular width       | 0.15 mm | 0.1270 mm | 0.1524 mm |
|   Minimum via diameter        | 0.60 mm | 0.5080 mm | 0.5048 mm |
|   Copper to hole clearance    | 0.25 mm |      -    |      -    |
|   Copper to edge clearance    | 0.40 mm | 0.3810 mm | 0.2500 mm |
|   Copper to edge clearance  † | 0.30 mm | 0.3810 mm | 0.2500 mm |
| Holes                         |         |           |           |
|   Minimum through hole        | 0.30 mm | 0.2540 mm |      -    |
|   Hole to hole clearance      | 0.42 mm |      -    | 0.4064 mm |
| uVias                         |         |           |           |
|   Minimum uVia diameter       | 0.51 mm |      -    |      -    |
|   Minimum uVia hole           | 0.30 mm |      -    |      -    |
| Silkscreen                    |         |           |           |
|   Minimum item clearance      | 0.00 mm |      -    |      -    |
|   Minimum text height         | 0.80 mm |      -    | 0.8000 mm |
|   Minimum text thickness      | 0.15    |      -    | 0.1500 mm |
|                               |         |           |           |
| Solder mask/paste             |         |           |           |
|   Solder mask expansion       | 0.05 mm |           |           |
|                               |         |           |           |
| Copper zone                   |         |           |           |
|   Clearance                   | 0.30 mm |           |           |
|   Minimum width               | 0.30 mm |           |           |
|   Pad connections             | None    |           |           |
|   Thermal relief gap          | 0.50 mm |           |           |
|   Thermal spoke width         | 0.50 mm |           |           |

† Framework expansion card settings


## Predefined Sizes

| Track width | 0.5 oz, 5 °C | 0.5 oz, 10 °C | 0.5 oz, 20 °C | 1.0 oz, 20 °C | 2.0 oz, 20 °C |
|------------:|-------------:|--------------:|--------------:|--------------:|--------------:|
|     0.20 mm |       0.60 A |        0.85 A |        1.15 A |        1.35 A |        1.60 A |
|     0.25 mm |       0.70 A |        1.00 A |        1.35 A |        1.55 A |        1.85 A |
|     0.30 mm |       0.80 A |        1.10 A |        1.50 A |        1.75 A |        2.15 A |
|     0.40 mm |       1.00 A |        1.35 A |        1.80 A |        2.10 A |        2.60 A |
|     0.50 mm |       1.15 A |        1.55 A |        2.10 A |        2.45 A |        3.00 A |
|     0.60 mm |       1.25 A |        1.70 A |        2.35 A |        2.75 A |        3.40 A |
|     0.70 mm |       1.40 A |        1.90 A |        2.55 A |        3.00 A |        3.75 A |
|     0.80 mm |       1.50 A |        2.05 A |        2.80 A |        3.25 A |        4.10 A |
|     0.90 mm |       1.60 A |        2.20 A |        3.00 A |        3.50 A |        4.40 A |
|     1.00 mm |       1.70 A |        2.35 A |        3.20 A |        3.75 A |        4.70 A |
|     1.10 mm |       1.85 A |        2.50 A |        3.40 A |        3.95 A |        4.95 A |
|     1.20 mm |       1.90 A |        2.60 A |        3.55 A |        4.15 A |        5.25 A |
|     1.30 mm |       2.00 A |        2.75 A |        3.75 A |        4.40 A |        5.50 A |
|     1.40 mm |       2.10 A |        2.85 A |        3.90 A |        4.60 A |        5.75 A |
|     1.50 mm |       2.20 A |        3.00 A |        4.05 A |        4.75 A |        6.00 A |
|     1.60 mm |       2.30 A |        3.10 A |        4.25 A |        4.95 A |        6.25 A |
|     1.70 mm |       2.35 A |        3.20 A |        4.40 A |        5.15 A |        6.45 A |
|     1.80 mm |       2.45 A |        3.35 A |        4.55 A |        5.30 A |        6.70 A |
|     1.90 mm |       2.55 A |        3.45 A |        4.70 A |        5.50 A |        6.90 A |
|     2.00 mm |       2.60 A |        3.55 A |        4.80 A |        5.65 A |        7.15 A |
|     2.10 mm |       2.70 A |        3.65 A |        4.95 A |        5.85 A |        7.35 A |
|     2.20 mm |       2.75 A |        3.75 A |        5.10 A |        6.00 A |        7.55 A |
|     2.30 mm |       2.85 A |        3.85 A |        5.25 A |        6.15 A |        7.75 A |
|     2.40 mm |       2.90 A |        3.95 A |        5.35 A |        6.30 A |        7.95 A |
|     2.50 mm |       3.00 A |        4.05 A |        5.50 A |        6.45 A |        8.15 A |
|     2.60 mm |       3.05 A |        4.15 A |        5.65 A |        6.60 A |        8.35 A |
|     2.70 mm |       3.10 A |        4.25 A |        5.75 A |        6.75 A |        8.50 A |
|     2.80 mm |       3.20 A |        4.35 A |        5.90 A |        6.90 A |        8.70 A |
|     2.90 mm |       3.25 A |        4.40 A |        6.00 A |        7.05 A |        8.90 A |
|     3.00 mm |       3.30 A |        4.50 A |        6.15 A |        7.20 A |        9.10 A |

| Via diameter | Via hole |   5 °C |  10 °C |  20 °C |
|-------------:|---------:|-------:|-------:|-------:|
|       0.6 mm |   0.3 mm | 1.15 A | 1.55 A | 2.15 A |
|       0.8 mm |   0.4 mm | 1.35 A | 1.85 A | 2.50 A |
|       1.0 mm |   0.5 mm | 1.55 A | 2.10 A | 2.85 A |
|       1.2 mm |   0.6 mm | 1.70 A | 2.30 A | 3.15 A |
|       1.4 mm |   0.7 mm | 1.85 A | 2.50 A | 3.40 A |
|       1.6 mm |   0.8 mm | 2.00 A | 2.70 A | 3.70 A |
|       1.8 mm |   0.9 mm | 2.15 A | 2.90 A | 3.95 A |
|       2.0 mm |   1.0 mm | 2.25 A | 3.10 A | 4.20 A |


## Net Classes

| Name     | Clearance | Track width | Via size | Via hole | uVia size | uVia hole | DP width |  DP gap |
|----------|----------:|------------:|---------:|---------:|----------:|----------:|---------:|--------:|
| Default  |   0.20 mm |     0.25 mm |  0.80 mm |  0.40 mm |   0.60 mm |   0.30 mm |  0.20 mm | 0.25 mm |
| Power    |   0.20 mm |     0.40 mm |  1.00 mm |  0.50 mm |   0.60 mm |   0.30 mm |  0.20 mm | 0.25 mm |
| 120 V    |   0.60 mm |     0.40 mm |  1.00 mm |  0.50 mm |   0.60 mm |   0.30 mm |  0.20 mm | 0.25 mm |
| 240 V    |   1.25 mm |     0.40 mm |  1.00 mm |  0.50 mm |   0.60 mm |   0.30 mm |  0.20 mm | 0.25 mm |
| 500+ V   |   2.60 mm |     0.40 mm |  1.00 mm |  0.50 mm |   0.60 mm |   0.30 mm |  0.20 mm | 0.25 mm |


---


### Mill/mm conversion table

|  mil |     mm |
|-----:|-------:|
|    4 | 0.1016 |
|    5 | 0.1270 |
|    6 | 0.1524 |
|    7 | 0.1778 |
| *  8 | 0.2032 |
|    9 | 0.2286 |
| * 10 | 0.2540 |
|   11 | 0.2794 |
| * 12 | 0.3048 |
|   13 | 0.3302 |
|   14 | 0.3556 |
|   15 | 0.3810 |
| * 16 | 0.4064 |
|   17 | 0.4318 |
|   18 | 0.4572 |
|   19 | 0.4826 |
| * 20 | 0.5080 |
