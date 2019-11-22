---
layout: default
title: Contact
id: contact
---

<form name="contact" method="POST" data-netlify="true">
    <p>
        <label> Your Name: <input type="text" name="name"/> </label>
    </p>
    <p>
        <label> Your Email: <input type="email" name="email"/> </label>
    </p>
    <p>
        <div class="form-group">
            <label for="message">Message:</label>
        <textarea class="form-control" id="message" rows="3" spellcheck="false"></textarea>
         </div>
    </p>
    <p>
        <button type="submit"> Send</button>
        <button type="reset"> Reset</button>
    </p>
</form>
