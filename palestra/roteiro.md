# Roteiro da Palestra — Construção de Currículos com IA

> Roteiro minuto-a-minuto. **Híbrido A+B**, 30–35 min, demo ao vivo (testada antes).
> Apresentador: Matheus Medina. Público: calouros do 1º semestre de Gestão em Saúde (UFCSPA).
> Substância em [conteudo-do-curriculo.md](conteudo-do-curriculo.md).

**Legenda:** 🎤 fala/mensagem · 🖥️ o que está na tela · 🎯 objetivo do bloco · ⏱️ tempo

---

## Bloco 0 — Abertura (0–2 min) ⏱️ 2 min
🎯 Quebrar o gelo e prometer valor concreto.

🖥️ Slide simples: título + "seu currículo daqui a 4 anos começa hoje".

🎤 Roteiro de fala:
- "Quem aqui já tem currículo pronto? E quem acha que não tem *nada* pra colocar nele?"
- Promessa: "Em 30 minutos você vai sair sabendo **o que** colocar, **como** escrever e
  **qual ferramenta** usar — de graça e sem saber programar."
- "E eu vou construir um currículo do zero, ao vivo, na frente de vocês."

---

## Bloco 1 — O choque de realidade: os robôs de RH (2–7 min) ⏱️ 5 min
🎯 Criar o problema. Por que o currículo bonito do Canva/Word pode te eliminar.

🖥️ Imagem do funil de ATS / currículo "quebrado" vs currículo limpo.

🎤 Pontos:
- A maioria das empresas usa **ATS** (Applicant Tracking System) pra triar currículos *antes* de um humano ver.
- Currículos super visuais (Canva, caixas de texto no Word) frequentemente **"quebram"** a leitura do robô → descarte automático.
- Não adianta ser o melhor candidato se o robô não consegue *ler* você.
- Gancho: "Existe um formato que os robôs amam — e ele é mais fácil de fazer do que o do Canva."

> ⚠️ Manter leve e rápido. É o susto, não a aula.

---

## Bloco 2 — O atalho: por que LaTeX + como usar com Prism (7–12 min) ⏱️ 5 min
🎯 Justificar **por que LaTeX** (comparando com Canva/Word) e **destruir o medo** de "programar".

### 2.1 — A comparação: Canva/Word × LaTeX (7–10 min)
🖥️ Mostrar lado a lado **3 telas**:
1. Um modelo bonito do **Canva** (trazer um pronto para a palestra).
2. Um currículo de **Word** com colunas/caixas de texto.
3. O **PDF gerado pelo LaTeX** (ex.: o CV do Matheus).

🎤 Por que LaTeX ganha para o ATS:
- **Canva:** lindo para humano, mas o robô lê tudo como **imagem/blocos soltos** → embaralha
  colunas, ícones e caixas. Resultado: o ATS lê "sopa de letras" ou nem lê.
- **Word:** colunas, tabelas e caixas de texto **bagunçam a ordem de leitura** do robô; o
  layout "quebra" em máquinas/versões diferentes.
- **LaTeX:** foca na **estrutura lógica** do texto → PDF **linear**, sempre igual em qualquer
  dispositivo, **100% legível pela máquina**. Bonito para o humano *e* para o robô.
- Frase-chave: "Currículo não é arte — é um documento que precisa ser **lido por um robô primeiro**."

> 💡 Dica de demonstração: se der, copiar o texto do PDF do Canva e colar no bloco de notas
> para mostrar **como o robô "enxerga"** (sai embaralhado). O do LaTeX sai limpo e na ordem.

### 2.2 — Como usar sem programar: o Prism (10–12 min)
🖥️ Mostrar lado a lado: o `.tex` (código) → o PDF lindo gerado.

🎤 Pontos:
- "Isso aqui é LaTeX. Parece código assustador, mas é só o **motor**. Você **não** mexe nele."
- "Não precisa **baixar nada nem instalar** — a gente já tem o **código pronto** (o template) e
  usa o **Prism** (prism.openai.com), editor da OpenAI, **de graça e sem precisar criar conta**."
- O fluxo: **copia o template → cola no Prism → conversa com a IA → baixa o PDF**. Só isso.
- "Você só **conversa** com a IA, como num ChatGPT, e ela mexe no motor pra você."

---

## Bloco 3 — DEMO AO VIVO: construindo a Júlia do zero (12–27 min) ⏱️ 15 min
🎯 O coração. Mostrar a "mágica" **e** ensinar o que vai no currículo (conteúdo da B embutido).

🖥️ Prism aberto, template `celiobjunior/resume-template` colado.

### 3.1 — Apresentar a persona (12–13 min)
🎤 "Essa é a Júlia. 18 anos, 1º semestre igual vocês. Trabalha no administrativo,
fez um Excel básico, inglês básico. Acha que **não tem nada**. Vamos ver."

### 3.2 — Cabeçalho + Educação (13–16 min)
🖥️ Pedir à IA: *"preenche o cabeçalho com nome, cidade, e-mail e LinkedIn da Júlia"*.
🎤 Recados rápidos:
- E-mail **profissional** (nada de apelido).
- "Educação é experiência": graduação **em andamento**, com conclusão prevista.
- Pra quem está começando, **Educação vai no topo**, antes de Experiência.

### 3.3 — Experiência: "não tenho nada" resolvido (16–20 min)
🖥️ Jogar a info solta: *"ela trabalha no administrativo, atende telefone e organiza papelada"*.
🎤 Mostrar a info solta virar bullet bom com a **fórmula** (substantivo de ação + o quê + resultado):
- Antes: "trabalho no administrativo" → Depois: "Atendimento ao público e triagem de demandas; organização e arquivo de documentos; agendamento e controle de planilhas."
- "Mesmo trabalho. Muda só **como se descreve** — e é nisso que a IA é boa."
- Regras: sem gerúndio, máx. 3 bullets, sem 'apoio/suporte' vago.

### 3.4 — Projetos e Voluntariados: o momento-chave (20–23 min)
🖥️ Seção vazia hoje.
🎤 **Virada de chave da palestra:**
- "Aqui tá vazio HOJE. Mas é a seção mais importante pra vocês."
- O que dá pra começar JÁ no 1º semestre: **ligas acadêmicas, projetos de extensão, iniciação científica, monitoria, eventos/atlética/CA, voluntariado**.
- "Essa palestra não é só pra fazer um PDF. É pra você sair sabendo **o que colecionar** nos próximos 4 anos."

### 3.5 — Habilidades + exportar PDF (23–25 min)
🖥️ Adicionar Excel, idiomas. Gerar o PDF da Júlia ao vivo.
🎤 "Em poucos minutos, o currículo 'vazio e assustador' da Júlia virou isso. Limpo, legível por robô, pronto."

### 3.6 — O salto: o CV do Matheus (25–27 min)
🖥️ Abrir o `curriculo.pdf` do Matheus.
🎤 "Esse é o meu. Mesmo template, mesmo método. E olha minha experiência mais antiga:
**vendedor numa cafeteria, 7 anos**. Todo mundo começa de algum lugar.
A Júlia daqui a alguns anos vira isso — se ela colecionar as coisas certas."

---

## Bloco 4 — O recado estratégico + aviso de ouro (27–31 min) ⏱️ 4 min
🎯 Honestidade e plano de ação.

🎤 Pontos:
- **Aviso de ouro:** "Não peça pra IA inventar seu currículo do zero — fica genérico e o RH percebe.
  Você escreve primeiro, mesmo que tosco, e a IA **melhora**. Ela refina sua história, não inventa."
- Boas práticas em 10 segundos: sem foto, sem idade/gênero, ordem cronológica inversa, não converter pra Word.
- **Primeira ação hoje:** "Saindo daqui: (1) crie um e-mail profissional, (2) abra o Prism, (3) cole o template, (4) preencha educação + 1 experiência."

---

## Bloco 5 — Links úteis + Perguntas (31–35 min) ⏱️ 4 min
🖥️ Slide final com QR code / links.

🎤 Links a entregar:
- Template no GitHub: `celiobjunior/resume-template`
- Prism: `prism.openai.com`
- Pasta `/prompts/` do repo (prompt pronto de RH/currículo)
- FAQ no README do repo
- LinkedIn do Matheus (prova social + networking)

🎤 Fechamento: "O melhor currículo não é o que você faz hoje — é o que você começa a construir hoje. Bora?"

🎤 Abrir para perguntas.

---

## Riscos & checklist pré-palestra
- [ ] Testar a demo no Prism **inteira** antes (login, colar template, prompts, exportar PDF).
- [ ] **Levar um modelo de currículo do Canva** (e um de Word) já abertos para a comparação do Bloco 2.
- [ ] (Opcional) Testar copiar o texto do PDF do Canva no bloco de notas para mostrar o "embaralhado".
- [ ] Ter o `curriculo.pdf` do Matheus já aberto numa aba.
- [ ] Ter os prompts da demo escritos num bloco de notas pra copiar/colar rápido.
- [ ] Plano de internet (backup de conexão / hotspot do celular).
- [ ] Slides mínimos: abertura, ATS, links finais.

## Pendências
- [ ] Ajustar tempos conforme ensaio (a demo tende a esticar).
- [ ] Decidir se haverá slides ou só tela do Prism.
- [ ] (Opcional) Montar os slides de apoio.
