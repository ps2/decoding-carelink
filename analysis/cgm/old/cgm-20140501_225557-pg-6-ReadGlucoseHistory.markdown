## do stuff with an insulin pump over RF
using ` Namespace(begin=None, bytesPerRecord=None, command='tweak', descr=None, dryrun=False, effectTime=None, end=None, init=False, maxRecords=None, name=None, no_postlude=False, no_prelude=False, no_rf_prelude=False, other='ReadGlucoseHistory', page=6, params=None, port='/dev/ttyUSB0', postfix=None, prefix=None, prefix_path='logs/20140501_225557-pg-6-', save=True, saveall=False, serial='584923', verbose=None) `
```
```
```
```
```
```
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 366L,
           'packets.transmit': 380L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 524L,
         'packets.transmit': 524L}}
```
```
```
### PUMP MODEL: `ReadPumpModel:size[64]:data:'722'`
<class 'decocare.commands.ReadGlucoseHistory'> {'page': 6}
response: ReadGlucoseHistory:size[1024]:[page][0]:data[1024]:
hexdump:
```python
0000   0x42 0x42 0x42 0x41 0x41 0x41 0x41 0x41    BBBAAAAA
0008   0x41 0x41 0x41 0x41 0x40 0x3f 0x3d 0x3c    AAAA@?=<
0010   0x3a 0x3a 0x3a 0x3a 0x3a 0x3a 0x3a 0x3b    :::::::;
0018   0x3b 0x3b 0x3b 0x3c 0x3c 0x3d 0x3c 0x13    ;;;<<=<.
0020   0x3b 0x13 0x3a 0x39 0x38 0x37 0x37 0x37    ;.:98777
0028   0x37 0x38 0x38 0x39 0x3a 0x3c 0x3d 0x3d    7889:<==
0030   0x3f 0x40 0x41 0x43 0x44 0x45 0x45 0x46    ?@ACDEEF
0038   0x46 0x45 0x62 0x0e 0x01 0xda 0x08 0x0e    FEb.....
0040   0x44 0x45 0x46 0x38 0xfa 0x25 0x0e 0x01    DEF8.%..
0048   0xe9 0x08 0x0f 0x38 0x37 0x37 0x37 0x37    ...87777
0050   0x38 0x38 0x38 0x38 0x37 0x36 0x35 0x34    88887654
0058   0x34 0x35 0x37 0x3a 0x3c 0x3f 0x41 0x44    457:<?AD
0060   0x47 0x49 0x4c 0x13 0x4e 0x13 0x52 0x55    GIL.N.RU
0068   0x58 0x59 0x59 0x59 0x59 0x58 0x58 0x5a    XYYYYXXZ
0070   0x5c 0x5e 0x5f 0x5f 0x5e 0x5b 0x58 0x54    \^__^[XT
0078   0x50 0x4d 0x49 0x46 0x44 0x43 0x42 0x40    PMIFDCB@
0080   0x3e 0x3c 0x3a 0x38 0x37 0x36 0x35 0x35    ><:87655
0088   0x13 0x35 0x37 0x38 0x38 0x38 0x38 0x38    .5788888
0090   0x13 0x38 0x37 0x37 0x37 0x37 0x38 0x38    .8777788
0098   0x38 0x38 0x38 0x38 0x37 0x36 0x35 0x36    88887656
00A0   0x38 0x39 0x3a 0x3a 0x3a 0x39 0x37 0x66    89:::97f
00A8   0x0e 0x01 0xc4 0x10 0x0e 0x36 0x34 0x33    .....643
00B0   0xbc 0x25 0x0e 0x01 0xd0 0x10 0x0f 0x33    .%.....3
00B8   0x33 0x33 0x33 0x34 0x35 0x37 0x38 0x38    33345788
00C0   0x39 0x39 0x13 0x39 0x13 0x39 0x39 0x38    99.9.998
00C8   0x37 0x38 0x38 0x38 0x37 0x36 0x34 0x33    78887643
00D0   0x32 0x31 0x33 0x34 0x34 0x36 0x38 0x39    21344689
00D8   0x39 0x38 0x39 0x3a 0x3c 0x3e 0x3f 0x41    989:<>?A
00E0   0x44 0x47 0x4a 0x4c 0x4e 0x4e 0x4d 0x4b    DGJLNNMK
00E8   0x4b 0x4c 0x4d 0x4d 0x4d 0x4e 0x4f 0x4f    KLMMMNOO
00F0   0x4f 0x4e 0x4b 0x49 0x46 0x43 0x41 0x40    ONKIFCA@
00F8   0x40 0x40 0x3f 0x3e 0x3c 0x3c 0x3b 0x3b    @@?><<;;
0100   0x3c 0x3d 0x3d 0x3c 0x3c 0x3c 0x3a 0x38    <==<<<:8
0108   0x7b 0x0e 0x01 0xf6 0x16 0x0e 0x39 0x39    {.....99
0110   0x3c 0x91 0x27 0x0e 0x01 0xc7 0x17 0x0f    <.'.....
0118   0x3a 0x39 0x37 0x35 0x34 0x33 0x33 0x34    :9754334
0120   0x35 0x37 0x39 0x3a 0x3b 0x3c 0x3d 0x3d    579:;<==
0128   0x3d 0x3a 0x36 0x32 0x31 0x32 0x31 0x2f    =:62121/
0130   0x2c 0x2c 0x2f 0x33 0x36 0x38 0x37 0x37    ,,/36877
0138   0x37 0x37 0x38 0x39 0x3a 0x3d 0x40 0x42    7789:=@B
0140   0x44 0x46 0x48 0x48 0x48 0x47 0x47 0x47    DFHHHGGG
0148   0x47 0x47 0x46 0x45 0x43 0x42 0x40 0x40    GGFECB@@
0150   0x3f 0x3f 0x40 0x42 0x42 0x42 0x42 0x41    ??@BBBBA
0158   0x40 0x3f 0x3e 0x3d 0x3c 0x3b 0x3a 0x39    @?>=<;:9
0160   0x38 0x37 0x37 0x38 0x3a 0x3c 0x3d 0x3d    8778:<==
0168   0x3b 0x36 0x32 0x33 0x34 0x33 0x31 0x2e    ;623431.
0170   0x2e 0x2f 0x31 0x33 0x34 0x35 0x36 0x37    ./134567
0178   0x38 0x36 0x35 0x33 0x33 0x32 0x32 0x33    86533223
0180   0x33 0x35 0x37 0x3a 0x3d 0x3f 0x40 0x41    357:=?@A
0188   0x42 0x44 0x45 0x47 0x48 0x49 0x4b 0x4c    BDEGHIKL
0190   0x4c 0x4b 0x4c 0x4f 0x53 0x55 0x55 0x54    LKLOSUUT
0198   0x56 0xc7 0x0e 0x02 0xf7 0x09 0x0e 0x57    V......W
01A0   0x58 0x62 0xa0 0x2c 0x0e 0x02 0xc5 0x0a    Xb.,....
01A8   0x0f 0x5f 0x5e 0x5e 0x5e 0x5e 0x5d 0x5d    ._^^^^]]
01B0   0x5e 0x60 0x62 0x64 0x66 0x68 0x69 0x6b    ^`bdfhik
01B8   0x6c 0x6e 0x6f 0x70 0x70 0x70 0x71 0x70    lnopppqp
01C0   0x6e 0x6b 0x69 0x66 0x64 0x62 0x5f 0x5d    nkifdb_]
01C8   0x5c 0x59 0x57 0x57 0x55 0x51 0x4f 0x4d    \YWWUQOM
01D0   0x4a 0x48 0x47 0x48 0x4a 0x4c 0x4c 0x4c    JHGHJLLL
01D8   0x4a 0x49 0x46 0x43 0x41 0x41 0x43 0x45    JIFCAACE
01E0   0x47 0x4a 0x4d 0x4e 0x4e 0x4e 0x52 0x57    GJMNNNRW
01E8   0x5c 0x5d 0x5a 0x54 0x50 0x4f 0x51 0x53    \]ZTPOQS
01F0   0x54 0x55 0x57 0x59 0x5c 0x5d 0x5e 0x5e    TUWY\]^^
01F8   0x5e 0x5d 0x5d 0x5e 0x5f 0x61 0x63 0x64    ^]]^_acd
0200   0x63 0x60 0x5e 0x5b 0x58 0x56 0x54 0x54    c`^[XVTT
0208   0x55 0x56 0x56 0x56 0x55 0x54 0x52 0x51    UVVVUTRQ
0210   0x4f 0x4e 0x4c 0x4a 0x4a 0x4d 0x51 0x54    ONLJJMQT
0218   0x54 0x53 0x52 0x51 0x51 0x51 0x51 0x53    TSRQQQQS
0220   0x55 0x57 0x59 0x5b 0x5c 0x5d 0x5d 0x5b    UWY[\]][
0228   0x58 0x57 0x56 0x56 0x58 0x13 0x59 0x5a    XWVVX.YZ
0230   0x58 0x56 0x13 0x54 0x13 0x53 0x53 0x9a    XV.T.SS.
0238   0x0e 0x02 0xec 0x15 0x0e 0x13 0x53 0x52    ......SR
0240   0x13 0x4e 0x4e 0xb2 0x2a 0x0e 0x02 0xc1    .NN.*...
0248   0x16 0x0f 0x4e 0x4f 0x51 0x54 0x54 0x52    ..NOQTTR
0250   0x4f 0x4e 0x4d 0x4c 0x4b 0x4b 0x4b 0x4a    ONMLKKKJ
0258   0x4a 0x4a 0x4a 0x4a 0x4a 0x4b 0x4b 0x4c    JJJJJKKL
0260   0x4d 0x4d 0x4e 0x4f 0x50 0x51 0x52 0x51    MMNOPQRQ
0268   0x51 0x50 0x4f 0x4e 0x4d 0x4c 0x4c 0x4d    QPONMLLM
0270   0x4e 0x4e 0x4e 0x4e 0x4d 0x4d 0x4e 0x50    NNNNMMNP
0278   0x50 0x4f 0x4e 0x4c 0x4a 0x49 0x48 0x46    PONLJIHF
0280   0x45 0x44 0x42 0x41 0x41 0x40 0x40 0x40    EDBAA@@@
0288   0x40 0x40 0x41 0x41 0x3f 0x3c 0x39 0x37    @@AA?<97
0290   0x35 0x33 0x32 0x33 0x35 0x35 0x37 0x13    5323557.
0298   0x39 0x13 0x3b 0x3b 0x3c 0x3e 0x3f 0x41    9.;;<>?A
02A0   0x42 0x44 0x45 0x46 0x47 0x49 0x4b 0x4c    BDEFGIKL
02A8   0x4e 0x4e 0x4d 0x4d 0x4c 0x4b 0x4b 0x4c    NNMMLKKL
02B0   0x4d 0x4e 0x4f 0x52 0x54 0x56 0x58 0x59    MNORTVXY
02B8   0x5a 0x5a 0x5c 0x5e 0x60 0x01 0x05 0x0e    ZZ\^`...
02C0   0x43 0xde 0x07 0x08 0x0e 0x43 0xdf 0x07    C....C..
02C8   0x0b 0x0e 0x23 0xd1 0x08 0x0d 0x00 0x03    ..#.....
02D0   0xd1 0x0e 0x03 0xd6 0x08 0x0e 0x01 0x03    ........
02D8   0x01 0x03 0x68 0xbc 0x2f 0x0e 0x03 0xe4    ..h./...
02E0   0x08 0x0f 0x69 0x69 0x68 0x66 0x63 0x5f    ..iihfc_
02E8   0x5b 0x58 0x56 0x57 0x58 0x5a 0x5c 0x5d    [XVWXZ\]
02F0   0x5f 0x60 0x62 0x63 0x64 0x65 0x65 0x65    _`bcdeee
02F8   0x65 0x65 0x64 0x63 0x61 0x60 0x60 0x61    eedca``a
0300   0x63 0x62 0x63 0x65 0x67 0x69 0x6b 0x69    cbcegiki
0308   0x65 0x61 0x5e 0x5b 0x57 0x54 0x52 0x52    ea^[WTRR
0310   0x51 0x4e 0x4c 0x49 0x47 0x44 0x42 0x41    QNLIGDBA
0318   0x3f 0x3f 0x3f 0x3f 0x3f 0x3f 0x3f 0x3f    ????????
0320   0x3e 0x3e 0x3f 0x3f 0x70 0x0e 0x03 0xc7    >>??p...
0328   0x0e 0x0e 0x3f 0x41 0x3d 0x2b 0x2c 0x0e    ..?A=+,.
0330   0x03 0xd6 0x0e 0x0f 0x3d 0x3d 0x3b 0x39    ....==;9
0338   0x37 0x36 0x35 0x35 0x34 0x34 0x34 0x33    76554443
0340   0x33 0x34 0x34 0x34 0x35 0x36 0x38 0x39    34445689
0348   0x3b 0x3d 0x3e 0x3d 0x3d 0x3c 0x3c 0x3c    ;=>==<<<
0350   0x3e 0x40 0x43 0x46 0x49 0x4d 0x50 0x51    >@CFIMPQ
0358   0x51 0x51 0x4f 0x4e 0x4c 0x4b 0x49 0x47    QQONLKIG
0360   0x13 0x45 0x43 0x13 0x42 0x40 0x13 0x3f    .EC.B@.?
0368   0x40 0x41 0x41 0x40 0x3f 0x3e 0x3d 0x3d    @AA@?>==
0370   0x3e 0x40 0x42 0x44 0x45 0x46 0x47 0x48    >@BDEFGH
0378   0x49 0x4a 0x4b 0x4c 0x4d 0x4e 0x4d 0x72    IJKLMNMr
0380   0x0e 0x03 0xd6 0x14 0x0e 0x4c 0x4a 0x3f    .....LJ?
0388   0xde 0x25 0x0e 0x03 0xe4 0x14 0x0f 0x3e    .%.....>
0390   0x3f 0x3f 0x3e 0x3e 0x3f 0x41 0x43 0x46    ??>>?ACF
0398   0x49 0x4c 0x4f 0x52 0x55 0x57 0x5a 0x5b    ILORUWZ[
03A0   0x5d 0x5f 0x60 0x62 0x61 0x61 0x62 0x64    ]_`baabd
03A8   0x66 0x67 0x68 0x68 0x68 0x68 0x69 0x6a    fghhhhij
03B0   0x6a 0x6b 0x6b 0x6c 0x6d 0x6d 0x6e 0x6f    jkklmmno
03B8   0x6f 0x70 0x71 0x72 0x72 0x73 0x73 0x73    opqrrsss
03C0   0x73 0x74 0x74 0x72 0x71 0x70 0x6f 0x6e    sttrqpon
03C8   0x6d 0x6b 0x69 0x67 0x66 0x64 0x62 0x60    mkigfdb`
03D0   0x5f 0x5d 0x5c 0x5b 0x55 0x47 0x3f 0x3b    _]\[UG?;
03D8   0x3d 0x43 0x49 0x4c 0x4c 0x48 0x43 0x3f    =CILLHC?
03E0   0x41 0x48 0x4d 0x4f 0x4e 0x4d 0x4c 0x4a    AHMONMLJ
03E8   0x49 0x48 0x48 0x48 0x48 0x49 0x49 0x4a    IHHHHIIJ
03F0   0x49 0x47 0x45 0x44 0x46 0x4a 0x4d 0x4d    IGEDFJMM
03F8   0x4c 0x0e 0x24 0xd9 0x05 0x08 0xa8 0x76    L.$....v
```
#### decoded:
```python
"0000   0x42 0x42 0x42 0x41 0x41 0x41 0x41 0x41    BBBAAAAA\n0008   0x41 0x41 0x41 0x41 0x40 0x3f 0x3d 0x3c    AAAA@?=<\n0010   0x3a 0x3a 0x3a 0x3a 0x3a 0x3a 0x3a 0x3b    :::::::;\n0018   0x3b 0x3b 0x3b 0x3c 0x3c 0x3d 0x3c 0x13    ;;;<<=<.\n0020   0x3b 0x13 0x3a 0x39 0x38 0x37 0x37 0x37    ;.:98777\n0028   0x37 0x38 0x38 0x39 0x3a 0x3c 0x3d 0x3d    7889:<==\n0030   0x3f 0x40 0x41 0x43 0x44 0x45 0x45 0x46    ?@ACDEEF\n0038   0x46 0x45 0x62 0x0e 0x01 0xda 0x08 0x0e    FEb.....\n0040   0x44 0x45 0x46 0x38 0xfa 0x25 0x0e 0x01    DEF8.%..\n0048   0xe9 0x08 0x0f 0x38 0x37 0x37 0x37 0x37    ...87777\n0050   0x38 0x38 0x38 0x38 0x37 0x36 0x35 0x34    88887654\n0058   0x34 0x35 0x37 0x3a 0x3c 0x3f 0x41 0x44    457:<?AD\n0060   0x47 0x49 0x4c 0x13 0x4e 0x13 0x52 0x55    GIL.N.RU\n0068   0x58 0x59 0x59 0x59 0x59 0x58 0x58 0x5a    XYYYYXXZ\n0070   0x5c 0x5e 0x5f 0x5f 0x5e 0x5b 0x58 0x54    \\^__^[XT\n0078   0x50 0x4d 0x49 0x46 0x44 0x43 0x42 0x40    PMIFDCB@\n0080   0x3e 0x3c 0x3a 0x38 0x37 0x36 0x35 0x35    ><:87655\n0088   0x13 0x35 0x37 0x38 0x38 0x38 0x38 0x38    .5788888\n0090   0x13 0x38 0x37 0x37 0x37 0x37 0x38 0x38    .8777788\n0098   0x38 0x38 0x38 0x38 0x37 0x36 0x35 0x36    88887656\n00A0   0x38 0x39 0x3a 0x3a 0x3a 0x39 0x37 0x66    89:::97f\n00A8   0x0e 0x01 0xc4 0x10 0x0e 0x36 0x34 0x33    .....643\n00B0   0xbc 0x25 0x0e 0x01 0xd0 0x10 0x0f 0x33    .%.....3\n00B8   0x33 0x33 0x33 0x34 0x35 0x37 0x38 0x38    33345788\n00C0   0x39 0x39 0x13 0x39 0x13 0x39 0x39 0x38    99.9.998\n00C8   0x37 0x38 0x38 0x38 0x37 0x36 0x34 0x33    78887643\n00D0   0x32 0x31 0x33 0x34 0x34 0x36 0x38 0x39    21344689\n00D8   0x39 0x38 0x39 0x3a 0x3c 0x3e 0x3f 0x41    989:<>?A\n00E0   0x44 0x47 0x4a 0x4c 0x4e 0x4e 0x4d 0x4b    DGJLNNMK\n00E8   0x4b 0x4c 0x4d 0x4d 0x4d 0x4e 0x4f 0x4f    KLMMMNOO\n00F0   0x4f 0x4e 0x4b 0x49 0x46 0x43 0x41 0x40    ONKIFCA@\n00F8   0x40 0x40 0x3f 0x3e 0x3c 0x3c 0x3b 0x3b    @@?><<;;\n0100   0x3c 0x3d 0x3d 0x3c 0x3c 0x3c 0x3a 0x38    <==<<<:8\n0108   0x7b 0x0e 0x01 0xf6 0x16 0x0e 0x39 0x39    {.....99\n0110   0x3c 0x91 0x27 0x0e 0x01 0xc7 0x17 0x0f    <.'.....\n0118   0x3a 0x39 0x37 0x35 0x34 0x33 0x33 0x34    :9754334\n0120   0x35 0x37 0x39 0x3a 0x3b 0x3c 0x3d 0x3d    579:;<==\n0128   0x3d 0x3a 0x36 0x32 0x31 0x32 0x31 0x2f    =:62121/\n0130   0x2c 0x2c 0x2f 0x33 0x36 0x38 0x37 0x37    ,,/36877\n0138   0x37 0x37 0x38 0x39 0x3a 0x3d 0x40 0x42    7789:=@B\n0140   0x44 0x46 0x48 0x48 0x48 0x47 0x47 0x47    DFHHHGGG\n0148   0x47 0x47 0x46 0x45 0x43 0x42 0x40 0x40    GGFECB@@\n0150   0x3f 0x3f 0x40 0x42 0x42 0x42 0x42 0x41    ??@BBBBA\n0158   0x40 0x3f 0x3e 0x3d 0x3c 0x3b 0x3a 0x39    @?>=<;:9\n0160   0x38 0x37 0x37 0x38 0x3a 0x3c 0x3d 0x3d    8778:<==\n0168   0x3b 0x36 0x32 0x33 0x34 0x33 0x31 0x2e    ;623431.\n0170   0x2e 0x2f 0x31 0x33 0x34 0x35 0x36 0x37    ./134567\n0178   0x38 0x36 0x35 0x33 0x33 0x32 0x32 0x33    86533223\n0180   0x33 0x35 0x37 0x3a 0x3d 0x3f 0x40 0x41    357:=?@A\n0188   0x42 0x44 0x45 0x47 0x48 0x49 0x4b 0x4c    BDEGHIKL\n0190   0x4c 0x4b 0x4c 0x4f 0x53 0x55 0x55 0x54    LKLOSUUT\n0198   0x56 0xc7 0x0e 0x02 0xf7 0x09 0x0e 0x57    V......W\n01A0   0x58 0x62 0xa0 0x2c 0x0e 0x02 0xc5 0x0a    Xb.,....\n01A8   0x0f 0x5f 0x5e 0x5e 0x5e 0x5e 0x5d 0x5d    ._^^^^]]\n01B0   0x5e 0x60 0x62 0x64 0x66 0x68 0x69 0x6b    ^`bdfhik\n01B8   0x6c 0x6e 0x6f 0x70 0x70 0x70 0x71 0x70    lnopppqp\n01C0   0x6e 0x6b 0x69 0x66 0x64 0x62 0x5f 0x5d    nkifdb_]\n01C8   0x5c 0x59 0x57 0x57 0x55 0x51 0x4f 0x4d    \\YWWUQOM\n01D0   0x4a 0x48 0x47 0x48 0x4a 0x4c 0x4c 0x4c    JHGHJLLL\n01D8   0x4a 0x49 0x46 0x43 0x41 0x41 0x43 0x45    JIFCAACE\n01E0   0x47 0x4a 0x4d 0x4e 0x4e 0x4e 0x52 0x57    GJMNNNRW\n01E8   0x5c 0x5d 0x5a 0x54 0x50 0x4f 0x51 0x53    \\]ZTPOQS\n01F0   0x54 0x55 0x57 0x59 0x5c 0x5d 0x5e 0x5e    TUWY\\]^^\n01F8   0x5e 0x5d 0x5d 0x5e 0x5f 0x61 0x63 0x64    ^]]^_acd\n0200   0x63 0x60 0x5e 0x5b 0x58 0x56 0x54 0x54    c`^[XVTT\n0208   0x55 0x56 0x56 0x56 0x55 0x54 0x52 0x51    UVVVUTRQ\n0210   0x4f 0x4e 0x4c 0x4a 0x4a 0x4d 0x51 0x54    ONLJJMQT\n0218   0x54 0x53 0x52 0x51 0x51 0x51 0x51 0x53    TSRQQQQS\n0220   0x55 0x57 0x59 0x5b 0x5c 0x5d 0x5d 0x5b    UWY[\\]][\n0228   0x58 0x57 0x56 0x56 0x58 0x13 0x59 0x5a    XWVVX.YZ\n0230   0x58 0x56 0x13 0x54 0x13 0x53 0x53 0x9a    XV.T.SS.\n0238   0x0e 0x02 0xec 0x15 0x0e 0x13 0x53 0x52    ......SR\n0240   0x13 0x4e 0x4e 0xb2 0x2a 0x0e 0x02 0xc1    .NN.*...\n0248   0x16 0x0f 0x4e 0x4f 0x51 0x54 0x54 0x52    ..NOQTTR\n0250   0x4f 0x4e 0x4d 0x4c 0x4b 0x4b 0x4b 0x4a    ONMLKKKJ\n0258   0x4a 0x4a 0x4a 0x4a 0x4a 0x4b 0x4b 0x4c    JJJJJKKL\n0260   0x4d 0x4d 0x4e 0x4f 0x50 0x51 0x52 0x51    MMNOPQRQ\n0268   0x51 0x50 0x4f 0x4e 0x4d 0x4c 0x4c 0x4d    QPONMLLM\n0270   0x4e 0x4e 0x4e 0x4e 0x4d 0x4d 0x4e 0x50    NNNNMMNP\n0278   0x50 0x4f 0x4e 0x4c 0x4a 0x49 0x48 0x46    PONLJIHF\n0280   0x45 0x44 0x42 0x41 0x41 0x40 0x40 0x40    EDBAA@@@\n0288   0x40 0x40 0x41 0x41 0x3f 0x3c 0x39 0x37    @@AA?<97\n0290   0x35 0x33 0x32 0x33 0x35 0x35 0x37 0x13    5323557.\n0298   0x39 0x13 0x3b 0x3b 0x3c 0x3e 0x3f 0x41    9.;;<>?A\n02A0   0x42 0x44 0x45 0x46 0x47 0x49 0x4b 0x4c    BDEFGIKL\n02A8   0x4e 0x4e 0x4d 0x4d 0x4c 0x4b 0x4b 0x4c    NNMMLKKL\n02B0   0x4d 0x4e 0x4f 0x52 0x54 0x56 0x58 0x59    MNORTVXY\n02B8   0x5a 0x5a 0x5c 0x5e 0x60 0x01 0x05 0x0e    ZZ\\^`...\n02C0   0x43 0xde 0x07 0x08 0x0e 0x43 0xdf 0x07    C....C..\n02C8   0x0b 0x0e 0x23 0xd1 0x08 0x0d 0x00 0x03    ..#.....\n02D0   0xd1 0x0e 0x03 0xd6 0x08 0x0e 0x01 0x03    ........\n02D8   0x01 0x03 0x68 0xbc 0x2f 0x0e 0x03 0xe4    ..h./...\n02E0   0x08 0x0f 0x69 0x69 0x68 0x66 0x63 0x5f    ..iihfc_\n02E8   0x5b 0x58 0x56 0x57 0x58 0x5a 0x5c 0x5d    [XVWXZ\\]\n02F0   0x5f 0x60 0x62 0x63 0x64 0x65 0x65 0x65    _`bcdeee\n02F8   0x65 0x65 0x64 0x63 0x61 0x60 0x60 0x61    eedca``a\n0300   0x63 0x62 0x63 0x65 0x67 0x69 0x6b 0x69    cbcegiki\n0308   0x65 0x61 0x5e 0x5b 0x57 0x54 0x52 0x52    ea^[WTRR\n0310   0x51 0x4e 0x4c 0x49 0x47 0x44 0x42 0x41    QNLIGDBA\n0318   0x3f 0x3f 0x3f 0x3f 0x3f 0x3f 0x3f 0x3f    ????????\n0320   0x3e 0x3e 0x3f 0x3f 0x70 0x0e 0x03 0xc7    >>??p...\n0328   0x0e 0x0e 0x3f 0x41 0x3d 0x2b 0x2c 0x0e    ..?A=+,.\n0330   0x03 0xd6 0x0e 0x0f 0x3d 0x3d 0x3b 0x39    ....==;9\n0338   0x37 0x36 0x35 0x35 0x34 0x34 0x34 0x33    76554443\n0340   0x33 0x34 0x34 0x34 0x35 0x36 0x38 0x39    34445689\n0348   0x3b 0x3d 0x3e 0x3d 0x3d 0x3c 0x3c 0x3c    ;=>==<<<\n0350   0x3e 0x40 0x43 0x46 0x49 0x4d 0x50 0x51    >@CFIMPQ\n0358   0x51 0x51 0x4f 0x4e 0x4c 0x4b 0x49 0x47    QQONLKIG\n0360   0x13 0x45 0x43 0x13 0x42 0x40 0x13 0x3f    .EC.B@.?\n0368   0x40 0x41 0x41 0x40 0x3f 0x3e 0x3d 0x3d    @AA@?>==\n0370   0x3e 0x40 0x42 0x44 0x45 0x46 0x47 0x48    >@BDEFGH\n0378   0x49 0x4a 0x4b 0x4c 0x4d 0x4e 0x4d 0x72    IJKLMNMr\n0380   0x0e 0x03 0xd6 0x14 0x0e 0x4c 0x4a 0x3f    .....LJ?\n0388   0xde 0x25 0x0e 0x03 0xe4 0x14 0x0f 0x3e    .%.....>\n0390   0x3f 0x3f 0x3e 0x3e 0x3f 0x41 0x43 0x46    ??>>?ACF\n0398   0x49 0x4c 0x4f 0x52 0x55 0x57 0x5a 0x5b    ILORUWZ[\n03A0   0x5d 0x5f 0x60 0x62 0x61 0x61 0x62 0x64    ]_`baabd\n03A8   0x66 0x67 0x68 0x68 0x68 0x68 0x69 0x6a    fghhhhij\n03B0   0x6a 0x6b 0x6b 0x6c 0x6d 0x6d 0x6e 0x6f    jkklmmno\n03B8   0x6f 0x70 0x71 0x72 0x72 0x73 0x73 0x73    opqrrsss\n03C0   0x73 0x74 0x74 0x72 0x71 0x70 0x6f 0x6e    sttrqpon\n03C8   0x6d 0x6b 0x69 0x67 0x66 0x64 0x62 0x60    mkigfdb`\n03D0   0x5f 0x5d 0x5c 0x5b 0x55 0x47 0x3f 0x3b    _]\\[UG?;\n03D8   0x3d 0x43 0x49 0x4c 0x4c 0x48 0x43 0x3f    =CILLHC?\n03E0   0x41 0x48 0x4d 0x4f 0x4e 0x4d 0x4c 0x4a    AHMONMLJ\n03E8   0x49 0x48 0x48 0x48 0x48 0x49 0x49 0x4a    IHHHHIIJ\n03F0   0x49 0x47 0x45 0x44 0x46 0x4a 0x4d 0x4d    IGEDFJMM\n03F8   0x4c 0x0e 0x24 0xd9 0x05 0x08 0xa8 0x76    L.$....v"
```
### end stats
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 384L,
           'packets.transmit': 399L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 548L,
         'packets.transmit': 548L}}
```
