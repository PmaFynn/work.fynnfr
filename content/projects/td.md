---
title: 'td'
date: 2024-10-13T14:28:59+02:00
tags: ['Rust', 'TODO', 'Terminal User Interface', 'CLI']
# weight: 1
# aliases: ["/first"]
author: "Me"
# author: ["Me", "You"] # multiple authors
hideAuthor: true
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
# description: "Desc Text."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: false
ShowBreadCrumbs: false
ShowPostNavLinks: false
ShowWordCount: false
ShowRssButtonInSectionTermList: true
UseHugoToc: true
# cover:
#     image: "/home/fynn/projects/hugo/fynnfr/static/movies/dontLikeCover.png" # image path/url
#     # alt: "<alt text>" # alt text
#     # caption: "<text>" # display caption under cover
#     # relative: false # when using page bundles set this to true
#     hidden: false # only hide on current single page
---
## Rust todo Application: [Github](https://github.com/pmafynn/td)

<!--![Build Status](https://img.shields.io/github/workflow/status/yourusername/yourprojectname/CI)-->
<!-- ![License](https://img.shields.io/github/license/yourusername/yourprojectname)-->
<!--![Version](https://img.shields.io/github/v/release/yourusername/yourprojectname)-->
![Showcase](/static/projects/tdShowcase.gif)

![test](/static/home/me.png)
A simple, fast, and efficient TUI todo application written in Rust with *vim bindings*.

### Features

#### CLI Features

- Add new tasks **FAST** (see usage below)

#### TUI Features - Keybinds

| Action                                                                      | Keybind    |
|-----------------------------------------------------------------------------|------------|
| quit application                                                            | q, Esc     |
| exit out of help                                                            | Esc        |
| down                                                                        | j          |
| up                                                                          | k          |
| toggle visible todos                                                        | h, l, tab  |
| goTop                                                                       | g          |
| completly delete a finished todo                                            | d          |
| add new todo                                                                | a          |
| rename selected todo                                                        | n          |
| goBottom                                                                    | G          |
| search for *input* <- highlights all but selects only the last found        | /          |
| switch status of selected todo                                              | enter      |

### Installation

#### Prerequisites

- Ensure you have [Rust](https://www.rust-lang.org/tools/install) installed on your machine.

#### Clone the repository

```sh
git clone https://github.com/pmafynn/td.git
cd td
```

#### Build the application

```sh
cargo build --release
```

#### Run the application

```sh
./target/release/td
```

Create alias or add to path if you like it

### Usage

Here are some common commands you can use with this ToDo application:

#### Add a new task

```sh
td "new task"
```
or 
```sh
td new task
```
#### Enter TUI

```sh
td
```

#### For more options and usage, run:

```sh
td --help
```

### License

[LICENSE](LICENSE.md)

### Acknowledgements

- Thanks to the [Rust](https://www.rust-lang.org/) community for their amazing work on the language and ecosystem.
