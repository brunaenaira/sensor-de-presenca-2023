**Documentação do Projeto de Sensor de Presença com NodeMCU**

Bem-vindo à documentação do projeto de sensor de presença com NodeMCU! Este documento fornecerá todas as informações necessárias para entender o funcionamento e reproduzir esse projeto. Leia atentamente as seções a seguir para obter uma visão geral completa.

## Descrição do Funcionamento e Uso

O projeto de sensor de presença com NodeMCU é um sistema que detecta a presença de pessoas em um ambiente. Ele utiliza um sensor de presença para capturar o movimento e envia informações sobre a detecção para um servidor MQTT, permitindo o monitoramento e controle remoto.

Ao reproduzir esse projeto, você poderá configurar e personalizar a detecção de presença em diferentes ambientes, como residências, escritórios ou espaços públicos. O sistema fornece uma maneira eficiente e escalável de acompanhar a presença em tempo real e acionar ações com base nessa detecção.

Execução do sensor de movimento NodeMCU com comunicação MQTT. Ele inicia conectando-se ao servidor MQTT, configura os tópicos de publicação e inscrição e, em seguida, entra em um loop de leitura do estado do sensor de movimento.

Se o movimento for detectado, o sensor envia uma mensagem MQTT para o servidor e aguarda uma confirmação. Além disso, o NodeMCU também aguarda e recebe mensagens MQTT do servidor. Quando uma mensagem é recebida, ela é processada e uma ação correspondente é executada, se necessário. Em seguida, o fluxo volta à leitura do estado do sensor para repetir o ciclo.


## Software e Documentação de Código

O software desenvolvido para esse projeto é escrito em linguagem de programação C e utiliza a plataforma Arduino IDE 2.1.0. 

## Descrição do Hardware Utilizado

O hardware utilizado neste projeto inclui os seguintes componentes:

- NodeMCU (ESP8266): Plataforma de desenvolvimento baseada em ESP8266, com suporte Wi-Fi integrado.
- Sensor de Presença: Sensor PIR (Passive Infrared) para detectar movimento no ambiente.
- Componentes Eletrônicos: Resistores, jumpers, buzzer, protoboard, capacitores e fios necessários para a montagem e conexão dos componentes.
-	Conversor USB-Serial: O NodeMCU tem um conversor USB-Serial integrado, que permite que o microcontrolador seja programado e se comunique com um computador através de uma porta USB.
-Regulador de tensão: O NodeMCU tem um regulador de tensão integrado que converte a tensão de entrada para a tensão de operação do microcontrolador.
-Conector de alimentação: O NodeMCU possui um conector de alimentação que pode ser usado para alimentar a placa com uma fonte de energia externa.
-LED de status: O NodeMCU tem um LED integrado que pode ser programado para indicar o status do sistema.
-Antena Wi-Fi: O NodeMCU tem uma antena Wi-Fi integrada para fornecer conectividade sem fio.
-GPIO: O NodeMCU possui pinos GPIO (General Purpose Input/Output) que podem ser usados para conectar sensores, atuadores e outros componentes eletrônicos.
-Memória flash: O NodeMCU possui uma memória flash integrada que pode ser usada para armazenar o código do programa e outros dados.


## Documentação das Interfaces, Protocolos e Módulos de Comunicação

O projeto utiliza as seguintes interfaces, protocolos e módulos de comunicação:

- Comunicação via Internet (TCP/IP): O NodeMCU se conecta a uma rede Wi-Fi para estabelecer a comunicação via Internet.
- Protocolo MQTT: O sistema utiliza o protocolo MQTT para enviar e receber mensagens entre o NodeMCU e um servidor MQTT (broker). Ele permite a publicação dos dados de detecção de presença e a subscrição para receber comandos ou outras informações.


## Conclusão

Essa documentação forneceu uma visão geral abrangente do projeto de sensor de presença com NodeMCU. Agora você possui as informações necessárias para reproduzir o projeto, desde  funcionamento básico até os detalhes do hardware e software utilizados.

Aproveite o desenvolvimento do seu próprio sistema de sensor de presença e desfrute dos recursos de comunicação e controle remoto via Internet oferecidos pela integração com o protocolo MQTT.
