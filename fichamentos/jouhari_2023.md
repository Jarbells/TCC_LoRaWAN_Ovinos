# Fichamento - Jouhari et al. (2023)

## Referência

JOUHARI, Mohammed; SAEED, Nasir; ALOUINI, Mohamed-Slim; AMHOUD, El Mehdi. *A Survey on Scalable LoRaWAN for Massive IoT: Recent Advances, Potentials, and Challenges*. IEEE Communications Surveys & Tutorials, 2023. DOI: 10.1109/COMST.2023.3274934.

## Tipo de fonte

Artigo científico de revisão.

## Tema central da fonte

O artigo apresenta uma revisão sobre os desafios de escalabilidade em redes LoRaWAN para cenários de Massive IoT, isto é, cenários com grande quantidade de dispositivos conectados transmitindo pequenos volumes de dados.

Os autores discutem os principais problemas que afetam a capacidade da rede, como interferência entre sinais LoRa, colisões entre transmissões simultâneas, limitações do mecanismo ADR, restrições de duty cycle, uso de spreading factors, densificação de gateways, mecanismos de controle de acesso ao meio e alternativas para melhorar a escalabilidade.

## Para que essa fonte serve no meu TCC?

Essa fonte serve para fundamentar a parte teórica sobre escalabilidade em redes LoRaWAN.

No meu TCC, ela será usada para explicar que o LoRaWAN é adequado para aplicações de IoT de longo alcance e baixo consumo, mas que sua escalabilidade é limitada quando muitos dispositivos finais transmitem dados simultaneamente. Essa limitação é importante para meu trabalho porque o monitoramento de vários ovinos exige avaliar como a rede se comporta conforme aumenta o número de nós.

## Ideia principal

Jouhari et al. (2023) mostram que o LoRaWAN é uma tecnologia promissora para Massive IoT devido ao seu longo alcance, baixo consumo energético e baixo custo. Entretanto, em redes densas, a grande quantidade de dispositivos finais pode gerar interferência, colisões e queda de desempenho.

O artigo mostra que a escalabilidade do LoRaWAN depende de fatores como:

- quantidade de dispositivos finais;
- distribuição dos dispositivos na área;
- número e posicionamento de gateways;
- escolha dos spreading factors;
- potência de transmissão;
- largura de banda;
- taxa de dados;
- restrições de duty cycle;
- mecanismos de acesso ao meio;
- desempenho do ADR;
- interferência entre transmissões simultâneas.

## O que posso citar com segurança?

- LoRa é a camada física, enquanto LoRaWAN atua na camada MAC da pilha LoRa.
- LoRaWAN utiliza uma topologia estrela-de-estrelas, conectando dispositivos finais a gateways.
- LPWANs são adequadas para aplicações IoT por oferecerem longo alcance, baixo consumo energético e baixo custo.
- LoRaWAN é usado em aplicações de Massive IoT, nas quais muitos dispositivos transmitem pequenas quantidades de dados.
- Apesar das vantagens, interferência e colisões em transmissões simultâneas são limitações importantes para a escalabilidade.
- O ADR busca ajustar parâmetros como data rate, spreading factor e potência de transmissão.
- O ADR padrão pode ter desempenho reduzido em redes muito densas e em canais variantes no tempo.
- A escalabilidade pode ser melhorada por estratégias como atribuição eficiente de spreading factors, cancelamento de interferência, densificação de gateways, alocação de canais, uso de MAC alternativos e técnicas de aprendizado de máquina.
- A densificação de gateways pode melhorar cobertura e escalabilidade, mas não elimina todos os problemas da rede.
- O aumento da quantidade de dispositivos em uma rede LoRaWAN exige preocupação com colisões, interferência e capacidade da rede.

## Onde essa fonte entra no meu TCC?

Esta fonte pode ser usada principalmente em quatro partes:

1. **Introdução**  
   Para apresentar LoRaWAN como tecnologia adequada para IoT rural e mostrar que escalabilidade é um desafio.

2. **Fundamentação teórica**  
   Para explicar LPWAN, LoRa, LoRaWAN, arquitetura da rede, ADR, spreading factor, gateway, end device, interferência, colisões e escalabilidade.

3. **Justificativa**  
   Para sustentar que avaliar o comportamento da rede com muitos dispositivos é necessário antes de pensar em aplicações reais em larga escala.

4. **Trabalhos relacionados**  
   Para mostrar que já existe uma revisão ampla sobre escalabilidade LoRaWAN, mas que ela não trata especificamente do monitoramento de ovinos no Sertão Central.

## Relação com o meu TCC

O artigo de Jouhari et al. (2023) está relacionado ao meu TCC porque trata diretamente da escalabilidade de redes LoRaWAN, que é o foco técnico central da minha pesquisa.

Meu trabalho avalia, por simulação, como uma rede LoRaWAN se comporta quando vários ovinos são monitorados. Jouhari et al. (2023) ajuda a explicar por que esse tipo de análise é necessário: em redes com muitos dispositivos, a ocorrência de interferência, colisões e limitações de capacidade pode comprometer a entrega dos dados.

## Diferença entre o trabalho de Jouhari et al. (2023) e o meu trabalho

Jouhari et al. (2023) fazem uma revisão ampla da literatura sobre escalabilidade em LoRaWAN para Massive IoT. O objetivo deles é organizar e discutir soluções já propostas para melhorar a capacidade das redes LoRaWAN.

O meu trabalho não é uma revisão ampla sobre LoRaWAN. Meu objetivo é aplicar a análise de escalabilidade a um cenário específico: o monitoramento de ovinos no Sertão Central, considerando cenários de confinamento e pastagem.

Enquanto Jouhari et al. (2023) respondem à pergunta:

> Quais são os desafios, avanços e soluções existentes para tornar redes LoRaWAN escaláveis em Massive IoT?

O meu TCC busca responder:

> Como uma rede LoRaWAN se comporta, em termos de escalabilidade, quando vários ovinos são monitorados em cenários de confinamento e pastagem no Sertão Central?

## Limites da fonte

Esta fonte não deve ser usada para falar especificamente sobre ovinos, Sertão Central, sinais vitais ou o protótipo físico desenvolvido por Araujo (2024).

Ela também não deve ser usada como única fonte para afirmar detalhes práticos sobre pecuária inteligente, pois o foco do artigo é a escalabilidade técnica de LoRaWAN.

Jouhari et al. (2023) deve ser usado principalmente para explicar conceitos e desafios técnicos relacionados a LoRaWAN, Massive IoT, escalabilidade, interferência, colisões, ADR, spreading factor e gateways.

## Cuidado ao citar

Não afirmar que Jouhari et al. (2023) estudaram monitoramento de ovinos.

Não afirmar que eles fizeram simulação de pecuária ou de confinamento/pastagem.

Usar o artigo para sustentar ideias gerais e técnicas sobre escalabilidade LoRaWAN, especialmente quando o texto falar de muitos dispositivos conectados, interferência, colisões e aumento da demanda de conectividade.

## Frase pronta para usar na introdução

LoRaWAN tem se destacado como uma tecnologia LPWAN adequada para aplicações de IoT devido ao seu longo alcance, baixo consumo energético e baixo custo. No entanto, em cenários de Massive IoT, a escalabilidade da rede torna-se um desafio, uma vez que o aumento do número de dispositivos finais pode intensificar interferências e colisões entre transmissões simultâneas (JOUHARI et al., 2023).

## Frase pronta para usar na fundamentação teórica

Segundo Jouhari et al. (2023), LoRa corresponde à camada física da pilha de comunicação, enquanto LoRaWAN atua na camada MAC, organizando a comunicação entre dispositivos finais, gateways e servidores de rede. Essa arquitetura permite aplicações de longo alcance e baixo consumo, mas apresenta limitações quando muitos dispositivos compartilham o mesmo meio de transmissão.

## Frase pronta para usar na justificativa

A avaliação da escalabilidade é necessária porque redes LoRaWAN aplicadas a cenários com muitos dispositivos podem sofrer degradação de desempenho devido a interferências, colisões e limitações do mecanismo de acesso ao meio. Jouhari et al. (2023) destacam que a demanda crescente por conectividade em Massive IoT torna a escalabilidade um dos principais desafios para o desenvolvimento de redes LoRaWAN.

## Frase pronta para usar em trabalhos relacionados

Jouhari et al. (2023) apresentam uma revisão abrangente sobre os desafios de escalabilidade em redes LoRaWAN para Massive IoT, discutindo soluções relacionadas à atribuição de spreading factors, cancelamento de interferência, densificação de gateways, alocação de canais, mecanismos de MAC e uso de aprendizado de máquina. Diferentemente dessa revisão, a presente pesquisa avalia a escalabilidade de uma rede LoRaWAN em um cenário aplicado ao monitoramento de ovinos no Sertão Central, considerando situações de confinamento e pastagem.

## Principais conceitos retirados da fonte

### Massive IoT

Massive IoT representa cenários com grande quantidade de dispositivos conectados, normalmente transmitindo pequenos volumes de dados. A prioridade não é alta velocidade, mas sim conectar muitos dispositivos de forma eficiente.

### LPWAN

LPWAN significa Low-Power Wide-Area Network. São redes de longo alcance e baixo consumo energético, adequadas para dispositivos alimentados por bateria e aplicações que não exigem grande taxa de transmissão.

### LoRa

LoRa é a tecnologia de camada física, baseada em modulação Chirp Spread Spectrum. Ela permite comunicação de longo alcance, resistência a interferências e operação com baixo consumo energético.

### LoRaWAN

LoRaWAN é o protocolo de camada MAC que organiza a comunicação entre dispositivos finais, gateways e servidores de rede. A rede utiliza uma topologia estrela-de-estrelas.

### End Device

Dispositivo final da rede. No contexto do meu TCC, cada end device pode representar um ovino equipado com um dispositivo de monitoramento.

### Gateway

Equipamento responsável por receber as mensagens dos dispositivos finais e encaminhá-las ao servidor de rede. No meu TCC, será considerado um cenário com um gateway.

### Spreading Factor

Parâmetro da modulação LoRa que influencia alcance, tempo de transmissão e taxa de dados. Valores maiores aumentam o alcance e a sensibilidade, mas também aumentam o tempo no ar e o consumo de energia.

### ADR

Adaptive Data Rate. Mecanismo que ajusta parâmetros como taxa de dados, spreading factor e potência de transmissão para melhorar o desempenho da rede e reduzir consumo energético.

### Interferência

Ocorre quando transmissões se sobrepõem ou afetam a recepção de outras mensagens. Em redes densas, a interferência é um dos principais fatores que reduzem o desempenho.

### Colisão

Ocorre quando múltiplos dispositivos transmitem simultaneamente de forma que as mensagens não sejam recebidas corretamente pelo gateway.

### Densificação de gateways

Estratégia que consiste em aumentar o número de gateways para melhorar cobertura e capacidade. Apesar de ajudar, essa solução não resolve todos os problemas de escalabilidade.

## Soluções de escalabilidade discutidas no artigo

O artigo organiza soluções para melhorar a escalabilidade LoRaWAN em diferentes grupos:

1. **Atribuição de spreading factor**  
   Busca distribuir melhor os spreading factors entre os dispositivos para reduzir colisões e melhorar a capacidade da rede.

2. **Cancelamento de interferência**  
   Usa técnicas de processamento de sinal para tentar recuperar pacotes mesmo quando há transmissões sobrepostas.

3. **Densificação de gateways**  
   Aumenta a quantidade de gateways para melhorar cobertura e capacidade da rede.

4. **Alocação de janelas e canais**  
   Organiza melhor o uso dos canais e dos momentos de transmissão para reduzir colisões.

5. **Topologias além da estrela tradicional**  
   Avalia alternativas como comunicação multi-hop, relays e clustering.

6. **Carrier sensing**  
   Permite que dispositivos verifiquem se o canal está ocupado antes de transmitir, embora isso possa aumentar o consumo de energia.

7. **Slotted MAC**  
   Substitui ou adapta o acesso aleatório do tipo Aloha por esquemas baseados em intervalos de tempo.

8. **Aprendizado de máquina para MAC**  
   Usa técnicas de aprendizado para melhorar decisões de transmissão, alocação de recursos e redução de colisões.

## Importância para a minha metodologia

Esse artigo ajuda a justificar que a escalabilidade de LoRaWAN deve ser analisada considerando métricas de desempenho da rede, como entrega de pacotes, colisões, interferência, número de dispositivos e capacidade de comunicação.

No meu TCC, essa fonte ajuda a explicar por que será feita uma simulação variando o número de ovinos monitorados. Ao aumentar o número de dispositivos finais, a rede pode apresentar maior disputa pelo meio, mais colisões e perda de desempenho.

## Como posso diferenciar meu trabalho na banca

Se alguém perguntar por que meu trabalho é diferente de Jouhari et al. (2023), posso responder:

Jouhari et al. (2023) fazem uma revisão ampla sobre escalabilidade em redes LoRaWAN para Massive IoT, reunindo desafios e soluções propostas na literatura. Meu trabalho, por outro lado, aplica essa discussão a um cenário específico de monitoramento de ovinos no Sertão Central, avaliando por simulação o comportamento da rede em cenários de confinamento e pastagem.

## Relação com outras fontes do meu TCC

### Relação com Bor et al. (2016)

Bor et al. (2016) fazem uma análise mais clássica e experimental sobre a pergunta “redes LoRa escalam?”. Jouhari et al. (2023) amplia essa discussão ao revisar várias soluções recentes para escalabilidade LoRaWAN.

### Relação com Macedo et al. (2023)

Macedo et al. (2023) aplicam LoRaWAN ao contexto de pecuária inteligente, com confinamento e pastagem. Jouhari et al. (2023) oferece a base geral sobre escalabilidade LoRaWAN que ajuda a entender tecnicamente os desafios enfrentados nesse tipo de aplicação.

### Relação com Sarmento Neto et al. (2024)

Sarmento Neto et al. (2024) discutem limitações do ADR em cenários móveis. Jouhari et al. (2023) também aborda o ADR como mecanismo importante para desempenho e escalabilidade, mas em uma perspectiva mais ampla de revisão.

### Relação com LoRa Alliance (2020)

LoRa Alliance (2020) deve ser usada para especificações oficiais do protocolo LoRaWAN. Jouhari et al. (2023) deve ser usada para discussão acadêmica sobre desafios, limitações e soluções de escalabilidade.

## Palavras-chave úteis

- LoRaWAN
- LoRa
- LPWAN
- Massive IoT
- Escalabilidade
- Interferência
- Colisões
- Spreading Factor
- ADR
- Gateway
- End Device
- MAC Layer
- PHY Layer
- Duty Cycle
- Star-of-stars topology
- GW densification
- Carrier sensing
- Slotted MAC
- Interference cancellation
- Channel allocation
- Machine learning

## Classificação dentro da minha base

Pasta local:

`03_LoRaWAN_Escalabilidade`

Categoria:

Base teórica sobre escalabilidade LoRaWAN.

Importância:

Alta. Esta fonte complementa Bor et al. (2016) e oferece uma visão mais recente e ampla sobre os desafios e soluções de escalabilidade em redes LoRaWAN.
