<!DOCTYPE html>
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

</head>
<body>

<header>
  <span class="emoji">🎁</span>
  <h1>Kitty Gifts Support</h1>
  <p>Something broken? Question about your cat's kill count? We've got you.</p>
</header>

<main>

  <!-- Contact card -->
  <div class="contact-card">
    <div class="icon">✉️</div>
    <div>
      <h2>Contact Us</h2>
      <p>
        Can't find an answer below? Send us an email and we'll get back to you within 2 business days.
        Please include your device model and iOS version if you're reporting a bug.
      </p>
      <a class="btn" href="mailto:sean.d.lorenz@gmail.com">Email Support</a>
    </div>
  </div>

  
  <!-- Delete account -->
  <div class="delete-section">
    <h2>🗑️ Delete Your Account</h2>
    <p>
      To permanently delete your Kitty Gifts account and all associated data — including your kill log, cat profile, and friend connections — email us at <a href="mailto:sean.d.lorenz@gmail.com">sean.d.lorenz@gmail.com</a> with the subject line <strong>"Delete My Account"</strong> and the Google email address associated with your account.
    </p>
    <p>
      We'll process your request within 30 days and confirm by email once it's done.
    </p>
  </div>

</main>

<footer>
  &copy; 2026 Kitty Gifts &nbsp;·&nbsp;
  <a href="privacy-policy.html">Privacy Policy</a>
</footer>

<script>
  document.querySelectorAll(".faq-q").forEach(function(q) {
    q.addEventListener("click", function() {
      var item = this.closest(".faq-item");
      var isOpen = item.classList.contains("open");
      document.querySelectorAll(".faq-item").forEach(function(i) { i.classList.remove("open"); });
      if (!isOpen) item.classList.add("open");
    });
  });
</script>

</body>
</html>
