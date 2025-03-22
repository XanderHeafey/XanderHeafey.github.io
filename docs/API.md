---
title: Block Diagram
---

# Message Structure

## Direct Drive Message

|             |Byte 1|Byte 2|
|-------------|----------------------------------|----------------------------------|
|Varable Name |Change Direction                  |Motor Speed                       |
|Variable Type|uint8_t                           |int8_t                            |
|Min Value    |0                                 |-200                              |
|Max Value    |1                                 | 200                              |
|Example      |1                                 | 100                              |
|Use          |Tells motor to spin left or right.|Tells motor what speed to spin at.|

## Desired Speed

|             |Byte 1                            |  Byte 2                          |
|-------------|----------------------------------|----------------------------------|
|Varable Name |Change Speed                      |Motor Speed                       |
|Variable Type|int8_t                            |int8_t                            |
|Min Value    |1                                 |-200                              |
|Max Value    |9                                 | 200                              |
|Example      |5                                 | 50                               |
|Use          |Tells motor to change speed       |Tells motor what speed to spin at.|