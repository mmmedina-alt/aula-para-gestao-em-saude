<div align="center">

![License](https://img.shields.io/github/license/celiobjunior/resume-template?style=flat-square&color=blue)
![LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-473d3f?logo=latex&style=flat-square)
![Maintained](https://img.shields.io/badge/Maintained-Yes-green?style=flat-square)

</div>

<div align="center">
  <h3>
    <a href="#english">🇺🇸 English</a> | <a href="#português">🇧🇷 Português</a>
  </h3>
</div>

---

<div id="english"></div>

# LaTeX Resume Template 

A professional, clean, and easy-to-use resume template built with LaTeX. **You don't need to be a programmer to use it!**

## 🧩 How to use (No coding required)

If you are not familiar with GitHub or coding, the easiest way to edit your resume is using **[Prism](https://prism.openai.com/)**, an AI-powered code editor. 

> 💡 **What is a LaTeX file?** 
> Many people confuse LaTeX with a complex programming language, but it is actually just a text file used to generate a **high-quality PDF**. You don't need to know how to code to use it!

**Step-by-step guide:**
1. **Copy the code**: Open and copy all the text from the English resume file: [`resumes/en/resume.tex`](resumes/en/resume.tex).
2. **Open Prism**: Go to [prism.openai.com](https://prism.openai.com/). *You don't even need to create an account to use it and download the PDF!*
3. **Paste and Edit**: Create a new file in Prism and paste the code. 
4. **Use AI to help you**: You can edit the text yourself, or you can send your current CV to the chat and ask the AI (just like ChatGPT) to make the modifications for you.
5. **Download the PDF**: Once you are happy with the result, you can generate and download your high-quality PDF directly from Prism!

## ❓ Frequently Asked Questions (FAQ)

<details>
<summary><strong>Which version should I use?</strong></summary>

- Use the **English version** (`/resumes/en/`) for international applications (US, Europe, Remote work).
- Use the **Portuguese version** (`/resumes/pt-br/`) for the Brazilian market.
</details>

<details>
<summary><strong>I don't know LaTeX. Can I still use this?</strong></summary>

**Yes!** Since you will be using Prism, you don't need to understand anything about LaTeX. You can simply ask the AI in Prism to fill in your personal information and it will handle all the code structure for you. 
</details>

<details>
<summary><strong>Where can I get help with what to write?</strong></summary>

You can ask Prism's built-in AI directly! We have also included a `/prompts/` folder in this repository with some prompts that can help you write better bullet points for your experience using any AI.
</details>

<details>
<summary><strong>Should I put a photo on my resume?</strong></summary>

**No.** For most tech and professional jobs (especially international ones), photos are not recommended and can sometimes lead to automatic rejection by Applicant Tracking Systems (ATS).
</details>

<details>
<summary><strong>Can I convert this to Word?</strong></summary>

While possible, **it is not recommended**. One of the main benefits of LaTeX is that it creates a perfectly formatted PDF that looks professional on any device. Converting to Word often messes up the design.
</details>

<details>
<summary><strong>How do I generate the PDFs of my resumes?</strong></summary>

If you are using **Prism**, you can simply download the generated PDF directly from their interface. 

Alternatively, if you are using GitHub, every push (commit) to the repository triggers a workflow that compiles the `.tex` files and **commits the updated PDFs back into the repository**. After the workflow finishes (~1–2 min), the updated `curriculo.pdf` / `resume.pdf` will be available directly in the repo (no need to download artifacts).
</details>

<details>
<summary><strong>How do I edit my resume directly on GitHub (no local setup)?</strong></summary>

You can edit and regenerate your PDF entirely from the browser — no VS Code, no Git, no LaTeX install required:

1. Open the `.tex` file on GitHub (e.g. `resumes/pt-br/curriculo.tex`).
2. Click the **pencil icon ✏️** ("Edit this file").
3. Make your changes in the editor.
4. Click **"Commit changes..."** → write a message → commit directly to `main`.
5. The **Build workflow runs automatically** (watch the **Actions** tab — yellow dot while running, green when done).
6. When it turns green, the workflow has **committed the updated PDF back** to the repo. Open `curriculo.pdf` / `resume.pdf` to see the new version.

> ⚠️ If you also work locally, run `git pull` before editing locally again, since both your web edit and the auto-generated PDF live on the remote.
</details>

---

<div id="português"></div>

# Modelo de Currículo em LaTeX

Um modelo de currículo profissional, limpo e fácil de usar, feito em LaTeX. **Você não precisa ser um programador para usar ele!**

## 🧩 Como usar (Sem precisar programar)

Se você não tem familiaridade com GitHub ou código, a maneira mais fácil de usar este modelo é com o **[Prism](https://prism.openai.com/)**, um editor de código com inteligência artificial.

> 💡 **O que é um arquivo em LaTeX?** 
> Muitas pessoas confundem LaTeX com uma linguagem de programação complexa, mas na verdade é apenas um arquivo de texto usado para gerar um **PDF de alta qualidade**. Você não precisa saber programar para usar!

**Passo a passo:**
1. **Copie o código**: Abra e copie todo o texto do arquivo de currículo em português: [`resumes/pt-br/curriculo.tex`](resumes/pt-br/curriculo.tex).
2. **Acesse o Prism**: Acesse [prism.openai.com](https://prism.openai.com/). *Você nem precisa criar conta para editar e baixar!*
3. **Cole e Edite**: Crie um arquivo no Prism e cole o código.
4. **Use a IA a seu favor**: Você pode alterar o texto manualmente, ou pode enviar seu currículo atual no chat e pedir direto para a IA fazer as modificações para você, como num ChatGPT.
5. **Baixe o PDF**: Para gerar o PDF de alta qualidade, é só baixar pelo próprio Prism!

## ❓ Perguntas Frequentes (FAQ)

<details>
<summary><strong>Qual versão devo usar?</strong></summary>

- Use a **versão em Inglês** (`/resumes/en/`) para vagas internacionais (EUA, Europa, Vagas Remotas).
- Use a **versão em Português** (`/resumes/pt-br/`) para o mercado brasileiro.
</details>

<details>
<summary><strong>Eu não sei LaTeX. Ainda posso usar?</strong></summary>

**Sim!** Como você usará o Prism, não precisa entender nada de LaTeX. Você pode simplesmente pedir para a IA do Prism preencher suas informações pessoais e ela lidará com toda a estrutura do código para você.
</details>

<details>
<summary><strong>Onde consigo ajuda para escrever o conteúdo?</strong></summary>

Você pode pedir diretamente para a IA integrada do Prism! Nós também incluímos uma pasta `/prompts/` neste repositório com alguns prompts que podem te ajudar a escrever melhores descrições usando qualquer IA.
</details>

<details>
<summary><strong>Devo colocar foto no meu currículo?</strong></summary>

**Não.** Para a maioria das vagas de tecnologia e setores corporativos (especialmente internacionais), fotos não são recomendadas e podem atrapalhar a leitura por sistemas automáticos (ATS).
</details>

<details>
<summary><strong>Posso converter para Word?</strong></summary>

Embora seja possível, **não é recomendado**. Um dos principais benefícios do LaTeX é criar um PDF perfeitamente formatado que parece profissional em qualquer dispositivo. Converter para Word geralmente quebra o design.
</details>

<details>
<summary><strong>Como gero os PDFs do meu currículo?</strong></summary>

Se você estiver usando o **Prism**, basta baixar o PDF gerado diretamente pela interface deles.

Alternativamente, se você usa o GitHub, cada push (commit) no repositório dispara um workflow que compila os arquivos `.tex` e **commita os PDFs atualizados de volta no repositório**. Após o workflow terminar (~1–2 min), o `curriculo.pdf` / `resume.pdf` atualizado já estará disponível direto no repo (sem precisar baixar artifacts).
</details>

<details>
<summary><strong>Como edito meu currículo direto no GitHub (sem instalar nada)?</strong></summary>

Você pode editar e gerar um PDF novo inteiramente pelo navegador — sem VS Code, sem Git, sem instalar LaTeX:

1. Abra o arquivo `.tex` no GitHub (ex: `resumes/pt-br/curriculo.tex`).
2. Clique no ícone de **lápis ✏️** ("Edit this file").
3. Faça suas alterações no editor.
4. Clique em **"Commit changes..."** → escreva uma mensagem → commite direto na `main`.
5. O **workflow Build roda automaticamente** (acompanhe na aba **Actions** — bolinha amarela rodando, verde quando terminar).
6. Quando ficar verde, o workflow já terá **commitado o PDF atualizado de volta** no repo. Abra o `curriculo.pdf` / `resume.pdf` para ver a nova versão.

> ⚠️ Se você também trabalha localmente, rode `git pull` antes de editar de novo na sua máquina, já que tanto sua edição web quanto o PDF gerado automaticamente ficam no remoto.
</details>

---

## License / Licença

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.