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





## Задание 2.5

Параметры:

| dataset | points | hidden layers | learning rate |
| :--- | :---: | :---: | :---: |
| Simple | 100 | 4 | 0.3 |
| Diag | 100 | 2 | 0.3 |
| Split | 100 | 5 | 0.4 |
| Xor | 100 | 10 | 0.4 |
| Circle | 100 | 7 | 0.5 |
| Spiral | 100 | 10 | 0.4 |

### Датасет: `Simple`
```
Epoch  10  loss  60.99915109731188 correct 83  time 0.207s/epoch
Epoch  20  loss  52.541607548374586 correct 87  time 0.203s/epoch
Epoch  30  loss  40.67499081211925 correct 91  time 0.199s/epoch
Epoch  40  loss  29.42559805972808 correct 94  time 0.215s/epoch
Epoch  50  loss  21.61469999622802 correct 95  time 0.206s/epoch
Epoch  60  loss  16.775812027693842 correct 96  time 0.203s/epoch
Epoch  70  loss  18.764743250381095 correct 92  time 0.199s/epoch
Epoch  80  loss  21.028229365650866 correct 90  time 0.203s/epoch
Epoch  90  loss  10.383365931348884 correct 99  time 0.201s/epoch
Epoch  100  loss  8.803997672551727 correct 100  time 0.204s/epoch
Epoch  110  loss  7.8358998760609255 correct 100  time 0.196s/epoch
Epoch  120  loss  7.1114557033203605 correct 100  time 0.202s/epoch
Epoch  130  loss  6.567323752285434 correct 100  time 0.195s/epoch
Epoch  140  loss  6.351910415547513 correct 100  time 0.204s/epoch
Epoch  150  loss  7.800029222176302 correct 96  time 0.215s/epoch
Epoch  160  loss  11.579901891018014 correct 94  time 0.207s/epoch
Epoch  170  loss  8.823562806079751 correct 95  time 0.208s/epoch
Epoch  180  loss  6.442222248502906 correct 97  time 0.203s/epoch
Epoch  190  loss  5.451901356896082 correct 100  time 0.216s/epoch
Epoch  200  loss  4.913182162981808 correct 100  time 0.223s/epoch
Epoch  210  loss  4.624178470440341 correct 100  time 0.227s/epoch
Epoch  220  loss  4.48933594438574 correct 100  time 0.214s/epoch
Epoch  230  loss  4.581654834522073 correct 100  time 0.214s/epoch
Epoch  240  loss  5.096236885536395 correct 99  time 0.213s/epoch
Epoch  250  loss  6.642435849999491 correct 96  time 0.213s/epoch
Epoch  260  loss  8.52082776799423 correct 94  time 0.212s/epoch
Epoch  270  loss  6.533216008476694 correct 96  time 0.208s/epoch
Epoch  280  loss  3.962140207668744 correct 100  time 0.214s/epoch
Epoch  290  loss  3.233221845931613 correct 100  time 0.210s/epoch
Epoch  300  loss  3.0471049115582427 correct 100  time 0.208s/epoch
Epoch  310  loss  2.9326370782174274 correct 100  time 0.217s/epoch
Epoch  320  loss  2.8357631178181775 correct 100  time 0.208s/epoch
Epoch  330  loss  2.7467921275767613 correct 100  time 0.211s/epoch
Epoch  340  loss  2.6637638553302283 correct 100  time 0.207s/epoch
Epoch  350  loss  2.585867371022833 correct 100  time 0.208s/epoch
Epoch  360  loss  2.5125812612890495 correct 100  time 0.209s/epoch
Epoch  370  loss  2.4434797640536465 correct 100  time 0.209s/epoch
Epoch  380  loss  2.378199244176496 correct 100  time 0.247s/epoch
Epoch  390  loss  2.3166316197475934 correct 100  time 0.226s/epoch
Epoch  400  loss  2.2582632449440694 correct 100  time 0.230s/epoch
Epoch  410  loss  2.202838087494822 correct 100  time 0.234s/epoch
Epoch  420  loss  2.150131613830466 correct 100  time 0.221s/epoch
Epoch  430  loss  2.099944684654739 correct 100  time 0.210s/epoch
Epoch  440  loss  2.05209657829093 correct 100  time 0.213s/epoch
Epoch  450  loss  2.00642370047646 correct 100  time 0.215s/epoch
Epoch  460  loss  1.962777489658563 correct 100  time 0.212s/epoch
Epoch  470  loss  1.9210226651734563 correct 100  time 0.221s/epoch
Epoch  480  loss  1.8810357398691866 correct 100  time 0.212s/epoch
Epoch  490  loss  1.8427037453446002 correct 100  time 0.212s/epoch
Epoch  500  loss  1.8059231329369023 correct 100  time 0.200s/epoch
Done. Avg time: 0.211s/epoch
```

### Датасет: `Diag`
```
Epoch  10  loss  39.039870517831986 correct 89  time 0.085s/epoch
Epoch  20  loss  36.41520854950074 correct 89  time 0.084s/epoch
Epoch  30  loss  35.46827577077148 correct 89  time 0.087s/epoch
Epoch  40  loss  35.057958995494936 correct 89  time 0.086s/epoch
Epoch  50  loss  34.853795945182426 correct 89  time 0.085s/epoch
Epoch  60  loss  34.73527349753322 correct 89  time 0.084s/epoch
Epoch  70  loss  34.65204946535405 correct 89  time 0.086s/epoch
Epoch  80  loss  34.58007958867132 correct 89  time 0.083s/epoch
Epoch  90  loss  34.50540455540722 correct 89  time 0.086s/epoch
Epoch  100  loss  34.417263311821706 correct 89  time 0.089s/epoch
Epoch  110  loss  34.30448760863737 correct 89  time 0.095s/epoch
Epoch  120  loss  34.15279303909117 correct 89  time 0.090s/epoch
Epoch  130  loss  33.9481897079303 correct 89  time 0.088s/epoch
Epoch  140  loss  33.6806064251922 correct 89  time 0.092s/epoch
Epoch  150  loss  33.31779990306006 correct 89  time 0.101s/epoch
Epoch  160  loss  32.83291312062072 correct 89  time 0.096s/epoch
Epoch  170  loss  32.16662859015355 correct 89  time 0.091s/epoch
Epoch  180  loss  31.24344868053188 correct 89  time 0.091s/epoch
Epoch  190  loss  29.980901519814363 correct 89  time 0.100s/epoch
Epoch  200  loss  28.319347132067243 correct 89  time 0.102s/epoch
Epoch  210  loss  26.273616468052452 correct 89  time 0.099s/epoch
Epoch  220  loss  23.89181535271157 correct 89  time 0.095s/epoch
Epoch  230  loss  21.362768227151076 correct 89  time 0.102s/epoch
Epoch  240  loss  18.85669756000886 correct 92  time 0.090s/epoch
Epoch  250  loss  16.584765979804914 correct 94  time 0.094s/epoch
Epoch  260  loss  14.622239742930551 correct 96  time 0.094s/epoch
Epoch  270  loss  12.925577315800414 correct 99  time 0.099s/epoch
Epoch  280  loss  11.546741845285533 correct 99  time 0.093s/epoch
Epoch  290  loss  10.381840908487268 correct 99  time 0.086s/epoch
Epoch  300  loss  9.3829369828399 correct 99  time 0.090s/epoch
Epoch  310  loss  8.537830247471447 correct 100  time 0.103s/epoch
Epoch  320  loss  7.8220147073949855 correct 100  time 0.091s/epoch
Epoch  330  loss  7.205134814611604 correct 100  time 0.097s/epoch
Epoch  340  loss  6.665318291745369 correct 100  time 0.096s/epoch
Epoch  350  loss  6.187536184582298 correct 100  time 0.088s/epoch
Epoch  360  loss  5.770302214238236 correct 100  time 0.087s/epoch
Epoch  370  loss  5.410508375892539 correct 100  time 0.088s/epoch
Epoch  380  loss  5.094354520095578 correct 100  time 0.088s/epoch
Epoch  390  loss  4.806794185335473 correct 100  time 0.086s/epoch
Epoch  400  loss  4.548927167988861 correct 100  time 0.090s/epoch
Epoch  410  loss  4.3191784432805 correct 100  time 0.085s/epoch
Epoch  420  loss  4.108804167662592 correct 100  time 0.091s/epoch
Epoch  430  loss  3.918319077426866 correct 100  time 0.101s/epoch
Epoch  440  loss  3.738866098106779 correct 100  time 0.086s/epoch
Epoch  450  loss  3.5747668560972787 correct 100  time 0.090s/epoch
Epoch  460  loss  3.423050629140645 correct 100  time 0.088s/epoch
Epoch  470  loss  3.282486777626654 correct 100  time 0.085s/epoch
Epoch  480  loss  3.153340865617995 correct 100  time 0.084s/epoch
Epoch  490  loss  3.034549627345002 correct 100  time 0.084s/epoch
Epoch  500  loss  2.9226339870335347 correct 100  time 0.083s/epoch
Done. Avg time: 0.091s/epoch
```

### Датасет: `Split`
```
Epoch  10  loss  61.99216621359141 correct 66  time 0.271s/epoch
Epoch  20  loss  58.57230433745149 correct 70  time 0.263s/epoch
Epoch  30  loss  55.426035029142696 correct 70  time 0.263s/epoch
Epoch  40  loss  51.28627866540937 correct 75  time 0.264s/epoch
Epoch  50  loss  45.69524368936598 correct 81  time 0.262s/epoch
Epoch  60  loss  39.695986187903245 correct 87  time 0.262s/epoch
Epoch  70  loss  34.438423960396236 correct 90  time 0.262s/epoch
Epoch  80  loss  49.01039757586195 correct 70  time 0.262s/epoch
Epoch  90  loss  44.46391342355627 correct 75  time 0.262s/epoch
Epoch  100  loss  38.74865491508476 correct 78  time 0.262s/epoch
Epoch  110  loss  37.314511014356675 correct 79  time 0.270s/epoch
Epoch  120  loss  34.280367484468236 correct 83  time 0.262s/epoch
Epoch  130  loss  32.543224890686346 correct 83  time 0.263s/epoch
Epoch  140  loss  31.488766614629426 correct 83  time 0.262s/epoch
Epoch  150  loss  28.92995683891217 correct 85  time 0.264s/epoch
Epoch  160  loss  27.827518396777783 correct 85  time 0.267s/epoch
Epoch  170  loss  26.470271908808574 correct 85  time 0.263s/epoch
Epoch  180  loss  25.515757200218502 correct 86  time 0.326s/epoch
Epoch  190  loss  24.460005840561767 correct 87  time 0.306s/epoch
Epoch  200  loss  22.93849684018538 correct 88  time 0.290s/epoch
Epoch  210  loss  21.67977634078119 correct 88  time 0.274s/epoch
Epoch  220  loss  21.356099246105945 correct 89  time 0.271s/epoch
Epoch  230  loss  20.235582623105355 correct 89  time 0.296s/epoch
Epoch  240  loss  19.221078247573896 correct 89  time 0.302s/epoch
Epoch  250  loss  18.710624265838167 correct 89  time 0.274s/epoch
Epoch  260  loss  18.210442499594244 correct 89  time 0.267s/epoch
Epoch  270  loss  17.113035097547996 correct 90  time 0.268s/epoch
Epoch  280  loss  15.348062565239482 correct 90  time 0.270s/epoch
Epoch  290  loss  14.253187261513323 correct 93  time 0.270s/epoch
Epoch  300  loss  14.437335766624647 correct 92  time 0.264s/epoch
Epoch  310  loss  15.569767976989134 correct 91  time 0.266s/epoch
Epoch  320  loss  15.827937435451139 correct 91  time 0.266s/epoch
Epoch  330  loss  13.499535073320176 correct 94  time 0.271s/epoch
Epoch  340  loss  10.460051343989083 correct 96  time 0.274s/epoch
Epoch  350  loss  9.578685485270107 correct 96  time 0.270s/epoch
Epoch  360  loss  10.35613126036112 correct 96  time 0.284s/epoch
Epoch  370  loss  11.944712037525505 correct 96  time 0.302s/epoch
Epoch  380  loss  12.490226821262972 correct 94  time 0.298s/epoch
Epoch  390  loss  11.174389051704688 correct 96  time 0.280s/epoch
Epoch  400  loss  9.747134254231385 correct 96  time 0.305s/epoch
Epoch  410  loss  9.189545886453288 correct 96  time 0.303s/epoch
Epoch  420  loss  9.314816874878968 correct 96  time 0.325s/epoch
Epoch  430  loss  9.678079157233602 correct 96  time 0.299s/epoch
Epoch  440  loss  9.703981480926409 correct 96  time 0.284s/epoch
Epoch  450  loss  9.317192066054291 correct 96  time 0.296s/epoch
Epoch  460  loss  8.750144989386284 correct 96  time 0.287s/epoch
Epoch  470  loss  8.331407337505217 correct 96  time 0.284s/epoch
Epoch  480  loss  8.201759070535854 correct 96  time 0.281s/epoch
Epoch  490  loss  8.246147547119135 correct 96  time 0.298s/epoch
Epoch  500  loss  8.291471704907407 correct 96  time 0.314s/epoch
```

### Датасет: `Xor`
```
Epoch  10  loss  65.85221501395571 correct 65  time 0.830s/epoch
Epoch  20  loss  62.75909558686659 correct 71  time 0.802s/epoch
Epoch  30  loss  59.878716912011285 correct 71  time 0.808s/epoch
Epoch  40  loss  56.683800751115896 correct 76  time 0.817s/epoch
Epoch  50  loss  52.98189925416447 correct 78  time 0.815s/epoch
Epoch  60  loss  50.34785380645316 correct 72  time 0.821s/epoch
Epoch  70  loss  48.93870113975727 correct 69  time 0.826s/epoch
Epoch  80  loss  42.75111996250166 correct 81  time 0.835s/epoch
Epoch  90  loss  41.084932851172965 correct 80  time 0.819s/epoch
Epoch  100  loss  36.89482302473691 correct 86  time 0.827s/epoch
Epoch  110  loss  34.25810029611338 correct 87  time 0.841s/epoch
Epoch  120  loss  31.746966573402688 correct 87  time 0.865s/epoch
Epoch  130  loss  28.90779747580339 correct 87  time 0.829s/epoch
Epoch  140  loss  26.025339257548747 correct 92  time 0.830s/epoch
Epoch  150  loss  23.831553085862748 correct 92  time 0.828s/epoch
Epoch  160  loss  21.72520072176911 correct 93  time 0.827s/epoch
Epoch  170  loss  19.807170435346457 correct 94  time 0.823s/epoch
Epoch  180  loss  18.701104142004358 correct 93  time 0.814s/epoch
Epoch  190  loss  16.761525092260342 correct 94  time 0.861s/epoch
Epoch  200  loss  16.4656239214165 correct 94  time 0.839s/epoch
Epoch  210  loss  16.154662491211617 correct 93  time 0.849s/epoch
Epoch  220  loss  14.986689045106385 correct 93  time 0.825s/epoch
Epoch  230  loss  14.282256861612838 correct 93  time 0.822s/epoch
Epoch  240  loss  13.825086509096268 correct 93  time 0.818s/epoch
Epoch  250  loss  12.947557269989622 correct 94  time 0.854s/epoch
Epoch  260  loss  11.950950113904211 correct 94  time 0.865s/epoch
Epoch  270  loss  11.475087812605679 correct 96  time 0.870s/epoch
Epoch  280  loss  11.804943135144836 correct 94  time 0.835s/epoch
Epoch  290  loss  10.962862072365489 correct 96  time 0.824s/epoch
Epoch  300  loss  10.11410802873436 correct 97  time 0.818s/epoch
Epoch  310  loss  9.41244946541939 correct 97  time 0.820s/epoch
Epoch  320  loss  10.073990586700186 correct 96  time 0.816s/epoch
Epoch  330  loss  10.503250366053472 correct 96  time 0.847s/epoch
Epoch  340  loss  9.909567860244668 correct 96  time 0.843s/epoch
Epoch  350  loss  8.268338774332324 correct 97  time 0.838s/epoch
Epoch  360  loss  7.567646767618945 correct 98  time 0.832s/epoch
Epoch  370  loss  7.68024545366227 correct 97  time 0.849s/epoch
Epoch  380  loss  8.03283937529822 correct 97  time 0.835s/epoch
Epoch  390  loss  10.343444982413752 correct 93  time 0.854s/epoch
Epoch  400  loss  10.33489821321559 correct 97  time 0.825s/epoch
Epoch  410  loss  6.245682437142236 correct 98  time 0.816s/epoch
Epoch  420  loss  4.8111411520892755 correct 99  time 0.828s/epoch
Epoch  430  loss  4.548428926214164 correct 99  time 0.845s/epoch
Epoch  440  loss  4.359808136173892 correct 100  time 0.￼
828s/epoch
Epoch  450  loss  4.201748208314367 correct 99  time 0.896s/epoch
Epoch  460  loss  4.05794942079013 correct 100  time 0.848s/epoch
Epoch  470  loss  3.921707969166359 correct 100  time 0.809s/epoch
Epoch  480  loss  3.7932344624304806 correct 100  time 0.904s/epoch
Epoch  490  loss  3.6653988046395938 correct 100  time 0.909s/epoch
Epoch  500  loss  3.5481070260541965 correct 100  time 0.875s/epoch
Done. Avg time: 0.837s/epoch
```

### Датасет: `Circle`
```
Epoch  10  loss  58.26103513367239 correct 70  time 0.496s/epoch
Epoch  20  loss  55.414524168648 correct 70  time 0.515s/epoch
Epoch  30  loss  52.53334896885344 correct 70  time 0.517s/epoch
Epoch  40  loss  52.4737536819292 correct 71  time 0.561s/epoch
Epoch  50  loss  52.66912118911013 correct 79  time 0.506s/epoch
Epoch  60  loss  48.4520642625618 correct 76  time 0.494s/epoch
Epoch  70  loss  46.920411497898975 correct 83  time 0.494s/epoch
Epoch  80  loss  48.165225238027205 correct 86  time 0.500s/epoch
Epoch  90  loss  42.98388789941248 correct 87  time 0.479s/epoch
Epoch  100  loss  44.55117116116378 correct 83  time 0.456s/epoch
Epoch  110  loss  36.79304546436069 correct 90  time 0.459s/epoch
Epoch  120  loss  41.40461163386481 correct 86  time 0.446s/epoch
Epoch  130  loss  32.75401420923597 correct 92  time 0.465s/epoch
Epoch  140  loss  35.043055150101004 correct 87  time 0.533s/epoch
Epoch  150  loss  29.456564133255238 correct 92  time 0.496s/epoch
Epoch  160  loss  29.681848414767007 correct 89  time 0.498s/epoch
Epoch  170  loss  29.452376726683788 correct 89  time 0.464s/epoch
Epoch  180  loss  25.357483770851946 correct 93  time 0.464s/epoch
Epoch  190  loss  24.186282709068703 correct 93  time 0.456s/epoch
Epoch  200  loss  28.509320025510167 correct 87  time 0.451s/epoch
Epoch  210  loss  19.36091731631581 correct 96  time 0.461s/epoch
Epoch  220  loss  30.565889225185344 correct 89  time 0.458s/epoch
Epoch  230  loss  20.891139188603546 correct 92  time 0.449s/epoch
Epoch  240  loss  16.416321821141523 correct 94  time 0.451s/epoch
Epoch  250  loss  24.198997383779226 correct 90  time 0.463s/epoch
Epoch  260  loss  18.866025239078347 correct 93  time 0.478s/epoch
Epoch  270  loss  15.210493252985163 correct 97  time 0.467s/epoch
Epoch  280  loss  16.564163504092527 correct 92  time 0.451s/epoch
Epoch  290  loss  34.40618722312762 correct 85  time 0.443s/epoch
Epoch  300  loss  14.660561720677164 correct 92  time 0.489s/epoch
Epoch  310  loss  14.828726715452948 correct 96  time 0.460s/epoch
Epoch  320  loss  27.621049318262372 correct 88  time 0.445s/epoch
Epoch  330  loss  14.875927311007949 correct 96  time 0.445s/epoch
Epoch  340  loss  14.228207383327348 correct 97  time 0.442s/epoch
Epoch  350  loss  28.264487622616013 correct 89  time 0.444s/epoch
Epoch  360  loss  14.842576369609333 correct 93  time 0.442s/epoch
Epoch  370  loss  12.841110095659385 correct 98  time 0.445s/epoch
Epoch  380  loss  20.42305616047086 correct 90  time 0.440s/epoch
Epoch  390  loss  14.367418547764625 correct 96  time 0.461s/epoch
Epoch  400  loss  11.998745692831267 correct 99  time 0.487s/epoch
Epoch  410  loss  12.157252095343596 correct 99  time 0.492s/epoch
Epoch  420  loss  25.33949033537905 correct 89  time 0.467s/epoch
Epoch  430  loss  12.990361364467729 correct 97  time 0.551s/epoch
Epoch  440  loss  11.465931081133172 correct 99  time 0.484s/epoch
Epoch  450  loss  15.111629049644012 correct 95  time 0.496s/epoch
Epoch  460  loss  15.033634295033375 correct 95  time 0.477s/epoch
Epoch  470  loss  12.710406192499239 correct 96  time 0.470s/epoch
Epoch  480  loss  20.57655781570741 correct 90  time 0.464s/epoch
Epoch  490  loss  14.489116156548528 correct 95  time 0.462s/epoch
Epoch  500  loss  12.793867236681221 correct 96  time 0.457s/epoch
Done. Avg time: 0.474s/epoch
```

### Датасет: `Spiral`
```
Epoch  10  loss  67.32852159492147 correct 57  time 0.847s/epoch
Epoch  20  loss  67.05299687274571 correct 58  time 0.823s/epoch
Epoch  30  loss  66.93945260624534 correct 57  time 0.803s/epoch
Epoch  40  loss  66.87101710701445 correct 57  time 0.801s/epoch
Epoch  50  loss  66.84348425036269 correct 59  time 0.814s/epoch
Epoch  60  loss  66.81230546103224 correct 58  time 0.843s/epoch
Epoch  70  loss  66.7447885104426 correct 59  time 0.840s/epoch
Epoch  80  loss  66.77600548593956 correct 59  time 0.838s/epoch
Epoch  90  loss  66.9003310568826 correct 58  time 0.850s/epoch
Epoch  100  loss  66.78441056172467 correct 59  time 0.884s/epoch
Epoch  110  loss  66.73144143096663 correct 58  time 0.846s/epoch
Epoch  120  loss  66.66833977562241 correct 59  time 0.802s/epoch
Epoch  130  loss  66.61539423582326 correct 59  time 0.806s/epoch
Epoch  140  loss  66.57451686111405 correct 59  time 0.802s/epoch
Epoch  150  loss  66.48666604489657 correct 58  time 0.805s/epoch
Epoch  160  loss  66.44557266716508 correct 58  time 0.814s/epoch
Epoch  170  loss  66.39537792589847 correct 59  time 0.816s/epoch
Epoch  180  loss  66.30239758014221 correct 58  time 0.810s/epoch
Epoch  190  loss  66.30353713711126 correct 56  time 0.802s/epoch
Epoch  200  loss  66.4043319086964 correct 56  time 0.798s/epoch
Epoch  210  loss  66.32473868160496 correct 56  time 0.808s/epoch
Epoch  220  loss  66.23476196581382 correct 56  time 0.801s/epoch
Epoch  230  loss  66.15402819900298 correct 56  time 0.804s/epoch
Epoch  240  loss  66.13474666210845 correct 56  time 0.804s/epoch
Epoch  250  loss  66.05423911092514 correct 56  time 0.836s/epoch
Epoch  260  loss  65.9732650126887 correct 56  time 0.859s/epoch
Epoch  270  loss  65.97724752285171 correct 55  time 0.823s/epoch
Epoch  280  loss  65.77817969348081 correct 58  time 0.829s/epoch
Epoch  290  loss  65.68203370980248 correct 58  time 0.846s/epoch
Epoch  300  loss  65.64745666507565 correct 57  time 0.888s/epoch
Epoch  310  loss  65.5830887398293 correct 56  time 0.829s/epoch
Epoch  320  loss  65.59821580483475 correct 56  time 0.820s/epoch
Epoch  330  loss  65.63595771676997 correct 56  time 0.803s/epoch
Epoch  340  loss  65.57177369294702 correct 56  time 0.817s/epoch
Epoch  350  loss  65.57462935155588 correct 57  time 0.815s/epoch
Epoch  360  loss  65.45585323176441 correct 56  time 0.811s/epoch
Epoch  370  loss  65.23224187303012 correct 58  time 0.813s/epoch
Epoch  380  loss  65.2061106275553 correct 56  time 0.814s/epoch
Epoch  390  loss  65.12698190694584 correct 57  time 0.812s/epoch
Epoch  400  loss  65.11771820527767 correct 56  time 0.826s/epoch
Epoch  410  loss  65.01993317654174 correct 56  time 0.823s/epoch
Epoch  420  loss  65.03253230440363 correct 57  time 0.821s/epoch
Epoch  430  loss  65.14283638127866 correct 58  time 0.852s/epoch
Epoch  440  loss  64.91358193455694 correct 56  time 0.914s/epoch
Epoch  450  loss  64.89099481862067 correct 57  time 0.911s/epoch
Epoch  460  loss  64.8487308080618 correct 57  time 0.876s/epoch
Epoch  470  loss  64.79420026910097 correct 57  time 0.853s/epoch
Epoch  480  loss  64.73011588322129 correct 57  time 0.843s/epoch
Epoch  490  loss  64.82809728280093 correct 56  time 0.847s/epoch
Epoch  500  loss  64.65880254109305 correct 57  time 0.845s/epoch
Done. Avg time: 0.830s/epoch
```


## Задания 3.1 и 3.2
Вывод от `python project/parallel_check.py`

```
MAP
 
================================================================================
 Parallel Accelerator Optimizing:  Function tensor_map.<locals>._map, 
/home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (154)  
================================================================================


Parallel loop listing for  Function tensor_map.<locals>._map, /home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (154) 
-----------------------------------------------------------------------------------------------|loop #ID
    def _map(                                                                                  | 
        out: Storage,                                                                          | 
        out_shape: Shape,                                                                      | 
        out_strides: Strides,                                                                  | 
        in_storage: Storage,                                                                   | 
        in_shape: Shape,                                                                       | 
        in_strides: Strides,                                                                   | 
    ) -> None:                                                                                 | 
        sz = 1                                                                                 | 
        for i in range(out_shape.size):                                                        | 
            sz *= out_shape[i]                                                                 | 
                                                                                               | 
        # в minitorch вроде как так можно, так как не поддерживаются слайсы                    | 
        if np.array_equal(in_strides, out_strides) and np.array_equal(in_shape, out_shape):    | 
            for i in prange(sz):---------------------------------------------------------------| #2
                out[i] = fn(in_storage[i])                                                     | 
                                                                                               | 
        else:                                                                                  | 
            for original_out in prange(sz):----------------------------------------------------| #3
                index_out = np.zeros(out_shape.size, np.int32)---------------------------------| #0
                index_in = np.zeros(in_shape.size, np.int32)-----------------------------------| #1
                                                                                               | 
                to_index(original_out, out_shape, index_out)                                   | 
                broadcast_index(index_out, out_shape, in_shape, index_in)                      | 
                                                                                               | 
                position_in = index_to_position(index_in, in_strides)                          | 
                position_out = index_to_position(index_out, out_strides)                       | 
                out[position_out] = fn(in_storage[position_in])                                | 
--------------------------------- Fusing loops ---------------------------------
Attempting fusion of parallel loops (combines loops with similar properties)...
Following the attempted fusion of parallel for-loops there are 4 parallel for-
loop(s) (originating from loops labelled: #2, #3, #0, #1).
--------------------------------------------------------------------------------
---------------------------- Optimising loop nests -----------------------------
Attempting loop nest rewrites (optimising for the largest parallel loops)...
 
+--3 is a parallel loop
   +--0 --> rewritten as a serial loop
   +--1 --> rewritten as a serial loop
--------------------------------------------------------------------------------
----------------------------- Before Optimisation ------------------------------
Parallel region 0:
+--3 (parallel)
   +--0 (parallel)
   +--1 (parallel)


--------------------------------------------------------------------------------
------------------------------ After Optimisation ------------------------------
Parallel region 0:
+--3 (parallel)
   +--0 (serial)
   +--1 (serial)


 
Parallel region 0 (loop #3) had 0 loop(s) fused and 2 loop(s) serialized as part
 of the larger parallel loop (#3).
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
 
---------------------------Loop invariant code motion---------------------------
Allocation hoisting:
The memory allocation derived from the instruction at 
/home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (173) is 
hoisted out of the parallel loop labelled #3 (it will be performed before the 
loop is executed and reused inside the loop):
   Allocation:: index_out = np.zeros(out_shape.size, np.int32)
    - numpy.empty() is used for the allocation.
The memory allocation derived from the instruction at 
/home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (174) is 
hoisted out of the parallel loop labelled #3 (it will be performed before the 
loop is executed and reused inside the loop):
   Allocation:: index_in = np.zeros(in_shape.size, np.int32)
    - numpy.empty() is used for the allocation.
None
ZIP
 
================================================================================
 Parallel Accelerator Optimizing:  Function tensor_zip.<locals>._zip, 
/home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (208)  
================================================================================


Parallel loop listing for  Function tensor_zip.<locals>._zip, /home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (208) 
----------------------------------------------------------------------------------------|loop #ID
    def _zip(                                                                           | 
        out: Storage,                                                                   | 
        out_shape: Shape,                                                               | 
        out_strides: Strides,                                                           | 
        a_storage: Storage,                                                             | 
        a_shape: Shape,                                                                 | 
        a_strides: Strides,                                                             | 
        b_storage: Storage,                                                             | 
        b_shape: Shape,                                                                 | 
        b_strides: Strides,                                                             | 
    ) -> None:                                                                          | 
        sz = 1                                                                          | 
        for i in range(out_shape.size):                                                 | 
            sz *= out_shape[i]                                                          | 
                                                                                        | 
        if (                                                                            | 
            np.array_equal(out_strides, a_strides)                                      | 
            and np.array_equal(out_strides, b_strides)                                  | 
            and np.array_equal(out_shape, a_shape)                                      | 
            and np.array_equal(out_shape, b_shape)                                      | 
        ):                                                                              | 
            for i in prange(sz):--------------------------------------------------------| #7
                out[i] = fn(a_storage[i], b_storage[i])                                 | 
                                                                                        | 
        else:                                                                           | 
            for original_out in prange(sz):---------------------------------------------| #8
                index_out = np.zeros(out_shape.size, np.int32)--------------------------| #4
                index_a = np.zeros(a_shape.size, np.int32)------------------------------| #5
                index_b = np.zeros(b_shape.size, np.int32)------------------------------| #6
                                                                                        | 
                to_index(original_out, out_shape, index_out)                            | 
                broadcast_index(index_out, out_shape, a_shape, index_a)                 | 
                broadcast_index(index_out, out_shape, b_shape, index_b)                 | 
                                                                                        | 
                position_out = index_to_position(index_out, out_strides)                | 
                position_a = index_to_position(index_a, a_strides)                      | 
                position_b = index_to_position(index_b, b_strides)                      | 
                out[position_out] = fn(a_storage[position_a], b_storage[position_b])    | 
--------------------------------- Fusing loops ---------------------------------
Attempting fusion of parallel loops (combines loops with similar properties)...
Following the attempted fusion of parallel for-loops there are 5 parallel for-
loop(s) (originating from loops labelled: #7, #8, #4, #5, #6).
--------------------------------------------------------------------------------
---------------------------- Optimising loop nests -----------------------------
Attempting loop nest rewrites (optimising for the largest parallel loops)...
 
+--8 is a parallel loop
   +--4 --> rewritten as a serial loop
   +--5 --> rewritten as a serial loop
   +--6 --> rewritten as a serial loop
--------------------------------------------------------------------------------
----------------------------- Before Optimisation ------------------------------
Parallel region 0:
+--8 (parallel)
   +--4 (parallel)
   +--5 (parallel)
   +--6 (parallel)


--------------------------------------------------------------------------------
------------------------------ After Optimisation ------------------------------
Parallel region 0:
+--8 (parallel)
   +--4 (serial)
   +--5 (serial)
   +--6 (serial)


 
Parallel region 0 (loop #8) had 0 loop(s) fused and 3 loop(s) serialized as part
 of the larger parallel loop (#8).
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
 
---------------------------Loop invariant code motion---------------------------
Allocation hoisting:
The memory allocation derived from the instruction at 
/home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (234) is 
hoisted out of the parallel loop labelled #8 (it will be performed before the 
loop is executed and reused inside the loop):
   Allocation:: index_out = np.zeros(out_shape.size, np.int32)
    - numpy.empty() is used for the allocation.
The memory allocation derived from the instruction at 
/home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (235) is 
hoisted out of the parallel loop labelled #8 (it will be performed before the 
loop is executed and reused inside the loop):
   Allocation:: index_a = np.zeros(a_shape.size, np.int32)
    - numpy.empty() is used for the allocation.
The memory allocation derived from the instruction at 
/home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (236) is 
hoisted out of the parallel loop labelled #8 (it will be performed before the 
loop is executed and reused inside the loop):
   Allocation:: index_b = np.zeros(b_shape.size, np.int32)
    - numpy.empty() is used for the allocation.
None
REDUCE
 
================================================================================
 Parallel Accelerator Optimizing:  Function tensor_reduce.<locals>._reduce, 
/home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (269)  
================================================================================


Parallel loop listing for  Function tensor_reduce.<locals>._reduce, /home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (269) 
----------------------------------------------------------------------------|loop #ID
    def _reduce(                                                            | 
        out: Storage,                                                       | 
        out_shape: Shape,                                                   | 
        out_strides: Strides,                                               | 
        a_storage: Storage,                                                 | 
        a_shape: Shape,                                                     | 
        a_strides: Strides,                                                 | 
        reduce_dim: int,                                                    | 
    ) -> None:                                                              | 
        sz = 1                                                              | 
        for i in range(out_shape.size):                                     | 
            sz *= out_shape[i]                                              | 
                                                                            | 
        for original_in in prange(sz):--------------------------------------| #10
            index_out = np.zeros(out_shape.size, np.int32)------------------| #9
            to_index(original_in, out_shape, index_out)                     | 
            position_out = index_to_position(index_out, out_strides)        | 
            position_in_st = index_to_position(index_out, a_strides)        | 
                                                                            | 
            tmp = out[position_out]                                         | 
            for i in range(a_shape[reduce_dim]):                            | 
                position_in = position_in_st + a_strides[reduce_dim] * i    | 
                tmp = fn(tmp, a_storage[position_in])                       | 
            out[position_out] = tmp                                         | 
--------------------------------- Fusing loops ---------------------------------
Attempting fusion of parallel loops (combines loops with similar properties)...
Following the attempted fusion of parallel for-loops there are 2 parallel for-
loop(s) (originating from loops labelled: #10, #9).
--------------------------------------------------------------------------------
---------------------------- Optimising loop nests -----------------------------
Attempting loop nest rewrites (optimising for the largest parallel loops)...
 
+--10 is a parallel loop
   +--9 --> rewritten as a serial loop
--------------------------------------------------------------------------------
----------------------------- Before Optimisation ------------------------------
Parallel region 0:
+--10 (parallel)
   +--9 (parallel)


--------------------------------------------------------------------------------
------------------------------ After Optimisation ------------------------------
Parallel region 0:
+--10 (parallel)
   +--9 (serial)


 
Parallel region 0 (loop #10) had 0 loop(s) fused and 1 loop(s) serialized as 
part of the larger parallel loop (#10).
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
 
---------------------------Loop invariant code motion---------------------------
Allocation hoisting:
The memory allocation derived from the instruction at 
/home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (283) is 
hoisted out of the parallel loop labelled #10 (it will be performed before the 
loop is executed and reused inside the loop):
   Allocation:: index_out = np.zeros(out_shape.size, np.int32)
    - numpy.empty() is used for the allocation.
None
MATRIX MULTIPLY
 
================================================================================
 Parallel Accelerator Optimizing:  Function _tensor_matrix_multiply, 
/home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (297)  
================================================================================


Parallel loop listing for  Function _tensor_matrix_multiply, /home/aleksey/work/HSE/Prog/DL-2/hw_01/Minitorch/minitorch/fast_ops.py (297) 
-----------------------------------------------------------------------------------------------|loop #ID
def _tensor_matrix_multiply(                                                                   | 
    out: Storage,                                                                              | 
    out_shape: Shape,                                                                          | 
    out_strides: Strides,                                                                      | 
    a_storage: Storage,                                                                        | 
    a_shape: Shape,                                                                            | 
    a_strides: Strides,                                                                        | 
    b_storage: Storage,                                                                        | 
    b_shape: Shape,                                                                            | 
    b_strides: Strides,                                                                        | 
) -> None:                                                                                     | 
    """                                                                                        | 
    NUMBA tensor matrix multiply function.                                                     | 
                                                                                               | 
    Should work for any tensor shapes that broadcast as long as                                | 
                                                                                               | 
    ```                                                                                        | 
    assert a_shape[-1] == b_shape[-2]                                                          | 
    ```                                                                                        | 
                                                                                               | 
    Optimizations:                                                                             | 
                                                                                               | 
    * Outer loop in parallel                                                                   | 
    * No index buffers or function calls                                                       | 
    * Inner loop should have no global writes, 1 multiply.                                     | 
                                                                                               | 
                                                                                               | 
    Args:                                                                                      | 
        out (Storage): storage for `out` tensor                                                | 
        out_shape (Shape): shape for `out` tensor                                              | 
        out_strides (Strides): strides for `out` tensor                                        | 
        a_storage (Storage): storage for `a` tensor                                            | 
        a_shape (Shape): shape for `a` tensor                                                  | 
        a_strides (Strides): strides for `a` tensor                                            | 
        b_storage (Storage): storage for `b` tensor                                            | 
        b_shape (Shape): shape for `b` tensor                                                  | 
        b_strides (Strides): strides for `b` tensor                                            | 
                                                                                               | 
    Returns:                                                                                   | 
        None : Fills in `out`                                                                  | 
    """                                                                                        | 
    a_batch_stride = a_strides[0] if a_shape[0] > 1 else 0                                     | 
    b_batch_stride = b_strides[0] if b_shape[0] > 1 else 0                                     | 
                                                                                               | 
    b, n, m = out_shape                                                                        | 
    k = a_shape[-1]                                                                            | 
                                                                                               | 
    for pos in prange(b * n):------------------------------------------------------------------| #11
        batch = pos // n                                                                       | 
        i = pos % n                                                                            | 
        for j in range(m):                                                                     | 
            position_out = batch * out_strides[0] + i * out_strides[1] + j * out_strides[2]    | 
            position_a = batch * a_batch_stride + i * a_strides[1]                             | 
            position_b = batch * b_batch_stride + j * b_strides[2]                             | 
                                                                                               | 
            tmp = 0.0                                                                          | 
            for _ in range(k):                                                                 | 
                tmp += a_storage[position_a] * b_storage[position_b]                           | 
                position_a += a_strides[2]                                                     | 
                position_b += b_strides[1]                                                     | 
            out[position_out] = tmp                                                            | 
--------------------------------- Fusing loops ---------------------------------
Attempting fusion of parallel loops (combines loops with similar properties)...
Following the attempted fusion of parallel for-loops there are 1 parallel for-
loop(s) (originating from loops labelled: #11).
--------------------------------------------------------------------------------
----------------------------- Before Optimisation ------------------------------
--------------------------------------------------------------------------------
------------------------------ After Optimisation ------------------------------
Parallel structure is already optimal.
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
 
---------------------------Loop invariant code motion---------------------------
Allocation hoisting:
No allocation hoisting found
None
```