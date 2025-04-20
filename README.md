# IVRU COMPANY
### Check Point 1 - Edge Computing

(LOGO)

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
![Badge Concluido](http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge)

# Índice

* [Início](#ivru-company)
* [Descrição do Projeto](#descrição-do-projeto)
* [Funcionalidades do Projeto](#hammer-funcionalidades-do-projeto)
* [Demonstração da Aplicação](#demonstração-da-aplicação)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Autores](#autores)
* [Licença](#licença)


# Descrição do Projeto 

**O caso** apresenta uma Vinheria 
tradicional, que opera como loja 
física, e que está demandando o 
desenvolvimento de um portal de e
commerce, para começar a vender 
também na Internet, mas com uma 
exigência básica: que a loja virtual 
consiga criar uma experiência do 
usuário similar à do atendimento 
presencial em sua loja física.

**O projeto**
Fomos contratados pela Vinheria Agnello para desenvolver um sistema de monitoramento a ser instalado 
no ambiente em que os vinhos são armazenados. O dono da Vinheria informou que a qualidade do vinho é 
influenciada diretamente pelas condições de *temperatura, umidade e luminosidade do ambiente*. Neste 
primeiro momento, você propôs ao dono da Vinheria um projeto em etapas, de modo que seu 1° desafio é:
- Elaborar um sistema usando Arduino que faça a captura das informações de luminosidade do ambiente.  Para 
isso pesquise sobre o LDR e sobre conversores analógico para digital do Arduino. Verifique como eles 
funcionam e como poderiam ser usados no projeto.

- De posse dos dados coletados, implemente um sistema de alarme, utilizando LEDs, para sinalizar quando o a 
ambiente estiver OK, ou quando alguma grandeza estiver fora dos limites estipulados.  Use um LED verde 
para indicar que está OK, um LED amarelo para indica que está em níveis de alerta e um LED Vermelho para 
indicar que tem algum problema.

- Quando a luminosidade estiver em nível de alerta, deve soar uma buzina (buzzer) por 3 segundos. A buzina 
volta a soar caso a luminosidade permaneça em nível de alerta.


# :hammer: Funcionalidades do projeto

- `📡 Leitura da Luminosidade`:
  - Utilização de um sensor LDR (Light Dependent Resistor) para captar a luz ambiente.
  - Conversão dos dados analógicos utilizando o ADC (Conversor Analógico-Digital) do Arduino.
- `📊 Classificação dos Níveis de Luminosidade`:
  - OK: Ambiente em condições ideais de luminosidade.
  - Alerta: Nível próximo do limite seguro.
  - Perigo: Nível fora do padrão adequado.
- `💡 Sistema de Sinalização Visual (LEDs)`:
  -LED Verde: Luminosidade dentro dos padrões ideais.
  - LED Amarelo: Nível de alerta.
  - LED Vermelho: Nível de perigo.
- `🔊 Sistema de Alarme Sonoro`: descrição da funcionalidade 3
  - -Acionamento de um buzzer sempre que a luminosidade estiver em nível de alerta.
  - O alarme soa por 3 segundos e continua sendo acionado caso a condição persista.

- `⏱️ Monitoramento em Tempo Real`:
  - O sistema realiza a leitura e verificação contínua dos dados.
  - Resposta imediata a alterações na luminosidade para garantir a preservação ideal dos vinhos.

#  Demonstração da Aplicação

# Tecnologias utilizadas
<p align="center">
  <img src="https://img.shields.io/static/v1?label=&message=ARDUINO&color=blue&style=for-the-badge&logo=ARDUINO"/>
</p>

# Autores

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/37356058?v=4" width=115><br><sub>Camila Fernanda Alves</sub>](https://github.com/camilafernanda) |  [<img loading="lazy" src="https://avatars.githubusercontent.com/u/30351153?v=4" width=115><br><sub>Guilherme Lima</sub>](https://github.com/guilhermeonrails) |  [<img loading="lazy" src="https://avatars.githubusercontent.com/u/8989346?v=4" width=115><br><sub>Alex Felipe</sub>](https://github.com/alexfelipe) |
| :---: | :---: | :---: |

# Licença

Copyright :copyright: 2025 - Sistema de Monitoramento de Luminosidade para Adega – Vinheria Agnello 
