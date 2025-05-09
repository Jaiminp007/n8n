# YouTube Video Creation Automation with Heygen and OpenAI

This project automates the creation of YouTube videos using a combination of OpenAI, Heygen, n8n, and other tools to generate engaging content and upload it to YouTube.

## 🚀 Workflow Overview

1. **Download YouTube Video**: The process begins by downloading an existing YouTube video through n8n.
2. **Transcription**: The downloaded video is transcribed to extract the audio and convert it into text using AI transcription tools.
3. **AI Text Segmentation**: The transcription is processed by an AI agent, which divides the content into smaller, more digestible segments. These segments are stored in a **Google Sheet**, along with relevant metadata for each section.
4. **Image Generation**: Based on the segmented text, relevant image prompts are created and sent to an image generation API. These images are intended to match the theme of the video and will be used later in the video production process.
5. **Video Creation with Heygen**: The AI-generated images, combined with an AI avatar from Heygen, are used to produce a new video. The avatar narrates the segments, while the images appear as visual support.
6. **Subway Surfer Effect**: A Subway Surfer effect is applied at the bottom of the video, making it suitable for a "brain root" style reel.
7. **Video Upload to YouTube**: The final video is uploaded to YouTube, completing the process.
8. **Confirmation Email**: After the video is uploaded, a confirmation email is sent to notify you of the successful upload.
<img width="1377" alt="Screenshot 2025-05-08 at 2 19 00 AM" src="https://github.com/user-attachments/assets/32bba309-0faf-4ad7-bfea-8f621882c219" />


## 🛠 Tools & Technologies Used

* **n8n**: Workflow automation tool that ties all steps together.
* **OpenAI**: Used for transcription and text segmentation.
* **Google Sheets**: Stores transcriptions and video segments for further processing.
* **Image Generation API**: Generates images based on video segments.
* **Heygen**: AI-powered video generation using avatars and images.
* **Subway Surfer Effect**: Video editing for reel-style customization.
* **YouTube API**: Used to upload the final video.
* **Email Service**: Sends a confirmation email post-upload.

## 📦 Installation & Setup

### 1. Install n8n via Command Line

Make sure you have [Node.js](https://nodejs.org/) installed, then run:

```bash
npm install -g n8n
```

### 2. Start n8n

After installation, launch the n8n editor:

```bash
n8n
```

This will open the n8n editor in your browser at:

```
http://localhost:5678
```

### 3. Import the Workflow

* Download or copy the `data.json` file from this repository.
* In the n8n editor UI:

  * Click the menu icon (☰) in the top right.
  * Select **Import from File**.
  * Choose the `data.json` file.
* This will load the complete workflow into your n8n instance. You would find futher instructions there. 

## 🧠 Google Sheet Structure

<img width="1435" alt="Screenshot 2025-05-08 at 2 19 05 AM" src="https://github.com/user-attachments/assets/63652204-60eb-448e-8706-0d4c59a0615f" />

## 📩 Contact

For questions, feedback, or collaboration:

* Open an [issue](https://github.com/your-repo/issues) on GitHub.
* Submit a [pull request](https://github.com/your-repo/pulls) for contributions.
* Or reach out via email: **[jaiminjaiminpatel1@gmail.com](mailto:jaiminjaiminpatel1@gmail.com)**

We'd love to see how you customize or scale this workflow!

