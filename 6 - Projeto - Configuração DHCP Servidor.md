# 🌐 Configuração de Servidor DHCP no Cisco Packet Tracer  

Este projeto demonstra a configuração de um **Servidor DHCP** no **Cisco Packet Tracer**, responsável por distribuir automaticamente endereços IP, máscara de sub-rede, gateway padrão e DNS para os dispositivos da rede.  

---

## 📌 Topologia da Rede
A rede foi configurada com o seguinte esquema:  

- **Faixa de IP utilizada:** `192.168.1.0/24`  
- **Servidor DHCP:** `192.168.1.1`  
- **Gateway Padrão:** `192.168.1.1`  
- **DNS:** `192.168.1.1`  
- **Pool de IPs disponíveis:** `192.168.1.2 - 192.168.1.254`  
- **Quantidade máxima de usuários:** `253`  

---

## ⚙️ Configuração do Servidor DHCP
No servidor, ativamos o serviço **DHCP** e definimos os seguintes parâmetros:  

- **Pool Name:** `Richard`  
- **Default Gateway:** `192.168.1.1`  
- **DNS Server:** `192.168.1.1`  
- **Start IP Address:** `192.168.1.2`  
- **Subnet Mask:** `255.255.255.0`  
- **Máximo de usuários:** `253`  

📸 Imagens da configuração no Packet Tracer:  

<img width="507" height="389" alt="image" src="https://github.com/user-attachments/assets/303e70af-667b-4150-a35e-f098de5bf155" />

<img width="614" height="528" alt="image" src="https://github.com/user-attachments/assets/11dc2d69-87ee-4bd1-a83d-b8e7add2f22a" />


---

## 💻 Funcionamento
Após a configuração:  

- Os **PCs conectados à rede** receberam automaticamente seus endereços IP.  
- A comunicação entre dispositivos foi estabelecida com sucesso.  
- O servidor distribuiu IPs dinamicamente, garantindo agilidade e eficiência na rede.  

📹 Demonstração do funcionamento no Packet Tracer:  

![Letreiro animado bem vindo ao canal gamer colorido video](https://github.com/user-attachments/assets/5f654e06-9c62-435e-9967-3eb9e78eb6bd)


---

## 🚀 Benefícios do DHCP
- **Automatização:** elimina a necessidade de configurar IP manualmente em cada máquina.  
- **Escalabilidade:** ideal para redes com muitos dispositivos.  
- **Flexibilidade:** fácil gerenciamento de alterações na rede.  

---

🔹 Esse laboratório simula um ambiente real, onde o **DHCP é essencial para grandes redes**, otimizando a administração e reduzindo erros humanos.  

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue)
![Tecnologia](https://img.shields.io/badge/Tecnologia-Cisco%20Packet%20Tracer-orange)
![License](https://img.shields.io/badge/License-MIT-green)
