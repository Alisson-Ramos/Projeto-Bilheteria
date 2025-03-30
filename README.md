# Sistema de Reserva de Poltronas

## Descricao
Este programa em C++ gerencia a reserva de poltronas em um sistema de assentos. Permite que os usuarios visualizem o mapa de ocupacao, reservem assentos e consultem o faturamento total baseado nas reservas realizadas.

## Funcionalidades
- **Reserva de poltronas**: Permite aos usuarios selecionar e reservar poltronas disponiveis.
- **Visualizacao do mapa de ocupacao**: Exibe um mapa com poltronas livres e ocupadas.
- **Consulta de faturamento**: Calcula a receita com base nas poltronas reservadas.
- **DEBUG: Preenchimento aleatorio**: Opcao para simular reservas aleatorias de poltronas.

## Estrutura do Codigo
O programa e composto pelas seguintes funcoes principais:

- `menu_inicial()`: Exibe o menu principal e recebe a escolha do usuario.
- `gerar_matriz_poltronas()`: Inicializa a matriz representando os assentos.
- `exibir_mapa_ocupacao()`: Mostra o estado atual dos assentos.
- `reservar_poltrona(fileira, poltrona)`: Permite reservar uma poltrona especifica.
- `calcular_faturamento()`: Calcula e exibe o total arrecadado.
- `preencher_reservas_aleatorias(n)`: Preenche aleatoriamente `n` poltronas com reservas.

## Como Executar
Para compilar e executar o programa, utilize um compilador C++ como `g++`:

```sh
 g++ reserva_poltronas.cpp -o reserva_poltronas
 ./reserva_poltronas
```

## Autor
- Nome: Alisson Santos, Davi Coelho
- Versao: 0.0.1
- Data: 03/2025

