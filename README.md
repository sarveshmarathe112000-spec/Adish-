<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>All the Best Dr. Bhavna! | AIAPGET 2026</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
</head>
<body class="bg-gradient-to-br from-teal-900 via-emerald-800 to-slate-900 min-h-screen text-white flex flex-col items-center justify-between p-6">

  <!-- Header Section -->
  <header class="text-center mt-8 animate__animated animate__fadeInDown">
    <span class="bg-emerald-500/20 text-emerald-300 text-xs font-semibold uppercase tracking-widest px-4 py-1.5 rounded-full border border-emerald-500/30">
      AIAPGET Exam • Aug 22
    </span>
    <h1 class="text-4xl md:text-6xl font-extrabold mt-4 tracking-tight bg-clip-text text-transparent bg-gradient-to-r from-teal-200 via-emerald-400 to-amber-200">
      All the Best, Dr. Bhavna!
    </h1>
    <p class="mt-3 text-slate-300 text-lg max-w-lg mx-auto">
      Your dedication, late nights, and passion for medicine are about to pay off.
    </p>
  </header>

  <!-- Prep Milestones Section -->
  <main class="w-full max-w-4xl my-8">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      
      <div class="bg-slate-800/60 backdrop-blur-md p-6 rounded-2xl border border-slate-700/50 text-center hover:border-emerald-500/50 transition">
        <div class="text-3xl mb-2">📚</div>
        <h3 class="text-2xl font-bold text-emerald-400">100%</h3>
        <p class="text-slate-300 text-sm mt-1">Syllabus Mastered</p>
      </div>

      <div class="bg-slate-800/60 backdrop-blur-md p-6 rounded-2xl border border-slate-700/50 text-center hover:border-emerald-500/50 transition">
        <div class="text-3xl mb-2">🧬</div>
        <h3 class="text-2xl font-bold text-amber-400">Countless</h3>
        <p class="text-slate-300 text-sm mt-1">MCQs & Revisions Solved</p>
      </div>

      <div class="bg-slate-800/60 backdrop-blur-md p-6 rounded-2xl border border-slate-700/50 text-center hover:border-emerald-500/50 transition">
        <div class="text-3xl mb-2">🩺</div>
        <h3 class="text-2xl font-bold text-teal-300">Ready</h3>
        <p class="text-slate-300 text-sm mt-1">To Claim Your MD/MS Seat</p>
      </div>

    </div>

    <!-- Interactive Action Box -->
    <div class="mt-10 bg-gradient-to-r from-emerald-600/30 to-teal-600/30 backdrop-blur-lg p-8 rounded-3xl border border-emerald-500/40 text-center shadow-2xl">
      <h2 class="text-2xl font-bold mb-3">Unlock Your Victory Boost 🌟</h2>
      <p class="text-slate-200 text-sm mb-6">Click below to ignite your exam day energy!</p>
      
      <button id="wishBtn" onclick="triggerBoost()" class="bg-gradient-to-r from-amber-400 to-emerald-400 hover:from-amber-300 hover:to-emerald-300 text-slate-900 font-extrabold text-lg px-8 py-4 rounded-full shadow-lg transform active:scale-95 transition duration-200 animate-pulse">
        CLICK HERE FOR BLESSINGS ✨
      </button>

      <div id="secretMessage" class="hidden mt-6 p-4 bg-emerald-950/80 rounded-xl border border-emerald-400 text-emerald-200 animate__animated animate__zoomIn">
        🎓 **Dr. Bhavna, stay calm, stay focused, and conquer every section with confidence! You've got this!** 🩺
      </div>
    </div>
  </main>

  <!-- Footer -->
  <footer class="text-slate-400 text-xs text-center mb-4">
    Rooting for your success on August 22 • Built with ❤️
  </footer>

  <script>
    function triggerBoost() {
      // Confetti burst
      confetti({
        particleCount: 120,
        spread: 80,
        origin: { y: 0.6 }
      });

      // Reveal hidden message
      const msg = document.getElementById('secretMessage');
      msg.classList.remove('hidden');

      // Change button state
      const btn = document.getElementById('wishBtn');
      btn.innerText = "VICTORY AWAITS! 🚀";
      btn.classList.remove('animate-pulse');
    }
  </script>
</body>
</html>
