# IntroIfElse (AnoBissextoRPA)

Este projeto é uma automação desenvolvida em UiPath para verificar se um determinado ano fornecido pelo usuário é bissexto.

## Funcionalidades

- Solicita ao usuário a inserção de um ano através de uma caixa de diálogo.
- Realiza o cálculo lógico para determinar se o ano cumpre os requisitos de um ano bissexto.
- Exibe uma mensagem informando se o ano é bissexto ou não.
- Inclui duas implementações: uma utilizando Sequência (`If/Else`) e outra utilizando `Flowchart` (`Flow Decision`).

## Estrutura do Projeto

- `Main.xaml`: Fluxo principal que utiliza a estrutura de decisão "If" para validar o ano.
- `LeapYear.xaml`: Fluxo alternativo estruturado em Flowchart para a mesma finalidade.
- `project.json`: Arquivo de configuração com as dependências do projeto.

## Requisitos

- UiPath Studio 2025.10.8 ou superior.
- .NET Desktop Runtime compatível com o framework Windows.

## Como usar

1. Abra o projeto no UiPath Studio através do arquivo `project.json`.
2. Execute o fluxo `Main.xaml` ou `LeapYear.xaml`.
3. Insira o ano que deseja verificar na caixa de entrada.
4. Visualize o resultado na caixa de mensagem que aparecerá na tela.
