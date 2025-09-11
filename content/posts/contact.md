+++
Menu = 'main'
title = "Contact"
description = "Private tutoring in Economics, Management, and related subjects for A-level, IB, and university students."
author = "Jakub Trybull"
date = "2025-09-01T01:01:01+01:00"
+++
<section class="booking-section" style="text-align: center; margin-top: 2rem;">
  <!-- Booking text -->
  <p style="color: #004AAD; font-style: italic; font-size: 1.5rem;">
    Book your <span style="color: #A69408; font-weight: bold;">free</span> video consultation! :
  </p>

  <!-- Book button -->
  <a href="https://calendly.com/jakubtrybull/introductory-call" target="_blank" class="book-button">
    <img src="/img/bookbutton.jpg" alt="Book" class="book-img">
    <span class="book-text">Book</span>
  </a>
</section>

<!-- JS fallback for image -->
<script>
document.addEventListener("DOMContentLoaded", function() {
  const buttons = document.querySelectorAll(".book-button");
  buttons.forEach(btn => {
    const img = btn.querySelector("img");
    const text = btn.querySelector(".book-text");

    // Show text if image fails to load
    img.onerror = () => {
      text.style.display = "block";
    };
  });
});
</script>- 

(After which you should have my contact details, if you have further queries.)
