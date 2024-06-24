# Fully local File Converter web app using FFmpeg.wasm

This web application provides a user-friendly interface for converting video, audio, and image files to various formats using FFmpeg and Wasm. The app runs locally in your browser, leveraging the power of FFmpeg and Wasm for high-quality media conversions.

## Features

- Convert video files to multiple formats (e.g., MP4, AVI, MKV)
- Convert audio files to various formats (e.g., MP3, WAV, AAC)
- Convert image files to different formats (e.g., JPEG, PNG, WebP)
- User-friendly interface built with React and Tailwind CSS
- Sleek and customizable UI components from shadcn/ui

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/psv2522/converto.git
   cd converto
   ```

2. Install the dependencies:
   ```
   npm install
   ```

## Usage

1. Start the development server:
   ```
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:3000`.

3. Use the interface to upload your media files and select the desired output format.

4. Click the "Convert" button and wait for the process to complete.

5. Download your converted file.

## Building for Production

To create a production-ready build:

```
npm run build
npm start
```

## Technology Stack

- [Next.js](https://nextjs.org/) - React framework
- [React](https://reactjs.org/) - JavaScript library for building user interfaces
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [shadcn/ui](https://ui.shadcn.com/) - Re-usable components built with Radix UI and Tailwind CSS
- [FFmpeg](https://ffmpeg.org/) - Complete, cross-platform solution for recording, converting and streaming audio and video
