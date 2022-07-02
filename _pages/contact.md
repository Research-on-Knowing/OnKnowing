---
title: "Contact"
permalink: "/contact.html"
---

<form name="contactForm">    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<button class="btn btn-success" type="submit">Send</button>
</form>

<div class="col-md-6">
<a class="btn btn-success" href="mailto:{{ site.email }}?subject=Visitor to {{ site.name }} website">Email {{ site.email}}</a>
<div>