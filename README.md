
#### 🎯 Eline: Code-Challange

Este repositório serve como base para se inspirar e resolver problemas reais que podem servir de base para um projeto para o seu portfólio e muito mais,

#### 🎯 Características:
Os desafios têm como ênfase `Estrutura de Dados` que é um conceito muito essencial nos ambientes de desenvolvimento de software.

Sinta se a vontade para resolve-lo e qualquer dificuldade que tiver é só expor nos grupos que estão dentro da `Comunidade` que estaremos abertos para ajudá-lo. Então, bora chegar no fim da linha deste desafios? 🔥

### 🎯 Desafio 1: **Implementação de um Sistema de Fila de Atendimento**

- **Descrição:** Implemente uma API para gerenciar uma fila de atendimento em um serviço de suporte ao cliente. A fila deve suportar operações de inserção de novos clientes, remoção do cliente que foi atendido, e visualização do próximo cliente a ser atendido.
  
- **Frontend:** Crie uma interface onde os atendentes possam ver a fila de clientes em tempo real, adicionar novos clientes à fila e marcar o cliente atual como atendido.
  
- **Backend:** Implemente as operações de fila usando uma estrutura de dados de fila. Use um banco de dados para persistir a fila entre as sessões.
  
- **Exemplo Prático:** Imagine um sistema de suporte técnico onde os atendentes adicionam clientes à fila. A cada vez que um cliente é atendido, ele é removido da fila, e o próximo é exibido.

### 🎯 Desafio 2: **Sistema de Carrinho de Compras com Estrutura de Dados de Pilha**

- **Descrição:** Desenvolva um sistema de carrinho de compras onde os itens são adicionados em uma pilha. O usuário pode desfazer (remover) o último item adicionado com um clique, utilizando a operação de `pop`.
  
- **Frontend:** Implemente uma interface onde o usuário possa ver os itens no carrinho e um botão "Desfazer" que remove o último item adicionado.
  
- **Backend:** Use uma pilha para armazenar os itens do carrinho e implemente endpoints para adicionar itens, listar os itens no carrinho, e remover o último item adicionado.
  
- **Exemplo Prático:** Um cliente adiciona três produtos ao carrinho (Produto A, Produto B, Produto C). Ao clicar em "Desfazer", o Produto C é removido, deixando apenas os produtos A e B.

### 🎯 Desafio 3: **Sistema de Recomendação de Produtos Baseado em Hashing**

- **Descrição:** Crie um sistema de recomendação de produtos que usa uma tabela hash para associar categorias de produtos aos produtos mais populares. Quando um cliente visualiza uma categoria, os produtos recomendados são exibidos.
  
- **Frontend:** Implemente uma interface onde o usuário possa selecionar uma categoria de produtos e ver os produtos recomendados para essa categoria.
  
- **Backend:** Utilize uma tabela hash para armazenar a relação entre categorias e produtos recomendados. Crie endpoints para buscar os produtos recomendados com base na categoria selecionada.
  
- **Exemplo Prático:** Quando o usuário seleciona a categoria "Eletrônicos", o sistema usa a tabela hash para retornar os produtos mais populares dessa categoria.

###  🎯 Desafio 4: **Aplicativo de Monitoramento de Temperatura com Lista Encadeada**

- **Descrição:** Desenvolva um sistema de monitoramento de temperatura para uma cadeia de suprimentos onde as temperaturas são registradas em uma lista encadeada. O sistema deve permitir a adição de novos registros e a visualização da temperatura mais recente e da mais antiga.
  
- **Frontend:** Crie uma interface que exiba as temperaturas registradas, com opções para adicionar um novo registro e ver as temperaturas mais antiga e mais recente.
  
- **Backend:** Implemente uma lista encadeada para armazenar os registros de temperatura. Use endpoints para adicionar um novo registro e buscar as temperaturas mais antiga e recente.
  
- **Exemplo Prático:** Um caminhão transportando produtos perecíveis registra a temperatura a cada hora. O sistema mostra a temperatura mais recente registrada e a primeira registrada quando a viagem começou.

### 🎯 Desafio 5: **Sistema de Gerenciamento de Tarefas com Prioridades Usando Árvores Binárias**

- **Descrição:** Implemente um sistema de gerenciamento de tarefas onde cada tarefa tem uma prioridade, e as tarefas são armazenadas em uma árvore binária de busca, ordenadas por prioridade.
  
- **Frontend:** Desenvolva uma interface onde o usuário possa adicionar novas tarefas com diferentes prioridades, visualizar todas as tarefas em ordem de prioridade e remover tarefas concluídas.
  
- **Backend:** Use uma árvore binária de busca para armazenar as tarefas com base na prioridade. Implemente endpoints para adicionar tarefas, listar todas as tarefas em ordem de prioridade, e remover tarefas.
  
- **Exemplo Prático:** Um gestor de projetos insere tarefas no sistema com diferentes níveis de prioridade (alta, média, baixa). As tarefas são automaticamente ordenadas e exibidas para o usuário de acordo com a prioridade.


###  🎯 Desafio 6: **Sistema de Agendamento de Consultas Usando Heap (Fila de Prioridade)**

- **Descrição:** Desenvolva um sistema de agendamento de consultas médicas onde as consultas são ordenadas por prioridade (emergência, urgência, rotina). Use uma estrutura de dados de heap (min-heap ou max-heap) para gerenciar as prioridades das consultas.
  
- **Frontend:** Implemente uma interface onde os usuários possam agendar consultas selecionando a prioridade. A interface deve listar as consultas agendadas em ordem de prioridade.
  
- **Backend:** Use um heap para armazenar as consultas de acordo com a prioridade e implemente endpoints para adicionar novas consultas, visualizar a consulta de maior prioridade, e remover consultas quando atendidas.
  
- **Exemplo Prático:** Um paciente agenda uma consulta de emergência e outro uma consulta de rotina. A consulta de emergência deve aparecer primeiro na lista de consultas a serem atendidas.

### 🎯 Desafio 7: **Sistema de Inventário de Produtos com Árvore AVL**

- **Descrição:** Crie um sistema de inventário de produtos para uma loja que utiliza uma árvore AVL (árvore binária de busca balanceada) para manter os produtos ordenados por código ou nome. O sistema deve garantir que a árvore permaneça balanceada após cada inserção ou remoção.
  
- **Frontend:** Desenvolva uma interface onde o usuário possa adicionar, remover e buscar produtos pelo código ou nome. A interface deve listar os produtos em ordem alfabética ou por código.
  
- **Backend:** Implemente uma árvore AVL para gerenciar o inventário, com operações para inserir, remover e buscar produtos de forma eficiente.
  
- **Exemplo Prático:** Quando um novo produto é adicionado ao inventário, ele é automaticamente inserido na posição correta, mantendo a árvore balanceada. Isso permite buscas rápidas pelo código ou nome do produto.

### 🎯 Desafio 8: **Sistema de Registro de Ponto com Filas Circulares**

- **Descrição:** Implemente um sistema de registro de ponto para funcionários que utiliza uma fila circular para armazenar os registros de entrada e saída. A fila circular deve garantir que, quando cheia, o novo registro substitua o mais antigo.
  
- **Frontend:** Crie uma interface onde os funcionários possam registrar sua entrada e saída. A interface também deve permitir que os supervisores vejam os últimos registros de ponto.
  
- **Backend:** Use uma fila circular para armazenar os registros de ponto e implemente endpoints para adicionar novos registros e listar os registros mais recentes.
  
- **Exemplo Prático:** Um funcionário registra sua entrada às 08:00 e, ao longo do dia, faz vários registros de entrada e saída para intervalos. A fila circular mantém apenas os registros mais recentes, descartando os mais antigos quando necessário.
---

##### 🗃️ Vem participar com a gente ? 🔥
##### 🗃️ [Comunidade no WhatsApp](https://chat.whatsapp.com/JpL1PMj6gid7Dcb6L2MXdP) |  [Comunidade no Discord](discord.gg/aD7N9dhb)
