---
weight: 130
markup: "html"
---
{{< slide bg-color="electric" >}}
# Typed
Using [typed.js](https://mattboldt.com/demos/typed-js/)

------
## Typed
{{< typed cursor-char="🤖" >}}
I'm sorry Alice
I'm sorry Dave
I'm sorry Dave, I'm afraid I can't do that
{{< /typed >}}

------
## Typed - Source
{{< code lang="markdown" stretch="true" >}}
{{</* typed cursor-char="🤖" >}}
I'm sorry Alice
I'm sorry Dave
I'm sorry Dave, I'm afraid I can't do that
{{< /typed */>}}
{{< /code >}}

------
## Typed fragment
{{< typed class="text-code text-left" loop="false" show-cursor="false" >}}
$ git log^1000
{{< /typed >}}
 
{{< div "fragment" >}}
{{< code lang="bash" >}}
commit 9f79351399a410d668bcfb1a9049a5499c95dbb6 (HEAD -> master, origin/master)
Author: Someone
Date:   Mon Feb 4 13:43:56 2019 +0100
 
    Add typing
 
commit a66cc9a5e09dabd28c5f50f8c41e88645596acd6
Author: Somebody
Date:   Mon Feb 4 13:33:56 2019 +0100
 
    Add code presenting on docSite
 
commit 899ad1b7ae6d9ef3c2f90fbddfe7e2db5480476c
Author: Nobody
Date:   Mon Feb 4 13:23:56 2019 +0100
{{< /code >}}
{{< /div >}}

------
## Typed fragment - Source
{{< code lang="markdown" stretch="true" >}}
{{</* typed class="text-code text-left" loop="false" show-cursor="false" >}}
$ git log^1000
{{< /typed >}}
 
{{< div "fragment" >}}
{{< code lang="bash" >}}
commit 9f79351399a410d668bcfb1a9049a5499c95dbb6 (HEAD -> master, origin/master)
Author: Someone
Date:   Mon Feb 4 13:43:56 2019 +0100
 
    Add typing
 
commit a66cc9a5e09dabd28c5f50f8c41e88645596acd6
Author: Somebody
Date:   Mon Feb 4 13:33:56 2019 +0100
 
    Add code presenting on docSite
 
commit 899ad1b7ae6d9ef3c2f90fbddfe7e2db5480476c
Author: Nobody
Date:   Mon Feb 4 13:23:56 2019 +0100
{{< /code */>}}
{{< /code >}}
