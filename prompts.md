# 🛠️ Engenharia de Prompts e Cicatrizes (Troubleshooting)

Neste arquivo, documento as estratégias utilizadas para extrair o melhor conhecimento do NotebookLM sobre a metodologia de Benjamin Graham.

---

## 📝 Prompts de Exploração

### Prompt 1: Conceitual
> "Quais são os principais pilares da metodologia de investimentos de Benjamin Graham?"

**Raciocínio:** O objetivo era obter a base teórica. 
**Resultado:** A IA explicou bem o conceito de "Sr. Mercado" e "Margem de Segurança", mas de forma muito densa.

---

## 🩹 Cicatrizes e Refinamentos (Troubleshooting)

Durante o processo, encontrei dificuldades na separação dos tipos de investidores.

### Desafio 1: Mistura de Perfis
Ao perguntar sobre critérios de seleção, a IA misturou inicialmente regras para o investidor **defensivo** (passivo) com o **empreendedor** (ativo). 

**Ajuste (Prompt de Refinamento):**
> "Separe em tópicos distintos os 7 critérios quantitativos exclusivos para o investidor defensivo, focando em segurança e tamanho da empresa."

**Resultado:** O NotebookLM ajustou a resposta trazendo os parâmetros de Graham como "Faturamento > $100 milhões" e "P/L < 15".

### Desafio 2: Atualização de Valores
As fontes citam valores de 1973. Precisei de um prompt para contextualizar a realidade atual sugerida pelos comentadores (como Jason Zweig).

**Ajuste (Prompt de Contexto):**
> "Com base nas notas de rodapé das fontes, qual a atualização sugerida para o critério de 'Tamanho Adequado' em mercados modernos?"

**Resultado:** A IA identificou que o valor de mercado mínimo deve ser de aproximadamente **$2 bilhões** hoje.

---

## 🚀 Prompts Reutilizáveis (Para Revisão)

Para quem deseja continuar os estudos neste caderno, recomendo os seguintes comandos:

1. "Resuma a parábola do Sr. Mercado e explique como ela ajuda a controlar o lado emocional do investidor."
2. "Calcule o Número de Graham para uma empresa com LPA de [X] e VPA de [Y]."
3. "Quais são as 13 peças de conselho que Graham dá para evitar a especulação?"
