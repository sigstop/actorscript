
|ASCII string (non-canonical)      |Read as (canonical)                            |Category (cannonical)             |Matching Delimiters (canonical)|Unicode (hex) (canonical)|
|------------------|------------------------------------|----------------------|-------------------|-------------|
|#                 |end                                 |top level terminator  |                   |[25AE]       |
|:                 |of specified type                   |infix                 |                   |[003A]       |
|[:]               |this Actor's aspect                 |prefix                |                   |[2360]       |
|(<)               |injection                           |infix                 |                   |[29C0]       |
|(>)               |expression/pattern projection       |infix                 |                   |[29C1]       |
|!                 |resolve                             |prefix                |                   |[2B63]       |
|[.]               |qualified by                        |infix                 |                   |[22A1]       |
|.                 |is sent                             |infix                 |                   |[002E] \(ASCII 2E\)      |
|..                |delegate to this Actor              |prefix                |                   |[002E](http://www.fileformat.info/info/unicode/char/002e/index.htm) [002E](http://www.fileformat.info/info/unicode/char/002e/index.htm) |
|\|\|\|           |necessarily concurrent              |prefix                |                   |[25A1]       |
|\|->              |message type returns type           |infix                 |                   |[21A6]       |
|\|..>             |cacheable message type returns type |prefix                |                   |[007C](http://www.fileformat.info/info/unicode/char/007c/index.htm)  [002E](http://www.fileformat.info/info/unicode/char/002e/index.htm)  [002E](http://www.fileformat.info/info/unicode/char/002e/index.htm) [003E](http://www.fileformat.info/info/unicode/char/003e/index.htm) |
|-->               |message received                    |prefix                |^p unicode [00B6]  |[2192]       |
|<--               |be                                  |infix                 |                   |[2190]       |
|?                 |cases                               |seperator             |[?] unicode [2370] |[FFFD]       |
|[V]               |alterative cases                    |seperator             |? unicode [FFFD] and [?] unicode [2370]|[27CF]       |
|[?]               |end cases                           |terminator            |? unicode [FFFD] and **catch**? unicode [FFFD]|[2370]                    |
|^p                |another message handler             |seperator for handlers|                   |[00B6]       |
|^s                |end handlers                        |terminator            |**implements**     |[00A7]       |
|(:)               |case                                |seperator for case    |                   |[2982]       |
|@     |before                  |seperator             |**Let** bindings, **Do** preperations, **Enqueue**|[2BC3]|
|()                |end                                 |terminator            |**Do** expressions and (:) unicode [2982] |[FF61]|
|===               |defined as                          |infix                 |**implements**     |[2261]       |
|=^=               |to be                               |infix                 |                   |[225C]       |
|:=                |is assigned                         |infix                 |                   |[2254]         |
|$$                |matches value of                    |prefix                |                   |[2315]         |
|=                 |same as                             |infix                 |                   |[003D]       |
|[=]               |keyword **or** field                |infix                 |                   |[2338]       |
|:[=]              |assignable field                    |infix                 |                   |[003A](http://www.fileformat.info/info/unicode/char/003a/index.htm) [2338](http://www.fileformat.info/info/unicode/char/2338/index.htm) |
|<\|               |begin type parameters               |left delimiter        |\|> unicode [25B9] |[25C3]       |
|!!!               |spread                              |prefix                |                   |[2A5B]       |
|{                 |begin set                           |left delimiter        |} unicode [007D]   |[007B]       |
|[                 |begin list                          |left delimiter        |] unicode [005D]   |[005B]       |
|{\|               |begin multi-set                     |left delimiter        |\|} unicode [2984] |[2983]       |
|[\|               |array reference                     |left delimiter        |\|] unicode [27E7] |[27E6]       |
|(                 |begin grouping                      |left delimiter        |) unicode [0029]   |[0028]       |
|(\|               |begin syntax                        |left delimiter        |\|) unicode [2986] |[2985]       |
|(-)               |nothing                             |expression            |                   |[229D]       |
|<<-               |one-way send                        |infix                 |                   |[219E]       |
|->>               |one-way receive                     |infix                 |^p unicode [00B6]  |[21A0]       |
|\|_\|             |join                                |infix                 |                   |[2294]         |
|[<=]              |constrained by                      |infix                 |                   |[2291]         |
|[>=]              |extends                             |infix                 |                   |[2292]         |
|==>               |logical implication                 |infix                 |                   |[21D2]         |
|<=>               |logical equivalence                 |infix                 |                   |[21D4]         |
|&                 |logical conjunction                 |infix                 |                   |[2227]         |
|\|\|              |logical disjunction                 |infix                 |                   |[2228]        |
|-\|               |logical negation                    |prefix                |                   |[00AC]         |
|\|-               |assert                              |prefix **and** infix  |                   |[22A2]         |
|\|\|-             |goal                                |prefix **and** infix  |                   |[22A9]         |
|//                |begin 1-line comment                |prefix                |EndOfLine charater |[002F](http://www.fileformat.info/info/unicode/char/002f/index.htm) [002F](http://www.fileformat.info/info/unicode/char/002f/index.htm)            |
|/*                |begin comment                       |left delimiter        |*/ unicode [002A](http://www.fileformat.info/info/unicode/char/002a/index.htm) [002F](http://www.fileformat.info/info/unicode/char/002f/index.htm)  |[002F](http://www.fileformat.info/info/unicode/char/002f/index.htm) [002A](http://www.fileformat.info/info/unicode/char/002a/index.htm)           |



[0024]:http://www.fileformat.info/info/unicode/char/0024/index.htm
[0028]:http://www.fileformat.info/info/unicode/char/0028/index.htm
[0029]:http://www.fileformat.info/info/unicode/char/0029/index.htm
[002A]:http://www.fileformat.info/info/unicode/char/002a/index.htm
[002E]:http://www.fileformat.info/info/unicode/char/002e/index.htm
[002F]:http://www.fileformat.info/info/unicode/char/002f/index.htm
[003D]:http://www.fileformat.info/info/unicode/char/003d/index.htm
[003E]:http://www.fileformat.info/info/unicode/char/003e/index.htm
[003A]:http://www.fileformat.info/info/unicode/char/003a/index.htm
[005B]:http://www.fileformat.info/info/unicode/char/005b/index.htm
[005D]:http://www.fileformat.info/info/unicode/char/005d/index.htm
[007B]:http://www.fileformat.info/info/unicode/char/007b/index.htm
[007C]:http://www.fileformat.info/info/unicode/char/007c/index.htm
[007D]:http://www.fileformat.info/info/unicode/char/007d/index.htm
[00A7]:http://www.fileformat.info/info/unicode/char/00a7/index.htm
[00AC]:http://www.fileformat.info/info/unicode/char/00ac/index.htm
[00B6]:http://www.fileformat.info/info/unicode/char/00b6/index.htm
[2190]:http://www.fileformat.info/info/unicode/char/2190/index.htm
[2192]:http://www.fileformat.info/info/unicode/char/2192/index.htm
[219E]:http://www.fileformat.info/info/unicode/char/219e/index.htm
[21A0]:http://www.fileformat.info/info/unicode/char/21a0/index.htm
[21A6]:http://www.fileformat.info/info/unicode/char/21a6/index.htm
[21D2]:http://www.fileformat.info/info/unicode/char/21d2/index.htm
[21D4]:http://www.fileformat.info/info/unicode/char/21d4/index.htm
[21E2]:http://www.fileformat.info/info/unicode/char/21e2/index.htm
[2227]:http://www.fileformat.info/info/unicode/char/2227/index.htm
[2228]:http://www.fileformat.info/info/unicode/char/2228/index.htm
[2254]:http://www.fileformat.info/info/unicode/char/2254/index.htm
[225C]:http://www.fileformat.info/info/unicode/char/225c/index.htm
[2261]:http://www.fileformat.info/info/unicode/char/2261/index.htm
[2291]:http://www.fileformat.info/info/unicode/char/2291/index.htm
[2292]:http://www.fileformat.info/info/unicode/char/2292/index.htm
[2294]:http://www.fileformat.info/info/unicode/char/2294/index.htm
[229D]:http://www.fileformat.info/info/unicode/char/229d/index.htm
[22A2]:http://www.fileformat.info/info/unicode/char/22a2/index.htm
[22A9]:http://www.fileformat.info/info/unicode/char/22a9/index.htm
[2315]:http://www.fileformat.info/info/unicode/char/2315/index.htm
[2338]:http://www.fileformat.info/info/unicode/char/2338/index.htm
[2339]:http://www.fileformat.info/info/unicode/char/2339/index.htm
[2360]:http://www.fileformat.info/info/unicode/char/2360/index.htm
[2370]:http://www.fileformat.info/info/unicode/char/2370/index.htm
[25A1]:http://www.fileformat.info/info/unicode/char/25a1/index.htm
[25AE]:http://www.fileformat.info/info/unicode/char/25ae/index.htm
[25B9]:http://www.fileformat.info/info/unicode/char/25b9/index.htm
[25C3]:http://www.fileformat.info/info/unicode/char/25c3/index.htm
[27CF]:http://www.fileformat.info/info/unicode/char/27cf/index.htm
[27E6]:http://www.fileformat.info/info/unicode/char/27e6/index.htm
[27E7]:http://www.fileformat.info/info/unicode/char/27e7/index.htm
[2982]:http://www.fileformat.info/info/unicode/char/2982/index.htm
[2983]:http://www.fileformat.info/info/unicode/char/2983/index.htm
[2984]:http://www.fileformat.info/info/unicode/char/2984/index.htm
[2985]:http://www.fileformat.info/info/unicode/char/2985/index.htm
[2986]:http://www.fileformat.info/info/unicode/char/2986/index.htm
[29C0]:http://www.fileformat.info/info/unicode/char/29C0/index.htm
[29C1]:http://www.fileformat.info/info/unicode/char/29C1/index.htm
[2B63]:http://www.fileformat.info/info/unicode/char/2b63/index.htm
[22A1]:http://www.fileformat.info/info/unicode/char/22a1/index.htm
[2A5B]:http://www.fileformat.info/info/unicode/char/2a5b/index.htm
[2BC3]:http://www.fileformat.info/info/unicode/char/2bc3/index.htm
[FF61]:http://www.fileformat.info/info/unicode/char/ff61/index.htm
[FFFD]:http://www.fileformat.info/info/unicode/char/fffd/index.htm
[1F441]:http://www.fileformat.info/info/unicode/char/1f441/index.htm
