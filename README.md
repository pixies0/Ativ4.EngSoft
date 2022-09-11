# Ativ4.EngSoft

Repositório para o desenvolvimento da prática dos requisitos

## Exercícios Propostos:

1. Definir 2 requisitos funcionais de um sistema qualquer.
2. Descrever o Caso de Uso Expandido para os 2 requisitos.
3. Descrever User Storie para os 2 requisitos.
4. Fazer o protótipo da tela para cada um dos requisitos.

Para desenvolver as questões anteriormente abordadas, consideramos como referência um sistema de agenda comercial que neste caso será uma barbearia.

### Definindo os requisitos:

Os requisitos funcionais, descritos para esse sistema, são: **Agendar um horário e Visualizar horários do dia**.

### Descrevendo os casos de uso expandido dos requisitos:

**Requisito 1:**

    • Nome: Agendar um horário.
    • Número: 01.
    • Atores: Cliente, Funcionário.
    • Finalidade: Marcar uma hora de visitação do cliente.
    • Visão geral: Este caso de uso tem como função efetuar  um determinado agendamento no sistema.
    • Tipo: Essencial

**Ações do atores:**

1. Cliente faz contato ou vai até a instalação e deseja marcar uma hora para cuidar de sua aparência.
2. Cliente informa seu nome, horário de sua preferência, e o tipo de abordagem.
3. O funcionário cataloga as informações recem coletadas do cliente através do formulário em questão.

**Respostas do sistema:**

1. Exibe a tela do formulário para agendar clientes.
2. Sistema insere os dados em um calendário, marcando assim o agendamento em ordem cronológica .
3. Sistema grava informações.

**Tratamento de Exceções:**

1.1. Funcionário verifica que o periódo que o cliente deseja já está preenchido.

1.2. Sistema sugere alguns horários vagos.

2.1. Funcionário informa que não há disponibilidade naquela Data.

2.2. Sistema exibe horários disponiveis para o dia utíl seguinte.
