# Cosmic Transcriber

**Cosmic Transcriber** is a desktop application for audio transcription and subtitling, powered by the open-source Whishper project. This application leverages Electron to provide a seamless, cross-platform transcription experience.

## Features

- **Audio Transcription:** Convert audio files into text with high accuracy.
- **Subtitling Support:** Generate subtitles for videos with a powerful subtitle editor.
- **Cross-Platform:** Available on Windows, with potential for macOS and Linux support.
- **User-Friendly Interface:** Simple and intuitive UI for easy navigation.
- **100% Local Processing:** Transcription, translation, and subtitle editing occur entirely on your machine.
- **Fast Performance:** Utilizes FasterWhisper for improved transcription times, with support for both CPU and NVIDIA GPU acceleration.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/richkel/cosmic-trascriber.git
   cd cosmic-trascriber
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Run the Application:**
   ```bash
   npm start
   ```

## Development

- **Main Technologies:**
  - Electron
  - Node.js
  - JavaScript

- **Project Structure:**
  - **Transcription-API:** API for running Faster-Whisper.
  - **Backend:** Coordinates frontend calls, database, and tasks.
  - **Frontend:** Web UI of the application.

## Acknowledgments

Cosmic Transcriber is powered by [Whishper](https://github.com/pluja/whishper), an open-source transcription and subtitling suite. Special thanks to the Whishper contributors for their incredible work in making audio transcription accessible and efficient.

## Roadmap

- **Local Folder as Media Input**
- **Full-Text Search Across Transcriptions**
- **User Authentication**
- **Audio Recording from Browser**
- **Support for Non-NVIDIA GPU Acceleration**

## Contributing

Contributions are welcome! Feel free to open a PR with your changes or take a look at the issues to see if there's something you can help with.

## Support

- **Monero:** 82x6cn628oTUXV63DxBd6MJB8d997FhaSaGFvoWMgwihVmgiXYQPAwm2BCH31AovA9Qnnv1qQRrJk83TaJ8DaSZU2zkbWfM
- **Bitcoin:** bc1qfph44jl4cy03stwfkk7g0qlwx2grldr9xpk086
- **Lightning Network:** (kycnotme)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
