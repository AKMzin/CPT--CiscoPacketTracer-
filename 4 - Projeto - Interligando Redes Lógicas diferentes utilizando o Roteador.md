# 🌐 Interligando Redes Lógicas Diferentes com Roteador

Este projeto mostra a configuração de uma rede no **Cisco Packet Tracer**, onde duas redes lógicas diferentes foram interligadas através de um **roteador**.  

---

## 📌 Objetivo
- Demonstrar a comunicação entre hosts em **redes IP diferentes** utilizando roteamento.  
- Configurar endereços IP, gateway padrão e interfaces do roteador.  
- Validar a conectividade com testes de **ping** entre os PCs.  

---

## 🖥️ Topologia da Rede
Abaixo está a topologia desenvolvida no Packet Tracer:

<img width="816" height="578" alt="70d0fcf3-2664-484b-ad18-9d5c1641dfda" src="https://github.com/user-attachments/assets/68b29703-7775-4afc-b189-21fcae397d68" />


---

## ⚙️ Configuração dos Hosts

### Rede 1 (192.168.0.0/24)
- **PC0:** 192.168.0.10 / 24 – Gateway: 192.168.0.254  
- **PC1:** 192.168.0.11 / 24 – Gateway: 192.168.0.254  

### Rede 2 (192.168.1.0/24)
- **PC2:** 192.168.1.10 / 24 – Gateway: 192.168.1.254  
- **PC3:** 192.168.1.11 / 24 – Gateway: 192.168.1.254

<img width="1395" height="411" alt="272c7e07-3d74-4fc7-abde-a4deb5ae8505" src="https://github.com/user-attachments/assets/1db96882-20b1-4570-a8c7-2eab50b1b77f" />


---

## 📡 Configuração do Roteador

### Interface G0/0  
- IP: 192.168.0.254  
- Máscara: 255.255.255.0  

### Interface G0/1  
- IP: 192.168.1.254  
- Máscara: 255.255.255.0

<img width="1337" height="387" alt="d3d30709-628a-490d-ae56-4605398c0c27" src="https://github.com/user-attachments/assets/bd5c1abd-0edf-4e03-9f8e-090006e05407" />


---

## ✅ Testes de Comunicação
Após a configuração, foi possível realizar testes de **ping** entre as redes:  

- PC0 ↔ PC2  
- PC1 ↔ PC3  

---

## 🎥 Demonstração
Veja abaixo a animação da simulação:  

![Letreiro animado bem vindo ao canal gamer colorido video(3)](https://github.com/user-attachments/assets/01f25d72-ba8b-48dd-a33a-f7cd4a4c8ccb)


---

## 🚀 Conclusão
Com essa prática, é possível entender como **roteadores são essenciais** para permitir a comunicação entre redes diferentes, garantindo a interligação de sub-redes no ambiente de redes de computadores.  
