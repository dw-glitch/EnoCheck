# EnoCheck

Sistema de pré check-in infantil com funcionalidades em tempo real, upload de arquivos e QR Code.

## 🚀 Tecnologias

- **Frontend**: React, HTML5, CSS3
- **Backend**: Node.js, Express.js
- **Banco de dados**: PostgreSQL + Sequelize
- **Tempo real**: Socket.IO
- **Upload**: Multer
- **QR Code**: API externa (qrserver.com)

## 📦 Como rodar o projeto

### Backend

```bash
cd server
npm install
cp .env.example .env  # configure o banco de dados aqui
npm run dev
