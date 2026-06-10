# OrbitEye – Sistema Inteligente de Monitoramento Ambiental

## Sobre o Projeto

O **OrbitEye** é uma solução tecnológica desenvolvida para auxiliar no monitoramento ambiental de áreas de risco, utilizando conceitos de Internet das Coisas (IoT), sensores inteligentes e sistemas de alerta.

Inspirado em tecnologias utilizadas por satélites de observação da Terra, o projeto busca identificar condições ambientais que possam indicar riscos de queimadas, secas e outros eventos climáticos extremos, permitindo ações preventivas e contribuindo para a preservação do meio ambiente.


## Problema

Desastres ambientais causam impactos significativos na sociedade e no meio ambiente. Muitas vezes, a identificação desses riscos ocorre de forma tardia, dificultando a tomada de decisões e aumentando os prejuízos.

A falta de monitoramento contínuo e acessível torna mais difícil prevenir situações críticas em áreas vulneráveis.


## Solução

O OrbitEye utiliza sensores para coletar dados ambientais em tempo real, monitorando fatores que podem indicar condições de risco.

Quando valores críticos são detectados, o sistema emite alertas visuais e sonoros para facilitar a rápida identificação do problema.


## Componentes Utilizados

* Arduino Uno
* Sensor de Temperatura e Umidade (DHT11)
* Sensor de Luminosidade (LDR)
* LEDs (Verde, Amarelo e Vermelho)
* Buzzer
* Resistores
* Protoboard
* Jumpers


## Funcionamento

O sistema realiza a leitura contínua dos sensores:

### Situação Normal

* Temperatura e luminosidade dentro dos limites seguros.
* LED verde aceso.
* Nenhum alerta é emitido.

### Situação de Atenção

* Valores próximos de condições de risco.
* LED amarelo aceso.
* Monitoramento intensificado.

### Situação de Risco

* Temperatura elevada e ambiente muito seco.
* LED vermelho aceso.
* Buzzer ativado.
* Alerta exibido no LCD.


## Tecnologias Utilizadas

* Linguagem C++
* Arduino IDE
* Tinkercad
* Git e GitHub


## Benefícios

* Monitoramento ambiental em tempo real.
* Identificação precoce de situações de risco.
* Apoio à preservação ambiental.
* Conscientização sobre sustentabilidade.
* Possibilidade de expansão para aplicações reais em larga escala.


## Objetivos do Projeto

* Monitorar condições ambientais continuamente.
* Auxiliar na prevenção de desastres ambientais.
* Fornecer alertas rápidos para situações críticas.
* Demonstrar a aplicação prática de tecnologias IoT.
* Incentivar o uso da tecnologia em prol da sustentabilidade.


## Integrantes:
Isadora Bradac Canovas RM - 569585
Kaua Miranda RM - 569473
Murilo Araujo RM - 573517

Projeto desenvolvido para a **Global Solution FIAP 2026**.

**Equipe OrbitEye** 

Este projeto foi desenvolvido exclusivamente para fins acadêmicos e educacionais.
