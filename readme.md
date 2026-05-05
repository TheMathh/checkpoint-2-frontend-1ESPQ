# Vinheria Agnello

## Descrição

O projeto Vinharia Agnello foi desenvolvido com base em um estudo de caso acadêmico, que apresenta uma vinheria familiar localizada em São Paulo, com mais de 15 anos de atuação no mercado.

A empresa se destaca pelo atendimento personalizado e pela orientação especializada oferecida aos clientes na escolha de vinhos. Durante a pandemia, a vinheria enfrentou desafios devido à redução do movimento presencial, o que levou à necessidade de adaptação para o ambiente digital por meio da criação de um site.

Este projeto tem como objetivo representar essa vinheria na web, apresentando suas informações, produtos e formas de contato.

---

## Estrutura do Projeto

O site é composto por 5 páginas principais:

- index.html
  Página inicial com apresentação da vinheria, vídeo institucional e informações gerais.

- historia.html 
  Apresenta a história da empresa e uma linha do tempo com sua evolução.

- produtos.html 
  Exibe os tipos de vinhos disponíveis, com descrições e uma tabela com informações relevantes.

- galeria.html
  Contém imagens relacionadas à vinheria, seus produtos e ambiente.

- contato.html 
  Página com formulário de contato para comunicação com a empresa.

## Funcionalidades Implementadas
- Navegação funcional entre todas as páginas
- Estrutura semântica usando `<header>`, `<main>`, `<footer>` e `<section>`
- Headings (`<h1>`, `<h2>`), parágrafos (`<p>`) e listas (`<ul>`) aplicados
- Meta tags `description` e `keywords` em cada página
- Links internos funcionando
- Inclusão das imagnes
- CSS global linkado (`style.css`)

## Efeitos Visuais ✨

Os efeitos visuais do Check-Point 02 estão definidos no arquivo `src/css/efeitos.css`, importado no `style.css`.

## Pseudo-classes utilizadas

| Pseudo-classe | Elemento | Efeito |

| `:focus` | `input` e `textarea` | Destaca o campo com borda vinho e sombra suave ao ser selecionado |
| `:nth-child(even)` | Linhas da `<table>` | Aplica fundo rosé alternado nas linhas pares da tabela de produtos |
| `:not(:first-child)` | Linhas ímpares da `<table>` | Garante fundo branco nas linhas ímpares, exceto o cabeçalho |
| `:valid` | `input` e `textarea` | Exibe borda verde quando o campo está preenchido corretamente |
| `:hover` | `nav ul li a` | Exibe sublinhado animado vinho ao passar o mouse nos links do menu |

## Pseudo-elementos utilizados

| Pseudo-elemento | Elemento | Efeito |

| `::before` | `main ul li` | Exibe uma etiqueta dourada "Reserva Especial" que aparece com animação ao hover |
| `::after` | `nav ul li a` | Linha vinho que cresce da esquerda para direita sob o link ao hover |

## Animações com `@keyframes`

| Nome | Aplicação | Descrição |

| `entradaHeader` | `header` | O cabeçalho desliza de cima para baixo com fade-in ao carregar a página |

## Transições

| Elemento | Efeito |

| Links do `nav` | Mudança de cor e espaçamento das letras de forma suave |
| `button` | Eleva e cresce levemente no hover; afunda ao ser clicado |
| Linhas da `<table>` | Fundo muda para rosé suavemente ao passar o mouse |
| Imagens | Crescem e inclinam levemente com sombra ao receber hover |

## Transformações CSS

| Transformação | Elemento | Descrição |

| `scale(1.05) rotate(2deg)` | `img:hover` | Imagens crescem e inclinam levemente ao receber hover |
| `translateY(-2px) scale(1.04)` | `button:hover` | Botão sobe e cresce ao receber hover |


## Como visualizar

-Link do github pages
https://anthonylealm.github.io/cp1-frontend-1ESPQ/

## Integrantes 

- Anthony Leal Monteiro 569616

- Arthur de Sá Lopes 569526

- Mateus Alves Borges 571424