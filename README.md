
<!DOCTYPE html>
<html lang="si">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>සචිත් ජයවර්ධන - A/L Chemistry Classes</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0; padding: 0;
      background: #f0f8ff;
      color: #222;
      line-height: 1.6;
    }
    header {
      background-color: #004080;
      color: white;
      padding: 20px 10px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.2em;
    }
    header p {
      font-size: 1.1em;
      margin-top: 5px;
    }
    main {
      max-width: 700px;
      margin: 30px auto;
      padding: 0 15px;
    }
    section {
      margin-bottom: 30px;
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgb(0 0 0 / 0.1);
    }
    h2 {
      color: #004080;
      margin-top: 0;
    }
    ul {
      list-style-type: disc;
      padding-left: 20px;
    }
    a.button {
      display: inline-block;
      background: #004080;
      color: white;
      padding: 12px 20px;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      transition: background 0.3s ease;
    }
    a.button:hover {
      background: #00264d;
    }
    footer {
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
      color: #555;
      border-top: 1px solid #ddd;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>සචිත් ජයවර්ධන</h1>
    <p>A/L Chemistry Classes 2025/2026</p>
  </header>
  <main>
    <section>
      <h2>පාඨමාලා විස්තර</h2>
      <ul>
        <li>විෂය: රසායන විද්‍යාව (Chemistry)</li>
        <li>මාධ්‍යය: සිංහල / ඉංග්‍රීසි</li>
        <li>පන්ති වර්ගය: Online (Zoom) සහ Physical</li>
        <li>Weekly MCQ drills, Past Papers Practice</li>
        <li>Doubt clearing sessions සහ Weekly Tests</li>
      </ul>
    </section>
    <section>
      <h2>Contact &amp; Join Links</h2>
      <p>WhatsApp සම්බන්ධ වීමට පහත බොත්තම ක්ලික් කරන්න:</p>
      <a href="https://wa.me/947XXXXXXXX" target="_blank" class="button">WhatsApp Join Link</a>
      <p style="margin-top:15px;">Zoom පන්ති සඳහා පහත ලින්ක් එක භාවිතා කරන්න:</p>
      <a href="https://zoom.us/j/XXXXXXXXXX" target="_blank" class="button">Zoom Join Link</a>
    </section>
  </main>
  <footer>
    &copy; 2025 සචිත් ජයවර්ධන | All rights reserved.
  </footer>
</body>
</html>
<section id="contact" className="bg-gray-100 py-10 px-4">
  <h2 className="text-2xl font-bold mb-4 text-center">Contact Us</h2>
  <div className="text-center text-gray-800">
    <p className="mb-2">📞 Call or WhatsApp: <a href="tel:+94771063321" className="text-blue-600 font-semibold">0771063321</a></p>
    <p>📧 Email: <a href="mailto:chemwarriors@gmail.com" className="text-blue-600">chemwarriors@gmail.com</a></p>
  </div>
</section>
{/* Floating Menu - Add this just before closing </div> or at the bottom of JSX return */}
<div className="fixed bottom-0 left-0 right-0 bg-white border-t shadow-md flex justify-around py-2 text-sm sm:hidden z-50">
  <a href="#home" className="text-blue-600 font-medium">Home</a>
  <a href="#schedule" className="text-blue-600 font-medium">Schedule</a>
  <a href="#join" className="text-blue-600 font-medium">Join</a>
  <a href="#contact" className="text-blue-600 font-medium">Contact</a>
</div>
return (
  <main>
    {/* Existing sections like video, schedule, etc. */}

    {/* Paste Contact Section here */}
    <section id="contact">...</section>

    {/* Paste Floating Menu just before closing tag */}
    <div className="fixed bottom-0 ...">...</div>
  </main>
);
