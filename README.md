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
src/emit/emit.c                             1525    1488    97%   87,143-144,414-415,503-504,507,678-679,782-784,793,826-827,1073,1075-1077,1164-1165,1280,1282-1289,1306,1961,1981,2036-2037,2052
src/emit/emitter.c                            28      28   100%   
src/emit/escape.c                             52      52   100%   
src/emit/memoize.c                            34      34   100%   
src/env/context.c                             26      26   100%   
src/env/env.c                                 84      84   100%   
src/env/env_utils.c                           77      77   100%   
src/env/envset.c                              44      41    93%   16,22,52
src/env/func.c                                23      23   100%   
src/env/nspc.c                                62      61    98%   34
src/env/tupleform.c                           38      38   100%   
src/env/type.c                               128     121    94%   128,132,149,156-159
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
src/lib/array.c                              333     314    94%   60,109,168-169,297-304,313-319
src/lib/engine.c                             130     128    98%   30-31
src/lib/event.c                               47      47   100%   
src/lib/func.c                               255     207    81%   88,172,208-212,215-222,225-229,232-234,237-243,246-251,254-260,270-274
src/lib/instr.c                               81      79    97%   39,78
src/lib/modules.c                            220     219    99%   252
src/lib/object.c                              85      81    95%   114,120-122
src/lib/object_op.c                          302     297    98%   57,362,396-398
src/lib/opfunc.c                              64      60    93%   13-16
src/lib/prim.c                               224     224   100%   
src/lib/prim_values.c                         30      30   100%   
src/lib/ptr.c                                102      99    97%   56,80,88
src/lib/shred.c                              255     247    96%   66,209-212,270,276,282
src/lib/string.c                             440     170    38%   34,87-88,91-97,100-106,109-116,119-127,134,136-138,141-143,149-153,156-161,163,166-172,174-176,180-184,186-188,190-203,206-213,215-222,224-231,241-242,250,264-271,273,275,278-285,287-290,292,294,297-300,302-308,310-317,319,321-322,325-328,330-337,339-346,348,350-351,354-361,363,365,368-371,373-381,383,385,388-391,393-404,406,408-409,412-415,417-424,426,428-433,435,437-438,441-449,451-457,460-461,464-465,468,470-471
src/lib/ugen.c                               234     234   100%   
src/lib/vararg.c                             132     131    99%   50
src/main.c                                    14      14   100%   
src/parse/check.c                           1000     967    96%   75,94,172,415-417,530,597,690,767-771,778,849-852,867,889,970-974,1067,1114-1115,1117-1118,1170,1396
src/parse/did_you_mean.c                      42      42   100%   
src/parse/func_operator.c                     12      12   100%   
src/parse/operator.c                         223     220    98%   275,333,342
src/parse/scan0.c                            323     316    97%   122,202,211,246,317-319
src/parse/scan1.c                            406     397    97%   34,64,95,134,342-343,354,517,555
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
src/vm/vm.c                                  579     535    92%   77-80,83-85,88-93,367,369-372,394-397,410,412-415,435-437,469,471-474,806,809-810,812-813,825,829-831
src/vm/vm_code.c                              48      48   100%   
src/vm/vm_name.c                               8       8   100%   
src/vm/vm_shred.c                             33      33   100%   
------------------------------------------------------------------------------
TOTAL                                      10077    9487    94%
------------------------------------------------------------------------------
lines: 94.1% (9487 out of 10077)
branches: 80.4% (4376 out of 5445)
```
