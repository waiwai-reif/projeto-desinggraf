# projeto-desing_graf
# FORMA — Estúdio de Design Gráfico
## Documentação do Projeto

---

### Estrutura de Pastas

```
projeto-design/
│
├── index.html              ← Página inicial (Home)
│
├── css/
│   └── estilo.css          ← CSS global (usado por todas as páginas)
│
├── pages/
│   ├── pagina01.html       ← Serviços (foco em tabelas)
│   ├── pagina02.html       ← Portfólio (foco em grid/galeria)
│   ├── pagina03.html       ← Contato (foco em formulários)
│   └── pagina07.html       ← Sobre o estúdio
│
├── images/                 ← Coloque aqui todas as imagens do projeto
│
└── document/
    └── README.md           ← Este arquivo
```

---

### Como usar as imagens

Para adicionar uma imagem real no portfólio (pagina02.html),
substitua a `<div class="thumb">` pelo código abaixo:

```html
<img src="../images/nome-do-arquivo.jpg" alt="Descrição do projeto">
```

O `../` sobe uma pasta (de /pages para a raiz), e então entra em /images.

---

### Caminhos do CSS

- Nas páginas dentro de `/pages`, o link para o CSS é:
  `<link rel="stylesheet" href="../css/estilo.css">`

- No `index.html` (raiz), o link é:
  `<link rel="stylesheet" href="css/estilo.css">`

---

### Tecnologias usadas

- HTML5 semântico
- CSS3 (variáveis, flexbox, grid, media queries)
- Google Fonts: Bebas Neue + DM Sans
- Sem JavaScript, sem frameworks externos

---

### Paleta de Cores (variáveis CSS)

| Variável            | Valor     | Uso                  |
|---------------------|-----------|----------------------|
| --cor-fundo         | #0e0e0e   | Fundo da página      |
| --cor-superficie    | #1a1a1a   | Cards e header       |
| --cor-borda         | #2e2e2e   | Bordas e divisores   |
| --cor-destaque      | #f0e040   | Amarelo de ênfase    |
| --cor-texto         | #f5f5f5   | Texto principal      |
| --cor-texto-suave   | #999999   | Texto secundário     |
