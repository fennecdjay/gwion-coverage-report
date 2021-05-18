# Gwion coverage
```
------------------------------------------------------------------------------
                           GCC Code Coverage Report
Directory: .
------------------------------------------------------------------------------
File                                       Lines    Exec  Cover   Missing
------------------------------------------------------------------------------
src/arg.c                                    221     164    74%   28-32,74-79,82-84,87-89,111-113,224-230,232-233,243-248,250-252,265-270,292-294,306,308,310,337-342,372
src/clean.c                                  307     298    97%   137-138,174-176,186,236,263-264
src/compile.c                                107      99    92%   65-66,93-94,157,174-176
src/emit/emit.c                             1825    1648    90%   47-48,141-163,168,170,177,188,197,254,261,264-265,272,318-319,325,384-385,432-434,439,505,525-529,592-593,599-600,691,693,895-897,967-969,979,1012-1013,1017,1219-1220,1236,1261-1262,1347-1348,1367,1441-1442,1469-1471,1503-1504,1511,1515-1517,1526-1527,1543-1546,1551,1623-1625,1666-1668,1675-1678,1778-1782,1785-1788,1791-1804,1807-1809,1819-1820,1838,1840-1841,1847,1881,1928,1955,2048-2057,2059-2067,2075-2084,2152-2153,2159-2161,2389,2447,2460-2462,2477
src/emit/emitter.c                            27      27   100%   
src/emit/escape.c                             52      52   100%   
src/emit/memoize.c                            33      33   100%   
src/env/context.c                             23      23   100%   
src/env/env.c                                 91      89    97%   68,105
src/env/env_utils.c                           74      74   100%   
src/env/envset.c                              49      46    93%   16,24,55
src/env/func.c                                30      30   100%   
src/env/nspc.c                                62      61    98%   34
src/env/tupleform.c                           38      37    97%   27
src/env/type.c                                98      92    93%   116-118,120-122
src/env/value.c                               23      23   100%   
src/gwion.c                                  153     140    91%   74,79,81-83,104,107-108,112,222-223,225-226
src/gwiondata.c                               31      31   100%   
src/import/cleaner.c                          20      20   100%   
src/import/import_cdef.c                     104      92    88%   67-69,84,97,111,126-128,139-141
src/import/import_checker.c                  218     170    78%   64,100-102,113,117,119-121,130,133,144,147-150,161-162,167,169-171,180-181,194,200-204,279,282-285,288-291,294-296,298,304,312-315
src/import/import_enum.c                      54      44    81%   79,87-88,100-106
src/import/import_fdef.c                     117     106    90%   45,58-59,62-64,103,105-106,140-141
src/import/import_internals.c                 30      24    80%   31-36
src/import/import_item.c                      40      35    87%   38-41,59
src/import/import_oper.c                      66      47    71%   73-77,79-81,83-88,90-94
src/import/import_special.c                   31      22    71%   24-25,30-31,58-62
src/import/import_tdef.c                      29      26    89%   32,37-38
src/import/import_type.c                      30      21    70%   21-23,34-39
src/import/import_udef.c                      49      45    91%   23-24,56-57
src/lib/array.c                              701     603    86%   21,32-35,46-51,58,63-70,73-78,81-87,90-96,111-115,178-188,190-191,225,229-230,242,303-305,342-349,358-364,530,543,554,563,636,650,697-703,836-840
src/lib/engine.c                             158     152    96%   25-26,63-66
src/lib/event.c                               44      44   100%   
src/lib/instr.c                              104      91    87%   31,33-34,38,51,59,63-64,142-146
src/lib/lib_func.c                           443     388    87%   55,88,111-112,122,249,341-347,360-361,388-389,397,399,402,406,408,410,435,445-446,459-460,462-463,465,496-502,505-514,516-522
src/lib/modules.c                            213     146    68%   171-172,175-177,180-181,184-191,194-198,201-205,223-224,227-232,237-241,243,246-252,254-257,259-263,265-271,274-278
src/lib/object.c                              71      70    98%   99
src/lib/object_op.c                          227     215    94%   27-28,33,53,121,252,259,298,306-309
src/lib/opfunc.c                              58      50    86%   14-17,70-73
src/lib/prim.c                               380     378    99%   188,416
src/lib/prim_values.c                         22      22   100%   
src/lib/ptr.c                                150     134    89%   65,68,87,133-134,137-142,167,173-176
src/lib/ref.c                                 62      57    91%   24-25,35-37
src/lib/shred.c                              278     267    96%   82,223-228,268,293,299,305
src/lib/string.c                             364     247    67%   198-202,204-206,208-220,223-230,232-238,240-246,256-257,265,278-282,285-292,294,297-304,306,309-317,319,322-326,329-336,338,341-350,352,355-365,367,383
src/lib/tmpl_info.c                           55      53    96%   30,87
src/lib/ugen.c                               252     228    90%   85-86,119-122,181-182,201-202,221-224,240-243,259-262,302-303
src/lib/union.c                              141      86    61%   16-17,23-24,27-30,41-44,60,69,78,82,101,104-105,108-112,114-128,131,134,137-143,146-152
src/lib/vararg.c                             143     140    97%   36,53,119
src/main.c                                    14      14   100%   
src/parse/check.c                           1175    1126    95%   75,139-141,152,158,280-281,294-296,479,653,736,792,856,866-867,915,992-994,1091,1149,1159,1201-1209,1220,1263,1287,1289,1330-1331,1376,1424-1427,1429,1487,1604,1676
src/parse/compat_func.c                       11      11   100%   
src/parse/did_you_mean.c                      36      36   100%   
src/parse/func_operator.c                     13      13   100%   
src/parse/func_resolve_tmpl.c                122     120    98%   44,70
src/parse/operator.c                         219     165    75%   56,122-124,263,265-275,277,281-285,288-295,298-313,318-319,322,324-328
src/parse/scan0.c                            327     293    89%   73-74,78,89-91,111-114,123,162-163,175-182,186,210-211,216,224,234,269-270,273,284,307-309
src/parse/scan1.c                            494     474    96%   54,162,289,300,302,318,436-437,448,465,468,511-512,528-531,612,651,684
src/parse/scan2.c                            402     396    98%   206,272-273,296,364,575
src/parse/scanx.c                             41      41   100%   
src/parse/template.c                          98      90    91%   23,32,35,71,86-87,129,132
src/parse/traverse.c                          45      44    97%   71
src/parse/type_decl.c                         51      43    84%   39-41,47-49,51,61
src/pass.c                                    38      38   100%   
src/plug.c                                   138     116    84%   99,112-118,144-148,164,168,219-224,227
src/soundinfo.c                               11      11   100%   
src/vm/closure.c                              13      12    92%   24
src/vm/driver.c                               32      32   100%   
src/vm/gack.c                                 47      45    95%   32-33
src/vm/shreduler.c                            78      78   100%   
src/vm/vm.c                                  722     572    79%   43-46,55,60,71,80-83,86-87,89-95,97-103,117-121,159-162,165-167,170-175,452,454-461,495,497-500,523-525,557,559-562,588,799,801-806,808-809,811,816-818,867,869-871,873-879,915,918-919,921-922,934,936-938,940,948,950-953,955,957,959-960,962-963,979,983-985,990-1001,1056-1057,1069-1074,1076-1077,1079-1089
src/vm/vm_code.c                             131     103    78%   84-94,97-102,170-180
src/vm/vm_name.c                               8       8   100%   
src/vm/vm_shred.c                             37      36    97%   30
------------------------------------------------------------------------------
TOTAL                                      12201   10907    89%
------------------------------------------------------------------------------
lines: 89.4% (10907 out of 12201)
branches: 71.3% (4839 out of 6788)
```
