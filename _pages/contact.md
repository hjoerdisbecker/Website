---
title: "Contact"
permalink: /contact/
---

**Institution:**
Faculty of Divinity
University of Cambridge

<p id="contact-email"></p>

<script>
  (function() {
    // hb462@cam.ac.uk encoded as char codes
    var c = [104,98,52,54,50,64,99,97,109,46,97,99,46,117,107];
    var email = c.map(function(n){ return String.fromCharCode(n); }).join('');
    var a = document.createElement('a');
    a.href = 'mailto:' + email;
    a.textContent = email;
    document.getElementById('contact-email').appendChild(a);
  })();
</script>
