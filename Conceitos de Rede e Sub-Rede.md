# 🌐 Conceitos de Rede e Sub-rede

Este documento apresenta os conceitos básicos de **Rede** e **Sub-rede**, fundamentais para compreender a organização e a comunicação entre dispositivos em um ambiente de **redes de computadores**.

---

## 📌 O que é uma Rede?
Uma **rede de computadores** é um conjunto de dispositivos interconectados que compartilham dados e recursos entre si.  
Esses dispositivos podem ser: **PCs, servidores, impressoras, roteadores e switches**.

### Características principais:
- Conexão entre dois ou mais dispositivos.  
- Comunicação via protocolos (ex: TCP/IP).  
- Compartilhamento de arquivos, internet e serviços.  

Exemplo de rede:  

192.168.0.0/24 → 256 endereços disponíveis (de 192.168.0.0 até 192.168.0.255)
---

## 📌 O que é uma Sub-rede?
Uma **sub-rede (subnet)** é uma divisão lógica dentro de uma rede maior.  
Ela serve para **organizar, otimizar e aumentar a segurança** do tráfego de dados.

### Benefícios do uso de sub-redes:
- 🔹 Melhor utilização dos endereços IP.  
- 🔹 Redução do tráfego desnecessário (broadcast).  
- 🔹 Maior controle e segmentação da rede.  
- 🔹 Facilidade de gerenciamento.  

Exemplo de sub-redes derivadas de `192.168.0.0/24`:  

- `192.168.0.0/25` → 126 hosts válidos  
- `192.168.0.128/25` → 126 hosts válidos  

---

## 🧮 Máscara de Sub-rede (Subnet Mask)
A **máscara de sub-rede** define quantos bits são usados para identificar a **rede** e quantos para identificar os **hosts**.

Exemplos comuns:  
- `255.255.255.0 (/24)` → até 254 hosts  
- `255.255.255.128 (/25)` → até 126 hosts  
- `255.255.255.192 (/26)` → até 62 hosts  

---

## 🔗 Conclusão
- **Rede:** Conjunto de dispositivos conectados.  
- **Sub-rede:** Segmentação lógica de uma rede maior.  
- **Máscara:** Define o tamanho da rede e o número de hosts possíveis.  

O entendimento desses conceitos é essencial para trabalhar com **roteamento, segurança e administração de redes**.
