---
layout: default
title: Contact
id: contact
---
<h5>Feel free to send a message!</h5>

<br>

<br>

<form name="contact" method="POST" data-netlify="true">
    <p>
        <label> Your Name: <input type="text" name="name"/> </label>
    </p>
    <p>
        <label> Your Email: <input type="email" name="email"/> </label>
    </p>
    <p>
        Message:
        <textarea name:"message" id="message" cols="40" rows="2"></textarea>
    </p>
    <p>
        <button type="submit"> Send</button>
        <button type="reset"> Reset</button>
    </p>
</form>
