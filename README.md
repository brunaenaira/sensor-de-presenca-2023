**Documentação do Projeto de Sensor de Presença com NodeMCU**

Bem-vindo à documentação do projeto de sensor de presença com NodeMCU! Este documento fornecerá todas as informações necessárias para entender o funcionamento e reproduzir esse projeto. Leia atentamente as seções a seguir para obter uma visão geral completa.

## Descrição do Funcionamento e Uso

O projeto de sensor de presença com NodeMCU é um sistema que detecta a presença de pessoas em um ambiente. Ele utiliza um sensor de presença para capturar o movimento e envia informações sobre a detecção para um servidor MQTT, permitindo o monitoramento e controle remoto.

Ao reproduzir esse projeto, você poderá configurar e personalizar a detecção de presença em diferentes ambientes, como residências, escritórios ou espaços públicos. O sistema fornece uma maneira eficiente e escalável de acompanhar a presença em tempo real e acionar ações com base nessa detecção.

## Software e Documentação de Código

O software desenvolvido para esse projeto é escrito em linguagem de programação C e utiliza a plataforma Arduino IDE 2.1.0. 

A documentação de código inclui informações sobre a estrutura do projeto, descrição das principais funções, configurações necessárias e exemplos de uso. Ela fornece todas as orientações necessárias para compilar, carregar e executar o software no NodeMCU.

## Descrição do Hardware Utilizado

O hardware utilizado neste projeto inclui os seguintes componentes:

- NodeMCU (ESP8266): Plataforma de desenvolvimento baseada em ESP8266, com suporte Wi-Fi integrado.
- Sensor de Presença: Sensor PIR (Passive Infrared) para detectar movimento no ambiente.
- Componentes Eletrônicos: Resistores, capacitores e fios necessários para a montagem e conexão dos componentes.

## Documentação das Interfaces, Protocolos e Módulos de Comunicação

O projeto utiliza as seguintes interfaces, protocolos e módulos de comunicação:

- Comunicação via Internet (TCP/IP): O NodeMCU se conecta a uma rede Wi-Fi para estabelecer a comunicação via Internet.
- Protocolo MQTT: O sistema utiliza o protocolo MQTT para enviar e receber mensagens entre o NodeMCU e um servidor MQTT (broker). Ele permite a publicação dos dados de detecção de presença e a subscrição para receber comandos ou outras informações.


## Conclusão

Essa documentação forneceu uma visão geral abrangente do projeto de sensor de presença com NodeMCU. Agora você possui as informações necessárias para reproduzir o projeto, desde  funcionamento básico até os detalhes do hardware e software utilizados.

Aproveite o desenvolvimento do seu próprio sistema de sensor de presença e desfrute dos recursos de comunicação e controle remoto via Internet oferecidos pela integração com o protocolo MQTT.
