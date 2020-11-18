# Gwion coverage
```
------------------------------------------------------------------------------
                           GCC Code Coverage Report
Directory: .
------------------------------------------------------------------------------
File                                       Lines    Exec  Cover   Missing
------------------------------------------------------------------------------
src/arg.c                                    177     177   100%   
src/clean.c                                  275     275   100%   
src/compile.c                                 91      88    96%   90-91,134
src/emit/emit.c                             1590    1530    96%   81,85-86,88,144-145,206-207,213,231,438-439,544,546,684-686,690-691,718-719,724,821-823,832,865-866,1082-1083,1122-1123,1205-1206,1310,1312-1321,1339,1366-1369,1717-1719,2065,2084,2124,2136-2138,2153
src/emit/emitter.c                            28      28   100%   
src/emit/escape.c                             52      52   100%   
src/emit/memoize.c                            33      33   100%   
src/env/context.c                             26      26   100%   
src/env/env.c                                 88      88   100%   
src/env/env_utils.c                           72      72   100%   
src/env/envset.c                              46      42    91%   16,23,27,53
src/env/func.c                                30      30   100%   
src/env/nspc.c                                62      61    98%   34
src/env/tupleform.c                           38      38   100%   
src/env/type.c                               137     124    90%   77,127-129,131-133,144,155,160-163
src/env/type_special.c                        34      34   100%   
src/env/value.c                               25      25   100%   
src/gwion.c                                  126     125    99%   69
src/gwiondata.c                               35      35   100%   
src/import/cleaner.c                          20      20   100%   
src/import/import_cdef.c                      82      78    95%   33-35,96
src/import/import_checker.c                  186     163    87%   102,113,117,119-121,133,147-150,161-162,169-171,189-193,234,240
src/import/import_enum.c                      51      51   100%   
src/import/import_fdef.c                      99      98    99%   95
src/import/import_internals.c                 24      24   100%   
src/import/import_item.c                      35      35   100%   
src/import/import_oper.c                      39      39   100%   
src/import/import_special.c                   28      28   100%   
src/import/import_tdef.c                      26      25    96%   32
src/import/import_type.c                      23      23   100%   
src/import/import_udef.c                      60      60   100%   
src/lib/array.c                              414     366    88%   53,56,89-90,117,174-175,206-216,218-221,255,268,270,272,323-324,380-387,396-402,459-463
src/lib/engine.c                             120     118    98%   29-30
src/lib/event.c                               47      47   100%   
src/lib/instr.c                              105     100    95%   39,41-42,46,59
src/lib/lib_func.c                           292     284    97%   88,193,228-232,298
src/lib/modules.c                            220     219    99%   252
src/lib/object.c                              83      82    98%   113
src/lib/object_op.c                          323     306    94%   57,258-259,354,365,373,419-428,430
src/lib/opfunc.c                              65      59    90%   13-16,81-82
src/lib/prim.c                               242     241    99%   241
src/lib/prim_values.c                         30      30   100%   
src/lib/ptr.c                                129     123    95%   59,85,134-136,150
src/lib/shred.c                              277     264    95%   82,224-227,231-235,291,297,303
src/lib/string.c                             372     247    66%   34,179-183,185-187,189-202,205-212,214-221,223-230,240-241,249,263-267,270-277,279,282-289,291-292,295-303,305-306,309-313,316-323,325,328-337,339-340,343-353,355-356,372
src/lib/ugen.c                               228     228   100%   
src/lib/vararg.c                             139     137    98%   35,52
src/main.c                                    14      14   100%   
src/parse/check.c                            933     909    97%   75,173,302-304,604,685-689,770-771,811,895,965,1012-1013,1015-1016,1067,1174,1283,1315
src/parse/compat_func.c                       11      11   100%   
src/parse/did_you_mean.c                      41      40    97%   40
src/parse/func_operator.c                     13      13   100%   
src/parse/func_resolve_tmpl.c                105     104    99%   59
src/parse/operator.c                         225     222    98%   278,336,345
src/parse/scan0.c                            317     307    96%   120,139-141,201,210,239,304-306
src/parse/scan1.c                            447     434    97%   56,86,157,376-377,388,468-471,522,582,616
src/parse/scan2.c                            410     406    99%   311,315,386,587
src/parse/scanx.c                             41      41   100%   
src/parse/stage.c                             14      14   100%   
src/parse/template.c                          99      92    92%   28,37,67,75,90-91,135
src/parse/traverse.c                          43      42    97%   67
src/parse/type_decl.c                         32      30    93%   12,19
src/pass.c                                    41      41   100%   
src/plug.c                                   123     123   100%   
src/soundinfo.c                               11      11   100%   
src/vm/closure.c                              13      12    92%   24
src/vm/driver.c                               32      32   100%   
src/vm/gack.c                                 47      45    95%   32-33
src/vm/shreduler.c                            85      85   100%   
src/vm/vm.c                                  588     535    91%   75-78,81-83,86-91,363,365-368,406,408-411,434-436,468,470-473,499,815,818-819,821-822,834,838-840,845-856
src/vm/vm_code.c                              47      47   100%   
src/vm/vm_name.c                               8       8   100%   
src/vm/vm_shred.c                             33      33   100%   
------------------------------------------------------------------------------
TOTAL                                      10497   10029    95%
------------------------------------------------------------------------------
lines: 95.5% (10029 out of 10497)
branches: 81.0% (4512 out of 5573)
```
