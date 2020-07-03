# Gwion coverage
```
------------------------------------------------------------------------------
                           GCC Code Coverage Report
Directory: .
------------------------------------------------------------------------------
File                                       Lines    Exec  Cover   Missing
------------------------------------------------------------------------------
src/arg.c                                    130     101    77%   15-19,130-136,138-139,148-153,155-157,163-168
src/clean.c                                  274     274   100%   
src/compile.c                                 86      83    96%   92-93,130
src/emit/emit.c                             1546    1507    97%   87,143-144,423-424,512,514,686-687,790-792,801,834-835,1058-1059,1097-1098,1186-1187,1240,1306,1308-1315,1332,1992,2011,2056,2066-2068,2083
src/emit/emitter.c                            28      28   100%   
src/emit/escape.c                             52      52   100%   
src/emit/memoize.c                            34      34   100%   
src/env/context.c                             26      26   100%   
src/env/env.c                                 85      85   100%   
src/env/env_utils.c                           77      77   100%   
src/env/envset.c                              44      41    93%   16,22,52
src/env/func.c                                23      23   100%   
src/env/nspc.c                                62      61    98%   34
src/env/tupleform.c                           38      38   100%   
src/env/type.c                               127     120    94%   127,131,148,155-158
src/env/type_special.c                        33      33   100%   
src/env/value.c                               25      25   100%   
src/gwion.c                                  138     137    99%   85
src/gwiondata.c                               35      35   100%   
src/import/cdef.c                             84      75    89%   87-88,107-113
src/import/checker.c                         209     183    87%   101,112,116,119-121,131,133-135,185,190-191,202-203,208,234,239-240,246-250,284,290
src/import/enum.c                             51      51   100%   
src/import/fdef.c                             92      92   100%   
src/import/internals.c                        14      14   100%   
src/import/item.c                             33      33   100%   
src/import/oper.c                             39      39   100%   
src/import/special.c                          29      29   100%   
src/import/tdef.c                             25      25   100%   
src/import/type.c                             23      23   100%   
src/import/udef.c                             60      60   100%   
src/lib/array.c                              341     321    94%   59,62,111,170-171,299-306,315-321
src/lib/engine.c                             130     128    98%   30-31
src/lib/event.c                               47      47   100%   
src/lib/func.c                               266     254    95%   88,176,212-216,274-278
src/lib/instr.c                               98      96    98%   39,78
src/lib/modules.c                            220     219    99%   252
src/lib/object.c                              85      81    95%   114,120-122
src/lib/object_op.c                          304     297    97%   57,273-274,368,402-404
src/lib/opfunc.c                              60      56    93%   13-16
src/lib/prim.c                               234     233    99%   234
src/lib/prim_values.c                         30      30   100%   
src/lib/ptr.c                                104     102    98%   56,82
src/lib/shred.c                              255     247    96%   66,209-212,270,276,282
src/lib/string.c                             440     170    38%   34,87-88,91-97,100-106,109-116,119-127,134,136-138,141-143,149-153,156-161,163,166-172,174-176,180-184,186-188,190-203,206-213,215-222,224-231,241-242,250,264-271,273,275,278-285,287-290,292,294,297-300,302-308,310-317,319,321-322,325-328,330-337,339-346,348,350-351,354-361,363,365,368-371,373-381,383,385,388-391,393-404,406,408-409,412-415,417-424,426,428-433,435,437-438,441-449,451-457,460-461,464-465,468,470-471
src/lib/ugen.c                               234     234   100%   
src/lib/vararg.c                             132     131    99%   50
src/main.c                                    14      14   100%   
src/parse/check.c                           1034     998    96%   75,94,178,285-286,297-298,309,574,641,732,808-812,819,890-893,907,911,933,1014-1018,1106,1153-1154,1156-1157,1209,1437
src/parse/compat_func.c                       11      11   100%   
src/parse/did_you_mean.c                      42      42   100%   
src/parse/func_operator.c                     13      13   100%   
src/parse/operator.c                         223     221    99%   333,342
src/parse/scan0.c                            323     316    97%   122,202,211,246,317-319
src/parse/scan1.c                            402     394    98%   53,87,128,336-337,348,511,549
src/parse/scan2.c                            408     406    99%   378,576
src/parse/scanx.c                             49      49   100%   
src/parse/stage.c                             14      14   100%   
src/parse/template.c                          88      84    95%   28,37,67,123
src/parse/traverse.c                          43      42    97%   67
src/parse/type_decl.c                         32      30    93%   12,19
src/pass.c                                    34      34   100%   
src/plug.c                                   113     113   100%   
src/soundinfo.c                               11      11   100%   
src/vm/driver.c                               32      32   100%   
src/vm/gack.c                                 45      43    95%   32-33
src/vm/shreduler.c                            85      85   100%   
src/vm/vm.c                                  574     530    92%   76-79,82-84,87-92,366,368-371,393-396,409,411-414,434-436,468,470-473,805,808-809,811-812,824,828-830
src/vm/vm_code.c                              45      45   100%   
src/vm/vm_name.c                               8       8   100%   
src/vm/vm_shred.c                             33      33   100%   
------------------------------------------------------------------------------
TOTAL                                      10178    9618    94%
------------------------------------------------------------------------------
lines: 94.5% (9618 out of 10178)
branches: 80.5% (4447 out of 5527)
```
