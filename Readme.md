# AI-Music-Recommend

# 🎵 AI-Music-Recommend

**AI-Music-Recommend** is a smart, AI-powered music recommendation system that leverages machine learning and music APIs to suggest tracks tailored to your tastes. Powered by Gradio for an interactive interface, this project is designed to help users discover new music effortlessly.

---

## 🚀 Introduction

AI-Music-Recommend bridges the gap between artificial intelligence and music discovery. By integrating with music APIs (like Spotify), it analyzes your preferences and recommends tracks that match your mood and style. The intuitive Gradio web interface makes getting recommendations quick and easy—perfect for music lovers, playlist curators, or anyone looking to expand their musical horizons.

---

## ✨ Features

- 🎧 **Personalized Recommendations:** Get track suggestions tailored to your tastes.
- 🖥️ **User-Friendly Interface:** Simple web interface built with Gradio.
- 🔐 **Secure Authentication:** Uses environment variables for API credentials.
- 🔄 **Automatic Token Refresh:** Keeps your API access fresh and uninterrupted.
- ⚡ **Easy Integration:** Designed with modular, readable Python code.

---

## 🛠️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/AI-Music-Recommend.git
   cd AI-Music-Recommend
   ```

2. **Create and Activate a Virtual Environment (Optional but Recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**
   - Create a `.env` file in the root directory:
     ```
     CLIENT_ID=your_spotify_client_id
     CLIENT_SECRET=your_spotify_client_secret
     REDIRECT_URI=http://localhost:8080/callback
     ```
   - Obtain these values from your music API provider (e.g., [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications)).

---

## 🚦 Usage

1. **Start the Application**
   ```bash
   python app.py
   ```
   or
   ```bash
   python gradioapp.py
   ```

2. **Interact via Web Interface**
   - Visit the provided local URL (e.g., `http://localhost:7860`) in your browser.
   - Authenticate with your music API account when prompted.
   - Input your favorite genres, artists, or moods.
   - Get personalized music recommendations instantly!

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

Please open an issue to discuss major changes or enhancements before submitting a PR.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> Made with ❤️ for music lovers and developers everywhere!

## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/gokilavani19/AI-Music-Recommend