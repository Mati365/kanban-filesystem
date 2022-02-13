# jira-filesystem

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/mati365/jira-filesystem?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/mati365/jira-filesystem?style=flat-square)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

Bored of navigation over slow JIRA web UI? Nothing lost! Use JIRA as your Linux FUSE filesystem!

## Proof of concept

Directory structure (generated using https://tree.nathanfriend.io/):

```bash
.
└── /media/jira/
    ├── backlog/
    │   └── implement-backlog-support.rb
    ├── releases/
    │   └── release-13-02-2022.md
    ├── assigned-to-me/
    │   └── tasks/
    │       └── create-fuse-proof-of-concept.md -> /media/jira/sprints/13-02-2022/kanban/in-progress/create-fuse-proof-of-concept.md
    └── sprints/
        └── 13-02-2022/
            └── kanban/
                ├── todo/
                │   ├── add-jira-api.md
                │   └── add-jira-filesystem-fuse.md
                ├── in-progress/
                │   └── create-fuse-proof-of-concept.md
                └── done/
                    └── something.md
```

## License

The MIT License (MIT)
Copyright (c) 2022 Mateusz Bagiński

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
