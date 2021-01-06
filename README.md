# Gwion coverage
```
------------------------------------------------------------------------------
                           GCC Code Coverage Report
Directory: .
------------------------------------------------------------------------------
File                                       Lines    Exec  Cover   Missing
------------------------------------------------------------------------------
src/arg.c                                    177     177   100%   
src/clean.c                                  281     279    99%   139-140
src/compile.c                                102      99    97%   90-91,151
src/emit/emit.c                             1619    1523    94%   144,150-151,153,211-212,264-265,271,378-380,385,451,471-475,538-539,545-546,626-629,631-632,640,642,742,801,810,907-909,919,952-953,1161-1162,1203-1204,1283-1284,1303,1400-1402,1434-1435,1442,1446-1448,1539-1541,1731,1804-1813,1815-1823,1831-1840,2099,2120,2162,2174-2176,2191
src/emit/emitter.c                            27      27   100%   
src/emit/escape.c                             52      52   100%   
src/emit/memoize.c                            33      33   100%   
src/env/context.c                             22      22   100%   
src/env/env.c                                 72      72   100%   
src/env/env_utils.c                           70      70   100%   
src/env/envset.c                              46      42    91%   16,23,27,53
src/env/func.c                                30      30   100%   
src/env/nspc.c                                62      54    87%   27-34
src/env/tupleform.c                           38      37    97%   27
src/env/type.c                               110     104    94%   127-129,131-133
src/env/value.c                               21      20    95%   11
src/gwion.c                                  134     133    99%   73
src/gwiondata.c                               35      35   100%   
src/import/cleaner.c                          20      20   100%   
src/import/import_cdef.c                      79      77    97%   67,80
src/import/import_checker.c                  207     184    88%   102,113,117,119-121,133,147-150,161-162,169-171,189-193,269,275
src/import/import_enum.c                      51      43    84%   79,96-102
src/import/import_fdef.c                      99      98    99%   95
src/import/import_internals.c                 23      23   100%   
src/import/import_item.c                      35      35   100%   
src/import/import_oper.c                      39      39   100%   
src/import/import_special.c                   28      28   100%   
src/import/import_tdef.c                      26      25    96%   32
src/import/import_type.c                      23      23   100%   
src/import/import_udef.c                      46      46   100%   
src/lib/array.c                              399     356    89%   53,56,89-90,117,173-174,206-216,218-219,253,257-258,367-374,383-389,440-444
src/lib/engine.c                             129     123    95%   25-26,63-66
src/lib/event.c                               44      44   100%   
src/lib/foreach.c                             19      18    94%   25
src/lib/instr.c                               99      94    94%   31,33-34,38,51
src/lib/lib_func.c                           276     250    90%   87,191,276-282,285-294,296-302
src/lib/modules.c                            219     217    99%   251,258
src/lib/object.c                              85      82    96%   122-124
src/lib/object_op.c                          227     206    90%   27-28,33,53,253,260,287-296,298,306-309
src/lib/opfunc.c                              58      54    93%   14-17
src/lib/prim.c                               248     247    99%   244
src/lib/prim_values.c                         22      22   100%   
src/lib/ptr.c                                143     130    90%   64,90,138-143,156,162-165
src/lib/shred.c                              280     270    96%   82,207,225-228,268,293,299,305
src/lib/string.c                             353     198    56%   169-173,175-177,179-191,194-201,203-209,211-217,220-228,230-246,249-253,256-263,265,268-275,277,280-288,290,293-297,300-307,309,312-321,323,326-336,338,341-349,351-357
src/lib/tmpl_info.c                           53      52    98%   30
src/lib/ugen.c                               253     241    95%   220-223,239-242,258-261
src/lib/union.c                              141      86    61%   16-17,23-24,27-30,41-44,60,69,78,82,101,104-105,108-112,114-128,131,134,137-143,146-152
src/lib/vararg.c                             142     139    97%   36,53,117
src/main.c                                    14      14   100%   
src/parse/check.c                            916     882    96%   73,156,162,268-269,282-284,306,337-341,596,769,779-780,822,842-844,983,1025-1033,1152,1292
src/parse/compat_func.c                       11      11   100%   
src/parse/did_you_mean.c                      41      32    78%   40,50-51,53-58
src/parse/func_operator.c                     13      13   100%   
src/parse/func_resolve_tmpl.c                108     107    99%   58
src/parse/operator.c                         146     145    99%   51
src/parse/scan0.c                            296     288    97%   120,199,209,246,257,280-282
src/parse/scan1.c                            455     441    96%   56,165,386-387,398,413,471-474,525,560,591,623
src/parse/scan2.c                            387     384    99%   278,348,549
src/parse/scanx.c                             38      38   100%   
src/parse/template.c                          99      92    92%   23,32,62,70,85-86,130
src/parse/traverse.c                          43      42    97%   67
src/parse/type_decl.c                         22      21    95%   25
src/pass.c                                    35      35   100%   
src/plug.c                                   123     123   100%   
src/soundinfo.c                               11      11   100%   
src/vm/closure.c                              13      12    92%   24
src/vm/driver.c                               32      32   100%   
src/vm/gack.c                                 47      44    93%   32-33,69
src/vm/shreduler.c                            85      85   100%   
src/vm/vm.c                                  612     522    85%   75-78,81-83,86-91,367,369-376,410,412-415,438-440,472,474-477,503,717-719,770,772-774,776-782,818,821-822,824-825,837,839-841,843,851,853-856,858,860,862-863,865-866,882,886-888,893-904,926,951-952
src/vm/vm_code.c                              93      93   100%   
src/vm/vm_name.c                               8       8   100%   
src/vm/vm_shred.c                             33      33   100%   
------------------------------------------------------------------------------
TOTAL                                      10478    9787    93%
------------------------------------------------------------------------------
lines: 93.4% (9787 out of 10478)
branches: 77.6% (4303 out of 5543)
```
