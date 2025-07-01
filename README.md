# 🎬 CinemaFlix-PI

## Sobre o Projeto

O **CinemaFlix** é uma aplicação web desenvolvida para simular a venda de ingressos de cinema, com foco em garantir a segurança e exclusividade na reserva de assentos por sessão. Inspirado por um incidente real no Shopping JK — onde dois clientes compraram ingressos para a mesma cadeira — o sistema foi criado para eliminar conflitos desse tipo, promovendo uma experiência confiável, fluida e sem constrangimentos.

---

## 🎯 Principais Objetivos

- **Evitar duplicidade de reservas:** Garantia de que cada cadeira possa ser reservada apenas uma vez por sessão, mesmo em situações de alta concorrência.
- **Simulação de aplicação real:** Integração de frontend (React) e backend (Node.js + MySQL) para uma experiência completa.
- **Prática de conceitos fundamentais:** Autenticação, requisições REST API, controle de estado no React e gerenciamento seguro de sessões.
- **Atualização de disponibilidade em tempo real:** Controle dinâmico das reservas e ocupação de assentos.

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- **React.js** (Vite)
- **Axios**

### Backend
- **Node.js**
- **Express**
- **MySQL**
- **Sequelize** (ou outro ORM)
- **JWT** (para autenticação)

---

## 📂 Funcionalidades

- **Cadastro e login de usuários**
- **Listagem de filmes em cartaz**
- **Escolha de sessões (data e horário)**
- **Seleção de cadeiras disponíveis**
- **Confirmação de reserva**
- **Prevenção de reservas duplicadas** (controle de concorrência no backend)
- **Histórico de ingressos por usuário** (em desenvolvimento)

---

## ⚠️ Segurança e Prevenção de Erros

O backend utiliza transações no banco de dados para garantir a integridade das reservas, prevenindo que duas pessoas reservem a mesma cadeira simultaneamente — mesmo diante de múltiplos acessos concorrentes.

---

## 📈 Melhorias Futuras

- Integração com pagamento online (Stripe, PayPal, etc.)
- Geração de QR Code para acesso ao cinema
- Dashboard administrativo para gerenciamento de sessões e salas
- Notificações automáticas por e-mail ou WhatsApp

---

## 👨‍💻 Sobre o Autor

Desenvolvido por **William dos Santos** como parte de um estudo prático em desenvolvimento de sistemas web, inspirado por um caso real.

---

## 📝 Licença

Este projeto está licenciado sob a **MIT License**. Sinta-se à vontade para utilizar e adaptar, desde que os devidos créditos sejam mantidos.