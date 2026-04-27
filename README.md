# 🔥 Streak Bot (@streakfirebot)

**Streak Bot** is a high-performance Telegram Business companion designed to gamify daily communication. By leveraging the native Telegram Business API, it automatically tracks and visualizes "streaks" (consecutive days of messaging) with stunning, evolving animations.

[**Launch Streak Bot on Telegram**](https://t.me/streakfirebot)

---

## ✨ Key Features

### 1. Native Business Integration
**No manual logging or tokens required.** The bot integrates directly into your Telegram account via the native **Telegram Business** settings. Once connected, it works silently in the background, detecting activity in your chats to keep your streaks alive.

### 2. Visual Evolution System
Streaks aren't just numbers; they are living entities. As your streak grows, it evolves through different stages, changing colors and animation styles:
* **Level 1-2:** *Spark & Flame* (Orange)
* **Level 4-6:** *Discharge & Plasma* (Purple/Blue)
* **Level 9-11:** *Pulsar & Absolute* (Cosmic/Teal)

### 3. Dynamic Web App (TWA)
A full-featured dashboard built for speed and aesthetics:
* **Monitor Progress:** View a ranked list of all active streaks with your contacts.
* **Visual Milestones:** Watch your fire evolve with high-quality Lottie animations.
* **Referral System:** Invite friends and track your referral stats directly in the UI.

### 4. Interactive Story Sharing
Celebrate your consistency! Generate custom video assets of your streaks to share directly to **Telegram Stories**, complete with a functional widget link that leads back to the bot.

### 5. Streak Recovery ("Freeze" Mechanics)
Life happens. If a streak is broken, it enters a **Frozen State**. Users can "defrost" and recover their progress using Telegram Stars, ensuring that months of consistency aren't lost to a single busy day.

---

## 🛠 How It Works

* **Business API:** Uses Telegram's native business message handlers to track interactions without ever storing or reading private message content.
* **Automated Logic:** A nightly task (00:00 GMT+3) calculates streak states, updates evolution levels, and manages "frozen" statuses.
* **Tech Stack:** Python-based backend (`aiogram`), MySQL for persistent data, and a responsive JS/HTML5 Web App.

---

## 🚀 Getting Started

1.  Open [**@streakfirebot**](https://t.me/streakfirebot) on Telegram.
2.  Ensure you have **Telegram Premium** (required by Telegram for Business features).
3.  Navigate to **Settings > Telegram for Business > Chatbots**.
4.  Add `@streakfirebot` and grant **"Read Messages"** permission.
5.  Start chatting! Your streaks will appear in the app automatically after 2 days of consistent activity.

---

## 🛡 Privacy & Support
The bot only tracks the *frequency* of communication to maintain the counter; your private conversations remain secure and private. For support or feedback, use the link provided within the Web App interface.

> **Note:** This repository contains documentation only. The source code is private.
