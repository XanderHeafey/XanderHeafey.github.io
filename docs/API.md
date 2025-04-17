---
title: API
---

# Message Structure

## Messages Sent

### Direct Drive and Speed Message

|             |Byte 1                            |Byte 2                            |
|-------------|----------------------------------|----------------------------------|
|Varable Name |Change Direction                  |Motor Speed                       |
|Variable Type|Char                              |Char                              |
|Min Value    |0                                 |1                                 |
|Max Value    |1                                 |9                                 |
|Example      |1                                 |5                                 |
|Use          |Tells motor to spin left or right.|Tells motor what speed to spin at.|

## Messages Recieved

### Distantce Data

|             |Byte 1                            |Byte 2                            |
|-------------|----------------------------------|----------------------------------|
|Varable Name |Change Direction                  |Motor Speed                       |
|Variable Type|Char                              |Char                              |
|Min Value    |0                                 |1                                 |
|Max Value    |1                                 |9                                 |
|Example      |1                                 |5                                 |
|Use          |Tells motor to spin left or right.|Tells motor what speed to spin at.|