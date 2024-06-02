# Aplicação React de Gerenciamento de Projetos e Tarefas

Projeto criado com as bibliotecas React JS e Material UI.

## Passo-a-passo para execução

1. Clonar o repositório
2. Localmente, entrar na pasta do projeto e instalar as dependências:
   `
   npm install
   `
3. Executar a aplicação:
   `
   npm start
   `
   ##
ALTERAÇÕES REALIZADAS NO CÓDIGO:

ListarTarefa.jsx
Adição dos estados 'historicoTarefas' e 'mostrarHistorico' para controlar o histórico de tarefas.
Adição do botão "Mostrar Histórico" para alternar a exibição do histórico de tarefas.
Criação de um segundo bloco de tabela para exibir o histórico de tarefas quando 'mostrarHistorico' for verdadeiro.
Modificação da lógica de exclusão para mover tarefas concluídas para o histórico.
