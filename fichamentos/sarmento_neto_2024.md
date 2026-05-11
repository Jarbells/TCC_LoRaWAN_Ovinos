# Fichamento - Sarmento Neto et al. (2024)

## Referência

SARMENTO NETO, Geraldo A.; SILVA, Thiago A. R.; ABREU, Pedro F. F.; VELOSO, Arthur F. S.; M., Luis H. O.; R. JUNIOR, José Valdemir. *A Percentile Based ADR for Mobile LoRaWAN Applications*. In: SIMPÓSIO BRASILEIRO DE REDES DE COMPUTADORES E SISTEMAS DISTRIBUÍDOS (SBRC), 42., 2024, Niterói/RJ. *Anais [...]*. Porto Alegre: Sociedade Brasileira de Computação, 2024. p. 43-56. DOI: 10.5753/sbrc.2024.1248.

## Tipo de fonte

Artigo científico publicado em simpósio.

## Tema central da fonte

O artigo discute as limitações do mecanismo ADR padrão em redes LoRaWAN quando aplicado a dispositivos móveis. Para lidar com esse problema, os autores propõem o P-ADR, uma abordagem baseada em percentis da relação sinal-ruído, ou SNR, para ajustar os parâmetros de transmissão de forma mais adequada em cenários nos quais as condições do canal variam com frequência.

## Para que essa fonte serve no meu TCC?

Essa fonte serve para fundamentar a parte do meu TCC relacionada à mobilidade dos dispositivos e às limitações do ADR padrão em redes LoRaWAN.

No meu caso, os dispositivos estarão associados a ovinos. Mesmo que meu trabalho não proponha um novo algoritmo de ADR, a mobilidade dos animais em cenários de pastagem pode alterar a distância entre os dispositivos e o gateway, modificando as condições de comunicação. Por isso, o artigo de Sarmento Neto et al. (2024) ajuda a justificar que a mobilidade precisa ser considerada na análise da rede.

## Ideia principal

Sarmento Neto et al. (2024) mostram que o ADR padrão pode apresentar limitações em aplicações móveis, porque ele foi pensado principalmente para cenários mais estáveis, nos quais as condições do canal não mudam rapidamente.

Em cenários móveis, a qualidade do sinal pode variar com frequência. Isso dificulta a escolha adequada dos parâmetros de transmissão, como fator de espalhamento e potência. Para melhorar esse processo, os autores propõem o P-ADR, que utiliza uma abordagem estatística baseada em percentis da SNR para tornar a adaptação mais adequada em cenários com variação do canal.

## O que posso citar com segurança?

- O ADR padrão pode ter desempenho limitado em cenários móveis.
- A mobilidade dos dispositivos pode causar variação nas condições do canal de comunicação.
- A variação da SNR afeta a escolha dos parâmetros de transmissão em redes LoRaWAN.
- O artigo propõe o P-ADR como uma alternativa ao ADR padrão.
- O P-ADR usa uma abordagem baseada em percentis para estimar a SNR.
- O objetivo do P-ADR é melhorar a confiabilidade da comunicação em cenários móveis.
- O desempenho é avaliado por meio de simulação.
- A métrica PDR, Packet Delivery Ratio, é usada para avaliar a entrega de pacotes.
- Os resultados indicam que o P-ADR melhora a taxa de entrega de pacotes em cenários móveis quando comparado ao ADR padrão.
- O artigo reforça que soluções de LoRaWAN em mobilidade precisam considerar a variação rápida do canal.

## Onde essa fonte entra no meu TCC?

Esta fonte pode ser usada principalmente em quatro partes:

1. **Introdução**  
   Para mostrar que a mobilidade dos dispositivos é um fator que pode afetar o desempenho de redes LoRaWAN.

2. **Justificativa**  
   Para explicar por que é importante avaliar a rede em cenários de pastagem, onde os animais podem se deslocar e alterar sua posição em relação ao gateway.

3. **Fundamentação teórica**  
   Para explicar o ADR e suas limitações em cenários móveis.

4. **Trabalhos relacionados**  
   Para comparar um estudo que propõe melhoria no ADR para mobilidade com o meu trabalho, que não propõe novo ADR, mas avalia a escalabilidade da rede usando configurações padrão.

## Relação com o meu TCC

O artigo de Sarmento Neto et al. (2024) está relacionado ao meu TCC porque ambos tratam de redes LoRaWAN em cenários onde a mobilidade pode influenciar a comunicação.

No meu trabalho, os dispositivos simulados representam ovinos monitorados. Em confinamento, os animais tendem a ficar mais concentrados e próximos ao gateway. Em pastagem, os animais podem se deslocar e se distribuir em uma área maior, o que pode alterar a qualidade do sinal recebido.

Assim, Sarmento Neto et al. (2024) ajuda a justificar que o comportamento da rede em mobilidade é relevante e que o ADR padrão pode não responder adequadamente a variações rápidas do canal.

## Diferença entre o trabalho de Sarmento Neto et al. (2024) e o meu trabalho

Sarmento Neto et al. (2024) propõem um novo mecanismo de ADR, chamado P-ADR, voltado para aplicações móveis em LoRaWAN.

O meu trabalho não propõe um novo algoritmo de ADR. Meu objetivo é avaliar, por simulação, a escalabilidade de uma rede LoRaWAN aplicada ao monitoramento de ovinos no Sertão Central, considerando cenários de confinamento e pastagem.

Enquanto Sarmento Neto et al. (2024) buscam melhorar o mecanismo de adaptação de taxa de dados em cenários móveis, o meu TCC busca entender como a rede se comporta quando aumenta o número de ovinos monitorados.

## Limites da fonte

Esta fonte não deve ser usada para falar diretamente sobre ovinos, pecuária, Sertão Central ou sinais vitais de animais.

Também não deve ser usada para afirmar que meu trabalho irá propor um novo ADR, pois essa não é a proposta do meu TCC.

Sarmento Neto et al. (2024) deve ser usado principalmente para falar sobre mobilidade em LoRaWAN, limitações do ADR padrão, variação de SNR, PDR e propostas de melhoria para cenários móveis.

## Cuidado ao citar

Não dizer que Sarmento Neto et al. (2024) estudaram ovinos.

Não dizer que meu trabalho usa ou implementa o P-ADR, a menos que isso seja decidido posteriormente.

Usar o artigo para sustentar a ideia de que a mobilidade afeta o desempenho do ADR padrão e que cenários móveis precisam ser avaliados com cuidado.

## Frase pronta para usar na introdução

A mobilidade dos dispositivos pode afetar o desempenho de redes LoRaWAN, pois a variação da posição dos nós altera as condições do canal de comunicação. Sarmento Neto et al. (2024) mostram que o ADR padrão apresenta limitações em cenários móveis, o que pode comprometer a taxa de entrega de pacotes quando a qualidade do enlace varia rapidamente.

## Frase pronta para usar na justificativa

Como os ovinos podem se deslocar em áreas de pastagem, a posição dos dispositivos em relação ao gateway tende a variar ao longo do tempo. Essa mobilidade pode alterar as condições de comunicação da rede e influenciar o desempenho do ADR padrão, aspecto já apontado por Sarmento Neto et al. (2024) em aplicações móveis de LoRaWAN.

## Frase pronta para usar em trabalhos relacionados

Sarmento Neto et al. (2024) propuseram o P-ADR, um mecanismo baseado em percentis de SNR para melhorar o desempenho do ADR em aplicações móveis de LoRaWAN. Os autores observaram que o ADR padrão pode apresentar limitações quando as condições do canal variam rapidamente. Diferentemente desse estudo, a presente pesquisa não propõe um novo algoritmo de ADR, mas avalia a escalabilidade de uma rede LoRaWAN aplicada ao monitoramento de ovinos em cenários de confinamento e pastagem.

## Principais conceitos retirados da fonte

### ADR

ADR significa Adaptive Data Rate. É o mecanismo usado em LoRaWAN para ajustar parâmetros de transmissão, como taxa de dados e potência, buscando melhorar o desempenho da rede e economizar energia.

### Mobilidade

A mobilidade ocorre quando os dispositivos mudam de posição ao longo do tempo. Essa mudança pode alterar a distância até o gateway e modificar a qualidade do sinal recebido.

### SNR

SNR significa Signal-to-Noise Ratio, ou relação sinal-ruído. É uma medida da qualidade do sinal recebido. Em redes LoRaWAN, a SNR é usada para apoiar decisões relacionadas à escolha dos parâmetros de transmissão.

### P-ADR

P-ADR é o mecanismo proposto pelos autores. Ele utiliza uma abordagem baseada em percentis para estimar a SNR e ajustar os parâmetros de transmissão em cenários móveis.

### PDR

PDR significa Packet Delivery Ratio. Essa métrica representa a proporção de pacotes enviados que foram recebidos com sucesso. Quanto maior o PDR, melhor o desempenho da comunicação.

## Importância para a minha metodologia

Esse artigo ajuda a justificar que a simulação de cenários com mobilidade ou variação de posição é importante em redes LoRaWAN.

No meu TCC, o cenário de pastagem pode representar uma situação mais dinâmica do que o confinamento, já que os animais podem se espalhar pela área. Por isso, mesmo usando o ADR padrão, é importante avaliar como a rede se comporta quando os nós não estão sempre próximos do gateway.

## Como posso diferenciar meu trabalho na banca

Se alguém perguntar por que meu trabalho é diferente de Sarmento Neto et al. (2024), posso responder:

Sarmento Neto et al. (2024) propõem e avaliam um novo mecanismo de ADR para aplicações móveis em LoRaWAN, chamado P-ADR. O meu trabalho não propõe novo ADR. Eu utilizo a tecnologia LoRaWAN em um cenário aplicado ao monitoramento de ovinos no Sertão Central e avalio a escalabilidade da rede em cenários de confinamento e pastagem, observando o impacto do aumento do número de animais monitorados.

## Palavras-chave úteis

- LoRaWAN
- ADR
- P-ADR
- Mobilidade
- SNR
- PDR
- Packet Delivery Ratio
- Adaptive Data Rate
- Aplicações móveis
- LPWAN
- Simulação
- Parâmetros de transmissão
- Qualidade do canal
- Fator de espalhamento
- Taxa de entrega de pacotes

## Classificação dentro da minha base

Pasta local:

`04_ADR_Mobilidade`

Categoria:

Base técnica sobre ADR, mobilidade e desempenho LoRaWAN.

Importância:

Alta. Esta fonte ajuda a justificar por que a mobilidade dos animais em pastagem pode afetar o desempenho da rede LoRaWAN.
