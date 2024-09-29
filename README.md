# 💰 Conversor de Moedas com Python

Desenvolvi essa aplicação para colocar em prática os conceitos que venho estudando e para enriquecer meu portfólio. O projeto consiste em um aplicativo simples para conversão de moedas. 

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **AwesomeAPI**: Utilizada para buscar as cotações das moedas.
- **requests**: Para fazer as requisições à API.
- **json**: Para interpretar as respostas da API.
- **datetime**: Para capturar a data e hora atuais.
- **customtkinter**: Para desenvolver interfaces interativas.
- **matplotlib**: Para gerar gráficos de variação das cotações.

## 🧩 Estrutura e Conceitos

- **Packages, módulos, funções e tratamentos de erros**: Foram aplicados para melhorar a organização do código, garantindo uma estrutura sólida e de fácil manutenção.

## 📝 Funcionalidades do Aplicativo

O projeto é iniciado pelo script `IniciaApp.py`, que carrega a `janelaPrincipal`, onde o usuário pode:

1. Selecionar uma moeda para conversão.
2. Visualizar o nome da moeda, a data e hora atuais.
3. Inserir valores para conversão entre reais e a moeda escolhida.
4. Se um valor inválido for inserido, uma mensagem de erro é exibida.
5. Clicar em um botão para visualizar um gráfico com as últimas 30 cotações da moeda.

## 🗂️ Principais Módulos

- **hora.py**: Responsável pela requisição da data e hora.
- **cotacao.py**: Responsável pela obtenção das cotações das moedas.
- **janelaPrincipal.py**: Layout principal da aplicação.
- **Pasta moedas**: Onde cada moeda está separada em um arquivo individual para facilitar a manutenção do código.

## 🔧 Melhorias Futuras

Ainda há várias possibilidades de aprimoramento, como:

- Adicionar mais cotações.
- Melhorar os tratamentos de erro.
- Otimizar a navegação do app para evitar a abertura de várias janelas.

No entanto, o projeto cumpriu seu objetivo inicial e pretendo continuar evoluindo a aplicação com novas funcionalidades no futuro.
