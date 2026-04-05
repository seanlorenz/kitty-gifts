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

  <!-- FAQ -->
  <div class="faq">
    <h2 class="section">Frequently Asked Questions</h2>

    <div class="faq-item">
      <div class="faq-q">How do I log a kill? <span class="arrow">▼</span></div>
      <div class="faq-a">Tap the <strong>➕ New Kill</strong> tab at the bottom of the app. Select the type of animal your cat brought you, then tap the big button. A eulogy will be generated automatically and your kill will appear on your Home feed.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">How do I invite a friend to compete? <span class="arrow">▼</span></div>
      <div class="faq-a">Go to the <strong>🐱 My Cat</strong> tab and tap <strong>Generate Invite Link</strong>. Copy the link and send it to your friend via text, email, or any app you like. Once they open the link and sign in, you'll both automatically appear on each other's leaderboard. No friend request needed.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">Why isn't my friend showing up on the leaderboard? <span class="arrow">▼</span></div>
      <div class="faq-a">Make sure your friend opened the invite link <em>before</em> signing in for the first time. If they signed in first and then tried the link, the connection may not have been established. Ask them to try signing out, then opening the invite link again and signing back in.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">My kills disappeared after reinstalling the app. What happened? <span class="arrow">▼</span></div>
      <div class="faq-a">As long as you sign in with the same Google account you used before, all your data will be restored automatically. Your kills are stored in the cloud, not on your device, so reinstalling won't erase anything.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">The Google sign-in isn't working. What should I do? <span class="arrow">▼</span></div>
      <div class="faq-a">
        Try these steps in order:
        <br /><br />
        1. Make sure you have a stable internet connection.<br />
        2. Force-close the app and reopen it.<br />
        3. Check that your iOS is up to date.<br />
        4. If the issue persists, email us with your device model and iOS version.
      </div>
    </div>

    <div class="faq-item">
      <div class="faq-q">How do I change my cat's name? <span class="arrow">▼</span></div>
      <div class="faq-a">Go to the <strong>🐱 My Cat</strong> tab and tap <strong>Rename Cat</strong>. Type the new name and tap Save.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">How do I add or change my cat's photo? <span class="arrow">▼</span></div>
      <div class="faq-a">Go to the <strong>🐱 My Cat</strong> tab. Tap the 📷 button on your cat's profile photo, or tap <strong>New Photo</strong>. Choose an image from your photo library. The photo will be cropped to a square and saved to your profile automatically.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">How are points calculated? <span class="arrow">▼</span></div>
      <div class="faq-a">Different animals are worth different point values based on how impressive (or unlikely) the catch is. Snakes are worth 150 points, bunnies 120, mystery animals 200 — all the way down to bugs at 20 points. Points accumulate over time and determine your position on the leaderboard.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">Can I delete a kill entry I logged by mistake? <span class="arrow">▼</span></div>
      <div class="faq-a">Individual kill deletion isn't available in the current version of the app. If you need a specific entry removed, contact us at sean.d.lorenz@gmail.com with your account email and a description of the entry and we'll remove it for you.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">Is Kitty Gifts free? <span class="arrow">▼</span></div>
      <div class="faq-a">Yes — Kitty Gifts is completely free to download and use. There are no in-app purchases or subscriptions.</div>
    </div>

    <div class="faq-item">
      <div class="faq-q">What data does Kitty Gifts collect? <span class="arrow">▼</span></div>
      <div class="faq-a">We collect your Google account name and email (for sign-in), your cat's name and optional photo, and your kill log entries. We don't collect location data, contacts, or payment information. See our full <a href="privacy-policy.html" style="color:#FF6B35;">Privacy Policy</a> for details.</div>
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
