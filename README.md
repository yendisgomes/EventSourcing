# EventSourcing

![image](https://github.com/user-attachments/assets/1adf6d97-7ec0-44a8-bab0-de0961a5b282)

# Event Sourcing - Bank Account

Este projeto implementa um exemplo de Event Sourcing para uma aplicação de gerenciamento de contas bancárias.

## Objetivo

Demonstrar como usar Event Sourcing para gerenciar o estado de uma conta bancária, armazenando eventos que representam mudanças no estado da conta.

## Estrutura do Projeto

- **Eventos**: Representam ações específicas realizadas na conta bancária.
- **Agregado de Domínio (`BankAccount`)**: Contém a lógica de negócios para manipular a conta bancária e aplicar eventos.
- **Reprodução de Eventos (`ReplayEvents`)**: Permite reconstruir o estado da conta a partir de eventos armazenados.

## Como Executar

1. Clone este repositório:
   ```sh
   git clone https://github.com/yendisgomes/EventSourcing.git


1. Navegue até o diretório do projeto:
   ```sh
   cd EventSourcing


3. Execute o programa:
   ```sh
   dotnet run


