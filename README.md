Вроде как логи обучения надо прикрепить в `README` (как написано в задании), поэтому вот:

## Задание 1.5

Параметры:

| dataset | points | hidden layers | learning rate |
| :--- | :---: | :---: | :---: |
| Diag | 100 | 2 | 0.3 |
| Split | 100 | 5 | 0.4 |
| Xor | 100 | 10 | 0.4 |
| Circle | 100 | 7 | 0.5 |

### Датасет: `Diag`
```
Epoch  10  loss  51.73847623226733 correct 88
Epoch  20  loss  41.52644428294431 correct 88
Epoch  30  loss  38.56384237156677 correct 88
Epoch  40  loss  37.45708162800955 correct 88
Epoch  50  loss  36.9739061535161 correct 88
Epoch  60  loss  36.7332349373723 correct 88
Epoch  70  loss  36.5926800853418 correct 88
Epoch  80  loss  36.49033830607965 correct 88
Epoch  90  loss  36.397366299430985 correct 88
Epoch  100  loss  36.29689703067465 correct 88
Epoch  110  loss  36.17711731955695 correct 88
Epoch  120  loss  36.02783010042538 correct 88
Epoch  130  loss  35.837433962030296 correct 88
Epoch  140  loss  35.591700643875036 correct 88
Epoch  150  loss  35.27227916154024 correct 88
Epoch  160  loss  34.85479262135446 correct 88
Epoch  170  loss  34.30679462823198 correct 88
Epoch  180  loss  33.58567518097459 correct 88
Epoch  190  loss  32.6779796138954 correct 88
Epoch  200  loss  31.523283473180875 correct 88
Epoch  210  loss  30.12574482032603 correct 88
Epoch  220  loss  28.491600653445882 correct 88
Epoch  230  loss  26.61663242453816 correct 88
Epoch  240  loss  24.5982063661654 correct 88
Epoch  250  loss  22.507128096446014 correct 88
Epoch  260  loss  20.4649449571754 correct 88
Epoch  270  loss  18.597722455746368 correct 95
Epoch  280  loss  16.887037076147095 correct 96
Epoch  290  loss  15.338768676934935 correct 97
Epoch  300  loss  13.955953829165928 correct 98
Epoch  310  loss  12.753723682354869 correct 99
Epoch  320  loss  11.702884187748884 correct 99
Epoch  330  loss  10.781602360485918 correct 99
Epoch  340  loss  9.965252277652812 correct 99
Epoch  350  loss  9.231817876172824 correct 99
Epoch  360  loss  8.583908381369362 correct 99
Epoch  370  loss  8.005654096914437 correct 99
Epoch  380  loss  7.499074937077913 correct 99
Epoch  390  loss  7.052334374239175 correct 99
Epoch  400  loss  6.652684633068982 correct 99
Epoch  410  loss  6.290613331956146 correct 99
Epoch  420  loss  5.962581162893824 correct 100
Epoch  430  loss  5.662319797801424 correct 100
Epoch  440  loss  5.386843481075473 correct 100
Epoch  450  loss  5.133545360129413 correct 100
Epoch  460  loss  4.90013795133914 correct 100
Epoch  470  loss  4.684606618795455 correct 100
Epoch  480  loss  4.485172029202601 correct 100
Epoch  490  loss  4.300259146081801 correct 100
Epoch  500  loss  4.128479649209421 correct 100
```

### Датасет: `Split`
```
Epoch  10  loss  69.01153847262133 correct 66
Epoch  20  loss  68.95304844246984 correct 66
Epoch  30  loss  68.88057922090265 correct 69
Epoch  40  loss  68.77652943353588 correct 69
Epoch  50  loss  68.57120919928374 correct 68
Epoch  60  loss  68.30176701815058 correct 61
Epoch  70  loss  68.0823316598396 correct 56
Epoch  80  loss  67.88457948930903 correct 59
Epoch  90  loss  67.6498411963601 correct 60
Epoch  100  loss  67.38345773826384 correct 61
Epoch  110  loss  67.07036724002161 correct 64
Epoch  120  loss  66.68802424323242 correct 64
Epoch  130  loss  66.21030016521968 correct 66
Epoch  140  loss  65.59495089079063 correct 71
Epoch  150  loss  64.77707546327039 correct 75
Epoch  160  loss  63.675035130527434 correct 75
Epoch  170  loss  62.1573110222276 correct 77
Epoch  180  loss  60.02797235949389 correct 81
Epoch  190  loss  57.112012915675386 correct 90
Epoch  200  loss  53.198590738719574 correct 95
Epoch  210  loss  47.93380151865729 correct 95
Epoch  220  loss  40.74686446843667 correct 97
Epoch  230  loss  41.49303760542179 correct 79
Epoch  240  loss  45.52285268771148 correct 76
Epoch  250  loss  34.163378855722215 correct 85
Epoch  260  loss  37.03414194270832 correct 81
Epoch  270  loss  32.001153769281345 correct 85
Epoch  280  loss  28.346359856867817 correct 85
Epoch  290  loss  31.207527479741156 correct 85
Epoch  300  loss  28.233732542553817 correct 85
Epoch  310  loss  22.45383070735132 correct 90
Epoch  320  loss  22.800273533885175 correct 88
Epoch  330  loss  28.88911755318325 correct 85
Epoch  340  loss  22.92274286941209 correct 88
Epoch  350  loss  18.09882085118706 correct 92
Epoch  360  loss  17.70959323212068 correct 92
Epoch  370  loss  23.910756731799836 correct 88
Epoch  380  loss  25.560814476440694 correct 87
Epoch  390  loss  15.830469508070061 correct 92
Epoch  400  loss  12.88747819574664 correct 95
Epoch  410  loss  12.673607033785425 correct 94
Epoch  420  loss  16.73839269769592 correct 92
Epoch  430  loss  37.85893680101406 correct 83
Epoch  440  loss  15.984144892288478 correct 92
Epoch  450  loss  10.381361707451518 correct 98
Epoch  460  loss  9.669875134630336 correct 98
Epoch  470  loss  9.286580064201107 correct 98
Epoch  480  loss  9.233294472083761 correct 98
Epoch  490  loss  12.003288192078552 correct 93
Epoch  500  loss  56.12599141192447 correct 83
```

### Датасет: `Xor`
```
Epoch  10  loss  64.1025434415571 correct 78
Epoch  20  loss  60.135624968590484 correct 74
Epoch  30  loss  56.37648569476486 correct 75
Epoch  40  loss  52.9195786022011 correct 82
Epoch  50  loss  49.612198109702746 correct 84
Epoch  60  loss  46.32349696352748 correct 87
Epoch  70  loss  43.00653063486743 correct 91
Epoch  80  loss  39.59638733080527 correct 91
Epoch  90  loss  36.78237525106585 correct 91
Epoch  100  loss  34.717781664208516 correct 90
Epoch  110  loss  31.75500468290332 correct 90
Epoch  120  loss  30.373305642092426 correct 90
Epoch  130  loss  27.861519933103786 correct 91
Epoch  140  loss  26.03677572420172 correct 92
Epoch  150  loss  24.778386221426683 correct 93
Epoch  160  loss  24.627001149054593 correct 91
Epoch  170  loss  25.20255324970122 correct 90
Epoch  180  loss  21.887017022677366 correct 93
Epoch  190  loss  20.04819022430481 correct 92
Epoch  200  loss  19.186640264684456 correct 92
Epoch  210  loss  18.872266990044064 correct 93
Epoch  220  loss  21.190579784457807 correct 92
Epoch  230  loss  40.86870680653231 correct 79
Epoch  240  loss  15.156791100757772 correct 94
Epoch  250  loss  14.832811828388857 correct 94
Epoch  260  loss  24.342513408334653 correct 87
Epoch  270  loss  15.328877008018287 correct 94
Epoch  280  loss  13.0713327330623 correct 94
Epoch  290  loss  17.240803470245936 correct 95
Epoch  300  loss  18.188856464357656 correct 92
Epoch  310  loss  12.439440340179232 correct 96
Epoch  320  loss  15.6064105089617 correct 95
Epoch  330  loss  13.715291065224415 correct 95
Epoch  340  loss  18.005695534150266 correct 93
Epoch  350  loss  12.550929551319395 correct 96
Epoch  360  loss  11.707347000900672 correct 94
Epoch  370  loss  11.01008483270225 correct 95
Epoch  380  loss  10.581418528112371 correct 97
Epoch  390  loss  15.242100554303715 correct 93
Epoch  400  loss  16.007958011543746 correct 91
Epoch  410  loss  12.564387823653323 correct 96
Epoch  420  loss  10.681770392574329 correct 97
Epoch  430  loss  10.394454070334007 correct 96
Epoch  440  loss  13.693186608309945 correct 94
Epoch  450  loss  15.544038484584105 correct 95
Epoch  460  loss  9.196917326250496 correct 95
Epoch  470  loss  9.739608087589056 correct 96
Epoch  480  loss  11.88538647862472 correct 95
Epoch  490  loss  12.41369598879504 correct 95
Epoch  500  loss  9.153273219787932 correct 96
```

### Датасет: `Circle`
```
Epoch  10  loss  61.609373502901306 correct 69
Epoch  20  loss  61.50866163804392 correct 69
Epoch  30  loss  61.413253741336135 correct 69
Epoch  40  loss  61.29952131058171 correct 69
Epoch  50  loss  61.16238011974168 correct 69
Epoch  60  loss  60.99493431178644 correct 69
Epoch  70  loss  60.798720227048236 correct 69
Epoch  80  loss  60.57186763496069 correct 69
Epoch  90  loss  60.322337054518066 correct 69
Epoch  100  loss  60.007387620935454 correct 69
Epoch  110  loss  59.59584699369608 correct 69
Epoch  120  loss  59.0945155470456 correct 69
Epoch  130  loss  58.433505844747636 correct 69
Epoch  140  loss  57.67336029362845 correct 69
Epoch  150  loss  56.52950688022037 correct 69
Epoch  160  loss  54.6536739828804 correct 69
Epoch  170  loss  52.534176690558205 correct 69
Epoch  180  loss  49.79671233750085 correct 74
Epoch  190  loss  51.08011745420135 correct 69
Epoch  200  loss  45.412253611391954 correct 79
Epoch  210  loss  61.278767291434384 correct 69
Epoch  220  loss  43.36685810577194 correct 74
Epoch  230  loss  48.25850038616567 correct 70
Epoch  240  loss  43.21497179585422 correct 74
Epoch  250  loss  40.62896338313813 correct 75
Epoch  260  loss  40.432772553018125 correct 75
Epoch  270  loss  39.25812819754706 correct 76
Epoch  280  loss  36.18730745181924 correct 79
Epoch  290  loss  37.20660893196538 correct 79
Epoch  300  loss  30.08154536574331 correct 81
Epoch  310  loss  39.06841911871188 correct 79
Epoch  320  loss  25.32760499244005 correct 84
Epoch  330  loss  26.62975360450577 correct 82
Epoch  340  loss  36.69558925851324 correct 80
Epoch  350  loss  15.88992734517255 correct 96
Epoch  360  loss  13.953621645400203 correct 97
Epoch  370  loss  18.35848119736728 correct 91
Epoch  380  loss  25.572758006750544 correct 85
Epoch  390  loss  13.381038153460539 correct 99
Epoch  400  loss  11.926578881247066 correct 99
Epoch  410  loss  12.290198260095995 correct 94
Epoch  420  loss  99.61871861014185 correct 76
Epoch  430  loss  12.428618487074218 correct 98
Epoch  440  loss  10.53055533006405 correct 100
Epoch  450  loss  9.581578593972184 correct 100
Epoch  460  loss  9.022501161563708 correct 100
Epoch  470  loss  14.09614141743917 correct 94
Epoch  480  loss  42.377277097005305 correct 85
Epoch  490  loss  9.643513560103795 correct 100
Epoch  500  loss  8.571260161140263 correct 100
```
