# Clean Beamer TeX Template

- [Arquivo README em português](README_PT.md)

TeX template that I made to use in presentations, events and lectures.

# Features to be Implemented

- [ ] How to change the position of each frame's title

# About the Template

To use it, you have to fill the `title`, `author`, `institute` and `date` variables, in the `Usage Changes` section. To create a frame, use the `createFrame` function, following the template's examples.

Beamer size specifications: 
- Width: `128 mm`.
- Height: `96 mm`.

To change block's shape and color, use
```tex
\setbeamertemplate{blocks}[rounded][shadow=true]
\setbeamercolor{block title}{bg=color}
\setbeamercolor{block body}{bg=color}
```

To change Beamer's background to monochromatic, use
```tex
\setbeamercolor{background canvas}{bg=color}
```

To change Beamer's background to vertical gradient, use
```tex
\setbeamertemplate{background canvas}[vertical shading][bottom=color,top=color]
```

Regarding the comments, I have a personal taste for this style (60 columns length and centralized text), I think it catches the user's attention.

# License

This repository is licensed under the terms of [MIT License](LICENSE).
