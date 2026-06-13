# Contexto do projeto — aula-para-gestao-em-saude

> Este arquivo é lido automaticamente pelo Claude Code ao abrir uma sessão nesta pasta.
> Serve para continuar o trabalho que começou em outra sessão (no repositório `-resume-template`).

## O que é este repositório

Cópia do repositório `-resume-template` (um modelo de currículo em LaTeX, bilíngue
PT/EN, do autor original Celio B Junior, licença Apache 2.0), criado para evoluir
em uma nova direção: **material de aula sobre Gestão em Saúde**.

- Histórico git **completo** foi preservado na cópia (último commit herdado: `343e6e3`).
- Repositório no GitHub (privado): https://github.com/mmmedina-alt/aula-para-gestao-em-saude
- O `origin` já aponta para esse repo novo.
- O repositório original `-resume-template` continua intacto, sem alterações.

## Ambiente já configurado (LaTeX)

Instalado e testado na máquina (macOS 13 Ventura) — vale para qualquer projeto:

- **BasicTeX** (TeX Live 2026) — `pdflatex` em `/Library/TeX/texbin`
- Pacotes extras instalados via `tlmgr`: `enumitem`, `titlesec`, `xurl`, `cm-super`
  (fontes escaláveis, necessárias por causa do `microtype` + `fontenc T1`)
- Extensão **LaTeX Workshop** instalada no VS Code (`Ctrl+Alt+V` = preview;
  `Ctrl+S` recompila)
- Ambos os currículos (`resumes/pt-br/curriculo.tex` e `resumes/en/resume.tex`)
  compilam sem erro.

> Se em terminal novo o `pdflatex` não aparecer, rode: `eval "$(/usr/libexec/path_helper)"`
> ou garanta `/Library/TeX/texbin` no PATH. Se o LaTeX Workshop não achar o pdflatex,
> reabra o VS Code.

## Currículo do dono do repo (Matheus Medina)

`resumes/pt-br/README.md` contém o guia pessoal do Matheus. As versões `.tex` são o
currículo real dele. **Não inventar nem alterar dados pessoais** sem pedir.

### Conversão para Markdown (feito)

- Criado `resumes/pt-br/curriculo.md` = versão **fiel** do `curriculo.tex`, sem alterar
  nenhuma informação (só adaptações de formatação que o Markdown exige).
- **Pendente:** versão em inglês `resumes/en/resume.md` (a partir de `resume.tex`) — ainda não feita.
- **Pendente:** commit/push do `curriculo.md` (ainda não commitado).

## Próximos passos discutidos

1. (Opcional) Gerar `resumes/en/resume.md` a partir de `resume.tex`.
2. Commit + push do(s) Markdown(s).
3. Direção maior: transformar/criar conteúdo de **aula de Gestão em Saúde** (a definir com o usuário).

## Preferências de trabalho observadas

- Usuário **não programa**; prefere explicações claras em português e instruções passo a passo.
- Comandos que precisam de `sudo`/senha são executados **pelo usuário** no terminal dele
  (o agente não tem TTY para digitar senha).
