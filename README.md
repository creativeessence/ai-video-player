# 🎥 AI-Powered Video Navigator

An intelligent video player web app that enhances the viewing experience using AI. Leveraging the [MAVI API](https://docs.openinterx.com/), the player provides contextual navigation and smart summarization features — making it easier than ever to understand and interact with video content.

## ✨ Features

- 🔍 **"Go To" Navigation**  
  Instantly jump to the part of the video that matches your query or interest (e.g., "when they talk about the product launch").

- 🧠 **Smart Video Summary**  
  View a concise AI-generated summary of the entire video at the **beginning** or **end**.

- ⏸️ **Scene Summary on Pause**  
  When the video is paused, get an on-the-spot AI summary of what just happened.

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/creativeessence/ai-video-navigator.git
cd ai-video-navigator
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Setup Environment Variables

Create a `.env` file in the root directory and add your MAVI API key:

```env
MAVI_API_KEY=your_mavi_api_key_here
CALLBACK_URI=your_callback_uri_if_applicable
```

### 4. Run the App

```bash
npm run dev
# or
yarn dev
```

The app will be available at `http://localhost:3000`.

## 🧠 How It Works

- The app sends the video URL to the MAVI API.
- It retrieves processed AI data such as timeline segments, summaries, and indexed content.
- This data powers:
  - The **"Go To"** search via semantic context matching.
  - **Summary overlays** that appear at logical breakpoints (start, end, pause).

## 🛠️ Tech Stack

- **Frontend:** React
- **Backend:** Flask
- **AI Integration:** [MAVI API](https://docs.openinterx.com/)
- **Video Playback:** HTML5 video + custom controls

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

## 📄 License

[MIT](LICENSE)

---

### 🙌 Acknowledgements

Built with ❤️ using [MAVI API](https://openinterx.com), which powers contextual understanding of video content via AI.
Made by ❤️ [Connor Daly](https://github.com/creativeessence) during [OIX Hackathon](https://lu.ma/pp4gvgmi?tk=SC87lH).
