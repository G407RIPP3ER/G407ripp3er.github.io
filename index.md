<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>ak sv – red team & ai security</title>

  <!-- Tailwind via CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- AOS (Animate On Scroll) -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  <style>
    /* Custom tweaks */
    body { background: #0b0b0b; color: #e0e0e0; }
    .neon { text-shadow: 0 0 8px #00ffff, 0 0 12px #00ffff; }
    .btn-neon {
      @apply px-4 py-2 border border-cyan-400 rounded hover:shadow-lg transition-shadow;
    }
  </style>
</head>
<body class="min-h-screen flex flex-col">

  <!-- Hero -->
  <header class="flex-1 flex flex-col justify-center items-center text-center p-8">
    <h1 class="text-5xl neon font-mono" data-aos="fade-down">ak sv</h1>
    <p class="mt-4 text-xl" data-aos="fade-up" data-aos-delay="200">
      red teamer • security researcher • adrenaline junkie
    </p>
    <a href="#projects" class="btn-neon mt-6 neon" data-aos="zoom-in" data-aos-delay="400">
      view projects
    </a>
  </header>

  <!-- Projects Section -->
  <section id="projects" class="p-8 bg-gray-900">
    <h2 class="text-3xl neon font-mono mb-6" data-aos="fade-right">projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <!-- Project Card -->
      <div class="bg-gray-800 p-6 rounded-xl" data-aos="flip-left">
        <h3 class="text-2xl neon font-semibold mb-2">powershell toolkit</h3>
        <p>Custom red-team modules: enumeration, credential theft, stealth exfil.</p>
        <a href="https://github.com/G407RIPP3ER/ps-tools" class="text-cyan-300 inline-block mt-2 hover:underline">
          view repo →
        </a>
      </div>
      <!-- Repeat for more projects -->
      <div class="bg-gray-800 p-6 rounded-xl" data-aos="flip-right" data-aos-delay="100">
        <h3 class="text-2xl neon font-semibold mb-2">ai-driven c2</h3>
        <p>Proof-of-concept for a GPT-powered command-and-control framework.</p>
        <a href="https://github.com/G407RIPP3ER/ai-c2" class="text-cyan-300 inline-block mt-2 hover:underline">
          view repo →
        </a>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <footer class="text-center p-6 mt-auto">
    <p data-aos="fade-up">📫 &nbsp; ak.sv [at] example.com</p>
    <p class="mt-2 text-sm text-gray-500" data-aos="fade-up" data-aos-delay="100">
      © 2025 ak sv
    </p>
  </footer>

  <!-- AOS Init -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script> AOS.init({ duration: 800, once: true }); </script>
</body>
</html>
