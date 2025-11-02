# Aiury - Disruptive Architectures: IoT, IOB & Generative IA

**Autores:**  
- João Victor Madella – RM 561007  
- Nathália Mantovani de Falco — RM 99904  
- Renato de Angelo – RM 560585  

---

## Objetivo
Prototipo funcional capaz de receber mensagens, classificar riscos automaticamente, responder e armazenar dados no **Oracle Cloud**. Evolução da Sprint 1 com integração real entre **Node-RED, MQTT e Oracle APEX**.

---

## Tecnologias utilizadas
- **Oracle APEX & ORDS:** RESTful Services para receber dados via POST.  
- **Oracle Autonomous Database:** Armazena alertas e mensagens.  
- **Node-RED:** Processa mensagens, classifica riscos e envia para a API/MQTT.  
- **MQTT:** Comunicação em tempo real simulando IoT.

---

## Funcionalidades
- Envio de mensagens simuladas.  
- Classificação de risco (baixo, médio, alto).  
- Resposta automática baseada no risco.  
- Armazenamento seguro no banco Oracle.  
- Publicação de alertas em tempo real via MQTT.
