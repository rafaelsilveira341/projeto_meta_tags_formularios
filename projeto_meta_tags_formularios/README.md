# Projeto - Meta Tags e Formulários HTML

## Curso
**Tecnologia em Sistemas para Internet**

## Disciplina
**Construção de Páginas Web I**

## Professor
**Anderson José Lauer**

## Descrição

Este projeto foi desenvolvido para demonstrar, por meio de exemplos práticos em HTML, a utilização de:

- Meta tags do elemento `<head>`;
- Tipos de campos de formulário HTML;
- Atributos do elemento `<form>`;
- Atributos utilizados em elementos de entrada.

Todos os arquivos possuem comentários no próprio código explicando a função dos elementos e apresentando exemplos de utilização.

## Estrutura do projeto

```text
projeto_meta_tags_formularios/
│
├── index.html
├── meta-tags.html
├── formularios-tipos-1.html
├── formularios-tipos-2.html
├── atributos-formulario.html
└── README.md
```

## Conteúdo

### A e B - Meta Tags

O arquivo `meta-tags.html` apresenta:

- charset
- viewport
- description
- author
- og:title
- og:description
- og:image
- og:url
- referrer
- content-security-policy
- robots
- keywords
- theme-color
- color-scheme
- favicon

### C - Tipos de formulário

O arquivo `formularios-tipos-1.html` apresenta:

- color
- date
- datetime-local
- email
- file
- hidden
- image

### D - Tipos de formulário

O arquivo `formularios-tipos-2.html` apresenta:

- month
- number
- range
- search
- tel
- time
- url
- week

### E - Atributos

O arquivo `atributos-formulario.html` apresenta:

#### Atributos do formulário

- action
- target
- method
- autocomplete

#### Atributos de entrada

- value
- readonly
- disabled
- size
- maxlength
- min
- max
- multiple
- placeholder
- required
- autofocus
- autocomplete

## Como executar

1. Baixe ou clone este projeto.
2. Abra a pasta no Visual Studio Code.
3. Abra o arquivo `index.html`.
4. Execute o arquivo utilizando um navegador.
5. Navegue pelos links para visualizar os exemplos.

Também é possível utilizar uma extensão como **Live Server** no Visual Studio Code.

## Publicação no GitHub

Para publicar:

```bash
git init
git add .
git commit -m "Projeto inicial - Meta Tags e Formulários HTML"
git branch -M main
git remote add origin URL_DO_SEU_REPOSITORIO
git push -u origin main
```

Substitua `URL_DO_SEU_REPOSITORIO` pelo endereço do seu repositório no GitHub.

## Observação

O arquivo `favicon.ico` é citado como exemplo na página `meta-tags.html`. Caso você queira demonstrar o favicon funcionando, coloque um arquivo chamado `favicon.ico` na raiz do projeto.

## Objetivo acadêmico

O objetivo é compreender como recursos do HTML são utilizados para estruturar páginas, fornecer metadados, melhorar a apresentação de conteúdos compartilhados e criar formulários com diferentes tipos de entrada e atributos.
