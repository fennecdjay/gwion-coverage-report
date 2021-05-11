# Gwion coverage
```
------------------------------------------------------------------------------
                           GCC Code Coverage Report
Directory: .
------------------------------------------------------------------------------
File                                       Lines    Exec  Cover   Missing
------------------------------------------------------------------------------
src/arg.c                                    214     163    76%   28-32,73-78,81-83,105-107,213-219,221-222,232-237,239-241,254-259,281-283,295,297,299,326-328,358
src/clean.c                                  302     296    98%   137-138,229,256-257,358
src/compile.c                                104     101    97%   92-93,153
src/emit/emit.c                             1800    1512    84%   47-48,141-163,166-177,188,197,209-210,254,261,264-265,272,306-309,318-319,325,432-434,439,505,525-529,592-593,599-600,646-649,691,693,774-776,779-784,793,797-803,805,840,856,865,961-963,967-970,973,1006-1007,1011,1153-1156,1159-1168,1171-1172,1174-1181,1215-1216,1257-1258,1343-1344,1363,1437-1438,1465-1467,1499-1500,1507,1511-1513,1522-1523,1539-1542,1547,1619-1621,1662-1664,1671-1674,1774-1778,1781-1784,1787-1800,1803-1805,1815-1816,1834,1836-1837,1843,1868,1893,1913,1940,2033-2042,2044-2052,2060-2069,2135-2138,2144-2146,2220-2221,2240,2262-2267,2270-2273,2276-2278,2281-2287,2290-2293,2296-2303,2306-2314,2319,2337,2372,2429,2442-2444,2459
src/emit/emitter.c                            27      27   100%   
src/emit/escape.c                             52      52   100%   
src/emit/memoize.c                            30       0     0%   18-24,27-31,34-39,42-46,49-54,56
src/env/context.c                             23      23   100%   
src/env/env.c                                 90      88    97%   67,104
src/env/env_utils.c                           72      72   100%   
src/env/envset.c                              49      46    93%   16,24,55
src/env/func.c                                30      30   100%   
src/env/nspc.c                                61      49    80%   24-34,46
src/env/tupleform.c                           38      37    97%   27
src/env/type.c                                98      92    93%   116-118,120-122
src/env/value.c                               23      22    95%   11
src/gwion.c                                  144     138    95%   74,97,100-101,211-212
src/gwiondata.c                               35      35   100%   
src/import/cleaner.c                          20      20   100%   
src/import/import_cdef.c                      96      90    93%   84,97,111,139-141
src/import/import_checker.c                  219     194    88%   102,113,117,119-121,133,147-150,161-162,169-171,180-181,200-204,285,291
src/import/import_enum.c                      51      43    84%   79,100-106
src/import/import_fdef.c                     111     107    96%   62-64,103
src/import/import_internals.c                 23      23   100%   
src/import/import_item.c                      35      35   100%   
src/import/import_oper.c                      46      46   100%   
src/import/import_special.c                   33      28    84%   64-68
src/import/import_tdef.c                      26      25    96%   32
src/import/import_type.c                      23      23   100%   
src/import/import_udef.c                      46      46   100%   
src/lib/array.c                              702     604    86%   21,32-35,46-51,58,63-70,73-78,81-87,90-96,111-115,178-188,190-191,225,229-230,242,303-305,342-349,358-364,530,543,554,563,636,650,698-704,837-841
src/lib/engine.c                             134     125    93%   25-26,63-66,76-78
src/lib/event.c                               44      44   100%   
src/lib/instr.c                              105      97    92%   31,33-34,38,51,59,63-64
src/lib/lib_func.c                           443     381    86%   55,88,110-112,114-119,122,249,341-347,360-361,388-389,397,399,402,406,408,410,435,445-446,459-460,462-463,465,496-502,505-514,516-522
src/lib/modules.c                            213     146    68%   171-172,175-177,180-181,184-191,194-198,201-205,223-224,227-232,237-241,243,246-252,254-257,259-263,265-271,274-278
src/lib/object.c                              71      67    94%   99,105-107
src/lib/object_op.c                          225     190    84%   27-28,53,110-112,114-116,137-142,213-215,252,259,287-296,298,306-309
src/lib/opfunc.c                              58      50    86%   14-17,70-73
src/lib/prim.c                               380     378    99%   188,416
src/lib/prim_values.c                         22      22   100%   
src/lib/ptr.c                                150     134    89%   65,68,87,133-134,137-142,167,173-176
src/lib/ref.c                                 56      51    91%   24-25,35-37
src/lib/shred.c                              278     266    95%   82,223-228,265,268,293,299,305
src/lib/string.c                             364     247    67%   198-202,204-206,208-220,223-230,232-238,240-246,256-257,265,278-282,285-292,294,297-304,306,309-317,319,322-326,329-336,338,341-350,352,355-365,367,383
src/lib/tmpl_info.c                           55      53    96%   30,87
src/lib/ugen.c                               253     231    91%   85-86,119-122,201-202,221-224,240-243,259-262,302-303
src/lib/union.c                              141      86    61%   16-17,23-24,27-30,41-44,60,69,78,82,101,104-105,108-112,114-128,131,134,137-143,146-152
src/lib/vararg.c                             143     140    97%   36,53,119
src/main.c                                    14      14   100%   
src/parse/check.c                           1127    1041    92%   75,91-93,139-141,152,158,280-281,294-296,353-355,479,653,736,792,856,866-867,915,954-965,976-982,990-992,1082-1085,1138,1148,1190-1198,1209,1252,1276,1278,1319-1320,1365,1411-1416,1418,1476,1497,1567-1569,1571-1572,1574-1575,1609
src/parse/compat_func.c                       11      11   100%   
src/parse/did_you_mean.c                      36      36   100%   
src/parse/func_operator.c                     13      13   100%   
src/parse/func_resolve_tmpl.c                122     120    98%   48,74
src/parse/operator.c                         163     162    99%   56
src/parse/scan0.c                            314     291    92%   73-74,78,117,156-157,169,171,195-196,201,209,219,254-255,258,269,292-294,308,328-329
src/parse/scan1.c                            482     457    94%   54,108-109,162,289,300,302,387,408-409,414,423,440,443,486-487,503-506,557,578,596,635,667
src/parse/scan2.c                            401     395    98%   206,272-273,296,364,574
src/parse/scanx.c                             41      41   100%   
src/parse/template.c                          98      90    91%   23,32,35,71,86-87,129,132
src/parse/traverse.c                          45      44    97%   71
src/parse/type_decl.c                         35      34    97%   39
src/pass.c                                    35      35   100%   
src/plug.c                                   138     137    99%   164
src/soundinfo.c                               11      11   100%   
src/vm/closure.c                              13      12    92%   24
src/vm/driver.c                               32      32   100%   
src/vm/gack.c                                 47      44    93%   32-33,69
src/vm/shreduler.c                            85      85   100%   
src/vm/vm.c                                  719     549    76%   43-46,55,60,71,80-83,86-87,89-95,97-103,117-121,159-162,165-167,170-175,453,455-458,471-475,496,498-501,512-529,558,560-563,589,800,802-807,809-810,812,817-819,868,870-872,874-880,916,919-920,922-923,935,937-939,941,949,951-954,956,958,960-961,963-964,980,984-986,991-1002,1053-1058,1070-1075,1077-1078,1080-1090
src/vm/vm_code.c                             130     102    78%   32,84-94,97-102,171-180
src/vm/vm_name.c                               8       8   100%   
src/vm/vm_shred.c                             35      34    97%   30
------------------------------------------------------------------------------
TOTAL                                      11913   10573    88%
------------------------------------------------------------------------------
lines: 88.8% (10573 out of 11913)
branches: 71.2% (4690 out of 6583)
```
