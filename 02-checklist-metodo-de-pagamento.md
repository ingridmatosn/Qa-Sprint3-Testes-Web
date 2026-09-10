# Checklist — "Método de pagamento" e "Adicionar cartão"

Urban Routes, Google Chrome em 800 x 600. 34 verificações, 18 aprovadas e 16 reprovadas.

| № | Descrição da revisão | Status | Bug |
|---|---|---|---|
| **Método de pagamento** | | | |
| 1 | Clicar no campo "Adicionar cartão" abre o formulário | APROVADO |  |
| 2 | Por padrão, o campo está vazio | APROVADO |  |
| 3 | Botão "Adicionar" salva os dados | APROVADO |  |
| 4 | Quando um cartão é adicionado, a interface mostra os últimos 4 dígitos do número | REPROVADO | [KAN-1](https://ingridmatos.atlassian.net/browse/KAN-1) |
| 5 | Clicar em "Cancelar" fecha o formulário | APROVADO |  |
| 6 | Clicar no "X" fecha a janela sem salvar os dados | APROVADO |  |
| **Campo Número** | | | |
| 7 | Formato nnnn nnnn nnnn | APROVADO |  |
| 8 | Somente números, 12 símbolos | APROVADO |  |
| 9 | Restrições para nnnn: de 0000 | REPROVADO | [KAN-2](https://ingridmatos.atlassian.net/browse/KAN-2) |
| 10 | Restrições para nnnn: de 9999 | REPROVADO | [KAN-3](https://ingridmatos.atlassian.net/browse/KAN-3) |
| 11 | Os espaços são inseridos automaticamente quando o usuário insere o número e clica fora do campo | REPROVADO | [KAN-4](https://ingridmatos.atlassian.net/browse/KAN-4) |
| 12 | É impossível inserir mais de 12 símbolos | REPROVADO | [KAN-5](https://ingridmatos.atlassian.net/browse/KAN-5) |
| 13 | O sistema não permite inserir letras (latinas e não latinas) | REPROVADO | [KAN-7](https://ingridmatos.atlassian.net/browse/KAN-7) |
| 14 | O sistema não permite alfanumérico | REPROVADO | [KAN-9](https://ingridmatos.atlassian.net/browse/KAN-9) |
| 15 | O sistema não permite usar hífen como separador | REPROVADO | [KAN-8](https://ingridmatos.atlassian.net/browse/KAN-8) |
| **Campo Código** | | | |
| 16 | Formato nn | APROVADO |  |
| 17 | Somente números, 2 símbolos | APROVADO |  |
| 18 | Não é possível digitar 00 | REPROVADO | [KAN-10](https://ingridmatos.atlassian.net/browse/KAN-10) |
| 19 | É possível digitar 01 | APROVADO |  |
| 20 | É possível digitar 02 | APROVADO |  |
| 21 | É possível digitar 03 | APROVADO |  |
| 22 | É possível digitar 98 | APROVADO |  |
| 23 | É possível digitar 99 | APROVADO |  |
| 24 | Não é possível digitar 100 | REPROVADO | [KAN-11](https://ingridmatos.atlassian.net/browse/KAN-11) |
| 25 | Se forem inseridos menos de 2 símbolos, o botão "Adicionar" permanece inativo | APROVADO |  |
| 26 | O sistema não permite inserir letras (latinas e não latinas) | REPROVADO | [KAN-12](https://ingridmatos.atlassian.net/browse/KAN-12) |
| 27 | O sistema não permite alfanumérico | REPROVADO | [KAN-13](https://ingridmatos.atlassian.net/browse/KAN-13) |
| 28 | O sistema não permite caracteres especiais | REPROVADO | [KAN-14](https://ingridmatos.atlassian.net/browse/KAN-14) |
| 29 | Botão "Adicionar" fica inativo com o campo vazio | APROVADO |  |
| **Campos Número e Código combinados** | | | |
| 30 | Valores válidos nos dois campos habilitam o botão "Adicionar" | APROVADO |  |
| 31 | Valores inválidos nos dois campos não habilitam o botão | REPROVADO | [KAN-15](https://ingridmatos.atlassian.net/browse/KAN-15) |
| 32 | Número válido e código inválido não habilitam o botão | REPROVADO | [KAN-16](https://ingridmatos.atlassian.net/browse/KAN-16) |
| 33 | Número inválido e código válido não habilitam o botão | REPROVADO | [KAN-17](https://ingridmatos.atlassian.net/browse/KAN-17) |
| 34 | Campos "Número" e "Código" vazios não habilitam o botão | APROVADO |  |

> Padrão observado: as verificações de formato passam, mas quase toda a validação de limite e de tipo falha. O formulário aceita entrada que deveria recusar.

