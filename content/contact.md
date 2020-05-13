---
title: "Contact"
date: 2020-05-06
type: "page"
---

Send me a message.

<form action="https://us-central1-mattlevan.cloudfunctions.net/contact" method="POST">
  <input type="text" name="name" id="name" placeholder="Name" required>
  <input type="email" name="email" id="email" placeholder="Email" required>
  <textarea name="message" id="message" placeholder="Message" style="height:150px" required></textarea>
  <input type="submit"></button>
</form>