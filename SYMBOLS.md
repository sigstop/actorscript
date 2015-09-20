
|ASCII string      |Read as                             |Category              |Matching Delimiters|Unicode (hex)|
|------------------|------------------------------------|----------------------|-------------------|-------------|
|#                 |end                                 |top level terminator  |                   |[25AE]       |
|:                 |of specified type                   |infix                 |                   |[003A]       |
|[:]               |this Actor's aspect                 |prefix                |                   |[2360]       |
|(<)               |injection                           |infix                 |                   |23C0         |
|(>)               |expression/pattern projection       |infix                 |                   |23C0         |
|[.]               |qualified by                        |infix                 |                   |22A1         |
|.                 |is sent                             |infix                 |                   |             |
|..                |delegate to this Actor              |prefix                |                   |23C0         |
|\|*\|             |necessarily concurrent              |prefix                |                   |29B7         |
|\|->              |message type returns type           |infix                 |                   |23C0         |
|\|..>             |cacheable message type returns type |prefix                |                   |23C0         |
|-->               |message received                    |prefix                |^p                 |23C0         |
|<--               |be                                  |infix                 |                   |23C0         |
|?                 |cases                               |seperator             |[?]                |23C0         |
|[V]               |alterative cases                    |seperator             |? and **catch**[?] |23C0         |
|[?]               |end cases                           |terminator            |                   |23C0         |
|^p                |another message handler             |seperator for handlers|                   |23C0         |
|^s                |end handlers                        |terminator            |**implements**     |23C0         |
|(:)               |case                                |seperator for case    |                   |2982         |
|@     |before                  |seperator             |**Let** bindings, **Do** preperations, **Enqueue**|[2BC3]|
|()                |end                                 |terminator            |**Do** expressions and (:) |2982 |
|===               |defined as                          |infix                 |**implements**     |23C0         |
|=^=               |to be                               |infix                 |                   |225C         |
|:=                |is assigned                         |infix                 |                   |2254         |
|$$                |matches value of                    |prefix                |                   |2254         |
|=                 |same as                             |infix                 |                   |2254         |
|[=]               |keyword **or** field                |infix                 |                   |2238         |
|:[=]              |assignable field                    |infix                 |                   |             |
|<\|               |begin type parameters               |left delimiter        |\|>                |             |
|\\\|/             |spread                              |prefix                |                   |2A5B         |
|{                 |begin set                           |left delimiter        |}                  |             |
|[                 |begin list                          |left delimiter        |]                  |             |
|{                 |begin set                           |left delimiter        |}                  |             |
|[\|               |array reference                     |left delimiter        |\|]                |             |
|(                 |begin grouping                      |left delimiter        |)                  |             |
|(\|               |begin syntax                        |left delimiter        |\|)                |             |
|(-)               |nothing                             |expression            |                   |229D         |
|<<-               |one-way send                        |infix                 |                   |219E         |
|->>               |join                                |infix                 |                   |2294         |


[25AE]:http://www.fileformat.info/info/unicode/char/25ae/index.htm
[003A]:http://www.fileformat.info/info/unicode/char/003a/index.htm
[2360]:http://www.fileformat.info/info/unicode/char/2360/index.htm
[2BC3]:http://www.fileformat.info/info/unicode/char/2bc3/index.htm
