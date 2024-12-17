# * Projeto Tela de Login*

Este projeto é composto por três telas básicas de um fluxo de interface de usuário desenvolvido com *HTML* e *CSS. A proposta é demonstrar um processo simples e funcional de navegação entre as telas, simulando um **fluxo de login*.

## *Estrutura do Projeto*

A organização dos arquivos está da seguinte forma:

plaintext
projeto/
│
├── index             # Tela Inicial
├── Tela_02           # Tela de Login (e-mail e senha)
├── Tela_03           # Tela de Boas-Vindas
└── README.md         # Documentação do projeto

## *Descrição Geral*

O projeto apresenta as seguintes telas:

1. *Tela Inicial (index.html)*:  
   - Uma imagem de fundo (fornecida no arquivo tela1.png) ocupa toda a tela.  
   - Um botão invisível, posicionado sobre a imagem, permite a navegação para a *Tela de Login*.

2. *Tela de Login (Tela_02)*:  
   - Formulário simples contendo campos para *e-mail* e *senha*.  
   - Um botão "Entrar" redireciona o usuário para a *Tela de Boas-Vindas*.  
   - Link adicional para um possível cadastro: *"Registre-se aqui"*.

3. *Tela de Boas-Vindas (Tela_03)*:  
   - Mensagem centralizada: *"Seja bem-vindo(a)!"*.  
   - Um botão "Voltar ao Início" leva o usuário de volta para a *Tela Inicial*.

---

## *Fluxo de Navegação*

O fluxo entre as telas funciona da seguinte forma:

1. O usuário inicia na *Tela Inicial*.  
   - Clicando no botão invisível, ele é levado para a *Tela de Login*.

2. Na *Tela de Login*, o usuário:  
   - Preenche os campos de e-mail e senha (simulados, sem validação).  
   - Ao clicar no botão "Entrar", ele é redirecionado para a *Tela de Boas-Vindas*.

3. Na *Tela de Boas-Vindas*, o usuário visualiza uma mensagem de boas-vindas.  
   - Clicando em "Voltar ao Início", ele retorna para a *Tela Inicial*.
