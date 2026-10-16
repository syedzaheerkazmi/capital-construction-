inbox .html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Capital Construction — house construction, grey structure, finishing and renovation services in Islamabad, Pakistan.">
  <meta name="theme-color" content="#12243a">
  <title>Capital Construction | Islamabad</title>
  <style>
    :root{--navy:#12243a;--blue:#1e4568;--gold:#d7a94b;--ink:#182230;--muted:#647184;--paper:#f5f7fa;--white:#fff}
    *{box-sizing:border-box} html{scroll-behavior:smooth}
    body{margin:0;font-family:Arial,"Noto Sans",sans-serif;color:var(--ink);line-height:1.65;background:#fff}
    a{color:inherit;text-decoration:none}
    .wrap{width:min(1120px,92%);margin:auto}
    header{position:sticky;top:0;z-index:10;background:rgba(18,36,58,.97);color:#fff;border-bottom:2px solid var(--gold)}
    .nav{display:flex;align-items:center;justify-content:space-between;gap:20px;padding:14px 0}
    .brand{font-weight:800;letter-spacing:.4px;font-size:1.08rem}.brand span{color:var(--gold)}
    nav{display:flex;gap:20px;flex-wrap:wrap;font-size:.92rem}nav a:hover{color:var(--gold)}
    .hero{background:linear-gradient(120deg,rgba(11,27,45,.94),rgba(23,58,88,.83)),linear-gradient(45deg,#12243a,#53718d);color:#fff;padding:92px 0 86px}
    .hero-grid{display:grid;grid-template-columns:1.2fr .8fr;gap:40px;align-items:center}
    .eyebrow{color:var(--gold);text-transform:uppercase;letter-spacing:2px;font-weight:700;font-size:.8rem}
    h1{font-size:clamp(2.2rem,5vw,4.1rem);line-height:1.12;margin:12px 0 18px}
    .hero p{font-size:1.1rem;color:#e1e8ef;max-width:650px}
    .actions{display:flex;gap:12px;flex-wrap:wrap;margin-top:28px}
    .btn{display:inline-block;padding:12px 18px;border-radius:7px;font-weight:700;border:1px solid transparent}
    .btn-gold{background:var(--gold);color:#182230}.btn-outline{border-color:#d9e3ed;color:#fff}
    .hero-card{background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.2);border-radius:16px;padding:28px}
    .hero-card h3{margin-top:0;color:var(--gold)}.hero-card li{margin:10px 0}
    section{padding:68px 0}.soft{background:var(--paper)}
    .section-head{text-align:center;max-width:740px;margin:0 auto 36px}
    .section-head h2{font-size:clamp(1.8rem,3vw,2.5rem);margin:8px 0;color:var(--navy)}
    .section-head p{color:var(--muted);margin:0}
    .cards{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
    .card{background:#fff;border:1px solid #e3e8ee;border-radius:12px;padding:24px;box-shadow:0 8px 24px rgba(18,36,58,.05)}
    .icon{font-size:1.8rem}.card h3{color:var(--navy);margin:12px 0 8px}.card p{color:var(--muted);margin:0}
    .project-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .project{min-height:205px;border-radius:12px;padding:22px;display:flex;flex-direction:column;justify-content:flex-end;color:white;background:linear-gradient(145deg,#284e70,#12243a);position:relative;overflow:hidden}
    .project:before{content:"";position:absolute;width:170px;height:170px;border:2px solid rgba(215,169,75,.45);transform:rotate(35deg);right:-35px;top:-45px}
    .project strong,.project span{position:relative}.project strong{font-size:1.15rem}.project span{font-size:.9rem;color:#e0e7ef}
    .note{margin-top:20px;text-align:center;color:var(--muted);font-size:.92rem}
    .steps{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}
    .step{padding:20px;border-left:3px solid var(--gold);background:#fff;border-radius:0 8px 8px 0}
    .step b{display:block;color:var(--navy);margin-bottom:6px}
    .contact{background:var(--navy);color:#fff}.contact .section-head h2{color:#fff}.contact .section-head p{color:#d5dee8}
    .contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:30px;align-items:start}
    .contact-box{border:1px solid rgba(255,255,255,.2);padding:24px;border-radius:12px;background:rgba(255,255,255,.05)}
    .contact-box p{margin:8px 0;color:#e0e7ef}.contact-box a{color:var(--gold);font-weight:700}
    .form label{display:block;margin:12px 0 5px}.form input,.form textarea{width:100%;padding:12px;border-radius:6px;border:1px solid #ccd5df;font:inherit}
    .form textarea{min-height:100px;resize:vertical}.form button{margin-top:14px;cursor:pointer}
    footer{background:#0a1727;color:#c9d2dc;padding:24px 0;font-size:.9rem}
    .footer-row{display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap}
    .socials{display:flex;gap:14px;flex-wrap:wrap}.socials a{color:var(--gold)}
    .warning{background:#fff7e6;border:1px solid #f1d18b;color:#5c4717;padding:12px 14px;border-radius:8px;font-size:.9rem;margin-top:18px}
    @media(max-width:800px){.hero-grid,.contact-grid{grid-template-columns:1fr}.cards,.project-grid{grid-template-columns:1fr 1fr}.steps{grid-template-columns:1fr 1fr}nav{gap:10px;font-size:.82rem}}
    @media(max-width:520px){.nav{align-items:flex-start;flex-direction:column}.cards,.project-grid,.steps{grid-template-columns:1fr}.hero{padding:64px 0}.actions .btn{width:100%;text-align:center}}
  </style>
</head>
<body>
<header>
  <div class="wrap nav">
    <a class="brand" href="#home">CAPITAL <span>CONSTRUCTION</span></a>
    <nav aria-label="Main navigation">
      <a href="#services">Services</a><a href="#projects">Projects</a><a href="#process">Our Process</a><a href="#contact">Contact</a>
    </nav>
  </div>
</header>

<main>
  <section class="hero" id="home">
    <div class="wrap hero-grid">
      <div>
        <div class="eyebrow">Building with care • Islamabad</div>
        <h1>Build your home with confidence.</h1>
        <p>Capital Construction provides house construction, grey structure, finishing and renovation services. We focus on clear communication, careful workmanship and project coordination.</p>
        <div class="actions">
          <a class="btn btn-gold" href="#contact">Request a Consultation</a>
          <a class="btn btn-outline" href="#projects">View Our Work</a>
        </div>
      </div>
      <aside class="hero-card">
        <h3>Our Services</h3>
        <ul>
          <li>House construction & grey structure</li>
          <li>RCC, shuttering and concrete work</li>
          <li>Finishing, renovation and repairs</li>
          <li>Project coordination and site supervision</li>
        </ul>
      </aside>
    </div>
  </section>

  <section id="services">
    <div class="wrap">
      <div class="section-head">
        <div class="eyebrow">What we do</div><h2>Construction services</h2>
        <p>From the structure to the finishing details, discuss your project requirements with our team.</p>
      </div>
      <div class="cards">
        <article class="card"><div class="icon">🏗️</div><h3>Grey Structure</h3><p>Construction coordination for foundations, columns, beams, slabs, masonry and related structural work according to approved plans.</p></article>
        <article class="card"><div class="icon">🏠</div><h3>Complete Construction</h3><p>Plan and coordinate the major stages of a home-building project, with scope and materials agreed in advance.</p></article>
        <article class="card"><div class="icon">🛠️</div><h3>Finishing & Renovation</h3><p>Interior and exterior finishing, repairs and renovation work tailored to the project requirements.</p></article>
      </div>
    </div>
  </section>

  <section class="soft" id="projects">
    <div class="wrap">
      <div class="section-head">
        <div class="eyebrow">Our portfolio</div><h2>Featured projects</h2>
        <p>Replace these sample cards with real project photos, locations and descriptions.</p>
      </div>
      <div class="project-grid">
        <div class="project"><strong>Residential Construction</strong><span>Add project location and details</span></div>
        <div class="project"><strong>Grey Structure</strong><span>Add project location and details</span></div>
        <div class="project"><strong>Exterior & Finishing</strong><span>Add project location and details</span></div>
      </div>
      <p class="note">Please publish only genuine project photos and accurate claims about your work.</p>
    </div>
  </section>

  <section id="process">
    <div class="wrap">
      <div class="section-head">
        <div class="eyebrow">How we work</div><h2>A clear process from start to finish</h2>
        <p>Agree on the scope, responsibilities, schedule and quality checks before work begins.</p>
      </div>
      <div class="steps">
        <div class="step"><b>01 · Discuss</b>Share your plot details, drawings, requirements and budget range.</div>
        <div class="step"><b>02 · Scope</b>Confirm work items, labour/material responsibilities and payment stages in writing.</div>
        <div class="step"><b>03 · Build</b>Coordinate the site team and follow the approved drawings and technical instructions.</div>
        <div class="step"><b>04 · Review</b>Review completed work and record agreed changes and outstanding items.</div>
      </div>
      <div class="warning"><strong>Important:</strong> Structural design and safety-critical decisions should be checked by a qualified structural engineer. This website is a business introduction, not a substitute for engineering approval.</div>
    </div>
  </section>

  <section class="contact" id="contact">
    <div class="wrap">
      <div class="section-head">
        <div class="eyebrow">Get in touch</div><h2>Tell us about your project</h2>
        <p>Serving Islamabad, Pakistan.</p>
      </div>
      <div class="contact-grid">
        <div class="contact-box">
          <h3>Capital Construction</h3>
          <p><strong>Service area:</strong> Islamabad, Pakistan</p>
          <p><strong>Phone / WhatsApp:</strong> +92 311 1526358</p>
          <p><strong>Email:</strong> Add your business email</p>
          <p><strong>Office address:</strong> Add only if you want it public</p>
          <div class="socials" style="margin-top:18px">
            <a href="#" aria-label="Facebook profile">Facebook</a>
            <a href="#" aria-label="Instagram profile">Instagram</a>
            <a href="#" aria-label="TikTok profile">TikTok</a>
            <a href="#" aria-label="YouTube channel">YouTube</a>
            <a href="#" aria-label="LinkedIn profile">LinkedIn</a>
            <a href="#" aria-label="WhatsApp Business">WhatsApp</a>
          </div>
          <p style="font-size:.85rem">Replace the links above with your real official profile links before publishing.</p>
        </div>
        <form class="contact-box form" onsubmit="return sendMessage(event)">
          <h3>Quick enquiry</h3>
          <label for="name">Your name</label><input id="name" name="name" required>
          <label for="phone">Phone number</label><input id="phone" name="phone" inputmode="tel" required>
          <label for="details">Project details</label><textarea id="details" name="details" placeholder="Area, plot size and type of work"></textarea>
          <button class="btn btn-gold" type="submit">Prepare WhatsApp Message</button>
          <p style="font-size:.82rem;color:#d5dee8">This form opens WhatsApp after you add your business number in the code.</p>
        </form>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="wrap footer-row">
    <div>© <span id="year"></span> Capital Construction. All rights reserved.</div>
    <div>Professional construction services • Islamabad</div>
  </div>
</footer>
<script>
  document.getElementById('year').textContent = new Date().getFullYear();
  function sendMessage(event) {
    event.preventDefault();
    // Replace 923001234567 with your WhatsApp number in international format, digits only.
    const businessNumber = "923111526358";
    const name = document.getElementById('name').value.trim();
    const phone = document.getElementById('phone').value.trim();
    const details = document.getElementById('details').value.trim();
    const message = `New construction enquiry%0AName: ${encodeURIComponent(name)}%0APhone: ${encodeURIComponent(phone)}%0AProject: ${encodeURIComponent(details)}`;
    if (businessNumber === "923111526358") {
      alert("Before publishing, add your real WhatsApp number in index.html. The form is not connected yet.");
      return false;
    }
    window.open(`https://wa.me/${businessNumber}?text=${message}`, "_blank", "noopener");
    return false;
  }
</script>
</body>
</html>
