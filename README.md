# Gwion coverage
```
------------------------------------------------------------------------------
                           GCC Code Coverage Report
Directory: .
------------------------------------------------------------------------------
File                                       Lines    Exec  Cover   Missing
------------------------------------------------------------------------------
src/arg.c                                    130     101    77%   15-19,130-136,138-139,148-153,155-157,163-168
src/compile.c                                 86      83    96%   90-91,127
src/emit/emit.c                             1501    1472    98%   87,412-413,497-498,501,645-646,651,750-752,756-759,761,1241,1243-1250,1268,1914,2023
src/emit/emitter.c                            28      28   100%   
src/emit/escape.c                             52      52   100%   
src/emit/memoize.c                            34      34   100%   
src/env/context.c                             26      26   100%   
src/env/env.c                                 84      84   100%   
src/env/env_utils.c                           70      70   100%   
src/env/envset.c                              42      39    92%   16,22,50
src/env/nspc.c                                62      61    98%   34
src/env/tupleform.c                           38      38   100%   
src/env/type.c                               128     121    94%   127,131,148,155-158
src/env/value.c                               25      25   100%   
src/gwion.c                                  138     137    99%   85
src/gwiondata.c                               35      35   100%   
src/import/cdef.c                             84      72    85%   32-34,87-88,107-113
src/import/checker.c                         208     180    86%   101,112,116,119-121,131,133-135,185,188-191,202-203,208,234,239-240,246-250,283,289
src/import/enum.c                             51      51   100%   
src/import/fdef.c                             93      93   100%   
src/import/internals.c                        14      14   100%   
src/import/item.c                             33      33   100%   
src/import/oper.c                             39      39   100%   
src/import/special.c                          28      28   100%   
src/import/tdef.c                             25      25   100%   
src/import/type.c                             23      23   100%   
src/import/udef.c                             60      60   100%   
src/lib/array.c                              327     308    94%   60,109,167-168,294-301,310-316
src/lib/engine.c                             121     121   100%   
src/lib/event.c                               47      47   100%   
src/lib/func.c                               242     240    99%   92,176
src/lib/gack.c                                50      47    94%   32-33,54
src/lib/instr.c                               79      79   100%   
src/lib/modules.c                            220     219    99%   252
src/lib/object.c                              91      89    97%   116-117
src/lib/object_op.c                          332     328    98%   57,383,417-418
src/lib/opfunc.c                              64      60    93%   13-16
src/lib/prim.c                               224     224   100%   
src/lib/prim_values.c                         30      30   100%   
src/lib/ptr.c                                102     100    98%   56,80
src/lib/shred.c                              250     242    96%   65,207-210,268,274,280
src/lib/string.c                             440     170    38%   34,87-88,91-97,100-106,109-116,119-127,134,136-138,141-143,149-153,156-161,163,166-172,174-176,180-184,186-188,190-203,206-213,215-222,224-231,241-242,250,264-271,273,275,278-285,287-290,292,294,297-300,302-308,310-317,319,321-322,325-328,330-337,339-346,348,350-351,354-361,363,365,368-371,373-381,383,385,388-391,393-404,406,408-409,412-415,417-424,426,428-433,435,437-438,441-449,451-457,460-461,464-465,468,470-471
src/lib/ugen.c                               234     234   100%   
src/lib/vararg.c                             126     125    99%   47
src/main.c                                    14      14   100%   
src/parse/check.c                            975     951    97%   75,94,166,506,544-545,558,572,664,739-743,750,840,862,1043,1090-1091,1093-1094,1146,1365
src/parse/did_you_mean.c                      42      42   100%   
src/parse/func.c                              23      23   100%   
src/parse/operator.c                         211     208    98%   261,319,328
src/parse/scan0.c                            320     317    99%   141,220,254
src/parse/scan1.c                            388     379    97%   16,61,130,324-325,334,454,497,535
src/parse/scan2.c                            414     413    99%   585
src/parse/scanx.c                             46      46   100%   
src/parse/stage.c                             14      14   100%   
src/parse/template.c                          88      84    95%   28,37,67,123
src/parse/traverse.c                          43      42    97%   67
src/parse/type_decl.c                         49      47    95%   33,40
src/parse/type_utils.c                        17       4    23%   14-18,21-22,24-29
src/pass.c                                    34      34   100%   
src/plug.c                                   113     113   100%   
src/soundinfo.c                               11      11   100%   
src/vm/driver.c                               32      32   100%   
src/vm/shreduler.c                            85      85   100%   
src/vm/vm.c                                  574     551    96%   77-80,83-85,88-93,368,370-373,411,413-416
src/vm/vm_code.c                              48      48   100%   
src/vm/vm_name.c                               8       8   100%   
src/vm/vm_shred.c                             33      33   100%   
------------------------------------------------------------------------------
TOTAL                                       9698    9186    94%
------------------------------------------------------------------------------
lines: 94.7% (9186 out of 9698)
branches: 80.2% (4247 out of 5297)
```
