## **🔐 Proxy Direto vs Proxy Reverso**

📌 Introdução

Um proxy é um intermediário entre um cliente e um servidor. Ele ajuda a controlar acessos, melhorar desempenho, aplicar segurança e balancear cargas.
Existem dois tipos principais: Proxy Direto (Forward Proxy) e Proxy Reverso (Reverse Proxy).
##
🔹 Proxy Direto (Forward Proxy)

✅ Características:

- Fica entre o cliente e a Internet.

- O cliente faz requisições ao proxy, e ele encaminha ao servidor.

- Útil para controle de acesso e anonimato do usuário.

- Pode filtrar conteúdo e armazenar cache.

📊 Exemplo de uso:

- Empresas que bloqueiam sites ou monitoram tráfego de funcionários.

- Usuário que quer ocultar seu IP ao acessar a Internet.

<img width="1370" height="502" alt="image" src="https://github.com/user-attachments/assets/3c4e3c68-071b-4944-a295-52f8c9a1bc39" />

#

🔹 Proxy Reverso (Reverse Proxy)

✅ Características:

- Fica entre o servidor e a Internet.

- Os clientes não sabem que estão falando com o proxy.

- Usado para distribuição de carga (load balancing).

- Pode proteger servidores de ataques diretos.

- Também faz cache e compressão para otimizar desempenho.

📊 Exemplo de uso:

- Grandes sites que usam Nginx ou HAProxy para balancear servidores web.

- Serviços de CDN (Cloudflare, Akamai).
<img width="1440" height="1011" alt="image" src="https://github.com/user-attachments/assets/360ab3ac-d51c-4622-8b02-6a6291d75cac" />
