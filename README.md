# sonukumar.github.io
Want to help people who are struggling with mental health or who feel lonely.
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>You're Not Alone | Talk & Heal</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #f5f7fb;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      color: white;
      padding: 50px 20px;
      text-align: center;
    }
    header h1 { font-size: 2.2rem; }
    header p { font-size: 1.1rem; }
    section {
      padding: 30px 15px;
      max-width: 1000px;
      margin: auto;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 16px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
      margin-bottom: 25px;
    }
    h2 {
      color: #2575fc;
      font-size: 1.5rem;
    }
    .chat-box {
      border: 1px solid #ddd;
      border-radius: 12px;
      padding: 12px;
      height: 260px;
      overflow-y: auto;
      background: #fafafa;
      font-size: 0.95rem;
    }
    .chat-input {
      display: flex;
      margin-top: 10px;
    }
    .chat-input input {
      flex: 1;
      padding: 12px;
      border-radius: 10px 0 0 10px;
      border: 1px solid #ccc;
      outline: none;
      font-size: 1rem;
    }
    .chat-input button {
      padding: 12px 18px;
      border: none;
      background: #2575fc;
      color: white;
      border-radius: 0 10px 10px 0;
      cursor: pointer;
      font-size: 1rem;
    }
    footer {
      background: #222;
      color: #ccc;
      text-align: center;
      padding: 20px 10px;
      font-size: 0.9rem;
    }
    @media (max-width: 600px) {
      header h1 { font-size: 1.8rem; }
      h2 { font-size: 1.3rem; }
      .chat-box { height: 220px; }
    }
  </style>
</head>
<body><header>
  <h1>You’re Not Alone 🤍</h1>
  <p>A safe place to talk, share, and feel heard</p>
</header><section>
  <div class="card">
    <h2>About Me</h2>
    <p>
      Hello, my name is <strong>Sonu Kumar</strong>. I created this platform to support people who feel lonely, sad, stressed, or emotionally tired.
      Sometimes we don’t need advice — we just need someone who listens. I’m here to listen to you without judgment.
    </p>
  </div>  <div class="card">
    <h2>What I Offer</h2>
    <ul>
      <li>One-to-one text conversation</li>
      <li>Emotional support for loneliness and stress</li>
      <li>A safe and respectful environment</li>
      <li>Friendly and understanding chats</li>
    </ul>
    <p><em>Note: This is not medical or professional therapy, but a human-to-human support space.</em></p>
  </div>  <div class="card">
    <h2>Live Chat</h2>
    <p><strong>Welcome 🤍</strong><br>
    If you're feeling lonely, stressed, or just need someone to listen — you’re in the right place.
    You can start chatting with me anytime. Your identity is not required.</p><div class="chat-box" id="chatBox">
  <p><strong>System:</strong> Hi 🤍 I’m here for you. You can talk freely and safely.</p>
</div>

<div class="chat-input">
  <input type="text" id="messageInput" placeholder="Type your message here..." />
  <button onclick="sendMessage()">Send</button>
</div>

  </div><div class="chat-input">
  <input type="text" id="messageInput" placeholder="Type your message..." />
  <button onclick="sendMessage()">Send</button>
</div>

  </div>
</section><footer>
  <p>© 2025 You’re Not Alone | Created with care 🤍</p>
</footer><section>
  <div class="card">
    <h2>Custom Domain (Optional)</h2>
    <p>
      You can use a personal domain like <strong>www.youarenotalone.in</strong> instead of GitHub’s link.
    </p>
    <ul>
      <li>Buy a domain from GoDaddy, Namecheap, or Google Domains</li>
      <li>Connect it to GitHub Pages (free hosting remains)</li>
      <li>This improves trust and professionalism</li>
    </ul>
    <p><em>I can guide you step-by-step whenever you’re ready.</em></p>
  </div>
</section><script>
  function sendMessage() {
    const input = document.getElementById('messageInput');
    const chatBox = document.getElementById('chatBox');

    if (input.value.trim() !== '') {
      const msg = document.createElement('p');
      msg.innerHTML = '<strong>You:</strong> ' + input.value;
      chatBox.appendChild(msg);
      chatBox.scrollTop = chatBox.scrollHeight;
      input.value = '';
    }
  }
</script><!-- Tawk.to Live Chat Script --><script type="text/javascript">
var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
(function(){
var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
s1.async=true;
s1.src='https://embed.tawk.to/REPLACE_WITH_YOUR_ID/1hxxxxx';
s1.charset='UTF-8';
s1.setAttribute('crossorigin','*');
s0.parentNode.insertBefore(s1,s0);
})();
</script><!-- End Tawk.to Live Chat Script --></body>
</html>
