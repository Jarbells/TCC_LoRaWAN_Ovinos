# Fichamento - LoRa Alliance (2020)

## Referência

LORA ALLIANCE. *TS001-1.0.4 LoRaWAN® L2 1.0.4 Specification*. Fremont: LoRa Alliance, 2020.

## Tipo de fonte

Especificação técnica oficial.

## Tema central da fonte

O documento apresenta a especificação oficial do protocolo LoRaWAN L2 versão 1.0.4. Ele descreve o funcionamento da camada LoRaWAN, incluindo arquitetura da rede, classes de dispositivos, formatos de pacotes e quadros, comandos MAC, janelas de recepção, ativação dos dispositivos, ADR, retransmissões e modos de operação das classes A, B e C.

## Para que essa fonte serve no meu TCC?

Essa fonte serve como referência técnica oficial para explicar o funcionamento do protocolo LoRaWAN.

No meu TCC, ela deve ser usada quando eu precisar definir conceitos do próprio padrão LoRaWAN, como:

- end-device;
- gateway;
- Network Server;
- topologia estrela-de-estrelas;
- comunicação uplink e downlink;
- classes A, B e C;
- janelas de recepção RX1 e RX2;
- ADR;
- comandos MAC;
- OTAA e ABP;
- duty cycle;
- retransmissões.

Essa fonte não serve para discutir diretamente ovinos, pecuária inteligente ou simulação, mas é essencial para fundamentar tecnicamente o protocolo usado no trabalho.

## Ideia principal

A especificação da LoRa Alliance (2020) descreve o protocolo LoRaWAN como uma rede otimizada para dispositivos alimentados por bateria, podendo estes estar fixos ou em movimento. A rede é normalmente organizada em topologia estrela-de-estrelas, na qual os gateways retransmitem mensagens entre os dispositivos finais e o servidor de rede.

O documento também define que a comunicação entre dispositivos finais e gateways ocorre por rádiofrequência em salto único, enquanto os gateways se conectam ao servidor de rede por conexões IP. A comunicação é bidirecional, mas o tráfego predominante esperado é o uplink, isto é, dos dispositivos finais para a rede.

## O que posso citar com segurança?

- LoRaWAN é um protocolo de rede otimizado para dispositivos finais alimentados por bateria.
- Os dispositivos finais podem ser móveis ou fixos.
- Redes LoRaWAN são normalmente organizadas em topologia estrela-de-estrelas.
- Gateways retransmitem mensagens entre dispositivos finais e o Network Server.
- Dispositivos finais usam comunicação de rádiofrequência de salto único com um ou mais gateways.
- Gateways se conectam ao Network Server por conexões IP.
- A comunicação é geralmente bidirecional.
- O tráfego predominante esperado é o uplink, ou seja, dos dispositivos finais para o servidor de rede.
- A seleção da taxa de dados envolve um compromisso entre alcance de comunicação e duração da transmissão.
- A infraestrutura LoRaWAN pode gerenciar taxa de dados e potência de transmissão por meio do ADR.
- Todos os dispositivos LoRaWAN devem implementar pelo menos a Classe A.
- Dispositivos Classe A abrem duas janelas curtas de recepção após cada transmissão uplink.
- Dispositivos Classe B possuem janelas adicionais de recepção em horários programados.
- Dispositivos Classe C mantêm janelas de recepção quase continuamente abertas, consumindo mais energia.
- OTAA e ABP são os dois modos de ativação de dispositivos em uma rede LoRaWAN.
- O ADR pode aumentar a vida útil da bateria e maximizar a capacidade da rede, mas pode não ser adequado quando o canal muda rapidamente.

## Onde essa fonte entra no meu TCC?

Esta fonte pode ser usada principalmente em três partes:

1. **Fundamentação teórica**  
   Para explicar oficialmente o que é LoRaWAN, como a rede é organizada, quais são os componentes da arquitetura e como funcionam as classes de dispositivos.

2. **Metodologia**  
   Para justificar decisões de simulação relacionadas à presença de end-devices, gateway, tráfego uplink, ADR e classe dos dispositivos.

3. **Introdução**  
   De forma mais breve, para apresentar LoRaWAN como tecnologia de comunicação de longo alcance e baixo consumo adequada a dispositivos de IoT.

## Relação com o meu TCC

A especificação LoRa Alliance (2020) está relacionada ao meu TCC porque o meu trabalho pretende analisar a escalabilidade de uma rede LoRaWAN aplicada ao monitoramento de ovinos.

Como meu estudo usa LoRaWAN como tecnologia de comunicação, preciso de uma fonte oficial para definir corretamente a arquitetura da rede, os componentes envolvidos e os mecanismos básicos do protocolo.

No meu caso, cada ovino monitorado pode ser representado na simulação como um end-device. Esses dispositivos enviam dados periodicamente para um gateway, que representa o ponto de recepção da rede. Esse modelo está alinhado com a arquitetura LoRaWAN descrita pela LoRa Alliance.

## Diferença entre a LoRa Alliance (2020) e os artigos científicos do meu TCC

A LoRa Alliance (2020) não é um estudo experimental nem uma revisão acadêmica. Ela é uma especificação técnica oficial.

Por isso, ela deve ser usada para definir o funcionamento do protocolo LoRaWAN, e não para provar resultados de desempenho.

Para falar de desempenho, escalabilidade, colisões, interferência e simulação, devo usar fontes como:

- Bor et al. (2016);
- Jouhari et al. (2023);
- Macedo et al. (2023);
- Sarmento Neto et al. (2024).

A LoRa Alliance (2020) responde à pergunta:

> Como o protocolo LoRaWAN é oficialmente definido?

Meu TCC busca responder:

> Como uma rede LoRaWAN se comporta, em termos de escalabilidade, quando vários ovinos são monitorados em cenários de confinamento e pastagem no Sertão Central?

## Limites da fonte

Esta fonte não deve ser usada para afirmar que LoRaWAN é escalável em qualquer cenário.

Também não deve ser usada para afirmar que LoRaWAN é ideal para ovinos, pecuária ou Sertão Central.

A especificação deve ser usada para conceitos oficiais do protocolo, não para conclusões de desempenho.

Para discutir limitações de escalabilidade, devo usar artigos científicos. Para dizer como o protocolo funciona oficialmente, devo usar a LoRa Alliance.

## Cuidado ao citar

Não escrever:

> A LoRa Alliance (2020) demonstrou que LoRaWAN é escalável para monitoramento de ovinos.

Isso estaria errado, porque a especificação não fez esse experimento.

O correto é escrever:

> Segundo a LoRa Alliance (2020), redes LoRaWAN são normalmente organizadas em topologia estrela-de-estrelas, na qual gateways retransmitem mensagens entre dispositivos finais e o servidor de rede.

Ou:

> A especificação LoRaWAN define que a infraestrutura da rede pode gerenciar taxa de dados e potência de transmissão dos dispositivos por meio do mecanismo ADR (LORA ALLIANCE, 2020).

## Frase pronta para usar na fundamentação teórica

Segundo a LoRa Alliance (2020), redes LoRaWAN são normalmente organizadas em topologia estrela-de-estrelas, na qual os gateways retransmitem as transmissões entre os dispositivos finais e o Network Server. Os dispositivos finais utilizam comunicação de rádiofrequência de salto único com um ou mais gateways, enquanto os gateways se conectam ao servidor de rede por meio de conexões IP.

## Frase pronta para usar na introdução

LoRaWAN é um protocolo de rede voltado a dispositivos de baixo consumo energético, geralmente alimentados por bateria, podendo ser aplicado a dispositivos fixos ou móveis. Sua arquitetura utiliza gateways para retransmitir os dados enviados pelos dispositivos finais ao servidor de rede, sendo o tráfego uplink predominante nesse tipo de comunicação (LORA ALLIANCE, 2020).

## Frase pronta para usar na metodologia

No modelo considerado neste trabalho, os dispositivos associados aos ovinos são representados como end-devices LoRaWAN, responsáveis pelo envio periódico de dados ao gateway. Essa estrutura segue a arquitetura descrita pela LoRa Alliance (2020), na qual dispositivos finais se comunicam por rádiofrequência com um ou mais gateways, que retransmitem as mensagens ao servidor de rede.

## Frase pronta sobre ADR

A especificação LoRaWAN define que a infraestrutura da rede pode gerenciar individualmente a taxa de dados e a potência de transmissão dos dispositivos por meio do mecanismo ADR, com o objetivo de aumentar a vida útil da bateria e maximizar a capacidade da rede (LORA ALLIANCE, 2020).

## Principais conceitos retirados da fonte

### LoRaWAN

Protocolo de rede voltado a aplicações de baixo consumo energético e longo alcance, estruturado para comunicação entre dispositivos finais, gateways e servidores de rede.

### End-device

Dispositivo final da rede. No meu TCC, cada end-device pode representar um ovino equipado com um dispositivo de monitoramento.

### Gateway

Equipamento que recebe transmissões dos dispositivos finais e as retransmite ao Network Server. Também pode ser chamado de concentrador, roteador, ponto de acesso ou estação-base.

### Network Server

Servidor responsável por gerenciar a rede LoRaWAN, receber dados encaminhados pelos gateways e coordenar aspectos da comunicação.

### Topologia estrela-de-estrelas

Estrutura em que os dispositivos finais não se comunicam diretamente entre si. Eles transmitem dados para um ou mais gateways, que encaminham as mensagens ao servidor de rede.

### Uplink

Comunicação enviada do dispositivo final para a rede. No contexto do meu TCC, é o envio dos dados de monitoramento dos ovinos para o gateway.

### Downlink

Comunicação enviada da rede para o dispositivo final. Pode ser usada para comandos, configurações ou respostas.

### Classe A

Classe básica obrigatória em todos os dispositivos LoRaWAN. Após cada transmissão uplink, o dispositivo abre duas janelas curtas de recepção para possíveis mensagens downlink. É a classe de menor consumo energético.

### Classe B

Classe que adiciona janelas de recepção programadas, sincronizadas por beacons enviados pelos gateways. Permite que a rede saiba em quais momentos o dispositivo estará escutando.

### Classe C

Classe em que o dispositivo mantém a recepção quase continuamente aberta, fechando apenas durante transmissões. Possui menor latência, mas maior consumo de energia.

### ADR

Adaptive Data Rate. Mecanismo que permite ajustar parâmetros como taxa de dados e potência de transmissão. O objetivo é melhorar o uso da rede, economizar energia e maximizar a capacidade.

### RX1 e RX2

Janelas de recepção abertas após uma transmissão uplink. Se o dispositivo não recebe uma mensagem destinada a ele em RX1, ele abre RX2.

### OTAA

Over-the-Air Activation. Processo de ativação em que o dispositivo realiza um procedimento de entrada na rede antes de participar da comunicação.

### ABP

Activation By Personalization. Processo em que o dispositivo já é configurado previamente com as informações necessárias para participar de uma rede LoRaWAN específica.

### Duty cycle

Limitação relacionada ao tempo de transmissão permitido em determinada faixa de frequência, conforme regulações locais e regras da rede.

## Importância para a minha metodologia

Essa fonte ajuda a manter a metodologia tecnicamente correta.

Quando eu disser que os ovinos serão representados como dispositivos finais LoRaWAN, que esses dispositivos enviarão dados ao gateway, que o tráfego será predominantemente uplink ou que o ADR será considerado na simulação, a especificação da LoRa Alliance será a base oficial.

Ela também ajuda a evitar erros conceituais, como confundir LoRa com LoRaWAN ou afirmar que os dispositivos finais se comunicam diretamente entre si na arquitetura padrão.

## Como posso diferenciar essa fonte na banca

Se alguém perguntar por que usei a LoRa Alliance (2020), posso responder:

Usei a especificação da LoRa Alliance porque ela é a fonte oficial do protocolo LoRaWAN. Ela não é usada para provar desempenho da rede, mas para definir corretamente a arquitetura, os componentes e os mecanismos do protocolo, como end-devices, gateways, Network Server, classes de dispositivos, janelas de recepção e ADR.

## Relação com outras fontes do meu TCC

### Relação com Bor et al. (2016)

Bor et al. (2016) ajudam a discutir se redes LoRa conseguem escalar. A LoRa Alliance (2020) define oficialmente o funcionamento do protocolo LoRaWAN.

### Relação com Jouhari et al. (2023)

Jouhari et al. (2023) revisam desafios e soluções de escalabilidade em LoRaWAN. A LoRa Alliance (2020) fornece a base oficial do protocolo usado nessas discussões.

### Relação com Macedo et al. (2023)

Macedo et al. (2023) aplicam LoRaWAN à pecuária inteligente por simulação. A LoRa Alliance (2020) ajuda a fundamentar os conceitos técnicos da rede usados nesse tipo de estudo.

### Relação com Sarmento Neto et al. (2024)

Sarmento Neto et al. (2024) discutem limitações do ADR em cenários móveis. A LoRa Alliance (2020) define o funcionamento oficial do ADR dentro do protocolo LoRaWAN.

## Palavras-chave úteis

- LoRaWAN
- LoRa Alliance
- Especificação técnica
- End-device
- Gateway
- Network Server
- Star-of-stars topology
- Uplink
- Downlink
- ADR
- Adaptive Data Rate
- Class A
- Class B
- Class C
- RX1
- RX2
- OTAA
- ABP
- MAC commands
- Duty cycle
- Data rate
- TX power

## Classificação dentro da minha base

Pasta local:

`06_Especificacoes_Tecnicas`

Categoria:

Especificação oficial do protocolo LoRaWAN.

Importância:

Alta. Esta fonte deve ser usada como base oficial para conceitos técnicos do protocolo, mas não como fonte principal para resultados de desempenho ou escalabilidade.
