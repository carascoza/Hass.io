# Hass.io
 Ambiente de Automação residencial, Introdução ao Home Assistant (Hass.io)
---
Title: Ambeinte de Automação residencial, Introdução ao Home Assistant (Hass.io)
Description: Repositórios de scripts para Home Assistant e integrações.
Author: Carascoza
Date: 20/08/2024
---

# Tutorial: Introdução ao Home Assistant

>[!IMPORTANT]
> :construction: Projeto em construção :construction:

## Tabela dos repositórios arquivos e scripts de configuração 

| Ambiente              | Descrição                     | Link                                                       |
|:-----------           |    :---------:                |:----                                                       |
| configuration	        | arquivo base de configuração  |[configuration](./Home_Assistant/config/configuration.yaml) |
| HA                    | Comandos HA Supervisor        |[HA](./HA/HA_comandos.md)                                   |

## Integrando tudo.

Home Assistant é um software de código aberto, grátis e que pode ser executado em um Raspberry Pi, em um computador ou em um conteiner Docker. Sua principal função é integrar tudo. Ele permite que diferentes dispositivos, de diferentes marcas, conversem e reajam juntos, conforme regras definidas pelo usuário.

Pode ser acessado via web ou por aplicativo. É uma solução bem completa de automação, identificando desde o status dos dispositivos até se a pessoa está andando ou dirigindo (rastreando o celular). Permite ser totalmente personalizado, ajustando-se cada item da interface de controle.

## Dispositivos de hospedagem

### Raspberry Pi

O Raspberry Pi é um computador do tamanho de um cartão de crédito e baixíssimo consumo energético. Pode ficar ligado 24 horas por dia e não impactar praticamente nada na conta de luz. A partir da versão 3 já é capaz de rodar uma instância do Home Assistant sem maiores problemas.

Caso opte por usar um Raspberry Pi, recomendo que use um dedicado ao Home Assistant. Basta baixar a imagem do sistema operacional já pronta no site, salvar em um cartão SD e ligar. Tudo estará preparado para ser usado.

### Computador
O Home Assistant pode funcionar em um computador, como se fosse um programa comum. A grande vantagem deste método é que computador, em geral, têm desempenho mais que suficiente para rodar uma instância de Home Assistant. A desvantagem é o volume do equipamento e, dependendo do caso, o consumo energético. No caso de computadores, geralmente não há problema em dar outros usos para máquina, não precisando mantê-la exclusivamente para o Home Assistant.

### Conteiner Docker
A maneira mais avançada. A única desvantagem é que exige alguns conhecimentos técnicos mais específicos. Porém, permite melhor uso dos recursos computacionais, facilitando o uso compartilhado da máquina.

## Instalação
Para garantir sempre uma instalação usando-se os recursos mais atualizados, recomendo sempre seguir o site oficial.

https://www.home-assistant.io/installation/

Selecione o tipo de instalação e siga os passos descritos no site.

## Glossário
Termos importantes:

- `Hass:`: Abreviação de Home Assistant. É o software em si.

- `Home Assistant Supervisor:`: Parte responsável pelo controle do Hass. Sua instalação não é obrigatória, mas facilita muito para iniciantes.

- `Hass.io:`: Home Assistant somando ao Supervisor. É a solução pronta, que já contém os addons a um clique de distância.

- `Addons:`: Programas auxiliares ao Hass. Podem ser instalados também separadamente, sem usar a opção de addons. São exemplos: NodeRed e Mosquitto (MQTT).

- `HassOS:`: Sistema operacional. É baixada uma imagem já completa, com o Hass e o Hass.io prontos.

- `Home Assistant Core:`: Home Assistant que usa ambiente virtual Python.

- `MQTT:`: Protocolo de mensagens muito útil para troca de informações entre dispositivos. A comunicação acontece entre um cliente e um broker.

- `Broker MQTT:`: Pode ser entendido como um mural de avisos. É a parte responsável por receber as mensagens e deixá-las disponíveis para os demais dispositivos. Geralmente usa-se um software chamado Mosquitto.

- `Cliente MQTT:`: Dispositivo que lê e escreve no broker. São exemplos de clientes lâmpadas, fechaduras, sensores etc.

- `NodeRed:`: Software de desenvolvimento baseada em fluxos. Facilita a criação de automações e pode facilmente ser integrado ao Hass.


## Sites e Referências Home Assistant

[Documentação Home Assintant.io](https://www.home-assistant.io/)

[Fórum Home Assistant Brasil](https://homeassistantbrasil.com.br/)

