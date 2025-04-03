---
layout: default
title: Khalil
author: "Khalil"
date: 2024-05-11 10:00:00
last_modified_at: 2025-03-22 10:30:00
css: 
  - /static/css/index.css
---
<form action="https://formspree.io/f/mldrezaz" method="POST">
    <h2>SIGN UP NOW FOR THE LATEST INFO AND UPDATES</h2>
    <p>BY REGISTERING, I AGREE TO THE 
        <a href="https://khaliiil.com/terms-conditions">TERMS & CONDITIONS</a> AND 
        <a href="https://khaliiil.com/privacy-policy">PRIVACY POLICY</a>
    </p>
    <div class="input-container">
        <input required type="email" id="email" name="email" placeholder=" " autocomplete="off">
        <label for="email">EMAIL ADDRESS</label>
    </div>
    <button id="subtn" type="submit">SEND</button>
</form>

<div class="expandable-row" onclick="toggleMessage(this)"><p class="left-text">MORE</p><p class="right-text">+</p></div>
<div class="expandable-message">
    Subscribe to my newsletter for updates, insights, and exclusive content straight to your inbox.  
    No spam—just things worth reading. By signing up, you agree to the  
    <a href="https://khaliiil.com/terms-conditions">TERMS & CONDITIONS</a> AND 
        <a href="https://khaliiil.com/privacy-policy">PRIVACY POLICY</a>.  
    Unsubscribe anytime.
</div>

<script>
function toggleMessage(element) {
    var message = element.nextElementSibling;
    var plusIcon = element.querySelector(".right-text");

    if (message.style.display === "none" || message.style.display === "") {
        message.style.display = "block";
        plusIcon.textContent = "−"; 
    } else {
        message.style.display = "none";
        plusIcon.textContent = "+";
    }
}
</script>