# PrimeTimeTables
Generates prime number time tables

This project uses the Haskell Stack toolchain
Can be build from project root with: ```stack build``` 
and run with ```stack exec PrimeTimeTables-exe```
Run tests with ```stack test```
Manually test library functinos with ```stack ghci```

Example output: 
```
Drawing times table for 5
        2     3     5     7    11
    |-----------------------------|
  2 |   4 |   6 |  10 |  14 |  22 |
    |-----------------------------|
  3 |   6 |   9 |  15 |  21 |  33 |
    |-----------------------------|
  5 |  10 |  15 |  25 |  35 |  55 |
    |-----------------------------|
  7 |  14 |  21 |  35 |  49 |  77 |
    |-----------------------------|
 11 |  22 |  33 |  55 |  77 | 121 |
    |-----------------------------|

Drawing times table for 10
        2     3     5     7    11    13    17    19    23    29
    |-----------------------------------------------------------|
  2 |   4 |   6 |  10 |  14 |  22 |  26 |  34 |  38 |  46 |  58 |
    |-----------------------------------------------------------|
  3 |   6 |   9 |  15 |  21 |  33 |  39 |  51 |  57 |  69 |  87 |
    |-----------------------------------------------------------|
  5 |  10 |  15 |  25 |  35 |  55 |  65 |  85 |  95 | 115 | 145 |
    |-----------------------------------------------------------|
  7 |  14 |  21 |  35 |  49 |  77 |  91 | 119 | 133 | 161 | 203 |
    |-----------------------------------------------------------|
 11 |  22 |  33 |  55 |  77 | 121 | 143 | 187 | 209 | 253 | 319 |
    |-----------------------------------------------------------|
 13 |  26 |  39 |  65 |  91 | 143 | 169 | 221 | 247 | 299 | 377 |
    |-----------------------------------------------------------|
 17 |  34 |  51 |  85 | 119 | 187 | 221 | 289 | 323 | 391 | 493 |
    |-----------------------------------------------------------|
 19 |  38 |  57 |  95 | 133 | 209 | 247 | 323 | 361 | 437 | 551 |
    |-----------------------------------------------------------|
 23 |  46 |  69 | 115 | 161 | 253 | 299 | 391 | 437 | 529 | 667 |
    |-----------------------------------------------------------|
 29 |  58 |  87 | 145 | 203 | 319 | 377 | 493 | 551 | 667 | 841 |
    |-----------------------------------------------------------|

Drawing times table for 40
          2      3      5      7     11     13     17     19     23     29     31     37     41     43     47     53     59     61     67     71     73     79     83     89     97
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
   2 |    4 |    6 |   10 |   14 |   22 |   26 |   34 |   38 |   46 |   58 |   62 |   74 |   82 |   86 |   94 |  106 |  118 |  122 |  134 |  142 |  146 |  158 |  166 |  178 |  194 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
   3 |    6 |    9 |   15 |   21 |   33 |   39 |   51 |   57 |   69 |   87 |   93 |  111 |  123 |  129 |  141 |  159 |  177 |  183 |  201 |  213 |  219 |  237 |  249 |  267 |  291 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
   5 |   10 |   15 |   25 |   35 |   55 |   65 |   85 |   95 |  115 |  145 |  155 |  185 |  205 |  215 |  235 |  265 |  295 |  305 |  335 |  355 |  365 |  395 |  415 |  445 |  485 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
   7 |   14 |   21 |   35 |   49 |   77 |   91 |  119 |  133 |  161 |  203 |  217 |  259 |  287 |  301 |  329 |  371 |  413 |  427 |  469 |  497 |  511 |  553 |  581 |  623 |  679 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  11 |   22 |   33 |   55 |   77 |  121 |  143 |  187 |  209 |  253 |  319 |  341 |  407 |  451 |  473 |  517 |  583 |  649 |  671 |  737 |  781 |  803 |  869 |  913 |  979 | 1067 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  13 |   26 |   39 |   65 |   91 |  143 |  169 |  221 |  247 |  299 |  377 |  403 |  481 |  533 |  559 |  611 |  689 |  767 |  793 |  871 |  923 |  949 | 1027 | 1079 | 1157 | 1261 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  17 |   34 |   51 |   85 |  119 |  187 |  221 |  289 |  323 |  391 |  493 |  527 |  629 |  697 |  731 |  799 |  901 | 1003 | 1037 | 1139 | 1207 | 1241 | 1343 | 1411 | 1513 | 1649 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  19 |   38 |   57 |   95 |  133 |  209 |  247 |  323 |  361 |  437 |  551 |  589 |  703 |  779 |  817 |  893 | 1007 | 1121 | 1159 | 1273 | 1349 | 1387 | 1501 | 1577 | 1691 | 1843 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  23 |   46 |   69 |  115 |  161 |  253 |  299 |  391 |  437 |  529 |  667 |  713 |  851 |  943 |  989 | 1081 | 1219 | 1357 | 1403 | 1541 | 1633 | 1679 | 1817 | 1909 | 2047 | 2231 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  29 |   58 |   87 |  145 |  203 |  319 |  377 |  493 |  551 |  667 |  841 |  899 | 1073 | 1189 | 1247 | 1363 | 1537 | 1711 | 1769 | 1943 | 2059 | 2117 | 2291 | 2407 | 2581 | 2813 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  31 |   62 |   93 |  155 |  217 |  341 |  403 |  527 |  589 |  713 |  899 |  961 | 1147 | 1271 | 1333 | 1457 | 1643 | 1829 | 1891 | 2077 | 2201 | 2263 | 2449 | 2573 | 2759 | 3007 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  37 |   74 |  111 |  185 |  259 |  407 |  481 |  629 |  703 |  851 | 1073 | 1147 | 1369 | 1517 | 1591 | 1739 | 1961 | 2183 | 2257 | 2479 | 2627 | 2701 | 2923 | 3071 | 3293 | 3589 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  41 |   82 |  123 |  205 |  287 |  451 |  533 |  697 |  779 |  943 | 1189 | 1271 | 1517 | 1681 | 1763 | 1927 | 2173 | 2419 | 2501 | 2747 | 2911 | 2993 | 3239 | 3403 | 3649 | 3977 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  43 |   86 |  129 |  215 |  301 |  473 |  559 |  731 |  817 |  989 | 1247 | 1333 | 1591 | 1763 | 1849 | 2021 | 2279 | 2537 | 2623 | 2881 | 3053 | 3139 | 3397 | 3569 | 3827 | 4171 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  47 |   94 |  141 |  235 |  329 |  517 |  611 |  799 |  893 | 1081 | 1363 | 1457 | 1739 | 1927 | 2021 | 2209 | 2491 | 2773 | 2867 | 3149 | 3337 | 3431 | 3713 | 3901 | 4183 | 4559 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  53 |  106 |  159 |  265 |  371 |  583 |  689 |  901 | 1007 | 1219 | 1537 | 1643 | 1961 | 2173 | 2279 | 2491 | 2809 | 3127 | 3233 | 3551 | 3763 | 3869 | 4187 | 4399 | 4717 | 5141 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  59 |  118 |  177 |  295 |  413 |  649 |  767 | 1003 | 1121 | 1357 | 1711 | 1829 | 2183 | 2419 | 2537 | 2773 | 3127 | 3481 | 3599 | 3953 | 4189 | 4307 | 4661 | 4897 | 5251 | 5723 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  61 |  122 |  183 |  305 |  427 |  671 |  793 | 1037 | 1159 | 1403 | 1769 | 1891 | 2257 | 2501 | 2623 | 2867 | 3233 | 3599 | 3721 | 4087 | 4331 | 4453 | 4819 | 5063 | 5429 | 5917 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  67 |  134 |  201 |  335 |  469 |  737 |  871 | 1139 | 1273 | 1541 | 1943 | 2077 | 2479 | 2747 | 2881 | 3149 | 3551 | 3953 | 4087 | 4489 | 4757 | 4891 | 5293 | 5561 | 5963 | 6499 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  71 |  142 |  213 |  355 |  497 |  781 |  923 | 1207 | 1349 | 1633 | 2059 | 2201 | 2627 | 2911 | 3053 | 3337 | 3763 | 4189 | 4331 | 4757 | 5041 | 5183 | 5609 | 5893 | 6319 | 6887 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  73 |  146 |  219 |  365 |  511 |  803 |  949 | 1241 | 1387 | 1679 | 2117 | 2263 | 2701 | 2993 | 3139 | 3431 | 3869 | 4307 | 4453 | 4891 | 5183 | 5329 | 5767 | 6059 | 6497 | 7081 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  79 |  158 |  237 |  395 |  553 |  869 | 1027 | 1343 | 1501 | 1817 | 2291 | 2449 | 2923 | 3239 | 3397 | 3713 | 4187 | 4661 | 4819 | 5293 | 5609 | 5767 | 6241 | 6557 | 7031 | 7663 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  83 |  166 |  249 |  415 |  581 |  913 | 1079 | 1411 | 1577 | 1909 | 2407 | 2573 | 3071 | 3403 | 3569 | 3901 | 4399 | 4897 | 5063 | 5561 | 5893 | 6059 | 6557 | 6889 | 7387 | 8051 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  89 |  178 |  267 |  445 |  623 |  979 | 1157 | 1513 | 1691 | 2047 | 2581 | 2759 | 3293 | 3649 | 3827 | 4183 | 4717 | 5251 | 5429 | 5963 | 6319 | 6497 | 7031 | 7387 | 7921 | 8633 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  97 |  194 |  291 |  485 |  679 | 1067 | 1261 | 1649 | 1843 | 2231 | 2813 | 3007 | 3589 | 3977 | 4171 | 4559 | 5141 | 5723 | 5917 | 6499 | 6887 | 7081 | 7663 | 8051 | 8633 | 9409 |
     |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
```
