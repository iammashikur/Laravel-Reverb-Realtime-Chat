# Laravel Reverb Chat 🚀

A real-time chat application built with Laravel, enabling users to communicate instantly through WebSocket connections.


## 🌟 Introduction

Laravel Reverb Chat is a dynamic, real-time messaging platform that enables instant communication between users. Built with modern technologies and a sleek interface, it provides a seamless chatting experience with real-time message broadcasting.
Laravel Reverb brings real-time messaging to life. As Laravel’s official WebSocket solution, Reverb handles instant message broadcasting with speed and reliability. Its deep framework integration makes building dynamic, live chat apps seamless and efficient.

## 🛠️ Tech Stack


### Backend:

- Laravel 12.x 🏗️
- PHP 8.2+ ⚡
- Laravel Reverb (WebSockets) 🔌
- MySQL/PostgreSQL 🗄️

### Frontend:

- Bootstrap 5 🎨
- jQuery 📱
- Font Awesome Icons ✨
- Laravel Blade Templates 🔧

### Real-time Features:

- WebSocket Integration 🔄
- Event Broadcasting 📡
- Real-time Message Updates ⚡

## 🚀 Features

- Instant Real-time Messaging ⚡
- User-friendly Interface 👥
- Responsive Design 📱
- Message Broadcasting 📢
- Clean & Modern UI 🎨


## ✨ Prerequisites

- PHP >= 8.2
- Laravel >= 10.x
- Composer
- Node.js & NPM
- WebSocket server (Laravel Reverb)


## 🖼️ Screenshots

### 📌 

![Login Screenshot](public/images/admin.png)

---

### 📌 

![Register Screenshot](public/images/user.png)

---


### 📌 

![Dashboard Screenshot](public/images/chat.png)

---

### 📌 

![Dashboard Screenshot](public/images/chat1.png)

---

### 📌 

![Dashboard Screenshot](public/images/chat2.png)

---


## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/Web-Dev-Kombee/Laravel-Reverb-Realtime-Chat.git
```

2. Install dependencies:
```bash
composer install
npm install
```

3. Configure environment:
```bash
cp .env.example .env
php artisan key:generate
```

4. Configure WebSocket settings in `.env`:
```env
BROADCAST_DRIVER=reverb
REVERB_APP_ID=your_app_id
REVERB_APP_KEY=your_app_key
REVERB_APP_SECRET=your_app_secret
```

5. Start development servers:
```bash
php artisan serve
npm run dev
php artisan reverb:start
```

## 📁 Project Structure

### Key Files

- `app/Http/Controllers/ChatAppController.php` - Handles chat logic
- `resources/views/chatroom.blade.php` - Chat interface
- `routes/web.php` - Route definitions
- `app/Events/MessagetSent.php` - Event broadcasting

### Routes

```php
POST /chat/room - Join chat room
POST /fire/message - Send messages
```

## 📌 Usage

1. Access the application through your browser
2. Enter your username to join the chat
3. Start sending messages in real-time
4. Messages are broadcasted to all connected users instantly

## 💖 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 👏 Acknowledgments

- Laravel Team
- WebSocket Technology
- Open Source Community

## 📜 **License**

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 **Author**

**Kombee Technologies**

- 🌐 [Portfolio](https://github.com/kombee-technologies)
- 💼 [LinkedIn](https://in.linkedin.com/company/kombee-global)
- 🌍 [Website](https://www.kombee.com/)

---

<p align="center">
  Built with ❤️ using Laravel
</p>

---

