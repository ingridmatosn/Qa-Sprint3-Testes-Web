# QA Sprint 3 — Testes Web Cross-Browser (Urban Routes)

Testes de layout, de formulário de pagamento e de regras de negócio da aplicação **Urban Routes**, executados em dois navegadores e duas resoluções, no bootcamp de Analista de QA da TripleTen.

## Documentação

- **[Checklist do layout](01-checklist-layout.md)** — comparação da interface com o design, em Chrome 800x600 e Firefox 1920x1080.
- **[Checklist "Método de pagamento"](02-checklist-metodo-de-pagamento.md)** — validações do formulário de cartão.
- **[Casos de teste do botão "Reservar"](03-casos-de-teste-botao-reservar.md)** — lógica de habilitação do botão.
- **[Casos de teste de locação](04-casos-de-teste-locacao.md)** — regras da reserva.
- A planilha e o documento originais também estão no repositório.

## Objetivo

Verificar se a interface corresponde ao design em diferentes navegadores e resoluções, se as validações do formulário de pagamento funcionam, e se as regras de habilitação da reserva se comportam conforme a especificação.

## Ambientes testados

| Navegador | Resolução |
|---|---|
| Google Chrome | 800 x 600 |
| Mozilla Firefox | 1920 x 1080 |

## Resultados

- **104 verificações registradas**: 60 aprovadas e 44 reprovadas.
- **32 defeitos reportados** no Jira (KAN-1 a KAN-33).
- Distribuição: 13 defeitos no checklist de layout, 16 no formulário de pagamento, 3 no botão "Reservar" e 1 na locação.

### Conclusão do sprint

> O Urban Routes apresenta uma proposta de uso simples e intuitiva, com um fluxo de reserva claro. No entanto, ao longo dos testes encontrei diversas inconsistências visuais em relação ao design (Figma), além de falhas de validação em campos importantes do formulário de pagamento e uma falha crítica que impede o cancelamento de corridas, o que compromete a confiança na experiência como um todo.
>
> **Considerando a quantidade e a gravidade dos bugs encontrados, não recomendo o lançamento do produto no estado atual.** Antes de disponibilizá-lo aos usuários, é fundamental corrigir os bugs críticos e de alta severidade e realizar uma nova rodada de testes de regressão.

## Ferramentas

Jira · Google Chrome e Mozilla Firefox · DevTools (emulação de resolução) · Figma (referência de design) · Google Sheets / Excel

## Estrutura do repositório

- `01-checklist-layout.md` — layout em 2 navegadores e 2 resoluções
- `02-checklist-metodo-de-pagamento.md` — validações do formulário de cartão
- `03-casos-de-teste-botao-reservar.md` — lógica do botão "Reservar"
- `04-casos-de-teste-locacao.md` — regras da locação
- Planilha e documento originais
- `README.md`

## O que aprendi

- O mesmo build se comporta de formas diferentes em navegadores e resoluções diferentes. Vários defeitos de layout só apareceram em 800x600, que é a resolução que ninguém testa por padrão.
- Comparar tela com Figma exige critério: nem toda diferença é bug, mas espaçamento, cor e texto fora do especificado são, e precisam ser reportados com o print lado a lado.
- Recomendar ou não o lançamento faz parte do trabalho de QA. Reunir a contagem e a severidade dos defeitos numa conclusão objetiva é o que transforma a execução em informação para quem decide.

## Melhorias a fazer

- Anexar os prints comparando tela e design em cada defeito de layout.
- Padronizar a numeração dos defeitos (o ID KAN-6 não aparece na sequência).
- Estender o checklist de layout ao Firefox em 800x600, hoje testado apenas em 1920x1080.

---

**Ingrid Matos** — Analista de QA Júnior
[LinkedIn](https://www.linkedin.com/in/ingridmatosn/) · [Portfólio de QA](https://github.com/ingridmatosn/QA-Portfolio-Main)
