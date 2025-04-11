
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pavuluri Neeraj - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Inter', sans-serif; line-height: 1.6; background: #f9f9f9; color: #333; }
    header { background: #111; color: #fff; padding: 2rem 1rem; text-align: center; }
    header h1 { font-size: 2.5rem; }
    nav ul { display: flex; justify-content: center; gap: 1.5rem; list-style: none; margin-top: 1rem; }
    nav a { color: #fff; text-decoration: none; font-weight: bold; }
    section { padding: 4rem 1rem; max-width: 900px; margin: auto; }
    .projects { display: grid; gap: 2rem; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); }
    .project { background: #fff; border-radius: 8px; padding: 1rem; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
    .project h3 { margin-bottom: 0.5rem; }
    footer { background: #111; color: #ccc; text-align: center; padding: 2rem 1rem; }
    a.button { background: #007bff; color: #fff; padding: 0.75rem 1.5rem; display: inline-block; border-radius: 5px; text-decoration: none; margin-top: 1rem; }
  </style>
</head>
<body>
  <header>
    <h1>Pavuluri Neeraj</h1>
    <p>Web Developer | Programmer | Tech Enthusiast</p>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Pavuluri Neeraj, a passionate web developer who loves building beautiful and functional websites and applications. I specialize in front-end technologies and enjoy learning new tools and frameworks.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>Portfolio Website</h3>
        <p>A modern personal portfolio built with HTML, CSS, and JavaScript.</p>
      </div>
      <div class="project">
        <h3>To-Do App</h3>
        <p>Simple and sleek to-do list app with local storage support.</p>
      </div>
      <div class="project">
        <h3>Weather App</h3>
        <p>Responsive weather dashboard using a public API to fetch weather data.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Feel free to reach out to me via email or connect on LinkedIn.</p>
    <a href="mailto:pavulurineeraj@example.com" class="button">Email Me</a>
  </section>

  <footer>
    <p>&copy; 2025 Pavuluri Neeraj. All rights reserved.</p>
  </footer>
</body>

