# DESAFIO-QA-BEEDOO-2026

## Aplicação analisada
https://creative-sherbet-a51eac.netlify.app/

---

# Objetivo da aplicação
A aplicação tem como objetivo permitir o cadastro e a visualização de cursos.  
O usuário pode preencher um formulário com informações do curso e realizar o cadastro. Após o cadastro, os cursos ficam disponíveis em uma listagem dentro da aplicação.

Dessa forma, o sistema funciona como um gerenciador simples de cursos, permitindo registrar, visualizar e gerenciar cursos cadastrados.

---

# Principais fluxos da aplicação

Durante a exploração da aplicação, foram identificados os seguintes fluxos principais:

### 1. Cadastro de curso
O usuário preenche os campos do formulário e realiza o cadastro de um novo curso.

### 2. Listagem de cursos
A aplicação exibe todos os cursos cadastrados para visualização.

### 3. Navegação entre páginas
O usuário pode navegar entre a página de cadastro e a página de listagem de cursos.

---

# Pontos críticos para teste

Durante a análise da aplicação, foram identificados alguns pontos considerados críticos para testes:

- Validação dos campos do formulário;
- Cadastro correto dos cursos;
- Exibição correta dos cursos na listagem;
- Tratamento de cenários negativos (campos vazios ou dados inválidos);
- Funcionamento da exclusão de cursos;
- Experiência do usuário durante o processo de cadastro.

---

# Estratégia de testes

Como a aplicação não possui documentação funcional disponível, foi realizada uma **análise exploratória** para compreender os fluxos principais do sistema.

A partir dessa análise, foram definidos cenários de teste considerando:

- Cenários positivos;
- Cenários negativos;
- Validações de campos;
- Comportamentos inesperados;
- Possíveis falhas de segurança.

---

# Casos de teste

Os cenários e casos de teste criados para a aplicação estão documentados na planilha abaixo:

https://docs.google.com/spreadsheets/d/1z-e4mXtVGOTId9fYEDOv6RPDnt3vQgD2fcGF6-cMKm8/edit?gid=0#gid=0

---

# Bugs encontrados

Durante a execução dos testes foram identificados alguns problemas no sistema, como:

- Falta de validação de campos obrigatórios;
- Permissão de cadastro com dados inválidos;
- Falha na exclusão de cursos;
- Interpretação de código HTML inserido pelo usuário;
- Execução de script no campo de cadastro (possível vulnerabilidade XSS);
- Erro 404 ao atualizar a página durante o preenchimento do formulário.

Os detalhes completos dos bugs estão documentados na planilha:

https://docs.google.com/spreadsheets/d/1z-e4mXtVGOTId9fYEDOv6RPDnt3vQgD2fcGF6-cMKm8/edit?usp=sharing

---

# Evidências da execução dos testes

As evidências da execução dos testes (prints e gravações de tela) estão disponíveis no link abaixo:

https://drive.google.com/drive/folders/1vAjvAruuljtJGqdX1gxrzQka_Hb6qjuk?usp=sharing

---

# Ferramentas utilizadas

- Google Sheets (documentação de casos de teste e bugs)
- Google Drive (armazenamento das evidências)
- GitHub (versionamento e entrega do desafio)
- Navegador Google Chrome
- ShareX (captura de tela e gravação)
