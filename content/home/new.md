---
weight: 40
markup: "html"
---
{{< slide bg-color="green" >}}
# Create new Presentation

------
## Steps
{{< code lang="text" focus="|1|5|7|10,13,16" >}}
$ sac deck new my-awesome-slides sac-theme/x.y.z
Initialized empty Git repository in my-awesome-slides/.git/
Adding snippets from sac-theme/x.y.z

$ cd my-awesome-slides

$ sac content new cover.md
my-awesome-slides/content/home/cover.md created

$ sac content new intro.md
my-awesome-slides/content/home/intro.md created

$ sac content new info.md
my-awesome-slides/content/home/info.md created

$ sac content new qa.md
my-awesome-slides/content/home/qa.md created
{{< /code >}}

{{< lines "bg-green" >}}
Create a new slides **Deck** with **Slides as Code theme**
Go to created repository
Create a new slide for the cover
Slides content could be split into multiple Markdown files.
{{< /lines >}}

------
## Directory Layout
```text
my-awesome-slides/
├── config.yaml
├── content
│   └── home
│       ├── cover.md
│       ├── info.md
│       ├── intro.md
│       └── qa.md
└── static
    ├── charts
    ├── codes
    ├── diagrams
    ├── images
    ├── sessions
    ├── sounds
    └── videos
```

------
## Content Format
Hugo ❤️ **Markdown**,<br>
but there are times when Markdown falls short

Instead of writing raw HTML,<br>
Hugo created **Shortcodes**.

A **Shortcode** is a simple snippet inside a content file<br>that will be rendered using a predefined template

```text
{{</* shortcode parameters >}}
content
{{< /shortcode */>}}
```

------
## Content Source
```text
---
weight: 10
markup: "html"
---
Markdown with Shortcodes content
```

------
## Content Rendering
{{< span "text-code" >}}**weight**{{< /span >}} in front-matter is used<br>to order content files when concatenating them.

**Slides as Code** doesn't use Hugo's Markdown renderer,<br> but Reveal.js Markdown renderer.

------
## Source Code
{{< slide bg-color="yellow">}}
In following slides, each slide has<br>a next slide containing its source code.

To ease the navigation into the slides

Hit {{< span "text-highlight-black" >}}M{{< /span >}} key to open the menu to navigate into the slides.

Hit {{< span "text-highlight-black" >}}O{{< /span >}} key to open the overview.
