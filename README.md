# Global Solution- Edge Computing ⚠️🌊
**Projeto: RiscoZero- Prevenção de rumptura de barragens ou prevenção de enchentes**

Este repositório contém o projeto desenvolvido para a Global Solution da disciplina *Edge Computing & Computer Systems* (FIAP - 2025). Trata-se de um sistema fisico montado com o Arduino UNO, focado no monitoramento das ruas em esatdos de grandes chuvas, barragens ou rios para casas ribeirinhas. Com o objetivo de previnir enchentes e desastres para com que a população consiga se preparar antes da água devastar 

---

## 🧩 Descrição do Desafio

Os desastres naturais desolam muitas pessoas em todo o mundo dado à este fato. Nosso desafio foi propor um sistema capaz de detectar condições ambientais inadequadas —**enchentes e desastres naturais**.

### Funcionalidades implementadas:

- Leitura do nível de distância da água com o Sensor de Distância;
- LEDs sinalizadores:
  - ✅ **Verde:** Níveis Ok;
  - ⚠️ **Amarelo:** Níveis Baixos;
  - ❌ **Vermelho:** Níveis MUITO ALTOS;
- Acionamento de buzzer quando houver alerta;

---

## 💡 Solução Técnica

O sistema foi **montado fisicamente** e também **simulado no Tinkercad**.

### 🔗 Simulação no Tinkercad

[Acesse o projeto clicando aqui](https://www.tinkercad.com/things/3vZDoUHcMat-gs-edge?sharecode=yStle8PU2NE4QmbFfadTpBKP9gtjjngHrMNJ6UOLQEk)

### 🖼️ Imagem da simulação no Tinkercad

> [image](https://github.com/user-attachments/assets/f7cc73ba-a4de-4be5-9908-9cffdcae1e93)

### 🎬 Vídeo Explicativo
> [clique aqui para acessar o vídeo](https://www.youtube.com/watch?v=yIJOSYBAGL0)


## 🔧 Componentes Utilizados

- 1 × **Arduino Uno R3**  
- 1 × **Sensor de Distância**
- 3 × **Resistor de 220 Ω** (`Colocados nos LEDs`) 
- 3 × **LEDs**:
  - 1 × Vermelho 
  - 1 × Verde 
  - 1 × Amarelo  
- 1 × **Buzzer Piezoelétrico**   
- Cabos Jumpers  
- 1 × Protoboard

---

## 🛠️ Montagem do Circuito (Resumo)

- **Sensor de Distância**: leitura feita nos pinos digitais 4 e 5;
- **LEDs**: conectados aos pinos digitais:
  - Verde → pino 13
  - Amarelo → pino 12
  - Vermelho → pino 11
- **Buzzer**: conectado ao pino digital 10;
- Resistores de 220 Ω conectados em série com cada LED;
- GND e 5V do Arduino distribuídos nos trilhos laterais da protoboard.

---

## 💾 Execução do Projeto

1. Monte o circuito conforme o esquema elétrico;
2. Faça o upload do código na placa usando a IDE do Arduino;
3. Ajuste a distância manualmente (ou use o controle do Tinkercad) para testar os diferentes comportamentos do sistema;
4. Observe os sinais visuais (LEDs) e sonoros (buzzer) em tempo real.

---

## 👥 Integrantes do Grupo

- **Julia Pompeu** – 561955
- **Giovana Rosatti Parreira** - 562275
