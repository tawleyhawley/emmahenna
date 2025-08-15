<form id="contact-form" method="POST" action="https://your-api-gateway-url/send-email">
  <label for="name">Name</label>
  <input type="text" id="name" name="name" required><br/>

  <label for="email">Email</label>
  <input type="email" id="email" name="email" required><br/>

  <label for="subject">Subject</label>
  <input type="text" id="subject" name="subject" required><br/>

  <label for="message">Message</label>
  <textarea id="message" name="message" required></textarea><br/>

  <button type="submit">Send Message</button>
</form>
