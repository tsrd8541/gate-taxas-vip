# taxas gate io: quanto custa operar, depositar e sacar na corretora, nível por nível

Quem digita "taxas gate io" quase nunca quer uma aula sobre modelo maker/taker. Quer saber uma coisa bem concreta: quanto sai da conta a cada ordem, a cada saque, a cada troca de real por stablecoin. O problema é que a resposta muda conforme o nível VIP, o tipo de ordem, a rede escolhida no saque e até a moeda em que você paga a taxa.

Este guia separa isso em partes, com os números que estão na página oficial de taxas da Gate e nas fontes públicas que dá para conferir hoje. Onde houver divergência entre o que circula em blogs e o que a corretora publica, isso vai estar dito com todas as letras.

## O que entra na conta quando você fala em taxas da Gate

Existem três blocos de custo, e eles não se comportam igual:

**1. Taxa de negociação** — spot, futuros, margem, opções, CFD. Depende do seu nível VIP e de a ordem ter entrado ou saído da liquidez do livro.

**2. Entrada e saída de dinheiro** — depósito em cripto (normalmente zero), saque em cripto (cobrado pela rede, com valor ajustado hora a hora) e operações com moeda fiduciária, que variam por região e por provedor de pagamento.

**3. Custos paralelos** — funding rate em contratos perpétuos, juros de empréstimo na margem, taxa fixa de 0,8% no Alpha, 1% no marketplace de NFT, swap overnight em CFD.

Um detalhe que vale mais do que qualquer tabela: a própria Gate informa que ajusta as taxas ao longo do tempo, e fez uma revisão completa da estrutura de spot e futuros com efeito em 9 de abril de 2026, anunciada em 25 de março do mesmo ano. Ou seja, número de blog com mais de um ano de idade em matéria de taxa costuma estar errado.

> A taxa que vale é a que aparece na sua tela de confirmação de ordem, já com o seu nível VIP aplicado. A tabela pública serve para planejar, não para fechar conta.

## Taxa de spot: 0,10% no nível inicial, e o desconto do GT

No nível de entrada (VIP0), a Gate cobra **0,10% para maker e 0,10% para taker** em negociação spot. Se você ativar o pagamento de taxas com GT — o token nativo da plataforma —, os dois lados caem para **0,09%**.

Vale registrar uma confusão comum. Muita gente encontra "0,2%" em artigos, vídeos e comparadores e assume que essa é a taxa base da Gate. A página oficial de taxas da corretora lista 0,10% no VIP0. O 0,2% reaparece com frequência em conteúdo antigo, em tabelas de terceiros e em textos gerados por agregadores que não têm data de verificação. Se você comparar propostas com base nesse número, a conclusão sai errada.

Outro ponto que passa batido: **do VIP0 ao VIP3, maker e taker são idênticos**. Descansar uma ordem limitada no livro não economiza nada nessa faixa. A separação entre os dois lados só começa no VIP4, e mesmo ali é pequena (0,095% maker contra 0,096% taker). Quem opera volume baixo e médio não deve contar com desconto de maker para melhorar o resultado.

Como referência de mercado, a análise da TradersUnion sobre taxas de corretoras coloca a média do setor em 0,194% para taker no spot e 0,15% para maker, com base em uma amostra de mais de 200 exchanges. Nessa régua, 0,10% nos dois lados fica bem abaixo da média — e a mesma análise aponta taxa de depósito zero e nota geral de 9,3/10 para a Gate.io no critério de custos.

## Futuros: 0,020% maker e 0,050% taker no VIP0

Nos contratos perpétuos com margem em USDT, o ponto de partida é **0,020% maker e 0,050% taker**. É aqui que vale a pena se preocupar com o tipo de ordem, porque a diferença entre limitada e mercado é de 2,5 vezes.

Um exemplo com números redondos: abrir uma posição de US$ 60.000 a mercado custa US$ 30 em taxa (0,050%). A mesma posição com ordem limitada que espera no livro custa US$ 12 (0,020%). A cobrança acontece na abertura, no fechamento e em reduções de posição; ordem cancelada ou não executada não gera taxa.

A escalada de taker nos futuros segue uma escada mais suave que a do spot e chega a **0,030% no VIP10, 0,022% no VIP14 e 0,016% no VIP15 e VIP16 (contratos do Grupo A)**. Para níveis altos, a Gate passou a diferenciar a taxa de taker por categoria de contrato — principal, intermediário e outros —, de modo que pares menos líquidos custam mais caro que BTC e ETH.

E tem o custo que não é taxa de negociação, mas pesa mais que ela em posições longas: o **funding rate**, liquidado a cada 8 horas entre longues e shorts. Quem fica dias dentro de um perpétuo pode acumular em funding mais do que pagou para abrir e fechar a operação. Em contratos com funding persistentemente positivo, o lado comprado paga.

## Depósito e saque: onde a conta costuma crescer

### Criptomoedas

Depositar cripto na Gate é gratuito do lado da plataforma. Você paga apenas a taxa da rede blockchain no momento do envio, que vai para os mineradores ou validadores, não para a corretora. Depósitos via P2P também não têm taxa da plataforma.

O saque é outra história, e é o ponto mais mal compreendido. **A taxa de saque é dinâmica**, recalibrada conforme a congestão da rede e ajustada com frequência próxima de uma hora. Você vê o valor exato e o mínimo de saque antes de confirmar. Isso significa que a mesma moeda pode custar 1 USDT de saque pela TRC-20 hoje e algo diferente depois, e que escolher ERC-20 para transferir valor pequeno costuma ser má ideia — a taxa pode representar uma fatia enorme do total.

Três hábitos reduzem esse custo de forma bem direta:

- Preferir redes de gás baixo (TRON, BNB Chain, soluções de camada 2) quando a carteira de destino aceita.
- Juntar saques pequenos em um só, em vez de mandar cinco transferências.
- Conferir a taxa na janela de saque no momento da operação, não de memória.

### Real (BRL) via PIX

Para quem opera do Brasil, esse é o dado mais procurado — e o mais fácil de errar. Segundo o próprio material de suporte da Gate sobre saque de BRL, **o PIX é o único método disponível** para retirar reais, **a taxa padrão é de 3% do valor sacado**, não existe valor mínimo, e o dinheiro normalmente cai na conta em até um dia útil. Fora do horário bancário, a liquidação escorrega para o dia útil seguinte.

A conta bancária de destino precisa estar no mesmo nome e CPF da conta na plataforma. Isso não é detalhe burocrático: se o titular divergir, o saque não passa.

Vale dizer com clareza: 3% é uma taxa alta comparada ao custo de tirar USDT por rede barata. Em valores pequenos, faz sentido converter e sacar em stablecoin por rede de baixo gás, desde que o destino aceite cripto. Em valores altos, 3% pode ser aceitável pela conveniência de cair direto em reais.

Há também um artigo da base de conhecimento da Gate sobre depósito e saque na plataforma que menciona 1,5% mais US$ 1 na entrada e isenção no saque. Trata-se de um texto genérico sobre a plataforma, enquanto o material específico sobre BRL aponta os 3%. Como os números conflitam, o mais confiável é tratar a taxa como algo que aparece na tela de confirmação do saque — e conferir ali antes de assinar.

### Fiat em geral

Depósito e saque em moeda fiduciária por Gate Pay ou transferência bancária têm preço definido por método (wire, ACH, cartão, P2P) e por região, porque dependem do parceiro de pagamento local. O depósito por P2P não tem taxa da plataforma, mas as condições aparecem no spread de quem anuncia, não em uma linha de taxa.

## Todos os 17 níveis VIP da Gate, com as taxas de spot atuais

A Gate opera uma escada de 17 faixas, de VIP0 a VIP16. Não existe mensalidade nem preço de assinatura: a conta é gratuita e o que você paga é a taxa por operação.

| Nível VIP | Taxa spot maker / taker | Taxa spot pagando com GT | Abrir conta ou conferir sua taxa |
| --- | --- | --- | --- |
| VIP0 | 0,100% / 0,100% | 0,0900% / 0,0900% | [Começar no nível de entrada da Gate](https://bit.ly/GateVIP) |
| VIP1 | 0,099% / 0,099% | 0,0890% / 0,0890% | [Registrar e subir de faixa](https://bit.ly/GateVIP) |
| VIP2 | 0,098% / 0,098% | 0,0880% / 0,0880% | [Abrir conta e ver os níveis](https://bit.ly/GateVIP) |
| VIP3 | 0,097% / 0,097% | 0,0870% / 0,0870% | [Ver a escada VIP completa](https://bit.ly/GateVIP) |
| VIP4 | 0,095% / 0,096% | 0,0860% / 0,0860% | [Criar conta na Gate](https://bit.ly/GateVIP) |
| VIP5 | 0,090% / 0,095% | 0,0810% / 0,0850% | [Ativar desconto por GT](https://bit.ly/GateVIP) |
| VIP6 | 0,085% / 0,090% | 0,0760% / 0,0810% | [Começar a operar na Gate](https://bit.ly/GateVIP) |
| VIP7 | 0,080% / 0,085% | 0,0700% / 0,0760% | [Abrir sua conta na Gate](https://bit.ly/GateVIP) |
| VIP8 | 0,075% / 0,080% | 0,0600% / 0,0720% | [Conferir taxas por nível](https://bit.ly/GateVIP) |
| VIP9 | 0,070% / 0,075% | 0,0500% / 0,0680% | [Registrar na Gate](https://bit.ly/GateVIP) |
| VIP10 | 0,040% / 0,058% | igual à taxa VIP | [Acessar a escada de taxas](https://bit.ly/GateVIP) |
| VIP11 | 0,030% / 0,045% | igual à taxa VIP | [Criar conta e negociar](https://bit.ly/GateVIP) |
| VIP12 | 0,020% / 0,037% | igual à taxa VIP | [Abrir conta na Gate](https://bit.ly/GateVIP) |
| VIP13 | 0,010% / 0,030% | igual à taxa VIP | [Ver condições de VIP alto](https://bit.ly/GateVIP) |
| VIP14 | 0,008% / 0,023% | igual à taxa VIP | [Começar agora na Gate](https://bit.ly/GateVIP) |
| VIP15 | 0% / 0,020% | igual à taxa VIP | [Registrar e conferir taxas](https://bit.ly/GateVIP) |
| VIP16 | 0% / 0,0175% | igual à taxa VIP | [Abrir conta na Gate](https://bit.ly/GateVIP) |

O limite de saque em 24 horas não acompanha o nível de verificação, e sim a faixa VIP. A Gate publica os seguintes tetos: US$ 3 milhões no VIP0, US$ 5 milhões no VIP5, US$ 8 milhões no VIP9, US$ 10 milhões no VIP12, US$ 20 milhões no VIP13, US$ 30 milhões no VIP14, US$ 40 milhões no VIP15 e US$ 50 milhões no VIP16.

Repare em duas coisas na tabela. Primeiro, o desconto do GT é real mas pequeno: 0,10% vira 0,09% no nível inicial, algo próximo de 10%. Segundo, **a partir do VIP10 as duas colunas se igualam** — pagar taxa com GT deixa de reduzir qualquer coisa exatamente nas faixas em que a taxa já é baixa. Se sua estratégia é acumular GT para baratear custo, o ganho existe, mas tem teto.

## Como a Gate calcula o seu nível VIP

O nível é definido pelo melhor resultado entre dois caminhos: volume negociado em 30 dias ou média de GT mantido nos últimos 14 dias. A reavaliação acontece periodicamente, e não é todo volume que conta igual.

Os pesos oficiais são estes:

- Volume de spot (incluindo Convert) e de negociação de ações: 100%
- Perpétuos em USDT, perpétuos em BTC e futuros de entrega em USDT: 40%
- Contratos em USD1 e opções: 20%
- Contratos de CFD: 10%

O volume de copy trading de spot e futuros entra nos totais. Como perpétuos contam apenas 40% do valor nocional, um operador de futuros precisa girar bem mais que um operador de spot para alcançar a mesma faixa. Isso muda a conta de quem planeja chegar a um nível específico só com derivativos.

## Custos paralelos que quase ninguém procura

Taxa de trading é a parte visível. Estas linhas costumam passar longe das comparações:

- **Alpha:** 0,8% fixo por negociação, em todos os níveis VIP. É cerca de oito vezes a taxa de spot base.
- **Marketplace de NFT:** 1% por transação.
- **Funding rate:** a cada 8 horas nos perpétuos — em posições mantidas por semanas, pode superar tranquilamente o custo de abertura e fechamento.
- **Empréstimo de margem:** taxa variável, definida por ativo, alavancagem, prazo e condição de mercado. Não tem tabela fixa.
- **CFD:** comissão por operação mais swap overnight para posições que atravessam o dia.
- **Gate Pay para comerciantes:** 0,5% por transação, com liquidação no mesmo dia e sem taxa de contestação.

## Gate em comparação com outras corretoras

| Item | Gate | Média de mercado (amostra de +200 corretoras) |
| --- | --- | --- |
| Taker spot | 0,10% | 0,194% |
| Maker spot | 0,10% | 0,15% |
| Taker futuros | 0,05% | 0,054% |
| Maker futuros | 0,02% | 0,024% |
| Taxa de depósito | 0 | 0 |
| Taxa de saque | fixa por moeda e rede; 3% no saque de BRL via PIX | variável |

Os dados de média vêm da compilação da TradersUnion. A comparação direta mostra que o spot da Gate é competitivo e que os futuros ficam praticamente na linha da média, sem vantagem expressiva. Em um comparativo frente à KuCoin, o spot aparece empatado em 0,10% nos dois lados, e os futuros da Gate vão de 0,015% a 0,02% no maker contra 0,02% da concorrente, com taker de 0,05% contra 0,06%.

Resumindo sem enfeite: a Gate é barata no spot para quem faz volume pequeno e mediano, e é competitiva nos futuros sem ser imbatível. O que costuma incomodar não é a taxa de negociação, e sim o custo de tirar o dinheiro — especialmente se o caminho for PIX.

## Como pagar menos taxa na prática

1. **Ative o pagamento de taxas com GT.** No VIP0, é a diferença entre 0,10% e 0,09%. Só não conte com isso acima do VIP10, onde o desconto deixa de existir.
2. **Use ordens limitadas nos futuros.** 0,020% contra 0,050% é uma redução de 60% no custo de entrada.

<details><summary>...</summary>

Ignore that. Let me finalize the list items.

3. **No spot, não espere prêmio por ser maker nos primeiros níveis.** Maker e taker são iguais até o VIP3. Se sua estratégia depende de rebate de maker, a Gate não entrega isso no começo.
4. **Escolha rede barata no saque.** Confira a taxa na janela de saque antes de confirmar e prefira TRON, BNB Chain ou camada 2 quando o destino aceitar.
5. **Agrupe saques.** Cinco transferências pequenas pagam cinco taxas fixas. Uma transferência única paga uma.
6. **Monitore o funding rate em posições de futuros mantidas por dias.** Ele roda a cada 8 horas e não aparece em nenhuma tabela de taxa de trading.
7. **Fuja das taxas fixas altas sem necessidade.** Alpha custa 0,8% e NFT 1%. Se existir alternativa com taxa menor para a mesma operação, ela vale a pena.

## Perguntas frequentes

### Qual é a taxa de trading mais baixa possível na Gate?

Zero no maker de spot, mas só a partir do VIP15. O taker mais baixo é 0,0175% no VIP16, na categoria de contratos principais. Chegar lá exige US$ 3 bilhões de volume em 30 dias ou uma posição relevante de GT.

### Vale a pena pagar taxa com GT mesmo assim?

No nível inicial, sim: 0,10% vira 0,09%. O ganho é proporcional e pequeno. Acima do VIP10, os dois números se igualam e o benefício desaparece na prática.

### Quanto custa sacar reais da Gate?

Segundo a documentação de suporte da própria plataforma sobre saque de BRL, a taxa padrão é 3% do valor, via PIX, com crédito em até um dia útil. Não há mínimo de saque. O valor exato aparece na tela de confirmação.

### Depósito na Gate tem taxa?

Depósito em criptomoeda não tem taxa da plataforma — só a taxa de rede paga ao blockchain no envio. Depósito via P2P também é isento do lado da Gate. Depósito em moeda fiduciária depende do método e da região.

### Por que encontro "0,2%" de taxa de spot em outros sites?

Porque parte do conteúdo de comparação não tem data de verificação e reaproveita números antigos ou de fontes secundárias. A página oficial de taxas da Gate lista 0,10% maker e 0,10% taker no VIP0. A taxa que realmente incide é a que aparece na sua conta.

### As taxas mudam com frequência?

Sim. A estrutura de spot e futuros foi revisada com efeito em 9 de abril de 2026, com reajuste de maker/taker e dos descontos de GT por faixa. Vale checar a página de taxas antes de montar qualquer estratégia de custo.

## O ponto de partida, na prática

Se você chegou aqui procurando "taxas gate io" para decidir se vale abrir conta, o resumo é: spot a 0,10% nos dois lados é barato para o padrão do mercado, futuros a 0,020%/0,050% são competitivos sem exagero, depósito em cripto é gratuito, e o saque é onde o custo aparece de verdade — principalmente no saque de reais, com os 3% do PIX.

Nada disso é decidido antes de você ter conta, porque a taxa depende do seu nível, do par e da rede que você escolhe. A escada completa, os limites de saque e a taxa de cada faixa ficam visíveis depois do login.

👉 [Abrir conta na Gate e conferir sua taxa real por nível](https://bit.ly/GateVIP)
