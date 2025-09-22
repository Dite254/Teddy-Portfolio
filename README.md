<!doctype html>
<article class="project">
<h3>Personal Photography Series</h3>
<p class="muted">Curated a 12-photo series focused on urban portraiture. Exhibited online and used as social content for portfolio growth.</p>
<div class="meta">Tools: Lightroom • Canon EOS</div>
</article>


</div>
</section>


<section id="contact" class="card" style="margin-top:18px">
<h2>Contact</h2>
<p class="muted">Want to work together? Send an email or use the contact form below.</p>


<form id="contactForm" onsubmit="event.preventDefault();openModal();">
<label for="name">Name</label>
<input id="name" placeholder="Your name" required />
<label for="email">Email</label>
<input id="email" type="email" placeholder="you@example.com" required />
<label for="message">Message</label>
<textarea id="message" rows="4" placeholder="Tell me about the project" required></textarea>
<div style="margin-top:12px"><button class="btn" type="submit">Send message</button></div>
</form>
</section>


<footer>
<div class="muted">Built with ♥ · Hosted on GitHub Pages · Replace content and images before public launch</div>
</footer>
</main>
</div>


<div id="modal" class="modal" aria-hidden="true">
<div class="panel">
<h3>Contact form submitted</h3>
<p class="muted">This demo doesn't actually send messages. Replace the form action with a service (Formspree, Netlify Forms, or a server) or use a mailto link in production.</p>
<div style="margin-top:12px;text-align:right"><button class="btn" onclick="closeModal()">Close</button></div>
</div>
</div>


<script>
function openModal(){document.getElementById('modal').classList.add('open');document.getElementById('modal').setAttribute('aria-hidden','false')}
function closeModal(){document.getElementById('modal').classList.remove('open');document.getElementById('modal').setAttribute('aria-hidden','true')}


// Small UX: enable deep links for projects or contact
(function(){
if(location.hash){var el=document.querySelector(location.hash);if(el)el.scrollIntoView({behavior:'smooth',block:'center'})}
})();
</script>
