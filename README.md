# 🍷 Vinheria Inteligente com Arduino

<p align="center">
  <img src="https://img.shields.io/badge/Arduino-Project-blue?style=for-the-badge&logo=arduino">
  <img src="https://img.shields.io/badge/FIAP-Checkpoint%201-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge">
</p>

---

## 📌 Descrição

Este projeto simula o funcionamento de uma **vinheria inteligente**, utilizando Arduino para monitorar a luminosidade do ambiente.

A proposta é demonstrar como a automação pode ser aplicada para preservar a qualidade dos vinhos, evitando exposição excessiva à luz.

---

## 📖 Explicação do Projeto

O sistema utiliza um sensor **LDR (Light Dependent Resistor)** para medir a intensidade luminosa do ambiente.

Com base nesses dados, o Arduino classifica a luminosidade em diferentes níveis e aciona LEDs indicadores para representar a condição do ambiente:

- 🟢 Verde → condição ideal  
- 🟡 Amarelo → atenção  
- 🔴 Vermelho → excesso de luz (prejudicial)  

---

## ⚙️ Componentes Utilizados

- 🔌 1x Arduino Uno  
- 🌗 1x LDR (sensor de luminosidade)  
- 🔧 1x Resistor 10kΩ (divisor de tensão)  
- 💡 3x LEDs:
  - 🟢 Verde → luminosidade ideal  
  - 🟡 Amarelo → atenção  
  - 🔴 Vermelho → alta luminosidade  
- 🔩 3x Resistores 220Ω  
- 🧩 Protoboard  
- 🔗 Jumpers  

---

## 🔌 Funcionamento

O LDR varia sua resistência de acordo com a luz:

- Mais luz → menor resistência  
- Menos luz → maior resistência  

O Arduino lê esses valores e define o estado do ambiente:

| Condição        | Ação do Sistema |
|----------------|----------------|
| Baixa luz      | LED verde      |
| Luz moderada   | LED amarelo    |
| Alta luz       | LED vermelho   |

---

## 🧠 Lógica do Sistema

- Leitura analógica do LDR (0 a 1023)  
- Processamento com `if/else`  
- Acionamento dos LEDs conforme o nível de luminosidade  

---

## 🔍 Observação Técnica

Os valores de referência podem ser ajustados no código para maior precisão, dependendo da iluminação do ambiente.

---

## 🎯 Objetivos

- Aplicar conceitos de Arduino  
- Trabalhar com sensores analógicos  
- Desenvolver lógica condicional  
- Simular automação real  

---

## 🛠️ Tecnologias Utilizadas

- Arduino  
- Tinkercad  
- Simulação de circuitos eletrônicos  

---

## 🔗 Acesse o Projeto

👉 **Tinkercad:**  
https://www.tinkercad.com/things/aF9FaJ41QnE-cpedge-projeto-vineheria?sharecode=4txdFv2fwuYmNPM_Ady9f2_K5OEiAhKL1tHLwtedA0M  

---

## 🎥 Demonstração

👉 **Vídeo no YouTube:**  
https://youtu.be/EX6CnPGPtnM  

---

## 👨‍💻 Integrantes

- Enzo Franco Rodrigues da Silva  
- Matheus Soares Amorim  
- Renato Mendes Ruiz  
- Gustavo Roberto Martins  
- Julia Moreira Rodrigues  

---

## 📚 Contexto Acadêmico

Projeto desenvolvido para o **Checkpoint 1 da FIAP**, sob orientação do professor **Lucas Demetrius Augusto**.

---

## ✅ Status

✔️ Projeto finalizado  
🚀 Pronto para entrega  
