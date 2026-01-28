# 🎬 TrackMaster – Ultimate Course Tracker

> **TrackMaster** is a powerful, modern web app to track YouTube courses like a pro.
> Import playlists, track progress automatically, take notes per video, and stay consistent — all **locally**, with **zero backend**.

![TrackMaster Banner](https://user-images.githubusercontent.com/placeholder/banner.png)

---

## 🚀 Features

✅ Import **YouTube playlists** using Playlist URL or ID
✅ Create **custom playlists** manually
✅ Add **individual YouTube videos** anytime
✅ **Automatic progress tracking** while watching
✅ Per-video **progress bar**
✅ **Mark videos completed**
✅ **Drag & drop** to reorder videos
✅ **Notes per video** (auto-saved)
✅ Persistent storage using **LocalStorage**
✅ Fully **responsive & modern UI**
✅ No backend – **100% client-side**

---

## 🧠 How It Works

* Uses **YouTube Data API v3** to fetch:

  * Playlist metadata
  * Video titles & durations
* Uses **YouTube IFrame Player API** to:

  * Play videos
  * Track watch progress in real time
* Stores everything locally in the browser:

  * Playlists
  * Notes
  * Watch progress
  * Completion state

⚠️ **No data ever leaves your browser**

---

## 🛠 Tech Stack

| Technology              | Usage                       |
| ----------------------- | --------------------------- |
| **HTML5**               | App structure               |
| **Tailwind CSS**        | Modern UI styling           |
| **Vanilla JavaScript**  | Core logic                  |
| **YouTube Data API v3** | Fetch playlist & video info |
| **YouTube IFrame API**  | Video playback & progress   |
| **SortableJS**          | Drag & drop reordering      |
| **Lucide Icons**        | Clean SVG icons             |
| **LocalStorage**        | Persistent data storage     |

---

## 📂 Project Structure

```bash
.
├── index.html      # Main application file
└── README.md       # Project documentation
```

> This is a **single-file app** — easy to deploy anywhere.

---

## 🔑 Setup & Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/trackmaster.git
cd trackmaster
```

### 2️⃣ Get a YouTube API Key

1. Go to **Google Cloud Console**
2. Create a new project
3. Enable **YouTube Data API v3**
4. Create an API Key

### 3️⃣ Add Your API Key

In `index.html`, replace:

```js
const YOUTUBE_API_KEY = "YOUR_API_KEY_HERE";
```

### 4️⃣ Run Locally

Just open the file:

```bash
index.html
```

✅ No build tools
✅ No server
✅ No dependencies

---

## 🎯 Usage Guide

### ➕ Add Playlist

* Click **Add Playlist**
* Import from YouTube **or**
* Create a custom playlist

### ▶ Watch Videos

* Click any video to start watching
* Progress auto-updates every second

### 📝 Take Notes

* Notes are **video-specific**
* Saved automatically

### 🔀 Reorder Videos

* Drag using the grip icon

### ✅ Track Progress

* Header shows:

  * Completed videos
  * Remaining time
  * Overall progress %

---

## 🧪 Tested On

✔ Chrome
✔ Edge
✔ Firefox
✔ Desktop & Mobile

---

## ⚠️ Limitations

* API quota depends on your YouTube API key
* Data is **browser-specific**
* Clearing browser storage resets progress

---

## 🌟 Roadmap (Future Ideas)

* ⏱ Resume video from last watched time
* ☁️ Cloud sync (Firebase / Supabase)
* 🌙 Theme switcher
* 📊 Analytics dashboard
* 🔐 Login support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

**MIT License**
Free to use, modify, and distribute.

---

## ❤️ Credits

Built with passion for **self-learning & consistency**.

If this helped you, **⭐ star the repo** and share it 🚀

---

