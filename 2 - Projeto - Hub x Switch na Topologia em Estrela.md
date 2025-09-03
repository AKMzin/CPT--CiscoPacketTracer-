# Objetivo do Projeto:
- Demonstrar, na prática, a diferença entre switch e hub utilizando uma topologia em estrela.
##
# Pontos importantes!!
- Todos os dispositivos conectados a um ponto central.
- Hub: envia dados para todos os dispositivos → mais tráfego, colisões.
- Switch: envia dados somente para o destino correto → comunicação mais rápida e eficiente.
- Foi utilizado o cabo Straight-Through, ideal para conectar computadores a dispositivos de rede (hub ou switch ou usado para conectar dispositivos diferentes entre si).
##
 A topologia em estrela foi escolhida por sua organização centralizada, onde todos os dispositivos se conectam a um ponto central (hub ou switch); neste projeto, serão utilizados computadores simulados para enviar e receber dados entre si, demonstrando como o hub envia informações para todos os dispositivos, gerando mais tráfego e possíveis colisões, enquanto o switch encaminha os dados apenas para o destino correto, tornando a comunicação mais eficiente e segura.

## Switch:
![Image](https://github.com/user-attachments/assets/4993ad9a-8163-4a3e-88ea-ab12630af909)

- Observação Técnica

- Um switch é um dispositivo de rede que conecta vários dispositivos (computadores, impressoras, servidores) dentro de uma mesma rede local (LAN). A função do Switch é como um porteiro inteligente: ele pega a “mensagem” de um computador e entrega só para quem precisa receber, sem encher todo mundo de tráfego desnecessário.

- No Cisco Packet Tracer, o switch pode parecer que está enviando dados para todos os dispositivos, mas isso não é um bug: é o processo de aprendizado do switch.
Quando ele ainda não conhece o endereço MAC de destino, realiza um flooding (envia para todas as portas) para descobrir onde o dispositivo está. Depois que o endereço é aprendido, os dados passam a ser encaminhados apenas para o destino correto.

## Hub:
![Image](https://github.com/user-attachments/assets/a5faedd6-46c6-4440-b7e0-0e842569c229)

- Observação Técnica
  
- Um hub é um dispositivo de rede que conecta vários computadores dentro de uma mesma rede local (LAN), assim como o switch. Recebe dados de um computador e envia para todos os dispositivos da rede, sem escolher o destino.

Isso pode causar tráfego desnecessário e colisões de dados.

- o hub é como um megafone — o que um computador “fala”, todo mundo ouve, mesmo que a mensagem seja só para uma pessoa.
##

# HUB vs SWITCH

- SWITCH:
![Image](https://github.com/user-attachments/assets/229134bc-d5c5-4b94-be81-7d7f997e51d3)
- HUB:
![Image](https://github.com/user-attachments/assets/62431001-c95a-4900-8374-3e023c8ab563)

- Observação Técnica
- Como podemos ver, o switch consegue organizar o tráfego de informações na rede, funcionando como um porteiro inteligente que entrega cada dado ao destino correto. Já o hub não possui essa capacidade de direcionamento, o que pode causar colisões e impedir que as informações cheguem adequadamente aos dispositivos.
- Switch: é usado em redes modernas porque organiza os dados e envia só para quem precisa. Isso deixa a rede mais rápida e sem confusão.
- Hub: hoje quase não se usa, mas pode servir em testes, estudos ou para mostrar como as redes antigas funcionavam. Ele manda tudo para todos, o que pode atrapalhar se tiver muita informação.

# Conclusão:
Este projeto evidencia que, mesmo com a mesma topologia, a escolha do dispositivo central (hub ou switch) impacta diretamente na eficiência, velocidade e segurança da rede.
