# Modelo TeX de Beamer Limpo

- [README file in English](README.md)

Modelo TeX que fiz para utilizar em apresetações, eventos e palestras.

# Recursos a serem Implementados

- [ ] Como mudar a posição do título da cada quadro

# Sobre o Modelo

Para usá-lo, você precisa preencher as variáveis `title`, `author`, `institute` e `date`, na seção `Alterações de Uso`. Para criar um quadro, utilize a função `criaQuadro`, seguindo os exemplos do modelo.

Especificações de dimensões do Beamer: 
- Largura: `128 mm`.
- Altura: `96 mm`.

Para alterar o formato e cor de um bloco, utilize
```tex
\setbeamertemplate{blocks}[rounded][shadow=true]
\setbeamercolor{block title}{bg=cor}
\setbeamercolor{block body}{bg=cor}
```

Para alterar a cor de fundo do Beamer para monocromática, utilize
```tex
\setbeamercolor{background canvas}{bg=cor}
```

Para alterar a cor de fundo do Beamer para degradê vertical, utilize
```tex
\setbeamertemplate{background canvas}[vertical shading][bottom=cor,top=cor]
```

A respeito dos comentários, eu tenho um gosto particular por esse estilo (comprimento de 60 colunas e texto centralizado), acho que chama bastante a atenção do usuário. 

# Licença

Esse repositório é licenciado sob os termos da [Licença MIT](LICENSE).
