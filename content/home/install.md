---
weight: 30
markup: "html"
---
{{< slide bg-color="green" >}}
# Installation

------
## Install CLI
{{< code lang="txt" focus="|1|9" >}}
$ brew install sacproj/sac/sac
==> Installing sac from sacproj/sac
==> Downloading https://github.com/sacproj/sac-cli/releases/download/x.y.z/sac-cli.tar.gz
==> Downloading from https://github-releases.githubusercontent.com/...
######################################################################## 100.0%

🍺  /usr/local/Cellar/sac/x.y.z: 7 files, 15.3KB, built in 4 seconds

$ sac doctor
sac x.y.z on Darwin

# Checking jq: OK
jq-1.6

# Checking realpath: OK
realpath (GNU coreutils) 8.32
Copyright (C) 2020 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Written by Padraig Brady.

# Checking hugo: OK
Hugo Static Site Generator v0.80.0/extended darwin/amd64 BuildDate: unknown
{{< /code >}}

{{< lines "bg-green" >}}
Install **Slides as Code CLI** with [Homebrew](https://brew.sh/) on {{< fab "fa-apple" >}} macOS and {{< fab "fa-linux" >}} Linux
Check required tools (hugo, jq, coreutils...)
{{< /lines >}}

------
## Install Theme
{{< code focus="|1|6" >}}
$ sac theme install github sacproj/sac-theme
Installing sac/x.y.z into /usr/local/share/sac/themes
Enter your password (for sudo access):
Password:

$ sac theme installed
/usr/local/share/sac/themes
└── sac
    └── x.y.z
{{< /code >}}

{{< lines "bg-green" >}}
Install latest **Slides as Code Theme**
Check installed themes
{{< /lines >}}
