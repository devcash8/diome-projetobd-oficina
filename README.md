# Oficina Mecânica - Esquema Conceitual

Este projeto é um sistema de gerenciamento de ordens de serviço para uma oficina mecânica. O esquema conceitual foi elaborado para atender às necessidades de controle de clientes, veículos, mecânicos e ordens de serviço.

## Objetivo

Gerenciar o fluxo de ordens de serviço desde a entrada do veículo até a conclusão dos serviços, incluindo a associação de peças e mão de obra.

## Diagrama Conceitual

![OFICINA PROJETO](https://github.com/user-attachments/assets/2209186c-d213-45d7-a221-3e6861a6bdf1)


## Tabelas e Relacionamentos

1. **Cliente**: Armazena informações sobre os clientes.
2. **Veículo**: Associado a um cliente, contém dados do veículo.
3. **Ordem de Serviço (OS)**: Gerencia o status, serviços e valores.
4. **Mecânico**: Contém informações dos profissionais que executam os serviços.
5. **Serviços**: Descreve os serviços disponíveis.
6. **Item_OS**: Relaciona os serviços executados em cada OS.
7. **Mecânico_OS**: Relaciona os mecânicos responsáveis por cada OS.
