# Checklist do layout — Urban Routes

Comparação da interface com o design, em dois navegadores e duas resoluções. 37 itens verificados em cada ambiente.

| № | Descrição da revisão | Chrome<br>800x600 | Firefox<br>1920x1080 | Bug |
|---|---|---|---|---|
| **Estado inicial do Urban Routes** | | | | |
| 1 | Exibe o título "Urban.Routes" | APROVADO | APROVADO |  |
| 2 | Exibe a palavra "PLATAFORMA" | REPROVADO | REPROVADO | [KAN-22](https://ingridmatos.atlassian.net/browse/KAN-22) |
| 3 | Exibe os campos "De" e "Para" | APROVADO | APROVADO |  |
| 4 | Na frente do campo "De" exibe um ícone vermelho | APROVADO | APROVADO |  |
| 5 | Na frente do campo "Para" exibe um ícone azul | APROVADO | APROVADO |  |
| 6 | Os campos "De" e "Para" estão vazios | APROVADO | APROVADO |  |
| **Layout modo Personal** | | | | |
| 7 | Exibe a frase "Carsharing ~ $2 Duração 2 min." | REPROVADO | REPROVADO | [KAN-23](https://ingridmatos.atlassian.net/browse/KAN-23) |
| 8 | Ao selecionar "Carsharing" no modo "Personal", exibe o botão "Reservar" | REPROVADO | REPROVADO | [KAN-24](https://ingridmatos.atlassian.net/browse/KAN-24) |
| 9 | Ao selecionar "Carsharing" no modo "Personal", é exibida a ilustração de um carro | APROVADO | APROVADO |  |
| **Layout do mapa** | | | | |
| 10 | Ao digitar os endereços, o mapa exibe a rota com o nome dos endereços "De" e "Para" | REPROVADO | REPROVADO | [KAN-25](https://ingridmatos.atlassian.net/browse/KAN-25) |
| 11 | Ao selecionar "Casual" no modo "Personal", são exibidos carros disponíveis no mapa | REPROVADO | REPROVADO | [KAN-26](https://ingridmatos.atlassian.net/browse/KAN-26) |
| 12 | Ao clicar em um carro disponível no mapa, é exibido o nome "BMW" | BLOQUEADO | BLOQUEADO | [KAN-26](https://ingridmatos.atlassian.net/browse/KAN-26) |
| 13 | O mapa é exibido no modo "Mapa" por padrão | APROVADO | APROVADO |  |
| 14 | O mapa é exibido com os controles de zoom (+/-) visíveis | APROVADO | APROVADO |  |
| 15 | No modo "Satélite", o mapa exibe a visualização de satélite corretamente | APROVADO | APROVADO |  |
| 16 | No modo "Satélite", os marcadores "De" e "Para" continuam visíveis | APROVADO | APROVADO |  |
| 17 | O ícone do "Street View" é exibido no mapa | APROVADO | APROVADO |  |
| 18 | No modo "Relevo", o mapa exibe a camada de elevação e topografia | APROVADO | APROVADO |  |
| **Layout tarifa Casual** | | | | |
| 19 | Ao selecionar a tarifa "Casual", exibe a marca do carro "BMW 750" | APROVADO | APROVADO |  |
| 20 | Ao selecionar o modo "Casual", exibe a frase "Apenas negócios, nada extra" | APROVADO | APROVADO |  |
| 21 | Exibe o ícone de pedestre seguido do texto "4 min. · 15 minutos de espera gratuita" no card do carro | REPROVADO | REPROVADO | [KAN-27](https://ingridmatos.atlassian.net/browse/KAN-27) |
| 22 | A ilustração do "BMW 750" é exibida com os detalhes de acabamento (reflexos, sombreamento, rodas, lataria) | REPROVADO | REPROVADO | [KAN-28](https://ingridmatos.atlassian.net/browse/KAN-28) |
| 23 | Exibe "câmera de painel · carregador de telefone" no card do carro | REPROVADO | REPROVADO | [KAN-29](https://ingridmatos.atlassian.net/browse/KAN-29) |
| **Layout carteira de motorista** | | | | |
| 24 | Ao adicionar a carteira de motorista, o contorno do campo fica verde e exibe um check | REPROVADO | REPROVADO | [KAN-30](https://ingridmatos.atlassian.net/browse/KAN-30) |
| 25 | Antes de adicionar, o campo "Carteira de motorista" é exibido com contorno cinza | APROVADO | APROVADO |  |
| 26 | Os campos "Carteira de motorista" e "Método de pagamento" têm o mesmo padrão de bordas e espaçamento | APROVADO | APROVADO |  |
| **Layout pop-up carro reservado** | | | | |
| 27 | Ao clicar em "Reservar", exibe "O carro foi reservado" | REPROVADO | REPROVADO | [KAN-31](https://ingridmatos.atlassian.net/browse/KAN-31) |
| 28 | Exibe a mensagem de "Espera gratuita" | APROVADO | APROVADO |  |
| 29 | Exibe a contagem regressiva para a chegada do carro | APROVADO | APROVADO |  |
| 30 | Exibe o modelo e a placa do carro | REPROVADO | REPROVADO | [KAN-32](https://ingridmatos.atlassian.net/browse/KAN-32) |
| 31 | Exibe o endereço do carro | APROVADO | APROVADO |  |
| 32 | Exibe a opção "Cancelar" | APROVADO | APROVADO |  |
| 33 | Exibe o ícone "i" com a frase "Saber mais sobre a viagem" e o preço da viagem abaixo | REPROVADO | REPROVADO | [KAN-33](https://ingridmatos.atlassian.net/browse/KAN-33) |
| **Layout cancelamento** | | | | |
| 34 | Ao clicar em "Cancelar", exibe o pop-up "Tem certeza que deseja cancelar a corrida?" com "Sim" e "Não" | BLOQUEADO | BLOQUEADO | [KAN-21](https://ingridmatos.atlassian.net/browse/KAN-21) |
| 35 | O botão "Não" é exibido na cor cinza | BLOQUEADO | BLOQUEADO | [KAN-21](https://ingridmatos.atlassian.net/browse/KAN-21) |
| 36 | O botão "Sim" é exibido na cor azul | BLOQUEADO | BLOQUEADO | [KAN-21](https://ingridmatos.atlassian.net/browse/KAN-21) |
| 37 | Exibe o pop-up "A corrida foi cancelada" com o botão "Entendido" na cor azul | BLOQUEADO | BLOQUEADO | [KAN-21](https://ingridmatos.atlassian.net/browse/KAN-21) |

> Os quatro itens de cancelamento ficaram bloqueados pelo mesmo defeito (KAN-21): sem o cancelamento funcionando, não há como verificar o layout das telas seguintes.

