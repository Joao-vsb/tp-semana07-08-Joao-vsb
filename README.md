[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KZhXwLZL)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=21430985)
# Trabalho Prático 05 - Semanas 7 e 8

**Páginas de detalhes dinâmicas**

Nessa etapa, vamos evoluir o trabalho anterior, acrescentando a página de detalhes, conforme o projeto escolhido. Imagine que a página principal (home-page) mostre um visão dos vários itens que existem no seu site. Ao clicar em um item, você é direcionado pra a página de detalhes. A página de detalhe vai mostrar todas as informações sobre o item do seu projeto. seja esse item uma notícia, filme, receita, lugar turístico ou evento.

Leia o enunciado completo no Canvas. 

**IMPORTANTE:** Assim como informado anteriormente, capriche na etapa pois você vai precisar dessa parte para as próximas semanas. 

**IMPORTANTE:** Você deve trabalhar e alterar apenas arquivos dentro da pasta **`public`,** mantendo os arquivos **`index.html`**, **`styles.css`** e **`app.js`** com estes nomes, conforme enunciado. Deixe todos os demais arquivos e pastas desse repositório inalterados. **PRESTE MUITA ATENÇÃO NISSO.**

## Informações Gerais

- Nome: João Vitor SIlva Barbosa
- Matricula: 837122
- Proposta de projeto escolhida: Livraria Virtual (CRUD de Livros)
- Breve descrição sobre seu projeto: Sistema de livraria online com listagem de livros em cards, preços com desconto e página de detalhes dinâmica mostrando título, descrição, conteúdo completo, categoria, autor e data de publicação.


## Cole aqui abaixo a estrutura JSON utilizada no app.js

```javascript
const dados = [
  {
    "id": 1,
    "titulo": "Dom Casmurro",
    "descricao": "Clássico da literatura brasileira sobre traição e ilusão.",
    "conteudo": "Romance de Machado de Assis que explora temas de amor, ciúmes e realidade versus aparência. Uma obra-prima da ficção nacional.",
    "categoria": "Ficção",
    "autor": "Machado de Assis",
    "data": "1899",
    "imagem": "https://via.placeholder.com/200x300/FF5733/FFFFFF?text=Dom+Casmurro"
  },
  {
    "id": 2,
    "titulo": "1984",
    "descricao": "Distopia sobre vigilância e controle totalitário.",
    "conteudo": "Livro de George Orwell que descreve um futuro opressivo onde o governo controla tudo, incluindo pensamentos. Um alerta sobre liberdade.",
    "categoria": "Distopia",
    "autor": "George Orwell",
    "data": "1949",
    "imagem": "https://via.placeholder.com/200x300/33FF57/FFFFFF?text=1984"
  },
  {
    "id": 3,
    "titulo": "O Senhor dos Anéis",
    "descricao": "Épica fantasia
