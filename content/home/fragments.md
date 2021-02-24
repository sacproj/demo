---
weight: 90
markup: "html"
---
{{< slide bg-color="electric" >}}
# Fragments

------
## Fragments Simple
{{< div "fragment" >}}A{{< /div >}}
{{< div "fragment" >}}B{{< /div >}}
{{< div "fragment" >}}C{{< /div >}}

------
## Fragments Simple - Source
{{< code lang="markdown" stretch="true" >}}
{{</* div "fragment" >}}A{{< /div >}}
{{< div "fragment" >}}B{{< /div >}}
{{< div "fragment" >}}C{{< /div */>}}
{{< /code >}}

------
## Fragments Index
{{< div "fragment" "1" >}}A{{< /div >}}
{{< div "fragment" "0" >}}B{{< /div >}}
{{< div "fragment" "2" >}}C{{< /div >}}

------
## Fragments Index - Source
{{< code lang="markdown" stretch="true" >}}
{{</* div "fragment" "1" >}}A{{< /div >}}
{{< div "fragment" "0" >}}B{{< /div >}}
{{< div "fragment" "2" >}}C{{< /div */>}}
{{< /code >}}

------
## Fragments Sync
{{< div "columns" >}}
{{< div "column" >}}
{{< div "fragment" "1" >}}A{{< /div >}}
{{< div "fragment" "0" >}}B{{< /div >}}
{{< div "fragment" "2" >}}C{{< /div >}}
{{< /div >}}

{{< div "column" >}}
{{< div "fragment" "0" >}}0{{< /div >}}
{{< div "fragment" "1" >}}1{{< /div >}}
{{< div "fragment" "2" >}}2{{< /div >}}
{{< /div >}}
{{< /div >}}

------
## Fragments Sync - Source
{{< code lang="markdown" stretch="true" >}}
{{</* div "columns" >}}
{{< div "column" >}}
{{< div "fragment" "1" >}}A{{< /div >}}
{{< div "fragment" "0" >}}B{{< /div >}}
{{< div "fragment" "2" >}}C{{< /div >}}
{{< /div >}}

{{< div "column" >}}
{{< div "fragment" "0" >}}0{{< /div >}}
{{< div "fragment" "1" >}}1{{< /div >}}
{{< div "fragment" "2" >}}2{{< /div >}}
{{< /div >}}
{{< /div */>}}
{{< /code >}}

------
## Fragments Lines
{{< lines >}}
Lorem **ipsum**
{{< span "text-highlight-pink" >}}dolor{{< /span >}}
{{< span "text-code text-20" >}}sit amet{{< /span >}}
{{< /lines >}}

------
## Fragments Lines - Source
{{< code lang="markdown" stretch="true" >}}
{{</* lines >}}
Lorem **ipsum**
{{< span "text-highlight-pink" >}}dolor{{< /span >}}
{{< span "text-code text-20" >}}sit amet{{< /span >}}
{{< /lines */>}}
{{< /code >}}
