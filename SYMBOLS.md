
|ASCII string      |Read as                             |Category              |Matching Delimiters|Unicode(hex)|
|------------------|------------------------------------|----------------------|-------------------|------------|
|#                 |end                                 |top level terminator  |                   |[32DA]      |
|:                 |of specified type                   |infix                 |                   |[003A]      |
|[:]               |this Actor's aspect                 |prefix                |                   |[2360]      |
|(<)               |injection                           |infix                 |                   |23C0        |
|(>)               |expression/pattern projection       |infix                 |                   |23C0        |
|[.]               |qualified by                        |infix                 |                   |22A1        |
|.                 |is sent                             |infix                 |                   |            |
|..                |delegate to this Actor              |prefix                |                   |23C0        |
|\|_\|             |necessarily concurrent              |prefix                |                   |29B7        |
|\|->              |message type returns type           |infix                 |                   |23C0        |
|\|..>             |cacheable message type returns type |prefix                |                   |23C0        |
|-->               |message received                    |prefix                |^p                 |23C0        |
|<--               |be                                  |infix                 |                   |23C0        |
|?                 |cases                               |seperator             |[?]                |23C0        |
|[V]               |alterative cases                    |seperator             |? and [?]          |23C0        |
|[?]               |end cases                           |terminator            |                   |23C0        |
|^p                |another message handler             |seperator for handlers|                   |23C0        |


[003A]:http://www.fileformat.info/info/unicode/char/003a/index.htm
[2360]:http://www.fileformat.info/info/unicode/char/2360/index.htm
[32DA]:http://www.fileformat.info/info/unicode/char/32da/index.htm
