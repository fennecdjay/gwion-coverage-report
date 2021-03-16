# Gwion coverage
```
------------------------------------------------------------------------------
                           GCC Code Coverage Report
Directory: .
------------------------------------------------------------------------------
File                                       Lines    Exec  Cover   Missing
------------------------------------------------------------------------------
src/arg.c                                    198     162    81%   27-31,190-196,198-199,209-214,216-218,231-236,258-260,272,274,276,331
src/clean.c                                  285     281    98%   137-138,242-243
src/compile.c                                102      99    97%   90-91,151
src/emit/emit.c                             1732    1586    91%   148,154-155,157,168,177,241-242,293-294,300,407-409,414,480,500-504,567-568,574-575,660,662,824,833,940-942,952,985-986,990,1194-1195,1236-1237,1322-1323,1342,1416-1417,1444-1446,1478-1479,1486,1490-1492,1515-1518,1523,1593-1595,1636-1638,1645-1648,1748-1752,1755-1758,1761-1774,1777-1779,1789-1790,1807,1809-1810,1816,1841,1886,1959-1968,1970-1978,1986-1995,2063-2064,2070-2072,2263,2284,2314,2317,2326,2338-2340,2355
src/emit/emitter.c                            27      27   100%   
src/emit/escape.c                             52      52   100%   
src/emit/memoize.c                            33      33   100%   
src/env/context.c                             22      22   100%   
src/env/env.c                                 72      72   100%   
src/env/env_utils.c                           70      70   100%   
src/env/envset.c                              46      24    52%   12-14,16,20-23,25-31,50-53,55,61,66
src/env/func.c                                30      30   100%   
src/env/nspc.c                                62      61    98%   34
src/env/tupleform.c                           38      37    97%   27
src/env/type.c                               100      94    94%   119-121,123-125
src/env/value.c                               23      22    95%   11
src/gwion.c                                  140     131    93%   74,97,100-101,148-152
src/gwiondata.c                               35      35   100%   
src/import/cleaner.c                          20      20   100%   
src/import/import_cdef.c                      94      92    97%   81,94
src/import/import_checker.c                  208     185    88%   102,113,117,119-121,133,147-150,161-162,169-171,189-193,271,277
src/import/import_enum.c                      51      43    84%   79,96-102
src/import/import_fdef.c                      98      97    99%   94
src/import/import_internals.c                 23      23   100%   
src/import/import_item.c                      35      35   100%   
src/import/import_oper.c                      39      39   100%   
src/import/import_special.c                   28      28   100%   
src/import/import_tdef.c                      26      25    96%   32
src/import/import_type.c                      23      23   100%   
src/import/import_udef.c                      46      46   100%   
src/lib/array.c                              496     395    79%   39,50-53,76-77,100-104,106-107,110-115,122,127-134,137-142,145-151,154-160,175-179,242-252,254-255,289,293-294,306,365-367,404-411,420-426,482-488,554-558
src/lib/engine.c                             132     126    95%   25-26,63-66
src/lib/event.c                               44      44   100%   
src/lib/instr.c                               99      94    94%   31,33-34,38,51
src/lib/lib_func.c                           280     253    90%   87,154,196,281-287,290-299,301-307
src/lib/modules.c                            210     146    69%   171-172,175-177,180-181,184-191,194-198,201-205,223-224,227-232,237-241,243,246-265,268-272
src/lib/object.c                              75      74    98%   104
src/lib/object_op.c                          227     217    95%   27-28,53,251,258,297,305-308
src/lib/opfunc.c                              58      50    86%   14-17,70-73
src/lib/prim.c                               367     365    99%   187,407
src/lib/prim_values.c                         22      22   100%   
src/lib/ptr.c                                141     128    90%   64,89,137-142,155,161-164
src/lib/ref.c                                 53      47    88%   24-25,35-37,61
src/lib/shred.c                              278     267    96%   82,223-228,268,293,299,305
src/lib/string.c                             363     246    67%   196-200,202-204,206-218,221-228,230-236,238-244,254-255,263,276-280,283-290,292,295-302,304,307-315,317,320-324,327-334,336,339-348,350,353-363,365,381
src/lib/tmpl_info.c                           55      52    94%   30,76,87
src/lib/ugen.c                               253     231    91%   85-86,119-122,200-201,220-223,239-242,258-261,301-302
src/lib/union.c                              141      86    61%   16-17,23-24,27-30,41-44,60,69,78,82,101,104-105,108-112,114-128,131,134,137-143,146-152
src/lib/vararg.c                             142     139    97%   36,53,117
src/main.c                                    14      14   100%   
src/parse/check.c                            978     941    96%   73,145,151,256-257,270-272,429,606,689,788,798-799,847,922-924,1015-1018,1071,1113-1121,1132,1199-1200,1244,1388
src/parse/compat_func.c                       11      11   100%   
src/parse/did_you_mean.c                      38      37    97%   40
src/parse/func_operator.c                     13      13   100%   
src/parse/func_resolve_tmpl.c                108     107    99%   58
src/parse/operator.c                         153     152    99%   51
src/parse/scan0.c                            296     287    97%   120,200,210,245,247,258,281-283
src/parse/scan1.c                            463     444    95%   54,162,288,290,393-394,405,422,425,467-468,484-487,538,573,604,636
src/parse/scan2.c                            390     385    98%   260-261,284,354,555
src/parse/scanx.c                             34      34   100%   
src/parse/template.c                          95      88    92%   23,32,62,70,85-86,126
src/parse/traverse.c                          45      44    97%   71
src/parse/type_decl.c                         30      29    96%   34
src/pass.c                                    35      35   100%   
src/plug.c                                   135     134    99%   164
src/soundinfo.c                               11      11   100%   
src/vm/closure.c                              13      12    92%   24
src/vm/driver.c                               32      32   100%   
src/vm/gack.c                                 47      45    95%   32-33
src/vm/shreduler.c                            85      85   100%   
src/vm/vm.c                                  619     523    84%   75-78,81-83,86-91,367,369-372,410,412-415,438-440,472,474-477,503,714,716-721,723-724,726,731-733,782,784-786,788-794,830,833-834,836-837,849,851-853,855,863,865-868,870,872,874-875,877-878,894,898-900,905-916,930,955-956
src/vm/vm_code.c                             122      95    77%   79-89,92-97,158-167
src/vm/vm_name.c                               8       8   100%   
src/vm/vm_shred.c                             33      33   100%   
------------------------------------------------------------------------------
TOTAL                                      11002   10075    91%
------------------------------------------------------------------------------
lines: 91.6% (10075 out of 11002)
branches: 73.1% (4525 out of 6187)
```
