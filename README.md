Alphabet (GOOGL) | Modelo de Valuation e Projeção de Valor de Mercado

Modelo financeiro integrado em Excel para projetar o valor de mercado futuro da Alphabet e estimar um preço-alvo, combinando DCF (FCFF e FCFE) com múltiplos de comparáveis. Projeções trimestrais de 2Q26e a 4Q26e e anuais de 2027 a 2031, sobre histórico de 2020 a 1Q26.

Arquivo: GabrielPorto_Alphabet.xlsx | Valores em US$ milhões

Como o modelo funciona
Build Up de receita por segmento: Search, YouTube Ads, Network, Subscriptions/Platforms/Devices, Google Cloud, Other Bets e Hedging. Cada linha cresce a partir de uma taxa de crescimento definida na aba de cenários.
Margens por segmento: Google Services e Google Cloud têm margem operacional própria. Other Bets e custos corporativos (nível Alphabet) entram como linhas de despesa separadas.
Demonstrações projetadas: DRE, Balanço e Fluxo de Caixa fechando entre si (checagem de balanceamento no BS), com schedules de apoio para dívida, CapEx/D&A e capital de giro (dias de receita, SG&A e COGS).
Valuation: DCF por FCFF e por FCFE (valor terminal por perpetuidade) e comparáveis por P/L, EV/Sales e EV/EBITDA.
Cenários (Bear / Base / Bull)

A aba Scenarios concentra todas as premissas operacionais e tem uma linha Running que define qual cenário alimenta o modelo. Drivers por cenário:

Crescimento de Search, YouTube Ads, Subscriptions e Cloud
Margem de Cloud e de Services
CapEx como % da receita
Crescimento de Network

O Base é a premissa central. Bear e Bull são derivados dele usando a volatilidade histórica de cada driver (k = desvio padrão / média, 13 trimestres de 1Q23 a 1Q26) multiplicada por um fator de intensidade. Ou seja, quanto mais volátil o histórico do segmento, mais aberto é o leque do cenário.

Other Bets e Hedging ficaram fora dos cenários por terem impacto geral baixo, mantidos em valores baseados no histórico.

Premissas principais (Base)
Crescimento de Search: 15% em 2026, 20% em 2027, desacelerando para 10% em 2031
Google Cloud: +30% nos trimestres de 2026, +50% em 2027, caindo para +10% em 2031, com margem subindo de 34% para 38%
CapEx em pico de 40% da receita em 2027 e reduzindo para 15% em 2031
Google Services: margem de 45% a 47%
Alíquota efetiva: 19,2%
Payout crescente ao longo do horizonte, dividido entre dividendos (20%) e recompra (80%)
Valuation

DCF

Ke de 10,455% via CAPM (Rf 4,6% do 10Y americano, beta 1,25, ERP 4,5% e CRP 0,23%)
WACC de aproximadamente 10,3%, com custo de dívida pós-imposto de 3,2%
Crescimento na perpetuidade (g) de 4,5%
Desconto no meio do período
Resultado no caso base: preço-alvo de US$ 251 (FCFF) e US$ 224 (FCFE), contra cotação de US$ 346,36 usada no modelo

Comparáveis

Meta, Amazon, Snap, Netflix, eBay, Microsoft e Apple
Estatísticas (mínimo, percentil 25, mediana, média, percentil 75, máximo) aplicadas aos denominadores da Alphabet para FY26 a FY28
Faixa implícita (football field): US$ 176 (baixo), US$ 292 (médio) e US$ 410 (alto)
Estrutura das abas
Aba	Conteúdo
Scenarios	Premissas Bear/Base/Bull e cálculo do k histórico
Build Up	Receita e resultado operacional por segmento
Income Statement / Q - Income Statement	DRE anual e trimestral
BS / Q - BS	Balanço anual e trimestral
CFS - Historical / CFS - Estimates	Fluxo de caixa reportado e projetado
Debt Schedule / Debt Compostion	Dívida, juros e composição dos bonds
CapEx & D&A	CapEx, depreciação e PP&E
DCF / Discount Factor	FCFF, FCFE, WACC e custo de capital
Comps / Multiplos base	Múltiplos de comparáveis e preço implícito
Macro	Juros e séries macro

Convenção de cores: hardcode, fórmula e premissa (legenda no topo de cada aba).

Fontes
Demonstrações financeiras: relatórios da Alphabet
Risk-free: Yahoo Finance (^TNX)
Equity Risk Premium: Statista
Country Risk Premium: Damodaran (NYU Stern)
Aviso

Projeto acadêmico e de estudo. Não é recomendação de investimento. As projeções dependem das premissas do autor e podem divergir bastante do resultado real.

Autor

Gabriel Porto | Engenharia Elétrica, Unicamp
