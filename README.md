### 🔗 [Live Demo](https://farhaaanz.github.io/Shunao)

# 🗣️ Shunao – Text to Speech Web App

**Shunao** (শুনাও) is a simple and sleek text-to-speech (TTS) generator built using vanilla HTML, CSS, and JavaScript. The name comes from the Bengali word "শুনাও", meaning "tell me". This project allows users to type or paste text, choose from available system voices, and hear the spoken version out loud.

## 🔧 Tools & Technologies Used

- **HTML** – For creating the structure of the web page  
- **CSS** – For styling and visual design  
- **JavaScript** – To handle the TTS logic using the Web Speech API  

## 🚀 How to Build & Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/shunao.git
   cd shunao
   ```

2. **Open `index.html`** in your browser:
   - You can simply double-click it, or
   - Run it using a local development server like Live Server (VS Code Extension)

3. **Usage:**
   - Type or paste any text into the textarea.
   - Select a voice from the dropdown.
   - Click the **"Shunao"** button to hear it spoken aloud.

## ✨ Key Features

- 🎙️ **Voice Selection:** Choose from available system voices (e.g., Microsoft Zira).
- 🎨 **Gradient UI:** Modern and responsive layout with a vibrant gradient background.
- 🔊 **Live Playback:** Instantly hear the spoken text using the Web Speech API.

## ⚠️ Challenges Faced

- Ensuring that voices are loaded properly before selection (handled via `onvoiceschanged`)
- Making the UI responsive and visually engaging with pure CSS
- Debugging voice assignment since different browsers handle it slightly differently
