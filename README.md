## Formação HTML Web Developer · DIO

![Html_Developer](https://github.com/user-attachments/assets/4dd8bd24-2a68-4cca-9c07-4e65f7464bf4)

---

# 🌐 Criação de Página Web com HTML e CSS — Fundamentos na Prática

## 1. Problema de Negócio

Qualquer desenvolvedor que inicia na área enfrenta um desafio concreto: **saber usar uma ferramenta não é o mesmo que saber aplicá-la com intenção.**

No aprendizado de HTML, é fácil memorizar tags de forma isolada sem entender como elas se combinam para criar uma página funcional. O desafio real é ir além da lista de comandos e **construir uma estrutura coesa, semântica e navegável** — mesmo com recursos básicos.

---

## 2. Contexto

Este projeto foi desenvolvido como desafio prático do módulo introdutório da **Formação HTML Web Developer** na DIO. O objetivo era construir uma página web real, combinando todas as tags estudadas em um único documento estruturado e estilizado.

O projeto não é um exercício isolado: é a fundação. Toda a carreira em desenvolvimento web parte do domínio consciente dessas primitivas — `h1` a `h6`, listas, links, ênfase textual, citações e semântica de documento. Fazer isso direito desde o início é uma escolha técnica deliberada.

---

## 3. Premissas

- O projeto utiliza exclusivamente **HTML5 e CSS3 nativos**, sem frameworks ou bibliotecas externas, para garantir compreensão do comportamento puro da linguagem.
- A tag `<font>` foi incluída intencionalmente como referência histórica — presente no conteúdo do curso — e não como prática recomendada para produção.
- O CSS foi mantido simples e separado (`css/style.css`) para demonstrar a separação entre estrutura e apresentação desde o primeiro projeto.
- O arquivo `index.html` cobre todas as tags obrigatórias do desafio e incorpora tags adicionais pesquisadas de forma autônoma.

---

## 4. Estratégia da Solução

A construção da página seguiu uma lógica progressiva de complexidade:

**Etapa 1 — Estrutura semântica do documento:** definição do esqueleto com `<!DOCTYPE html>`, `<head>` configurado com charset UTF-8 e viewport responsivo, e `<body>` como ponto de entrada do conteúdo.

**Etapa 2 — Hierarquia de conteúdo:** uso de `h1` a `h3` para criar uma hierarquia visual e semântica clara, com `p` para os blocos de texto corrido.

**Etapa 3 — Formatação inline e ênfase:** aplicação de `<i>`, `<u>`, `<strong>`, `<small>`, `<mark>`, `<sub>`, `<sup>`, `<del>` e `<abbr>` para demonstrar o comportamento de cada elemento em contexto real de uso.

**Etapa 4 — Organização por listas:** implementação de `<ol>` e `<ul>` para diferenciar conteúdo sequencial de conteúdo sem ordem definida.

**Etapa 5 — Citação e navegação:** uso de `<blockquote>` para destaque de citação e `<a>` com `target="_blank"` para link externo.

**Etapa 6 — Estilização desacoplada:** criação do arquivo `css/style.css` com font-family, espaçamentos, line-height e cor de links, reforçando a separação de responsabilidades entre HTML e CSS.

---

## 5. Insights Técnicos

A construção do projeto revelou decisões de design importantes para quem está aprendendo:

- **Separação de responsabilidades funciona na prática:** manter o CSS em arquivo separado desde o início cria um hábito que escala para projetos maiores — o HTML descreve o quê, o CSS descreve o como.
- **Tags de ênfase têm semântica, não apenas aparência:** `<strong>` e `<i>` carregam significado para leitores de tela e motores de busca, enquanto `<b>` e `<em>` são puramente visuais. Essa distinção importa desde o início.
- **`<abbr>` com `title` melhora acessibilidade imediatamente:** uma tag simples que entrega informação extra sem custo — boa prática de acessibilidade aplicável desde o HTML básico.
- **`<font>` existe no código intencionalmente:** estudar tags legadas permite entender por que foram substituídas e reforça a importância do CSS moderno para controle visual.

---

## 6. Resultados

O projeto entrega uma página web completa e funcional que cobre:

- Estrutura semântica válida em HTML5
- 12 tags obrigatórias do desafio implementadas em contexto real
- 3 tags adicionais pesquisadas e aplicadas de forma funcional (`<font>`, `<del>`, `<abbr>`)
- CSS externo com tipografia, espaçamento e cores consistentes
- Link funcional para o repositório com abertura em nova aba

O resultado demonstra não apenas que as tags foram usadas, mas que foram **combinadas com intenção** para produzir um documento coeso — que é exatamente a diferença entre executar um tutorial e entender o que foi construído.

---

## 7. Próximos Passos

- Evoluir a página para incluir **CSS Flexbox e Grid**, tornando o layout responsivo para diferentes dispositivos.
- Introduzir **formulários HTML** (`<form>`, `<input>`, `<button>`) como próximo bloco de fundamento.
- Publicar a página via **GitHub Pages** para torná-la acessível diretamente pelo browser, sem necessidade de clone local.
- Avançar para **JavaScript DOM** para adicionar interatividade à estrutura já construída.

---

## 🗂️ Estrutura do Projeto

<img width="711" height="459" alt="Screenshot_20251124-192621" src="https://github.com/user-attachments/assets/144a5cf5-2c41-4d17-acee-d32e72aa9924" />

---

## 🔤 Tecnologias Utilizadas

| Tecnologia | Uso no Projeto |
|------------|----------------|
| **HTML5** | Estrutura semântica e conteúdo da página |
| **CSS3** | Estilização desacoplada via arquivo externo |
| **Git** | Controle de versão |
| **GitHub** | Hospedagem do repositório |
| **VS Code** | Editor de código |

---

## 📥 Como Executar

```bash
git clone https://github.com/Santosdevbjj/criaPageWeb.git
```

Abra a pasta no VS Code e clique duas vezes no arquivo `index.html` para visualizar no navegador. Nenhuma dependência externa necessária.

---

**Contato:**

[![Portfólio Sérgio Santos](https://img.shields.io/badge/Portfólio-Sérgio_Santos-111827?style=for-the-badge&logo=githubpages&logoColor=00eaff)](https://portfoliosantossergio.vercel.app)

[![LinkedIn Sérgio Santos](https://img.shields.io/badge/LinkedIn-Sérgio_Santos-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/santossergioluiz)
