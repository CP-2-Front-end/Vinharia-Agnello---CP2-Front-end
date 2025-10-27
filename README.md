# Vinharia Agnello

>| Nome                     | RM     |
>| ------------------------ | ------ |
>| César André Zanin Filho  | 567615 |
>| Vinicius Kozonoe Guaglini | 567264 |

---

# Descrição

O projeto Vinharia Agnello apresenta um website institucional dedicado ao universo dos vinhos, com foco na experiência do usuário, estética refinada e conteúdo informativo.

O site inclui seções sobre a história da vinheria, detalhes de produtos (vinhos branco, tinto e rosé) e um formulário de contato funcional. Foi desenvolvido como exercício prático de front-end, utilizando HTML5 e CSS3.

---

# Navegação entre Páginas

O site da Vinharia Agnello foi desenvolvido com uma estrutura simples e intuitiva, permitindo que o usuário transite entre as páginas de forma fluida.
A navegação principal está localizada no menu do cabeçalho, presente em todas as páginas, garantindo uma experiência consistente.

Cada item do menu direciona o visitante para uma das seções principais:

## Início: 
página inicial com apresentação e destaques dos vinhos.

## História:
 trajetória da vinheria e vídeo sobre armazenagem controlada.

## Vinho Branco / Tinto / Rosé:
 detalhes de cada categoria, incluindo harmonizações e informações nutricionais.

Além disso, cada página de produto conta com um botão “Início”, posicionado no topo, que permite retornar rapidamente à página principal.

---

# Tecnologias Utilizadas

## HTML5: 
estrutura semântica das páginas.

## CSS3: 
estilização completa, com uso de pseudo-classes, pseudo-elementos e animações.

## Flexbox: 
organização responsiva de elementos.

## Design: 
inspirado em tons vinhos e dourados, remetendo à identidade visual da marca.

## @import: 
integração de arquivos de efeitos externos (efeitos.css).

---

# Funcionalidades

Menu de navegação entre páginas internas.

Sessão “História” com imagem ilustrativa e vídeo incorporado via YouTube.

Páginas de vinhos com informações nutricionais e sugestões de harmonização.

Formulário de contato interativo com efeitos de foco e animações.

Rodapé com seções de contato e copyright.

---

# Execução do Projeto

Abaixo estão as instruções para clonar o repositório, acessar o diretório e visualizar o site localmente.

 

1️) Clonar o repositório
"git clone <https://github.com/CP-2-Front-end/Vinharia-Agnello---CP2-Front-end.git>"


 

2️) Acessar o diretório do projeto
cd Vinharia-Agnello


 

3️) Abrir o projeto no Visual Studio Code
code .


Caso prefira, basta clicar duas vezes em index.html para abrir o site diretamente no navegador.

---

# Estrutura do Projeto 

A organização do projeto foi feita de forma modular, facilitando a manutenção e a navegação entre arquivos e pastas.

```
Vinharia-Agnello/
│
├── index.html
├── src/
│ ├── css/
│ │ ├── style.css
│ │ ├── branco.css
│ │ ├── rose.css
│ │ └── tinto.css
│ ├── pages/
│ │ ├── historia.html
│ │ ├── vinhoBranco.html
│ │ ├── vinhoTinto.html
│ │ └── vinhoRose.html
│ └── assets/
│ └── images/
│ ├── inicio.jpg
│ ├── tinto_imagens/
│ ├── rose_imagens/
│ ├── branco_imagens/
│ └── ...
│
└── README.md
``` 