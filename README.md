# Quran Radio Assets

This repository functions as the Content Delivery Network (CDN) for the Quran Radio mobile application. It hosts static assets including audio files, images, and configuration data to reduce the application's binary size and allow for dynamic updates.

## 🗂 Structure

The repository maintains a strict hierarchical structure:

### 🎵 Audio (`/audio`)
- **/adhan/**: Adhan recordings from various Muezzins and countries.
- **/quran/**: (Future) Individual Surah recitations or clips.
- **/stations/**: (Future) Station jingles or specific streaming assets.

### 🖼 Images (`/images`)
- **/backgrounds/**: High-resolution backgrounds for app theming.
- **/muezzins/**: Portraits or icons representing Muezzins.
- **/icons/**: Dynamic app icons or category thumbnails.

### 📄 Data (`/data`)
- **/metadata/**: JSON or config files that accompany the assets.

## 🔗 Usage

Assets are accessed directly via the raw GitHub content URL:
`https://raw.githubusercontent.com/ahalimfr/quran-radio-assets/main/{path/to/asset}`

**Example:**
`https://raw.githubusercontent.com/ahalimfr/quran-radio-assets/main/audio/adhan/adhan_makkah.mp3`

## 🚀 Deployment

Assets pushed to the `main` branch are immediately available to the production application.
Cache propagation is typically instant or within a few minutes depending on client-side caching strategies.

## 📝 License

All assets are property of their respective owners. This repository is intended solely for the operation of the Quran Radio App.