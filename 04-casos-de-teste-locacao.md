# Casos de teste — lógica da locação

Aplicação Urban Routes, Google Chrome em 800 x 600.

**Pré-condições comuns a todos os casos:**

1. Acessar o Urban Routes
2. Inserir "East 2nd Street, 601" no campo "De"
3. Inserir "1300 1st St" no campo "Para"
4. Escolher o modo "Personal"
5. Escolher "Compartilhamento de carro" como tipo de transporte
6. Clicar no botão "Reservar"

| ID | Caso de teste | Etapas | Resultado esperado | Resultado | Bug |
|---|---|---|---|---|---|
| T-1 | Lógica da reserva com os campos "De" e "Para" preenchidos | 1. Adicionar carteira de motorista<br>2. Adicionar um cartão<br>3. Clicar no botão "Reservar" | Uma janela com o título "O carro foi reservado" surge no centro da tela, com o ícone e o endereço do carro, o custo da corrida e o cronômetro do tempo de espera gratuito. | APROVADO |  |
| T-2 | Cancelamento da reserva | 1. Adicionar carteira de motorista<br>2. Adicionar um cartão<br>3. Clicar no botão "Reservar"<br>4. Clicar em "Cancelar"<br>5. Clicar na opção "Sim" | A corrida é cancelada. | REPROVADO | [KAN-21](https://ingridmatos.atlassian.net/browse/KAN-21) |
| T-3 | Não cancelamento da reserva | — | — | BLOQUEADO | [KAN-21](https://ingridmatos.atlassian.net/browse/KAN-21) |

> T-3 ficou bloqueado pelo mesmo defeito do T-2: sem o cancelamento funcionando, não é possível validar o cenário de não cancelamento. Essa é a falha crítica citada na conclusão do sprint.

