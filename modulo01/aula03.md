# Aula 03 – Markdown, README.md e Criação do Manual

## 📚 Disciplina

Versionamento de Código com Git e GitHub

## 🎓 Curso

Técnico em Desenvolvimento de Sistemas

## ⏱️ Duração

40 minutos

## 🚀 Projeto Integrador

Meu Manual de Git e GitHub

---

# 🎯 Objetivos da Aula

Ao final desta aula você deverá ser capaz de:

* Compreender o que é Markdown.
* Entender a importância da documentação técnica.
* Conhecer a função do arquivo README.md.
* Utilizar os principais elementos do Markdown.
* Produzir seu primeiro README estruturado.
* Realizar o primeiro commit da disciplina.
* Evoluir o Projeto Integrador.

---

# 🔄 Revisão das Aulas Anteriores

## Aula 01

Aprendemos:

* O que é versionamento;
* O que é histórico;
* O que é rastreabilidade;
* Por que o Git foi criado.

---

## Aula 02

Aprendemos:

* O que é GitHub;
* O que é um repositório;
* GitHub como portfólio;
* Estrutura inicial do Projeto Integrador.

---

# 🤔 Por Que Aprender Isso?

Imagine que você encontrou um projeto muito interessante no GitHub.

Ao abrir o repositório você encontra apenas:

```text
Projeto/
│
├── index.html
├── style.css
└── script.js
```

Sem explicação.

Sem instruções.

Sem documentação.

Você consegue descobrir:

* O objetivo do projeto?
* Como executá-lo?
* Quem o desenvolveu?
* Como utilizá-lo?

Provavelmente não.

Agora imagine o mesmo projeto contendo um README bem organizado.

A compreensão se torna muito mais fácil.

Por isso a documentação é uma das habilidades mais valorizadas no mercado de tecnologia.

---

# 📖 O Que É Markdown?

Markdown é uma linguagem simples utilizada para criar documentos formatados utilizando apenas texto.

Ela foi criada para permitir a produção rápida de documentação.

---

## Onde o Markdown é Utilizado?

Atualmente o Markdown é utilizado em:

* GitHub
* GitLab
* Bitbucket
* Documentações técnicas
* Wikis
* Blogs técnicos
* Projetos Open Source

---

# 📌 O Que É um README?

README significa:

```text
READ ME
↓
LEIA-ME
```

Normalmente é o primeiro arquivo visualizado quando alguém acessa um projeto.

---

## Função do README

Explicar:

* O que é o projeto;
* Quem desenvolveu;
* Como utilizar;
* Como instalar;
* Como contribuir.

---

# 💼 Mercado de Trabalho

Em muitas empresas o README é considerado obrigatório.

Um projeto sem documentação costuma gerar:

❌ Dificuldade de manutenção.

❌ Dificuldade de colaboração.

❌ Dificuldade de aprendizado.

---

Já um projeto bem documentado gera:

✅ Organização.

✅ Clareza.

✅ Profissionalismo.

✅ Facilidade de manutenção.

---

# 🧠 Principais Elementos do Markdown

---

## Títulos

Código:

```markdown
# Título Principal

## Subtítulo

### Seção
```

Resultado:

```markdown
# Título Principal

## Subtítulo

### Seção
```

---

## Texto em Negrito

Código:

```markdown
**Texto em negrito**
```

Resultado:

**Texto em negrito**

---

## Texto em Itálico

Código:

```markdown
*Texto em itálico*
```

Resultado:

*Texto em itálico*

---

## Listas

Código:

```markdown
- Item 1
- Item 2
- Item 3
```

Resultado:

* Item 1
* Item 2
* Item 3

---

## Listas Numeradas

Código:

```markdown
1. Primeiro
2. Segundo
3. Terceiro
```

Resultado:

1. Primeiro
2. Segundo
3. Terceiro

---

## Links

Código:

```markdown
[GitHub](https://github.com)
```

Resultado:

[GitHub](https://github.com)

---

## Blocos de Código

Código:

````markdown
```html
<h1>Olá Mundo</h1>
```
````

Resultado:

```html
<h1>Olá Mundo</h1>
```

---

## Tabelas

Código:

```markdown
| Tecnologia | Função |
|------------|---------|
| Git | Versionamento |
| GitHub | Hospedagem |
```

Resultado:

| Tecnologia | Função        |
| ---------- | ------------- |
| Git        | Versionamento |
| GitHub     | Hospedagem    |

---

# 🚀 Estrutura do README do Projeto Integrador

Nesta disciplina utilizaremos uma estrutura simples.

---

## Modelo Inicial

```markdown
# Meu Manual de Git e GitHub

Projeto desenvolvido durante a disciplina de Versionamento de Código com Git e GitHub.

## 👨‍🎓 Autor

Seu Nome

## 📚 Conteúdo

- Aula 01
- Aula 02
- Aula 03

## 🎯 Objetivo

Aprender Git e GitHub de forma prática e organizada.
```

---

# 🛠️ Mão na Massa

## Atividade Prática

### Passo 1

Abra a pasta:

```text
manual-git-github
```

---

### Passo 2

Abra o arquivo:

```text
README.md
```

---

### Passo 3

Substitua o conteúdo atual pelo modelo apresentado nesta aula.

---

### Passo 4

Crie:

```text
aula03/
│
└── resumo.md
```

---

### Passo 5

No arquivo:

```text
aula03/resumo.md
```

registre um resumo dos principais conceitos aprendidos.

---

# 🎉 Primeiro Commit da Disciplina

Chegou o momento do primeiro registro oficial de alterações.

---

## Conceito

Commit é um registro permanente no histórico do projeto.

Pense nele como uma fotografia do estado atual do projeto.

---

## Exemplo de Mensagem

```text
Cria estrutura inicial do manual
```

---

## O Que Ainda Não Faremos?

Nesta aula ainda não executaremos comandos Git diretamente.

Primeiro vamos compreender o conceito.

Os comandos serão aprofundados nas próximas aulas.

Por enquanto, vamos registrar a mensagem que utilizaremos futuramente.

---

# 📌 Atualizando Meu Manual de Git e GitHub

Ao final da aula sua estrutura deverá estar assim:

```text
manual-git-github/
│
├── README.md
│
├── aula01/
│   └── anotacoes.md
│
├── aula02/
│   └── resumo.md
│
└── aula03/
    └── resumo.md
```

---

# 🎯 Entregáveis da Aula

✔ README atualizado.

✔ Estrutura das três aulas criada.

✔ Resumo da Aula 03 produzido.

✔ Primeiro modelo de documentação criado.

✔ Mensagem do primeiro commit definida.

---

# 📊 Evidências de Aprendizagem

O professor deverá conseguir verificar:

* README estruturado;
* Uso correto de Markdown;
* Organização das pastas;
* Produção dos resumos;
* Compreensão da importância da documentação.

---

# 🚀 Desafio da Aula

Responda utilizando suas próprias palavras.

### Pergunta 1

Por que um README é importante para um projeto?

---

### Pergunta 2

O que aconteceria se um projeto não tivesse documentação?

---

### Pergunta 3

Por que empresas valorizam profissionais que documentam seus projetos?

---

### Pergunta 4

Qual a principal vantagem do Markdown em relação à formatação manual de documentos?

---

# 📚 Resumo da Aula

Nesta aula aprendemos:

✅ O que é Markdown.

✅ O que é um README.

✅ Como criar títulos.

✅ Como criar listas.

✅ Como criar links.

✅ Como criar tabelas.

✅ Como organizar documentação.

✅ Como estruturar o Projeto Integrador.

✅ O conceito de commit.

---

# 🔗 Preparando-se Para a Próxima Aula

Na próxima aula iniciaremos o uso prático do Git.

Vamos aprender:

* O que é Fork;
* O que é Clone;
* Repositório local e remoto;
* Como obter uma cópia de um projeto.

Será nossa entrada oficial no Módulo 2.

---

[⏪ Aula 02 – GitHub e o Mercado de Trabalho](aula02.md) | [🏠 Início](../README.md) | [⏩ Aula 04 – Fork e Clone](aula04.md)
