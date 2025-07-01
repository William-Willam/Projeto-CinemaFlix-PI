Projeto CinemaFlix-PI
🎬 Descrição do Projeto
O CinemaFlix é um sistema projetado para simular a venda de ingressos de um cinema, com ênfase na reserva de cadeiras por sessão. O objetivo principal é garantir que nenhuma cadeira seja vendida mais de uma vez, mesmo em situações de alta demanda.

A motivação para o desenvolvimento deste sistema surgiu a partir de um incidente real no cinema do Shopping JK, onde duas pessoas adquiriram ingressos para a mesma cadeira, resultando em conflito e constrangimento durante a exibição do filme. O CinemaFlix visa evitar esse tipo de erro, proporcionando um controle mais eficiente e seguro das reservas.

🎯 Objetivos do Projeto
Evitar conflitos de assentos duplicados.
Garantir que cada cadeira possa ser reservada apenas uma vez por sessão.
Simular uma aplicação completa com frontend (React) e backend (Node.js + MySQL).
Praticar conceitos de autenticação, requisições API REST e controle de estados no React.
Implementar controle de sessões e disponibilidade em tempo real.
🛠️ Tecnologias Utilizadas
Frontend
React.js
Vite
Axios
Backend
Node.js
Express
MySQL
Sequelize (ou outro ORM)
JWT (para autenticação)
📂 Funcionalidades
🔐 Login e cadastro de usuários
🎟️ Listagem de filmes em cartaz
🕒 Escolha de sessão (data e horário)
💺 Seleção de cadeiras disponíveis
✅ Confirmação de reserva
🔄 Prevenção de reservas duplicadas (concorrência controlada no backend)
🧾 Histórico de ingressos por usuário (em desenvolvimento)
⚠️ Prevenção de Erros
A lógica do backend foi implementada com transações no banco de dados, garantindo que duas pessoas não consigam reservar a mesma cadeira simultaneamente, mesmo em condições de alta concorrência (por exemplo, vários usuários clicando na mesma cadeira ao mesmo tempo).

📈 Futuras Melhorias
Integração com pagamento online (ex: Stripe ou PayPal)
Geração de QR Code para entrada no cinema
Dashboard administrativo para gerenciamento de sessões e salas
Notificações por e-mail ou WhatsApp
👨‍💻 Autor
Desenvolvido por William dos Santos como parte de um estudo prático em desenvolvimento de sistemas web, inspirado por um caso real.

📝 Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para usá-lo e adaptá-lo, desde que os devidos créditos sejam dados.

