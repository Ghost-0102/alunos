# Cadastro de Alunos - Linguagem Perl
Pedro Guilherme Cardoso Silva Lima

<hr>

## ➡️ Estrutura 
-> Organização: Funções 

-> Interação: O loop de controle

-> Execução: Lógica Sequencial e Condicional


## 📌 Avaliação da linguagem

### Sistema de tipos: Dinâmico
### Forma de execução: Interpretada


## 📌 Justificativa das Escolhas de Fluxo de Controle

### - O Loop while (1)

Justificativa: é permitir que o usuário realize múltiplas operações, sem ter que reiniciar o script a cada vez.
<img width="1172" height="624" alt="image" src="https://github.com/user-attachments/assets/6764e56f-09d0-4c93-a77a-42a4b82b5afc" />
<img width="1051" height="143" alt="image" src="https://github.com/user-attachments/assets/1bdf7e40-04d6-46d4-9da5-3af17cfac9b8" />

### - Estrutura condicional

Justificativa: Após o usuário digitar uma opção no menu, o programa precisa direcionar o fluxo de execução para a função correta.
<img width="1002" height="353" alt="image" src="https://github.com/user-attachments/assets/fffa131e-5390-4fbf-b41d-224b7e89eee1" />

## 📌 Modularização

### - A função menu_principal 

Funciona como um sumário do que o programa faz, sem se preocupar com os detalhes de como cada ação é executada.

### -  A função limpar_tela()

Ela é chamada no início do loop do menu e também antes de iniciar um novo cadastro. Se precisássemos mudar a forma como a tela é limpa no futuro, só precisaríamos alterar em um único lugar.

