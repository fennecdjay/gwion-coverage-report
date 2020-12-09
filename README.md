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
src/emit/emit.c                             1616    1563    96%   138,144-145,147,203-204,254-255,261,279,466-467,572,574,712-714,718-719,746-747,752,849-851,860,893-894,1110-1111,1150-1151,1233-1234,1341,1345-1347,1349,1394-1397,1737-1739,2085,2106,2148,2160-2162,2177
src/emit/emitter.c                            28      28   100%   
src/emit/escape.c                             52      52   100%   
src/emit/memoize.c                            33      33   100%   
src/env/context.c                             26      26   100%   
src/env/env.c                                 87      87   100%   
src/env/env_utils.c                           72      72   100%   
src/env/envset.c                              46      42    91%   16,23,27,53
src/env/func.c                                30      30   100%   
src/env/nspc.c                                62      61    98%   34
src/env/tupleform.c                           38      38   100%   
src/env/type.c                               137     125    91%   127-129,131-133,144,155,160-163
src/env/type_special.c                        34      34   100%   
src/env/value.c                               25      25   100%   
src/gwion.c                                  126     125    99%   69
src/gwiondata.c                               35      35   100%   
src/import/cleaner.c                          20      20   100%   
src/import/import_cdef.c                      79      78    98%   67
src/import/import_checker.c                  186     163    87%   102,113,117,119-121,133,147-150,161-162,169-171,189-193,234,240
src/import/import_enum.c                      53      52    98%   84
src/import/import_fdef.c                      99      98    99%   95
src/import/import_internals.c                 24      24   100%   
src/import/import_item.c                      35      35   100%   
src/import/import_oper.c                      39      39   100%   
src/import/import_special.c                   28      28   100%   
src/import/import_tdef.c                      26      25    96%   32
src/import/import_type.c                      23      23   100%   
src/import/import_udef.c                      60      60   100%   
src/lib/array.c                              407     363    89%   53,89-90,117,174-175,206-216,218-221,255,268,270,370-377,386-392,447-451
src/lib/engine.c                             126     124    98%   29-30
src/lib/event.c                               45      45   100%   
src/lib/instr.c                               98      93    94%   31,33-34,38,51
src/lib/lib_func.c                           292     284    97%   88,193,228-232,298
src/lib/modules.c                            220     219    99%   252
src/lib/object.c                              84      83    98%   114
src/lib/object_op.c                          330     312    94%   57,117,265-266,361,372,380,426-435,437
src/lib/opfunc.c                              64      58    90%   13-16,80-81
src/lib/prim.c                               242     241    99%   239
src/lib/prim_values.c                         30      30   100%   
src/lib/ptr.c                                154     141    91%   78,104,152-157,170,176-179
src/lib/shred.c                              278     270    97%   82,224-227,291,297,303
src/lib/string.c                             372     247    66%   34,179-183,185-187,189-202,205-212,214-221,223-230,240-241,249,263-267,270-277,279,282-289,291-292,295-303,305-306,309-313,316-323,325,328-337,339-340,343-353,355-356,372
src/lib/ugen.c                               255     243    95%   222-225,241-244,260-263
src/lib/vararg.c                             142     140    98%   35,52
src/main.c                                    14      14   100%   
src/parse/check.c                            948     931    98%   73,171,300-302,613,789-790,830,984,1031-1032,1034-1035,1086,1193,1334
src/parse/compat_func.c                       11      11   100%   
src/parse/did_you_mean.c                      41      40    97%   40
src/parse/func_operator.c                     13      13   100%   
src/parse/func_resolve_tmpl.c                105     104    99%   59
src/parse/operator.c                         222     220    99%   267,327
src/parse/scan0.c                            315     308    97%   119,199,208,236,301-303
src/parse/scan1.c                            454     440    96%   56,87,159,378-379,390,470-473,524,559,590,624
src/parse/scan2.c                            413     410    99%   312,382,583
src/parse/scanx.c                             41      41   100%   
src/parse/stage.c                             14      14   100%   
src/parse/template.c                          99      92    92%   28,37,67,75,90-91,135
src/parse/traverse.c                          43      42    97%   67
src/parse/type_decl.c                         32      31    96%   12
src/pass.c                                    41      41   100%   
src/plug.c                                   123     123   100%   
src/soundinfo.c                               11      11   100%   
src/vm/closure.c                              13      12    92%   24
src/vm/driver.c                               32      32   100%   
src/vm/gack.c                                 47      45    95%   32-33
src/vm/shreduler.c                            85      85   100%   
src/vm/vm.c                                  588     531    90%   75-78,81-83,86-91,363,365-368,406,408-411,434-436,468,470-473,499,815,818-819,821-822,834,838-840,845-856,863,865,867,878
src/vm/vm_code.c                              47      47   100%   
src/vm/vm_name.c                               8       8   100%   
src/vm/vm_shred.c                             33      33   100%   
------------------------------------------------------------------------------
TOTAL                                      10594   10133    95%
------------------------------------------------------------------------------
lines: 95.6% (10133 out of 10594)
branches: 80.5% (4555 out of 5659)
```
