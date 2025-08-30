# 📩 GetRestrictedMessagesBot  

> **Unlock the Unforwardable!**  
A Telegram bot that **bypasses forward restrictions** by re-uploading text, photos, videos, and even albums — powered by [Telethon](https://github.com/LonamiWebs/Telethon).  

---

## ✨ Features  

- 🔓 **Bypass Forward Restrictions**  
  Re-uploads text & media instead of forwarding — works even in channels that block forwarding.  

- 🔗 **Smart Link Parsing**  
  Supports multiple Telegram link formats:  
  - `https://t.me/username/123`  
  - `https://t.me/c/123456/789` (private channel links)  
  - `https://t.me/s/username/123`  

- 🖼 **Album Support**  
  Handles grouped media (photo/video albums) and sends them back as one collection.  

- 👤 **Access Control**  
  Works only for **authorized users** (defined in `.env`).  

- 🛡 **Private & Secure**  
  Only runs in **private chat** with you.  

- 🧹 **Auto-Cleanup**  
  Deletes downloaded files after sending — no clutter left behind.  

---

## ⚙️ Setup  

### 1. Clone the repo  
```bash
git clone https://github.com/yourusername/GetRestrictedMessagesBot.git
cd GetRestrictedMessagesBot
