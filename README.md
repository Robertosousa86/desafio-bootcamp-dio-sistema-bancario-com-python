# Desafio Bootcamp DIO - Sistema Bancário com Python

Desafio proposto durante o Bootcamp Python AI Backend Developer.
O Desafio consiste em criar um sistema bancário desenvolvido em Python com as seguintes funcionalidades:

## Operação de depósito
- Deve ser possível depositar valores positivos para a minha conta bancária. A v1 do projeto trabalha apenas com 1 usuário, dessa forma não precisamos nos preocupar em identificar qual é o número da agência e conta bancária. Todos os depósitos devem ser armazenados em uma variável e exibidos  na operação de extrato.

## Operação de saque
- O sistema deve pemitir a realização de três saques diários com limite máximo de R$ 500,00 por saque. Caso o usuário não tenha saldo em conta, o sistema deve exibir uma mensagem informando que não será possível sacar o dinheiro por falta  de saldo. Todos os saques devem ser armazenado e exibidos em um variável na operação extrato.

## Operação de extrato
- Essa operação deve listar todos os depósitos e saques realizados na conta. No fim da listagem deve ser exibibo o saldo atual da conta. Os valores devem ser exibidos utilizando o formato R$ xxx.xx, exemplo: 1500.45 = R$ 1500.45