# 🌍 Language Mirror

**Language Mirror** is a "Passive Immersion" Chrome extension designed for the busy learner. It seamlessly weaves language practice into your daily browsing by replacing a percentage of English words on any website with their foreign language equivalents.

---

## ✨ Features

* **Invisible Learning:** No more dedicated study sessions. Learn as you read the news, Reddit, or work blogs.
* **Customizable Intensity:** Adjust the "Immersion Level" (5%, 10%, or 20% of words) via a simple slider.
* **Instant Context:** Hover over any highlighted word to see the original English translation.
* **Pronunciation:** Click the speaker icon in the tooltip to hear the correct AI-generated pronunciation.
* **Vocabulary Vault:** Automatically tracks words you've interacted with for later review.

---

## 🛠️ Installation (Developer Mode)

Since this project is open-source and not yet on the Chrome Web Store, follow these steps to install it:

1.  **Download this Repository:** Click the green `<> Code` button and select **Download ZIP**, then unzip it on your computer.
2.  **Open Chrome Extensions:** In your browser, go to `chrome://extensions/`.
3.  **Enable Developer Mode:** Toggle the switch in the top-right corner to **ON**.
4.  **Load the Extension:** Click the **Load unpacked** button.
5.  **Select the Folder:** Navigate to and select the `language-mirror-main` folder (the one containing `manifest.json`).

---

## 📂 Project Structure

* `manifest.json`: The core configuration file for the extension.
* `content.js`: The "brain" that scans webpages and swaps words.
* `popup.html/js`: The user interface for settings and toggles.
* `icons/`: Contains the extension icons in 16, 48, and 128px sizes.
* `styles.css`: Handles the highlighting and tooltip design.

---

## 🤝 Contributing

Contributions are welcome! If you want to add a new language dictionary or improve the word-swapping logic:

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

**Built with ❤️ for language lovers everywhere. Like what you see? Support with a small donation @ https://www.chai4.me/languagemirror**
