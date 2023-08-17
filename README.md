# Sistema de Aluguel de Carros Simplificado

## Definição

O **Sistema de Aluguel de Carros Simplificado** é um sistema projetado para permitir que os clientes aluguem veículos por um período determinado. Ele visa simplificar o processo de aluguel, focalizando nas entidades principais: Cliente, Carro e Reserva.

## Entidades e Relacionamentos

### 1. Entidades

- **Cliente:** Representa um indivíduo que deseja alugar um carro. Armazena informações como nome, CPF, idade, CNH, endereço e número de contato.

- **Carro:** Representa um veículo disponível para aluguel. Mantém detalhes como marca, modelo, ano, placa e disponibilidade.

- **Reserva:** Refere-se a uma reserva específica feita por um cliente para alugar um carro. Contém informações como data de início, data de término, cliente associado e carro reservado.

### 2. Relacionamentos

- Um cliente pode fazer várias reservas, mas cada reserva está associada a apenas um cliente por vez.

- Um carro pode estar associado a várias reservas, mas cada reserva envolve apenas um carro.

- Cada reserva está vinculada a um carro específico que o cliente deseja alugar.

## Regra de Negócio

1. **Cadastro de Clientes e Carros:** O sistema permite o cadastro de novos clientes e carros, incluindo suas informações relevantes.

2. **Reservas:** Os clientes podem fazer reservas selecionando o carro desejado e as datas de início e término.

3. **Check-in e Check-out:** No momento da retirada, o sistema registra a condição do carro. Na devolução, verifica a quilometragem e o estado do veículo.

## Resumo

O **Sistema de Aluguel de Carros Simplificado** proporciona uma abordagem direta para gerenciar o processo de aluguel de carros. Através das entidades Cliente, Carro e Reserva, e dos relacionamentos entre elas, o sistema oferece uma experiência simples e eficiente para clientes que desejam alugar um veículo por um período determinado.

## Desenvolvedores

- Nelson Meduna GRR20223402
- Rafael Hideki Nakamura GRR2022
- William Yip GRR20185480
