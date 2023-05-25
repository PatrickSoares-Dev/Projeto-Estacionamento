# Sistema de Estacionamento

Este é um sistema de estacionamento simples desenvolvido em C# para controlar o registro, remoção e listagem de veículos estacionados. Ele permite adicionar veículos, remover veículos e listar os veículos estacionados.

## Funcionalidades

- Adicionar veículo: Permite ao usuário cadastrar um veículo no estacionamento informando a placa.
- Remover veículo: Permite ao usuário remover um veículo do estacionamento informando a placa e a quantidade de horas que o veículo permaneceu estacionado. O sistema calcula o preço total com base no preço inicial e no preço por hora e exibe o valor.
- Listar veículos: Exibe a lista de veículos estacionados no momento.

## Como utilizar

1. Ao iniciar o programa, você será solicitado a digitar o preço inicial do estacionamento.
2. Em seguida, você será solicitado a digitar o preço por hora do estacionamento.
3. Após configurar os preços, o menu será exibido.
4. Digite o número correspondente à opção desejada no menu:
   - 1: Cadastrar veículo
   - 2: Remover veículo
   - 3: Listar veículos
   - 4: Encerrar o programa

## Exemplo de Uso

Seja bem-vindo ao sistema de estacionamento!
Digite o preço inicial: 5
Agora digite o preço por hora: 2

Digite a sua opção:
1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar

Opção: 1

Digite a placa do veículo para estacionar: ABC123

Pressione uma tecla para continuar

Digite a sua opção:
1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar

Opção: 3

Os veículos estacionados são:
ABC123

Pressione uma tecla para continuar

Digite a sua opção:
1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar

Opção: 2

Digite a placa do veículo para remover: ABC123
Digite a quantidade de horas que o veículo permaneceu estacionado: 3

O veículo ABC123 foi removido e o preço total foi de: R$ 11

Pressione uma tecla para continuar

Digite a sua opção:
1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar

Opção: 4

O programa se encerrou


## Considerações Finais

Este projeto de estacionamento é uma aplicação básica que permite o controle simples de veículos estacionados. Ele pode ser utilizado como ponto de partida para o desenvolvimento de um sistema mais completo, adicionando funcionalidades como persistência de dados e melhorias na interface do usuário.
