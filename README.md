# Board

**Board** é um aplicativo simples de gerenciamento de tarefas baseado em um quadro Kanban. Ele permite aos usuários criar, editar, mover e excluir tarefas, facilitando o gerenciamento de projetos pessoais ou profissionais.

## Funcionalidades

- **Criação de tarefas**: Permite que os usuários criem novas tarefas com título e descrição.
- **Edição de tarefas**: Tarefas existentes podem ser editadas, alterando seu título e descrição.
- **Movimento de tarefas**: Tarefas podem ser movidas entre diferentes colunas (ex.: "Pendente", "Em andamento", "Concluído").
- **Deleção de tarefas**: O usuário pode excluir tarefas que não são mais necessárias.
- **Persistência de dados**: Armazena as tarefas, garantindo que as informações sejam mantidas entre sessões (por exemplo, usando banco de dados ou arquivos locais).
- **Interface gráfica simples**: Interface de usuário básica para interação com as tarefas.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal.
- **JavaFX / Swing**: Biblioteca para construção da interface gráfica.
- **SQLite / MySQL / H2 (opcional)**: Para persistência de dados (se aplicável).
- **Maven / Gradle**: Ferramentas para gerenciamento de dependências e build.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

- **src/**: Contém os arquivos de código-fonte.
  - **model/**: Contém as classes que representam os objetos principais do sistema (como Tarefa e Coluna).
  - **controller/**: Contém as classes responsáveis pela lógica de controle da aplicação (como movimentação de tarefas).
  - **view/**: Contém os arquivos responsáveis pela interface gráfica.
  - **utils/**: Utilitários e funções auxiliares.
