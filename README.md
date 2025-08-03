# web-application-tools-website
A collection of multi-purpose web application tools including image compressor, YouTube video downloader, Instagram photo saver, YouTube to MP3 converter, and more — all in one website. Designed for performance and simplicity, with integrated AdMob ads support for monetization.

# 🌐 Web Application Tools Website by Girijashankar Ray

A multi-purpose **web application platform** offering online utilities under one website with integrated **AdMob monetization**.

---

## 💡 Tools Offered

- ✅ **Image Compressor** (reduce image file size)
- ✅ **YouTube Video Downloader**
- ✅ **Instagram Photo & Video Saver**
- ✅ **YouTube to MP3 Converter**
- ✅ **PDF to JPG Converter**
- ✅ **JPG to PDF Converter**
- ✅ **QR Code Generator**
- ✅ **Text to Speech Converter**
- ✅ Many more tools coming soon!

---

## 🎯 Key Features

- Modern web design + responsive layout  
- Fast, lightweight, and easy to use  
- AdMob ads integration for monetization  
- All tools accessible in one place  
- Minimal backend for low-cost hosting  

---

## 🚀 Technologies Used

- HTML, CSS, JavaScript  
- PHP / Node.js backend (optional)  
- Google AdMob for monetization  
- APIs & libraries for tool functionality  

---

## 📂 Folder Structure

web-application-tools-website/
│
├── index.html
├── css/
│ └── styles.css
├── js/
│ └── main.js
│ └── tool-specific-scripts/
├── tools/
│ ├── image-compressor/
│ ├── youtube-downloader/
│ ├── instagram-downloader/
│ ├── youtube-to-mp3/
│ ├── pdf-to-jpg/
│ ├── jpg-to-pdf/
│ ├── qr-code-generator/
│ ├── text-to-speech/
│ └── more-tools/
├── assets/
│ ├── icons/
│ └── images/
├── ads/
│ └── admob-integration-code.html
├── README.md
└── LICENSE


---

## 👨‍💼 About Me

I'm **Girijashankar Ray**, Senior MIS Analyst and web application developer.  
I specialize in:
- Google Sheets + Apps Script automation  
- Dashboard development (Looker Studio, Excel)  
- AppSheet apps + web application design

📧 **girijashankar.career@gmail.com**  
[👉 LinkedIn](https://www.linkedin.com/in/girijashankarray/)

---

## 🤝 License

This project is free for personal & internal business use.  
For commercial deployment or resale, contact me for a license.

---

Made with 💙 by Girijashankar Ray
web-application-tools-website/
├── index.html
├── css/
├── js/
├── tools/
├── assets/
├── ads/
├── README.md
├── LICENSE

# Sample AdMob Integration Code (HTML + JS)
<!-- ✅ AdMob Banner Ad Example -->
<div id="ad-container" style="text-align:center; margin-top:20px;">
    <p>Advertisement</p>
    <!-- Replace the following script with your actual AdMob banner code -->
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
    <ins class="adsbygoogle"
         style="display:block"
         data-ad-client="ca-pub-xxxxxxxxxxxxxxxx"  <!-- 👉 Replace with your AdMob Publisher ID -->
         data-ad-slot="1234567890"                <!-- 👉 Replace with your Ad Slot ID -->
         data-ad-format="auto"
         data-full-width-responsive="true"></ins>
    <script>
         (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
</div>
👉 Important:

Replace ca-pub-xxxxxxxxxxxxxxxx with your actual AdMob Publisher ID

Replace data-ad-slot="1234567890" with your ad unit ID

Never click your own ads! AdMob strictly monitors that.

✅ 2️⃣ Sample Tool Landing Page Template
You can use this as a base for every tool page (tools/image-compressor/index.html, tools/youtube-downloader/index.html, etc.)

html
Copy
Edit

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Image Compressor - Web Application Tools</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f4f4f4; margin: 0; padding: 0; }
    header { background: #003366; color: white; padding: 20px; text-align: center; }
    main { padding: 20px; text-align: center; }
    footer { text-align: center; padding: 15px; background: #ddd; }
    input[type="file"] { margin-top: 15px; }
  </style>
</head>
<body>

<header>
  <h1>Image Compressor</h1>
  <p>Reduce your image size quickly without losing quality.</p>
</header>

<main>
  <h2>Upload your image</h2>
  <input type="file" accept="image/*">
  <p>(This is a demo landing page. Actual functionality will go here.)</p>
  
  <!-- ✅ Insert AdMob ad here -->
  <div style="margin-top:30px;">
      <!-- Include your admob-integration-code.html or paste ad code directly -->
      <iframe src="../../ads/admob-integration-code.html" style="border:none;width:100%;height:100px;"></iframe>
  </div>
</main>

<footer>
  <p>© 2025 Girijashankar Ray | <a href="../../index.html">Home</a></p>
</footer>

</body>
</html>
