### MIDNIGHTS analysis/bewest-pump/ReadHistoryData-page-27.data.list_opcodes.markdown: 4
## START logs/ReadHistoryData-page-27.data
#### STOPPING DOUBLE NULLS @ 1017, found 5 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xec 0xf6                                  ..
##### DEBUG DECIMAL
            236  246
#### RECORD 0 PumpSuspend 2012-10-15T18:08:47 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x00                                  ..
    decimal
             30    0
    datetime (2012-10-15T18:08:47)
    0000   0xaf 0x88 0x12 0x0f 0x0c                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 1 PumpResume 2012-10-15T18:31:07 head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0x00                                  ..
    decimal
             31    0
    datetime (2012-10-15T18:31:07)
    0000   0x87 0x9f 0x12 0x0f 0x0c                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 2 CalBGForPH 2012-10-15T18:36:06 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 154}
```
    op hex (2)
    0000   0x0a 0x9a                                  ..
    decimal
             10  154
    datetime (2012-10-15T18:36:06)
    0000   0x86 0xa4 0x32 0x0f 0x0c                   ..2..
    body (0)
--
    0000   0x0a 0x08                                  ..
    decimal
             10    8
    datetime (2012-10-15T21:33:41)
    0000   0xa9 0xa1 0x35 0x0f 0x8c                   ..5..
    body (0)
    HOUR BITS: [1, 0, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 27 CalBGForPH 2012-10-15T22:12:34 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 227}
```
    op hex (2)
    0000   0x0a 0xe3                                  ..
    decimal
             10  227
    datetime (2012-10-15T22:12:34)
    0000   0xa2 0x8c 0x36 0x0f 0x0c                   ..6..
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 28 ResultTotals 2012-08-15T13:12:47 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x07 0xa0                   .....
    decimal
              7    0    0    7  160
    datetime (2012-08-15T13:12:47)
    0000   0xaf 0x0c 0x6d 0xaf 0x0c                   ..m..
    body (41)
    hex
    0000   0x05 0x11 0x33 0x9a 0xbc 0x0d 0x00 0x00    ..3.....
    0008   0x07 0xa0 0x03 0xa0 0x30 0x04 0x00 0x34    ....0..4
    0010   0x00 0x8a 0x04 0x00 0x34 0x01 0xa0 0x29    ....4..)
    0018   0x02 0x60 0x3b 0x00 0x00 0x00 0x08 0x03    .`;.....
    0020   0x04 0x01 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5   17   51  154  188   13    0    0
              7  160    3  160   48    4    0   52
              0  138    4    0   52    1  160   41
              2   96   59    0    0    0    8    3
              4    1    0   12    0  232    0    0
              0
    DAY BITS: [1, 0, 1]
#### RECORD 29 CalBGForPH 2012-10-16T01:12:23 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 77}
```
    op hex (2)
    0000   0x0a 0x4d                                  .M
    decimal
             10   77
    datetime (2012-10-16T01:12:23)
    0000   0x97 0x8c 0x21 0x10 0x0c                   ..!..
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 30 BolusWizard 2012-10-16T14:10:39 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 0,
--
    decimal
             92   11   72   48    4   52  238    4
             24   72   20
    datetime (unknown)

    body (0)

#### RECORD 42 Bolus 2012-10-16T19:32:04 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 2.3, 'dual_component': '??', 'programmed': 2.3, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x17 0x17 0x00                        ....
    decimal
              1   23   23    0
    datetime (2012-10-16T19:32:04)
    0000   0x84 0xa0 0x53 0x10 0x0c                   ..S..
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 43 ResultTotals 2012-08-16T13:12:48 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0x64                   ....d
    decimal
              7    0    0    4  100
    datetime (2012-08-16T13:12:48)
    0000   0xb0 0x0c 0x6d 0xb0 0x0c                   ..m..
    body (41)
    hex
    0000   0x05 0x00 0x4d 0x4d 0x4d 0x01 0x00 0x00    ..MMM...
    0008   0x04 0x64 0x03 0x74 0x4f 0x00 0xf0 0x15    .d.tO...
    0010   0x00 0x52 0x00 0xf0 0x15 0x00 0xf0 0x64    .R.....d
    0018   0x00 0x00 0x00 0x00 0x00 0x00 0x04 0x04    ........
    0020   0x00 0x00 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5    0   77   77   77    1    0    0
              4  100    3  116   79    0  240   21
              0   82    0  240   21    0  240  100
              0    0    0    0    0    0    4    4
              0    0    0   12    0  232    0    0
              0
    DAY BITS: [1, 0, 1]
#### RECORD 44 ResultTotals 2012-08-17T13:12:49 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x03 0x84                   .....
    decimal
              7    0    0    3  132
    datetime (2012-08-17T13:12:49)
    0000   0xb1 0x0c 0x6d 0xb1 0x0c                   ..m..
    body (41)
    hex
    0000   0x05 0x0c 0x00 0xe8 0x00 0x00 0x00 0x00    ........
    0008   0x03 0x84 0x03 0x84 0x64 0x00 0x00 0x00    ....d...
    0010   0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00    ........
    0018   0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00    ........
    0020   0x00 0x00 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5   12    0  232    0    0    0    0
              3  132    3  132  100    0    0    0
              0    0    0    0    0    0    0    0
              0    0    0    0    0    0    0    0
              0    0    0   12    0  232    0    0
              0
    DAY BITS: [1, 0, 1]
#### RECORD 45 CalBGForPH 2012-10-18T02:34:42 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 168}
```
    op hex (2)
    0000   0x0a 0xa8                                  ..
    decimal
             10  168
    datetime (2012-10-18T02:34:42)
    0000   0xaa 0xa2 0x22 0x12 0x0c                   .."..
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 46 BolusWizard 2012-10-18T02:34:44 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 9,
--
    decimal
             92   14   64  111    4   80   55   20
            152   75   20  164  145   20
    datetime (unknown)

    body (0)

#### RECORD 68 Bolus 2012-10-18T18:35:45 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 2.7, 'dual_component': '??', 'programmed': 2.7, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x1b 0x1b 0x00                        ....
    decimal
              1   27   27    0
    datetime (2012-10-18T18:35:45)
    0000   0xad 0xa3 0x52 0x12 0x0c                   ..R..
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 69 ResultTotals 2012-08-18T13:12:50 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x05 0xd6                   .....
    decimal
              7    0    0    5  214
    datetime (2012-08-18T13:12:50)
    0000   0xb2 0x0c 0x6d 0xb2 0x0c                   ..m..
    body (41)
    hex
    0000   0x05 0x00 0x7c 0x54 0xa8 0x06 0x00 0x00    ..|T....
    0008   0x05 0xd6 0x03 0x7a 0x3c 0x02 0x5c 0x28    ...z<.\(
    0010   0x00 0xbb 0x02 0x5c 0x28 0x02 0x34 0x5d    ...\(.4]
    0018   0x00 0x28 0x07 0x00 0x00 0x00 0x06 0x04    .(......
    0020   0x01 0x01 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5    0  124   84  168    6    0    0
              5  214    3  122   60    2   92   40
              0  187    2   92   40    2   52   93
              0   40    7    0    0    0    6    4
              1    1    0   12    0  232    0    0
              0
    DAY BITS: [1, 0, 1]
#### RECORD 70 LowReservoir 2012-10-19T08:28:25 head[2], body[0] op[0x34]
###### DECODED
```python
{'amount': 20.0}
```
    op hex (2)
    0000   0x34 0xc8                                  4.
    decimal
             52  200
    datetime (2012-10-19T08:28:25)
    0000   0x99 0x9c 0x08 0x13 0x0c                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 71 PumpSuspend 2012-10-19T13:31:17 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x00                                  ..
--
    0000   0x08 0x50 0x0d 0x2d 0x6a 0x15 0x06 0x00    .P.-j...
    0008   0x00 0x00 0x00 0x1b 0x7d                   ....}
    decimal
              8   80   13   45  106   21    6    0
              0    0    0   27  125
    HOUR BITS: [1, 0, 1]
#### RECORD 79 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 27, 'amount': 1.1, 'curve': 20},
 {'age': 37, 'amount': 0.8, 'curve': 20}]
```
    op hex (8)
    0000   0x5c 0x08 0x2c 0x1b 0x14 0x20 0x25 0x14    \.,.. %.
    decimal
             92    8   44   27   20   32   37   20
    datetime (unknown)

    body (0)

`end logs/ReadHistoryData-page-27.data: 80 records`
