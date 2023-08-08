
_tournaments/
├── 2023-08-06-game_21ENs03/
│   ├── index.md
│   ├── game_21ENs03_1.md
│   ├── game_21ENs03_2.md
│   └── ...
├── 2023-08-06-game_21ENs04/
│   ├── index.md
│   ├── game_21ENs04_1.md
│   ├── game_21ENs04_2.md
│   └── ...
└── ...

In _config.yml
example
collections:
  people:
    output: true
    permalink: /people/:title/index.html

To link the structure above:
collections:
  tournaments:
    output: true
    permalink: /tournaments/:title/
