## Implementação do Sistema de Estacionamento

### Visão Geral

A implementação do sistema de estacionamento foi dividida em várias etapas, abordando desde a estrutura básica do projeto até a criação das funcionalidades necessárias para gerenciar os veículos. Este sistema permite adicionar, remover e listar veículos, além de calcular o valor total de estacionamento com base no tempo que o veículo permaneceu estacionado.

### Estrutura do Projeto

O projeto foi estruturado para manter uma separação clara entre as funcionalidades, utilizando classes para representar o estacionamento e suas operações. A classe principal é responsável por armazenar as informações necessárias, como o preço inicial e o preço por hora, bem como a lista de veículos atualmente estacionados.

### Funcionalidades Implementadas

1. **Adicionar Veículo**:
   - O sistema permite ao usuário adicionar um veículo ao estacionamento. Isso é feito solicitando ao usuário a placa do veículo, que é então armazenada em uma lista.

2. **Remover Veículo**:
   - Para remover um veículo, o sistema solicita a placa do veículo e verifica se ele está presente no estacionamento. Caso esteja, o sistema também solicita o tempo que o veículo ficou estacionado para calcular o valor total devido. Após o cálculo, o veículo é removido da lista e o usuário é informado do valor total.

3. **Listar Veículos**:
   - A funcionalidade de listar veículos permite ao usuário visualizar todos os veículos atualmente estacionados. Caso não haja veículos, uma mensagem informando que o estacionamento está vazio é exibida.

### Desafios e Soluções

Durante a implementação, um dos desafios foi garantir que o cálculo do valor total de estacionamento estivesse correto, especialmente considerando diferentes cenários de tempo de permanência. Além disso, foi necessário tratar casos onde o veículo não estava presente na lista ao tentar removê-lo, para evitar erros e garantir uma experiência de usuário robusta.

### Conclusão

A implementação do sistema de estacionamento foi um exercício prático que envolveu conceitos importantes de programação, como manipulação de listas, controle de fluxo com condicionais e loops, e interação com o usuário através do console. Esse projeto forneceu uma base sólida para o desenvolvimento de sistemas mais complexos no futuro.
