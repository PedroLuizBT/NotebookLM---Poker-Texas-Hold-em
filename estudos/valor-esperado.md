# 🃏 Estudo de Valor Esperado (EV — Expected Value)

Este guia apresenta o conceito de **Valor Esperado (EV)** no Texas Hold'em e sua relação com **Equidade** e **Pot Odds**.

---

## 1. O que é Valor Esperado (EV)?

O **Valor Esperado (EV — Expected Value)** representa o resultado médio esperado de uma decisão quando ela é repetida muitas vezes.

No poker, o EV permite avaliar se uma decisão tende a gerar **lucro ou prejuízo no longo prazo**, independentemente do resultado de uma mão específica.

---

## 2. Decisões: +EV, -EV e EV Neutro

- **+EV (Valor Esperado Positivo):** indica que uma decisão tende a gerar lucro no longo prazo.
- **-EV (Valor Esperado Negativo):** indica que uma decisão tende a gerar prejuízo no longo prazo.
- **EV = 0:** indica que a decisão está em um ponto de equilíbrio, sem lucro ou prejuízo esperado.

O objetivo de uma estratégia sólida é tomar decisões que, em média, maximizem o **EV**.

---

## 3. Por que o EV é importante?

O EV permite analisar decisões de forma matemática, em vez de depender apenas de sorte ou intuição.

Ele ajuda a:

- Avaliar se uma decisão é lucrativa no longo prazo.
- Comparar diferentes decisões possíveis.
- Entender a relação entre risco e recompensa.
- Identificar decisões que parecem boas no curto prazo, mas são ruins no longo prazo.

---

## 4. Fórmula básica do EV

Uma forma simplificada de calcular o Valor Esperado é:

$$
EV = (P_{\text{vitória}} \times \text{Ganho}) -
(P_{\text{derrota}} \times \text{Perda})
$$

Onde:

- **$P_{\text{vitória}}$:** probabilidade de vencer.
- **$P_{\text{derrota}}$:** probabilidade de perder.
- **Ganho:** quantidade de fichas obtidas quando a decisão é vencedora.
- **Perda:** quantidade de fichas perdida quando a decisão é derrotada.

Como as probabilidades de vitória e derrota somam 100%:

$$
P_{\text{derrota}} = 1 - P_{\text{vitória}}
$$

> **Nota:** Essa é uma forma simplificada de representar o EV. Cálculos reais de poker podem envolver empates, fold equity, diferentes resultados possíveis e outros fatores.

---

## 5. Relação entre EV, Equidade e Pot Odds

**Equidade** representa a probabilidade de sua mão vencer em determinado cenário.

**Pot Odds** representam o preço que o pote oferece para realizar um **Call**.

Em uma situação simples de Call, podemos comparar os dois valores:

- Se a **Equidade** for maior que as **Pot Odds**, o Call tende a ser **+EV**.
- Se a **Equidade** for menor que as **Pot Odds**, o Call tende a ser **-EV**.
- Se forem aproximadamente iguais, o Call está próximo do **EV neutro**.

> Essa comparação é uma simplificação e funciona melhor quando não existem outros fatores relevantes, como futuras decisões, rake ou ICM.

---

## 6. EV nas principais ações

### Call

O **Call** pode ser +EV quando a equidade da mão é suficiente para justificar o preço pago.

### Fold

O **Fold** evita investir mais fichas na mão.

As fichas já investidas anteriormente não devem ser consideradas como um custo adicional da decisão atual.

### Bet / Raise

**Bet** e **Raise** podem gerar EV através de:

- **Valor:** receber pagamento de mãos piores.
- **Fold Equity:** fazer mãos melhores desistirem.
- **Construção do pote:** aumentar o valor que pode ser ganho quando estamos à frente.

---

## 7. Curto Prazo vs. Longo Prazo

Uma decisão +EV **não garante que você vencerá uma mão específica**.

Por exemplo:

> Você pode fazer um Call com 70% de equidade e ainda perder a mão.

Isso acontece porque existe uma chance de 30% de derrota.

O EV representa o resultado esperado quando situações semelhantes são repetidas muitas vezes.

### Variância

A **variância** representa as oscilações naturais dos resultados causadas pela aleatoriedade.

Por isso:

- Uma decisão **+EV** pode perder no curto prazo.
- Uma decisão **-EV** pode ganhar no curto prazo.
- O resultado de uma única mão não determina se a decisão foi boa ou ruim.

---

## ⚠️ Limitações

O cálculo de EV pode se tornar mais complexo dependendo da situação.

Alguns fatores que podem influenciar o cálculo incluem:

- **Draws e Outs**
- **Fold Equity**
- **Equidade**
- **Pot Odds**
- **Rake**
- **ICM em torneios**
- Diferentes resultados possíveis para uma mesma ação

Esses conceitos serão estudados separadamente ao longo do projeto.

---

## 📝 Resumo

- **EV** representa o resultado esperado de uma decisão no longo prazo.
- **+EV** indica uma decisão lucrativa em média.
- **-EV** indica uma decisão prejudicial em média.
- **EV = 0** representa um ponto de equilíbrio.
- Em um **Call simples**, Equidade e Pot Odds podem ser comparadas para avaliar sua lucratividade.
- **Variância** faz com que os resultados de curto prazo não representem necessariamente a qualidade da decisão.
- O objetivo no poker é tomar decisões que maximizem o **EV no longo prazo**.
