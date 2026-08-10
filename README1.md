<!-- markdownlint-disable MD033 MD041 -->

<h1 align="center">🧗‍♀️ CodeClimb</h1>

<p align="center">
  <em>A gamified Data Structures & Algorithms learning platform — level up your DSA skills one climb at a time.</em>
</p>

<p align="center">
  <a href="https://hurmat.store/codeclimb/"><strong>🔗 Live Demo</strong></a>
</p>

<p align="center">
  <code>PHP</code> · <code>MySQL</code> · <code>Bootstrap 5.3</code> · <code>JavaScript</code>
</p>

---

### 📖 About

CodeClimb turns DSA practice into a game instead of a grind. Solve problems, track your progress, and climb the leaderboard against other learners — built to make Data Structures & Algorithms feel motivating, not overwhelming.

---

### ✨ Features

- 🔐 **Secure Authentication** — signup & login with bcrypt password hashing and duplicate-email detection
- 🔑 **Forgot Password Flow** — email-based reset via PHPMailer over Gmail SMTP
- 💪 **Live Password Strength Check** — real-time JS feedback while creating an account
- ✅ **Solved Questions Tracking** — every solved problem logged per user
- 🏆 **Leaderboard** — ranks users by problems solved
- 🎨 **Custom Dark UI** — navy, electric blue, violet & emerald theme

---

### 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, Bootstrap 5.3, JavaScript |
| Backend | PHP |
| Database | MySQL |
| Email | PHPMailer (Gmail SMTP) |
| Security | bcrypt password hashing |

---

### 🗄️ Database Schema

| Table | Purpose |
|---|---|
| `users` | User accounts & credentials |
| `questions` | DSA problem bank |
| `submissions` | Every attempt a user makes |
| `solved` | Tracks solved questions — powers the leaderboard |

---

### ⚙️ Getting Started

**Prerequisites:** PHP 7.4+, Composer, MySQL, a local server (e.g. XAMPP)

```bash
git clone https://github.com/hurmatfatima-tech/CodeClimb.git
cd CodeClimb
composer install
```

Import the provided `schema.sql` into MySQL, then create a `config.php` with your own credentials:

```php
define('DB_HOST', 'localhost');
define('DB_NAME', 'codeclimb');
define('DB_USER', 'your_db_username');
define('DB_PASS', 'your_db_password');

define('SMTP_HOST', 'smtp.gmail.com');
define('SMTP_PORT', 587);
define('SMTP_USER', 'your_email@gmail.com');
define('SMTP_PASS', 'your_app_password');
```

> ⚠️ `config.php` and real credentials are excluded via `.gitignore` — never commit them.

Then open `http://localhost/CodeClimb` in your browser.

---

### 🗺️ Roadmap

- [ ] Problem difficulty filters
- [ ] Topic-wise progress tracking
- [ ] Achievement badges for milestones
- [ ] Hints/discussion section per question

---

### 🤝 Contributing

Issues and pull requests are welcome — feel free to open one.

---

### 📬 Contact

**Hurmat Fatima**
📧 fatimahurmat237@gmail.com · 🌐 [hurmat.store](https://hurmat.store/) · 💻 [@hurmatfatima-tech](https://github.com/hurmatfatima-tech)

---

<p align="center"><sub>Built with 💚 while learning to climb, one problem at a time.</sub></p>
