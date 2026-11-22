---
title: "Contact"
permalink: /contact/
---

**Institutions:**
Faculty of Theology, University of Copenhagen  
Faculty of Divinity, University of Cambridge

<p id="contact-email"></p>

<script>
  (function() {
    // hbl@teol.ku.dk and hb462@cam.ac.uk encoded as char codes
    var codes = [[104,98,108,64,116,101,111,108,46,107,117,46,100,107], [104,98,52,54,50,64,99,97,109,46,97,99,46,117,107]];
    var el = document.getElementById('contact-email');
    codes.forEach(function(c, i) {
      var email = c.map(function(n){ return String.fromCharCode(n); }).join('');
      var a = document.createElement('a');
      a.href = 'mailto:' + email;
      a.textContent = email;
      if (i > 0) el.appendChild(document.createElement('br'));
      el.appendChild(a);
    });
  })();
</script>
