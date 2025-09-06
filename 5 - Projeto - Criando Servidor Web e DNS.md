# 🌐 Criando Servidor Web e DNS no Cisco Packet Tracer  

Este projeto demonstra a criação e configuração de um **Servidor Web** integrado a um **Servidor DNS** no **Cisco Packet Tracer**, possibilitando o acesso a páginas web através de nomes de domínio.  

---

## 📌 Objetivo
- Configurar um **Servidor Web** com suporte a DNS.  
- Realizar a resolução de nomes (domínio → IP).  
- Testar o acesso ao site configurado a partir de um PC da rede.  
- Simular um ambiente **mais próximo da realidade** com instalação de uma **Placa de Rede Gigabit** para maior eficiência na entrega de pacotes.  

---

## 🖥️ Estrutura da Rede

<img width="914" height="703" alt="image" src="https://github.com/user-attachments/assets/4d80e34c-dc5d-4274-86bc-b4e99611a926" />


- **Servidor (Server0)**  
  - IP: `192.168.10.1`  
  - Máscara: `255.255.255.0`  
  - Serviço DNS ativo → `www.github.com.br` → `192.168.10.1`  
  - Serviço Web ativo (HTTP).  
  - **Placa de Rede Gigabit instalada** para melhor desempenho, simulando uma situação real de alta demanda.  

- **Cliente (PC0)**  
  - IP: `192.168.10.2`  
  - Máscara: `255.255.255.0`  
  - Gateway: `192.168.10.1`  
  - DNS configurado: `192.168.10.1`  

---

## ⚙️ Configuração do DNS
No servidor, foi criado um **A Record** para mapear o domínio `www.github.com.br` para o IP `192.168.10.1`.

<img width="695" height="707" alt="df6240b2-ea5a-4601-8b6b-9ea5cf2f2a29" src="https://github.com/user-attachments/assets/0a6c0092-1337-4891-b218-3043e7b908f9" />


---

## ✅ Testes Realizados
1. O cliente (PC0) acessou o **Web Browser**.  
2. Foi digitado o endereço: `www.github.com.br`.  
3. O DNS converteu o nome para o IP do servidor (`192.168.10.1`).  
4. O servidor respondeu exibindo a página web corretamente.  

🎥 **Demonstração:**  
![Letreiro animado bem vindo ao canal gamer colorido video(4)](https://github.com/user-attachments/assets/1ce6b230-cf3a-4eb0-90b9-1f06a045f8cb)
 
![Letreiro animado bem vindo ao canal gamer colorido video(5)](https://github.com/user-attachments/assets/986f6d73-166f-47cd-9ac2-6c5079a4f89b)
  

---

## 🚀 Conclusão
Este laboratório mostra a importância do **DNS** para a navegação em redes e como a utilização de um **servidor bem configurado e otimizado (com placa Gigabit, no caso)** garante maior **eficiência, desempenho e confiabilidade** na entrega dos pacotes em situações reais.  

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue)
![Tecnologia](https://img.shields.io/badge/Tecnologia-Cisco%20Packet%20Tracer-orange)
![License](https://img.shields.io/badge/License-MIT-green)
