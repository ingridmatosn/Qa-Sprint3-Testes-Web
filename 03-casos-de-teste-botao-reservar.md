# Casos de teste — lógica do botão "Reservar"

Aplicação Urban Routes, navegador Google Chrome.

**Pré-condições comuns a todos os casos:**

1. Acessar o Urban Routes
2. Inserir "East 2nd Street, 601" no campo "De"
3. Inserir "1300 1st St" no campo "Para"
4. Escolher o modo "Personal"
5. Escolher "Compartilhamento de carro" como tipo de transporte
6. Clicar no botão "Reservar"

| ID | Caso de teste | Etapas | Resultado esperado | Resultado | Bug |
|---|---|---|---|---|---|
| T-1 | Lógica do botão com todos os campos obrigatórios preenchidos | 1. Adicionar carteira de motorista<br>2. Adicionar um cartão<br>3. Clicar no botão "Reservar" | Texto no botão "Reservar": "A rota será de ... quilômetros e levará ... minutos". Ao clicar, a janela "Carro reservado" é aberta. | APROVADO |  |
| T-2 | Todos os campos preenchidos, exceto a carteira de motorista | 1. Não adicionar carteira de motorista<br>2. Adicionar cartão<br>3. Clicar no botão "Reservar" | O sistema pede para adicionar a carteira de motorista antes de reservar. A janela "Carteira de motorista adicionada" aparece. | REPROVADO | [KAN-18](https://ingridmatos.atlassian.net/browse/KAN-18) |
| T-3 | Todos os campos preenchidos, exceto o método de pagamento | 1. Adicionar carteira de motorista<br>2. Não adicionar cartão<br>3. Clicar no botão "Reservar" | O sistema pede para adicionar o método de pagamento antes de reservar. A janela "Cartão adicionado" aparece. | REPROVADO | [KAN-19](https://ingridmatos.atlassian.net/browse/KAN-19) |
| T-4 | Campos obrigatórios preenchidos e endereços excluídos | 1. Adicionar carteira de motorista<br>2. Adicionar cartão<br>3. Clicar no botão "Reservar"<br>4. Deletar os endereços "De" e "Para" | Não é possível clicar no botão. | REPROVADO | [KAN-20](https://ingridmatos.atlassian.net/browse/KAN-20) |
| T-5 | Campos obrigatórios não preenchidos e endereços excluídos | 1. Não preencher os campos obrigatórios | A janela "Carteira de motorista adicionada" aparece. | BLOQUEADO |  |

> T-5 ficou bloqueado porque depende da correção dos defeitos anteriores para ser executado de forma conclusiva.

