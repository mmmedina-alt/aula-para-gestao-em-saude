# Currículo — Matheus Medina

Este é o meu currículo pessoal em LaTeX. Abaixo estão as instruções para editar, visualizar e atualizar no futuro.

---

## Como abrir e editar

1. Abra o VS Code na pasta `resume-template`
2. Abra o arquivo `resumes/pt-br/curriculo.tex`
3. Pressione `Ctrl+Alt+V` para abrir o preview do PDF ao lado
4. Edite o arquivo — a cada `Ctrl+S` o PDF atualiza automaticamente

> **Requisitos:** MiKTeX instalado + extensão LaTeX Workshop no VS Code.

---

## Estrutura do currículo

O arquivo `curriculo.tex` está organizado nas seguintes seções, nesta ordem:

1. **Cabeçalho** — nome, cidade, email, telefone
2. **Educação** — formações em ordem decrescente
3. **Experiência** — experiências profissionais em ordem decrescente
4. **Projetos e Voluntariados** — bolsas e projetos em ordem decrescente
5. **Habilidades** — linguagens, ferramentas, tecnologias, certificações e idiomas

---

## Como adicionar uma nova experiência

Copie o bloco abaixo e cole na posição correta (ordem decrescente por data):

```latex
\cventry{Nome da Empresa}{Cidade, UF}{Cargo}{Mês Ano -- Mês Ano}
    \begin{itemize}
        \item Descrição do que você fez.
        \item Outra descrição.
        \item Mais uma descrição.
    \end{itemize}
```

**Dicas para os bullets:**
- Comece sempre com um substantivo de ação (Gestão, Desenvolvimento, Criação, Análise...)
- Seja específico — evite termos genéricos como "apoio" ou "suporte"
- Máximo de 3 bullets por entrada para manter o visual limpo
- Evite gerúndio (fazendo, desenvolvendo) — prefira substantivos (desenvolvimento, criação)

---

## Como atualizar habilidades

As habilidades ficam no final do arquivo, na seção `\section{Habilidades}`. Basta adicionar ou remover itens nas listas existentes:

- **Linguagens** — linguagens de programação e marcação
- **Ferramentas** — softwares e plataformas do dia a dia
- **Tecnologias** — frameworks e bancos de dados
- **Certificações** — cursos com certificado relevante
- **Idiomas** — idiomas com nível de proficiência

---

## Como gerar o PDF

**Opção 1 — Automático (recomendado):**
Salve o arquivo com `Ctrl+S` — o LaTeX Workshop compila e atualiza o preview.

**Opção 2 — Manual pelo terminal:**
```bash
cd resumes/pt-br
pdflatex -interaction=nonstopmode curriculo.tex
```

O PDF gerado fica em `resumes/pt-br/curriculo.pdf`.

---

## Como subir as alterações no GitHub

```bash
git add resumes/pt-br/curriculo.tex
git commit -m "feat: atualizar currículo"
git push
```

> O GitHub Actions compila o LaTeX automaticamente a cada push e disponibiliza o PDF na aba **Actions > último build > Artifacts**.

---

## Checklist antes de atualizar

- [ ] Todas as experiências estão em ordem decrescente?
- [ ] Os cargos estão consistentes (empresa -- vínculo no 1º campo, cargo no 3º)?
- [ ] Os bullets seguem o padrão de substantivo + complemento?
- [ ] Português correto, sem gerúndios soltos?
- [ ] As datas estão no formato `Mês Ano -- Mês Ano`?
- [ ] O PDF compilou sem erros?
