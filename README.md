# 🌙 LUNA CORE — Edge Computing para Ambientes Espaciais

## 📌 Descrição do Projeto
O LUNA CORE é um sistema embarcado baseado em Arduino que simula um módulo de monitoramento autônomo para ambientes extremos como bases lunares ou marcianas. O sistema utiliza Edge Computing para tomar decisões localmente sem depender de comunicação externa.

---

## 🎯 Objetivo da Solução
Criar um sistema inteligente capaz de monitorar temperatura, gases e presença, reagindo em tempo real para garantir segurança em ambientes críticos.

---

## 🔧 Componentes Utilizados
- Arduino Uno  
- Sensor DHT22 (temperatura)  
- Sensor MQ2 (gás/fumaça)  
- Sensor PIR (movimento)  
- LCD 16x2 I2C  
- LEDs (verde, amarelo, vermelho)  
- Buzzer  

---

## ⚙️ Funcionamento do Sistema
O sistema opera de forma autônoma:

- Temperatura é monitorada continuamente
- Gás é detectado em tempo real
- Movimento é identificado por sensor PIR
- O sistema exibe informações no LCD
- LEDs indicam status (OK, alerta ou emergência)
- Buzzer ativa em situações críticas

---

## 🔌 Estrutura do Circuito
- DHT22 → pino 2  
- PIR → pino 3  
- MQ2 → A0  
- LED verde → 8  
- LED amarelo → 9  
- LED vermelho → 10  
- Buzzer → 11  
- LCD I2C → SDA (A4), SCL (A5)

---

## ▶️ Instruções de Execução
1. Abrir o projeto no Wokwi  
2. Montar o circuito conforme descrito  
3. Colar o código Arduino  
4. Iniciar a simulação  
5. Testar sensores e respostas do sistema  

---

## 👥 Integrantes do Grupo
- Murilo Monteiro Silva — RM 568719  
- Tiago Shimazaki Barros — RM 570359  

---

## 🔗 Links
- Simulação Wokwi: (colar link aqui)
- Vídeo da apresentação: (colar link aqui)
