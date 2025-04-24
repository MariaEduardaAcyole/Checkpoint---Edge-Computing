# IVRU COMPANY
### Check Point 1 - Edge Computing

![Badge Concluido](http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge)

## Índice

* [Início](#ivru-company)
* [Descrição do Projeto](#descrição-do-projeto)
* [Funcionalidades do Projeto](#funcionalidades-do-projeto)
* [Demonstração da Aplicação](#demonstração-da-aplicação)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Dependências](#dependências)
* [Como Reproduzir](#como-reproduzir)
* [Autores](#autores)
* [Licença](#licença)

## Descrição do Projeto

Este projeto foi desenvolvido para a **Vinheria Agnello**, com o objetivo de criar um sistema de monitoramento de luminosidade no ambiente onde os vinhos são armazenados. O sistema visa garantir que os vinhos permaneçam em condições ideais para sua conservação.

A solução utiliza **Arduino** para capturar dados de luminosidade (com um sensor LDR) e controlar a sinalização visual e sonora em caso de alertas.

## Funcionalidades do Projeto

- `📡 Leitura da Luminosidade`:
  - Utilização de um sensor LDR (Light Dependent Resistor) para captar a luz ambiente.
  - Conversão dos dados analógicos utilizando o ADC (Conversor Analógico-Digital) do Arduino.

- `📊 Classificação dos Níveis de Luminosidade`:
  - **OK**: Ambiente em condições ideais de luminosidade.
  - **Alerta**: Nível próximo do limite seguro.
  - **Perigo**: Nível fora do padrão adequado.

- `💡 Sistema de Sinalização Visual (LEDs)`:
  - **LED Verde**: Luminosidade dentro dos padrões ideais.
  - **LED Amarelo**: Nível de alerta.
  - **LED Vermelho**: Nível de perigo.

- `🔊 Sistema de Alarme Sonoro`:
  - Acionamento de um buzzer sempre que a luminosidade estiver em nível de alerta.
  - O alarme soa por 3 segundos e continua sendo acionado caso a condição persista.

- `⏱️ Monitoramento em Tempo Real`:
  - O sistema realiza a leitura e verificação contínua dos dados.
  - Resposta imediata a alterações na luminosidade para garantir a preservação ideal dos vinhos.

## Demonstração da Aplicação

[![Video da prática](https://img.youtube.com/vi/bMINbjy88VI/0.jpg)](https://www.youtube.com/watch?v=bMINbjy88VI)

## Tecnologias Utilizadas

<p align="center">
  <img src="https://img.shields.io/static/v1?label=&message=ARDUINO&color=blue&style=for-the-badge&logo=ARDUINO"/>
</p>

- **Arduino IDE**
- **Sensor LDR (Light Dependent Resistor)**
- **LEDs (Verde, Amarelo, Vermelho)**
- **Buzzer**
- **Placa Arduino** (modelo a ser especificado, por exemplo: Arduino Uno)

## Dependências

Para rodar este projeto, você precisará de:

- **Arduino IDE**: Para programar a placa Arduino.
- **Bibliotecas do Arduino**:

Além disso, você precisará do hardware adequado:

- **Placa Arduino** (por exemplo, Arduino Uno)
- **Sensor LDR**
- **LEDs** (Verde, Amarelo, Vermelho)
- **Buzzer**
- **Resistores** para o circuito

## Como Reproduzir

### 1. **Montagem do Circuito**:
   - Conecte o **sensor LDR** a uma entrada analógica no Arduino.
   - Conecte os **LEDs** (verde, amarelo e vermelho) às saídas digitais no Arduino.
   - Conecte o **buzzer** à saída digital.

### 2. **Carregando o Código**:
   - Abra o **Arduino IDE**.
   - Baixe ou copie o código-fonte do projeto.
   - Selecione a placa correta (ex: Arduino Uno) e a porta.
   - Clique em "Upload" para carregar o código na sua placa.

### 3. **Testando o Sistema**:
   - Após carregar o código, o Arduino começará a monitorar a luminosidade e acionar os LEDs conforme a intensidade da luz.
   - O buzzer será acionado caso a luminosidade entre no nível de alerta.

## Autores

- [Maria Eduarda Sousa Acyole de Oliveira `566337`](https://github.com/MariaEduardaAcyole)
- [Matheus Goes da Silva `566407`](https://github.com/Goes1404)
- [Arthur Marcio de Barros Silva `563359`](https://github.com/TutuMbs)
- [Gabriela Abdelnor Tavares `562291`](https://github.com/GabihAbdTavares)

## Licença

Copyright :copyright: 2025 - Sistema de Monitoramento de Luminosidade para Adega – Vinheria Agnello

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
