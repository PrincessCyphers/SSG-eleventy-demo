---
layout: layouts/post.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 4
---

<div>
  <div class="container">
  <form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" required /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" required /></label>
  </p>
  <p>
    <label>Your Role: <select name="role[]" multiple>
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
  </form>
  </div>

<!-----T&Cs------->
<div class="container">
<input type="checkbox" id="T&Cs" name="T&Cs" value="T&Cs">
<label for="T&Cs">I agree to the Terms of Service</label><br>
</div>

<!-----Subscribe------>
<form action="action_page.php">
  <div class="container">
  <br>
  <br>
    <h2>Enjoying this? Subscribe to our Newsletter</h2>
    <p>For updates and special announcements!</p>
  </div>

  <div class="container" style="background-color:white">
    <input type="text" placeholder="Email address" name="mail" required>
    <label>
      <input type="checkbox" checked="checked" name="subscribe"> Monthly Newsletter
    </label>
  </div>

  <div class="container">
    <input type="submit" value="Subscribe">
  </div>
</form>

</div>