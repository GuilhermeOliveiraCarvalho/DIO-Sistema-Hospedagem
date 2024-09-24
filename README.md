# Sistema de Hospedagem de Hotel em C#

Este repositório contém a solução para o **Desafio de Projeto** proposto no bootcamp **Randstad - Backend com .NET**, oferecido pela [Digital Innovation One (DIO)](https://www.dio.me/). O desafio tem como tema **Construindo um Sistema de Hospedagem de um Hotel utilizando C#**.

## 📜 Proposta do Desafio

O objetivo deste projeto é criar um sistema de hospedagem para um hotel, permitindo realizar reservas de suítes e calcular o valor das diárias, de acordo com algumas regras de negócio definidas. O projeto utiliza conceitos de **Orientação a Objetos** e a linguagem **C#** para desenvolver a solução.

## 📝 Regras do Desafio

1. **Classes Envolvidas**:
   - **Pessoa**: Representa o hóspede.
   - **Suite**: Representa as suítes disponíveis para hospedagem.
   - **Reserva**: Representa a reserva que relaciona hóspedes a uma suíte.

2. **Funcionalidades**:
   - **Cadastro de hóspedes**: O sistema permite cadastrar um número de hóspedes para a reserva, respeitando a capacidade máxima da suíte.
   - **Cadastro de suíte**: A suíte deve ter um tipo, capacidade máxima e valor da diária.
   - **Cálculo do valor da diária**: O sistema calcula o valor total da hospedagem, multiplicando os dias reservados pelo valor da diária. Caso o número de dias seja maior ou igual a 10, é concedido um desconto de **10%** no valor total.
   
3. **Validações**:
   - Não é possível realizar uma reserva em uma suíte que tenha capacidade menor do que o número de hóspedes.
   - O valor da diária é corretamente calculado e, se aplicável, o desconto é concedido para reservas longas (10 dias ou mais).

## 🚀 Funcionalidades Implementadas

- Cadastro de hóspedes e validação da capacidade da suíte.
- Cadastro de suíte com tipo, capacidade e valor da diária.
- Cálculo de diárias com desconto aplicado automaticamente para reservas de 10 dias ou mais.
- Exibição de mensagens informando se o desconto foi aplicado e o valor final da reserva.


