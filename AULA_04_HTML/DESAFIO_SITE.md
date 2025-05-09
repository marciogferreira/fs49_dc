# Desafio: Criando um Site com HTML Básico, Tabelas e Formulários

## Descrição

Neste desafio, você irá criar um site simples utilizando **somente HTML**. O objetivo é praticar a utilização de tags HTML básicas, a criação de tabelas e o uso de formulários. O site terá várias páginas, sendo que cada uma delas terá um propósito específico.

---

## Requisitos

Você precisa criar um site com as seguintes páginas e funcionalidades:

### Página 1: **Página Inicial**

* **Cabeçalho** com o título do site e uma breve descrição.
* **Menu de navegação** que permitirá ao usuário navegar para as outras páginas do site.
* **Conteúdo principal** com uma introdução sobre o site, por exemplo, o objetivo do site ou os produtos/serviços oferecidos.

### Página 2: **Tabela de Dados**

* **Tabela** com ao menos 3 colunas e 4 linhas de dados fictícios. Utilize a tag `<table>`, com as tags `<thead>`, `<tbody>`, e `<tr>`, para estruturar os dados.
* A tabela pode ser sobre qualquer assunto (ex.: Lista de produtos, tabela de alunos, ranking de jogos, etc.)

### Página 3: **Formulário de Contato**

* **Formulário** com pelo menos os seguintes campos:

  * Nome (input do tipo texto)
  * E-mail (input do tipo email)
  * Mensagem (textarea)
  * Botão de envio (button)
* Utilize a tag `<form>`, e crie as tags `<input>`, `<textarea>`, e `<button>`. Adicione a tag `action` (pode ser uma URL fictícia) e `method="POST"`, mas como estamos utilizando apenas HTML, o formulário não precisará ser funcional, apenas a estrutura deve ser criada.

### Página 4: **Sobre**

* Uma breve descrição sobre o site ou sobre a sua criação, com **parágrafos** e **listas** (ordenadas ou não).

### Extras (opcional):

* **Imagens**: Você pode adicionar uma imagem na Página Inicial ou na Página Sobre utilizando a tag `<img>`.
* **Links**: Adicione links nas páginas para facilitar a navegação entre elas. Utilize a tag `<a>` para criar links internos (entre as páginas do seu site).

---

## Instruções

1. **Estrutura do projeto**: Organize o projeto da seguinte maneira:

   * Crie uma pasta chamada `meu_site`.
   * Dentro da pasta `meu_site`, crie arquivos HTML para cada página:

     * `index.html` (Página Inicial)
     * `tabela.html` (Tabela de Dados)
     * `contato.html` (Formulário de Contato)
     * `sobre.html` (Sobre)

2. **Navegação**: Cada página deve ter links para as outras páginas do site. Adicione um menu de navegação simples na parte superior de cada página com os links correspondentes para:

   * Página Inicial
   * Tabela de Dados
   * Formulário de Contato
   * Sobre

3. **HTML básico**: Use apenas tags HTML para a construção do site. Não é necessário adicionar CSS ou JavaScript, pois o foco é em estruturar o conteúdo.

---

## Exemplo de Estrutura do Código HTML

Aqui está um exemplo básico para a **Página Inicial** (`index.html`):

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Simples</title>
</head>
<body>

    <header>
        <h1>Bem-vindo ao Meu Site!</h1>
        <p>Este é um exemplo de site simples utilizando apenas HTML.</p>
    </header>

    <nav>
        <ul>
            <li><a href="index.html">Página Inicial</a></li>
            <li><a href="tabela.html">Tabela de Dados</a></li>
            <li><a href="contato.html">Formulário de Contato</a></li>
            <li><a href="sobre.html">Sobre</a></li>
        </ul>
    </nav>

    <main>
        <h2>Introdução</h2>
        <p>Este site foi criado para mostrar como usar tags HTML básicas, tabelas e formulários.</p>
    </main>

    <footer>
        <p>&copy; 2025 Meu Site Simples</p>
    </footer>

</body>
</html>
```

---

## Dicas

* Não se esqueça de usar corretamente as tags de **estrutura** como `<header>`, `<nav>`, `<main>`, e `<footer>`.
* Para as tabelas, use a tag `<th>` para os cabeçalhos das colunas e a tag `<td>` para os dados das células.
* Utilize as tags `<ul>` e `<li>` para criar listas ordenadas ou não ordenadas.

---

## Envio

Boa sorte!
