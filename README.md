### ☠ TCC HTML e CSS

## Layout está [aqui neste Figma](https://www.figma.com/file/IvRyMgaJCedXHD9f2xhbfz/Crescer-2020-02?node-id=1812%3A324)

# Regras
- Individual
- Responsivo
- Mais fiel ao layout possível
- Organizado estruturalmente (arquivos, pastas, etc) 

## Dicas
- Usem `min-height: 100vh` e `margin: 0` no body
- Nas sections podem usar `min-height: {valor}vh` e a largura deve ser em `%` **NÃO** pode ser em `vw`
- Exportem as fotos em jpg, se tiver fundo transparente usem png
- Ícones e logo, exportem em .svg
- Usem transition nos cards das pessoas
- Voltem as aulas, vários componentes do TCC já foram explicados em aula
- ⚠Façam commits e pushes regularmente ⚠


## Fontes
Importem a fonte
``` html
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Open+Sans&display=swap" rel="stylesheet">
```

Usem cada uma conforme a necessidade.
```css
font-family: 'Montserrat', sans-serif;
font-family: 'Open Sans', sans-serif;
```

## Estrutura de diretórios ideal
```
│   index.html
│
│
├───/contato
│       index.html
│
├───/sobre
|       index.html
|
└───/assets
    │
    ├───/css
    │   ├───/common
    │   │       style.css
    |   |       header.css
    |   |       footer.css
    │   │
    │   ├───/contact
    │   │       contact.css
    │   │
    │   └───/about
    │           about.css
    │
    └───/img
            logo.svg
            another-img.png

    
```
