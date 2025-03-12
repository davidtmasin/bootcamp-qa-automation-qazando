# Bootcamp QAautomation - Qazando

Seja bem-vindo(a)! 👋

Este repositório destina-se ao armazenamento das práticas de testes realizadas no decorrer das aulas do Bootcamp QAautomation da Qazando e em minhas autoiniciativas de aprendizado, visando a melhora das habilidades técnicas com as ferramentas de automação de testes que foram proposta ao decorrer deste bootcamp tais como, Cypress, Maestro e K6.

---
 ## 1. Programação do Bootcamp QAautomation
 
 Serão 04 aulas que abordarão os seguintes assuntos:
 
#### 📌 Dia 01: Automação Web com Cypress 🌐

No dia 01, vamos mergulhar na Automação WEB com Cypress, do zero ao avançado!

✅ Como iniciar na automação de testes web com Cypress;

✅ Passo a passo para escrever seus primeiros testes;

✅ Os erros mais comuns que podem travar seu progresso;

✅ Dicas práticas para acelerar sua carreira como QA.
 
#### 📌 Dia 02: Automação API com Cypress 🚀

No dia 02, vamos mergulhar na **Automação de API com Cypress**, aprendendo como testar APIs de forma eficiente e automatizada!

✅ Como iniciar na automação de testes de API com Cypress;

✅ Métodos HTTP essenciais: GET, POST, PUT, DELETE;

✅ Como validar respostas e estruturar bons testes;

✅ Dicas para integrar testes de API na sua estratégia de qualidade.

#### 📌 Dia 03: Automação Mobile com Maestro 📱

No dia 03, vamos explorar a **Automação Mobile com Maestro**, uma das ferramentas mais promissoras para testar aplicativos de forma simples e eficiente!

✅ Como iniciar na automação de testes mobile com Maestro;

✅ Criando e rodando scripts de teste para apps Android e iOS;

✅ Melhores práticas para garantir testes confiáveis;

✅ Como integrar a automação mobile no seu fluxo de qualidade.

#### 📌 Dia 04: Testes de Perfomance com K6 🏃

⚠️ Aguardando conteúdo...

---
## 2. Tecnologias

As ferramentas utilizadas por mim ao longo deste bootcamp foram:

- VsCode
- Node.js (v22.14.0)
- npm (10.9.2)
- git (version 2.48.1.windows.1)
- Cypress (14.1.0)
- Postman
- Maestro
- K6

---
## 3. Testes

Para iniciar um projeto de testes com Cypress será necessária a execução dos seguintes comandos de terminal:

```sh
mkdir <nome_do_projeto>
cd <nome_do_projeto>
npm init -y
npm install cypress
```

Caso seja necessário trabalhar com variáveis sensíveis, crie o arquivo `cypress.env.json` e lembre-se de incluí-lo ao arquivo `.gitignore`, aqui temos um exemplo com algumas inclusões interessantes:

```.gitignore
.DS_Store
node_modules/
cypress/downloads/
cypress/screenshots/
cypress/videos/
```

Para facilitar sua vida, crie scripts personalizados no arquivo `package.json` para agilizar algumas ações, por exemplo:

```json
"scripts": {
    "cy:open": "cypress open",
    "cy:open:mobile": "cypress open --config viewportWidth=410,viewportHeight=860",
    "test": "cypress run",
    "test:mobile": "cypress run --config viewportWidth=410,viewportHeight=860",
    "test:cloud": "cypress run --record"
  }
```
---