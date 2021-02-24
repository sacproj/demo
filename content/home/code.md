---
weight: 120
markup: "html"
---
{{< slide bg-color="electric" >}}
# Code Presentation

------
## Code Inline
{{< code lang="javascript" >}}
// Include http module.
var http = require("http");
    ...
// Listen on the 8080 port.
}).listen(8080);
{{< /code >}}

------
## Code Inline - Source
{{< code lang="markdown" stretch="true" >}}
{{</* code lang="javascript" >}}
// Include http module.
var http = require("http");
    ...
// Listen on the 8080 port.
}).listen(8080);
{{< /code */>}}
{{< /code >}}

------
## Code Line numbers
{{< code lang="javascript" line-numbers="true" >}}
// Include http module.
var http = require("http");
    ...
// Listen on the 8080 port.
}).listen(8080);
{{< /code >}}

------
## Code Line numbers - Source
{{< code lang="markdown" stretch="true" >}}
{{</* code lang="javascript" line-numbers="true" >}}
// Include http module.
var http = require("http");
    ...
// Listen on the 8080 port.
}).listen(8080);
{{< /code */>}}
{{< /code >}}

------
## Code Source File
{{< code lang="go" src="codes/server.go" focus="|1,3-6|8-18|19-28" />}} 
{{< lines "bg-green" >}}
Present code found within any source file.
Without ever leaving your slideshow.
Using code presenting with (optional) annotations.
{{< /lines >}}

------
## Code Source File - Source
{{< code lang="markdown" stretch="true" >}}
{{</* code lang="go" src="codes/server.go" focus="|1,3-6|8-18|19-28" />}} 
{{< lines "bg-green" >}}
Present code found within any source file.
Without ever leaving your slideshow.
Using code presenting with (optional) annotations.
{{< /lines */>}}
{{< /code >}}

