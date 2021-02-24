---
weight: 110
markup: "html"
---
{{< slide bg-color="electric" >}}
# Boxes

------
# Boxes
{{< div "columns" >}}
{{< div "column col-off-10 col-30 fragment" "1" >}}
{{< box "bg-pink text-white" "1. Plan" >}}
<br>
Lorem ipsum dolor sit amet
<br>
<br>
{{< /box >}}
{{< /div >}}

{{< div "column col-off-20 col-30 fragment" "2" >}}
{{< box "bg-yellow text-white rounded" "2. Build" >}}
<br>
Sed do eiusmod tempor labore
<br>
<br>
{{< /box >}}
{{< /div >}}
{{< /div >}}

{{< div "fragment" "5" >}}
{{< fas "fa-sync fa-2x fa-spin" >}}
{{< /div >}}

{{< div "columns" >}}
{{< div "column col-off-10 col-30 fragment" "3" >}}
{{< box "bg-green text-white" "3. Measure" >}}
<br>
Cupidatat non proident sunt in
<br>
<br>
{{< /box >}}
{{< /div >}}

{{< div "column col-off-20 col-30 fragment" "4" >}}
{{< box "bg-electric text-white waved" "4. Repeat" >}}
<br>
Ut enim ad minim veniam prodient
<br>
<br>
{{< /box >}}
{{< /div >}}
{{< /div >}}

------
# Boxes - Source
{{< code lang="markdown" stretch="true" >}}
{{</* div "columns" >}}
{{< div "column col-off-10 col-30 fragment" "1" >}}
{{< box "bg-pink text-white" "1. Plan" >}}
<br>
Lorem ipsum dolor sit amet
<br>
<br>
{{< /box >}}
{{< /div >}}

{{< div "column col-off-20 col-30 fragment" "2" >}}
{{< box "bg-yellow text-white rounded" "2. Build" >}}
<br>
Sed do eiusmod tempor labore
<br>
<br>
{{< /box >}}
{{< /div >}}
{{< /div >}}

{{< div "fragment" "5" >}}
{{< fas "fa-sync fa-2x fa-spin" >}}
{{< /div >}}

{{< div "columns" >}}
{{< div "column col-off-10 col-30 fragment" "3" >}}
{{< box "bg-green text-white" "3. Measure" >}}
<br>
Cupidatat non proident sunt in
<br>
<br>
{{< /box >}}
{{< /div >}}

{{< div "column col-off-20 col-30 fragment" "4" >}}
{{< box "bg-electric text-white waved" "4. Repeat" >}}
<br>
Ut enim ad minim veniam prodient
<br>
<br>
{{< /box >}}
{{< /div >}}
{{< /div */>}}
{{< /code >}}
