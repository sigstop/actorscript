
|ASCII string      |Read as                             |Category              |Matching Delimiters|Unicode (hex)|
|------------------|------------------------------------|----------------------|-------------------|-------------|
|#                 |end                                 |top level terminator  |                   |[25AE]       |
|:                 |of specified type                   |infix                 |                   |[003A]       |
|[:]               |this Actor's aspect                 |prefix                |                   |[2360]       |
|(<)               |injection                           |infix                 |                   |[29C0]       |
|(>)               |expression/pattern projection       |infix                 |                   |[29C1]       |
|!                 |resolve                             |prefix                |                   |[2B63]       |
|[.]               |qualified by                        |infix                 |                   |[22A1]       |
|.                 |is sent                             |infix                 |                   |[002E]       |
|..                |delegate to this Actor              |prefix                |                   |[002E](http://www.fileformat.info/info/unicode/char/002e/index.htm) [002E](http://www.fileformat.info/info/unicode/char/002e/index.htm) **or** [2025](http://www.fileformat.info/info/unicode/char/2025/index.htm) |
|\|*\|             |necessarily concurrent              |prefix                |                   |[25A1]       |
|\|->              |message type returns type           |infix                 |                   |[21A6]       |
|\|..>             |cacheable message type returns type |prefix                |                   |[007C](http://www.fileformat.info/info/unicode/char/007c/index.htm)  [002E](http://www.fileformat.info/info/unicode/char/002e/index.htm)  [002E](http://www.fileformat.info/info/unicode/char/002e/index.htm) [003E](http://www.fileformat.info/info/unicode/char/003e/index.htm) **or** [21E2](http://www.fileformat.info/info/unicode/char/21e2/index.htm)         |
|-->               |message received                    |prefix                |^p                 |[2192]       |
|<--               |be                                  |infix                 |                   |[2190]       |
|?                 |cases                               |seperator             |[?]                |[FFFD]       |
|[V]               |alterative cases                    |seperator             |? and **catch**[?] |[27CF]       |
|[?]               |end cases                           |terminator            |                   |[2370]       |
|^p                |another message handler             |seperator for handlers|                   |[00B6]       |
|^s                |end handlers                        |terminator            |**implements**     |[00A7]       |
|(:)               |case                                |seperator for case    |                   |[2982]       |
|@     |before                  |seperator             |**Let** bindings, **Do** preperations, **Enqueue**|[2BC3]|
|()                |end                                 |terminator            |**Do** expressions and (:) |[FF61]|
|===               |defined as                          |infix                 |**implements**     |[2261]       |
|=^=               |to be                               |infix                 |                   |[225C]       |
|:=                |is assigned                         |infix                 |                   |[2254]         |
|$$                |matches value of                    |prefix                |                   |[0024]() [0024]() **or** [1F441]         |
|=                 |same as                             |infix                 |                   |2254         |
|[=]               |keyword **or** field                |infix                 |                   |2238         |
|:[=]              |assignable field                    |infix                 |                   |             |
|<\|               |begin type parameters               |left delimiter        |\|>                |             |
|!!!               |spread                              |prefix                |                   |2A5B         |
|{                 |begin set                           |left delimiter        |}                  |             |
|[                 |begin list                          |left delimiter        |]                  |             |
|{                 |begin set                           |left delimiter        |}                  |             |
|[\|               |array reference                     |left delimiter        |\|]                |             |
|(                 |begin grouping                      |left delimiter        |)                  |             |
|(\|               |begin syntax                        |left delimiter        |\|)                |             |
|(-)               |nothing                             |expression            |                   |229D         |
|<<-               |one-way send                        |infix                 |                   |219E         |
|->>               |one-way receive                     |infix                 |^p                 |21A0         |
|\|_\|             |join                                |infix                 |                   |2294         |
|[<=]              |constrained by                      |infix                 |                   |2291         |
|[>=]              |extends                             |infix                 |                   |2292         |
|==>               |logical implication                 |infix                 |                   |21E8         |
|<=>               |logical equivalence                 |infix                 |                   |21D4         |
|&                 |logical conjunction                 |infix                 |                   |00D9         |
|\|\|              |logical disjunction                 |infix                 |                   |00DA         |
|-\|               |logical negation                    |prefix                |                   |00D9         |
|\|-               |assets                              |prefix **and** infix  |                   |22A2         |
|\|\|-             |goal                                |prefix **and** infix  |                   |22A9         |
|//                |begin 1-line comment                |prefix                |EndOfLine charater |             |
|/*                |begin comment                       |left delimiter        |*/                 |             |



[25AE]:http://www.fileformat.info/info/unicode/char/25ae/index.htm
[002E]:http://www.fileformat.info/info/unicode/char/002e/index.htm
[003E]:http://www.fileformat.info/info/unicode/char/003e/index.htm
[003A]:http://www.fileformat.info/info/unicode/char/003a/index.htm
[007C]:http://www.fileformat.info/info/unicode/char/007c/index.htm
[00B6]:http://www.fileformat.info/info/unicode/char/00b6/index.htm
[00A7]:http://www.fileformat.info/info/unicode/char/00a7/index.htm
[2190]:http://www.fileformat.info/info/unicode/char/2190/index.htm
[2192]:http://www.fileformat.info/info/unicode/char/2192/index.htm
[21A6]:http://www.fileformat.info/info/unicode/char/21a6/index.htm
[21E2]:http://www.fileformat.info/info/unicode/char/21e2/index.htm
[2254]:http://www.fileformat.info/info/unicode/char/2254/index.htm
[225C]:http://www.fileformat.info/info/unicode/char/225c/index.htm
[2261]:http://www.fileformat.info/info/unicode/char/2261/index.htm
[2360]:http://www.fileformat.info/info/unicode/char/2360/index.htm
[2370]:http://www.fileformat.info/info/unicode/char/2370/index.htm
[25A1]:http://www.fileformat.info/info/unicode/char/25a1/index.htm
[27CF]:http://www.fileformat.info/info/unicode/char/27cf/index.htm
[2982]:http://www.fileformat.info/info/unicode/char/2982/index.htm
[29C0]:http://www.fileformat.info/info/unicode/char/29C0/index.htm
[29C1]:http://www.fileformat.info/info/unicode/char/29C1/index.htm
[2B63]:http://www.fileformat.info/info/unicode/char/2b63/index.htm
[22A1]:http://www.fileformat.info/info/unicode/char/22a1/index.htm
[2BC3]:http://www.fileformat.info/info/unicode/char/2bc3/index.htm
[FF61]:http://www.fileformat.info/info/unicode/char/ff61/index.htm
[FFFD]:http://www.fileformat.info/info/unicode/char/fffd/index.htm
[1F441]:http://www.fileformat.info/info/unicode/char/1f441/index.htm
