Desenvolvi essa aplicação para colocar em prática os conceitos que venho estudando e para enriquecer meu portfólio. O projeto consiste em um aplicativo simples para conversão de moedas.
Para isso, utilizei a API de cotações da AwesomeAPI, juntamente com as bibliotecas requests (para a requisição dos dados) e json (para interpretar as respostas). Usei também datetime para capturar a data e hora atuais, customtkinter para desenvolver as interfaces interativas, e matplotlib para gerar gráficos de variação das cotações.
Conceitos como packages, módulos, funções e tratamentos de erros foram aplicados para melhorar a organização do código, garantindo uma estrutura sólida e de fácil manutenção. O projeto é iniciado pelo script IniciaApp, que carrega a janelaPrincipal , onde o usuário pode selecionar uma moeda para conversão. A partir dessa seleção, uma nova janela exibe o nome da moeda, a data e hora atuais, e campos para conversão de valores entre reais e a moeda escolhida. Se um valor inválido for inserido, uma mensagem de erro é exibida. Além disso, há um botão que, ao ser clicado, mostra um gráfico com as últimas 30 cotações da moeda.
Os principais módulos são:
hora.py: responsável pela requisição da data e hora.
cotacao.py: responsável pela obtenção das cotações das moedas.
janelaPrincipal.py: layout principal.
Pasta moedas: onde cada moeda está separada em um arquivo individual para facilitar a manutenção do código.
OBS:Ainda há várias possibilidades de aprimoramento, como adicionar mais cotações, melhorar os tratamentos de erro e otimizar a navegação do app para evitar a abertura de várias janelas. No entanto, o projeto cumpriu seu objetivo inicial, e pretendo continuar evoluindo a aplicação com novas funcionalidades no futuro.

