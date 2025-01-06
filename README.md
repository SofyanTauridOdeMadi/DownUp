
# DownUp - A Cross-Platform Video Downloader 📥

DownUp is a cross-platform application built with Flutter to make downloading videos from various platforms (YouTube, Instagram, WhatsApp, etc.) seamless and efficient. This app allows users to download videos in their preferred quality and format while managing downloaded files effortlessly.

---

## 🌟 Features

1. **Input URL & Platform Detection**
    - Automatically detect the platform (YouTube, Instagram, WhatsApp, etc.) from the provided URL.
    - Validate URLs and notify users if unsupported or invalid.

2. **Quality & Format Selection**
    - Choose video quality: 360p, 720p, 1080p.
    - Select file format: MP4, MP3, or others (platform-dependent).

3. **Download with Progress Tracking**
    - Start downloads with real-time progress updates.
    - Error notifications with retry options for failed downloads.

4. **File Management**
    - Save files in a dedicated folder `/Downloads/DownUp`.
    - Automatic file naming based on platform and video title.

5. **Gallery Integration**
    - Access downloaded files directly in a special "MyDownloader" album in your device's gallery.

6. **Download History**
    - View metadata of downloaded files (name, platform, time, quality/format).
    - Easy access to previously downloaded content.

---

## 🛠️ Tech Stack

- **Framework**: [Flutter](https://flutter.dev/)
- **Language**: Dart
- **State Management**: Provider / Riverpod
- **Storage**: Hive for metadata, File system for videos
- **Networking**: HTTP / Dio

---

## 📱 Screenshots

| Input URL  | Quality Selection | Download Progress |
|------------|-------------------|--------------------|
| ![Input URL](https://via.placeholder.com/150) | ![Quality](https://via.placeholder.com/150) | ![Progress](https://via.placeholder.com/150) |

---

## 🚀 How to Run the Project

### Prerequisites
- Install [Flutter SDK](https://flutter.dev/docs/get-started/install) on your system.
- Ensure you have an emulator or connected device for testing.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/sofyantauridodemadi/downup.git
   cd downup
   ```
2. Install dependencies:
   ```bash
   flutter pub get
   ```
3. Run the app:
   ```bash
   flutter run
   ```

---

## 🧰 Dependencies

| Package Name          | Description                               |
|------------------------|-------------------------------------------|
| `http`                | For API calls and video metadata fetching |
| `dio`                 | For downloading video files               |
| `path_provider`       | To handle file storage paths              |
| `hive`                | Local storage for download metadata       |
| `gallery_saver`       | To save downloaded files in gallery       |
| `permission_handler`  | To request permissions for storage access |
| `flutter_spinkit`     | Loader animations for a better UI         |
| `logger`              | Logging for debugging and error handling  |

---

## 🎯 Roadmap

1. Add support for more platforms (TikTok, Facebook, etc.)
2. Improve UI/UX with animations (Lottie integration).
3. Add dark mode for the app.
4. Implement in-app video playback.
5. Introduce scheduling for downloads.

---

## 💡 Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request.

---

🎉 **Happy Downloading!** 🎉