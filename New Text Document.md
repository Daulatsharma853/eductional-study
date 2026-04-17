

<!DOCTYPE html>

<html lang="en">

<head>

&#x20;   <meta charset="UTF-8">

&#x20;   <meta name="viewport" content="width=device-width, initial-scale=1.0">

&#x20;   <title>EduSphere AI - Learn Everything | ₹499/Year ALL Courses</title>

&#x20;   <meta name="description" content="Learn Python, Java, AI, UPSC, JEE, NEET with AI Tutor. 200+ courses, 15K+ videos. Only ₹499/year for ALL courses!">

&#x20;   

&#x20;   <script src="https://cdn.tailwindcss.com"></script>

&#x20;   <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700\&family=DM+Sans:wght@400;500;600;700\&display=swap" rel="stylesheet">

&#x20;   

&#x20;   <script>

&#x20;       tailwind.config = {

&#x20;           theme: { extend: { fontFamily: { display: \['Space Grotesk', 'sans-serif'], body: \['DM Sans', 'sans-serif'] } } }

&#x20;       }

&#x20;   </script>

&#x20;   

&#x20;   <style>

&#x20;       :root {

&#x20;           --bg: #0a0f1a; --bg-light: #111827; --fg: #f1f5f9; --muted: #64748b;

&#x20;           --accent: #f97316; --card: #1e293b; --border: #334155;

&#x20;           --success: #10b981; --info: #06b6d4; --ai-purple: #a855f7; --error: #ef4444;

&#x20;       }

&#x20;       \* { font-family: 'DM Sans', sans-serif; box-sizing: border-box; margin: 0; padding: 0; }

&#x20;       body { background: var(--bg); color: var(--fg); line-height: 1.6; }

&#x20;       .font-display { font-family: 'Space Grotesk', sans-serif; }

&#x20;       

&#x20;       @keyframes float { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); } }

&#x20;       @keyframes glow { 0%, 100% { box-shadow: 0 0 20px rgba(168, 85, 247, 0.3); } 50% { box-shadow: 0 0 40px rgba(168, 85, 247, 0.6); } }

&#x20;       @keyframes fade-in { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }

&#x20;       @keyframes pulse { 0%, 100% { opacity: 1; } 50% { opacity: 0.5; } }

&#x20;       @keyframes slide-in { from { transform: translateX(-100%); } to { transform: translateX(0); } }

&#x20;       

&#x20;       .float { animation: float 4s ease-in-out infinite; }

&#x20;       .glow { animation: glow 2s ease-in-out infinite; }

&#x20;       .fade-in { animation: fade-in 0.5s ease-out forwards; }

&#x20;       .pulse { animation: pulse 2s ease-in-out infinite; }

&#x20;       .slide-in { animation: slide-in 0.3s ease-out; }

&#x20;       

&#x20;       .hero-gradient {

&#x20;           background: radial-gradient(ellipse 80% 50% at 50% -20%, rgba(249, 115, 22, 0.15), transparent),

&#x20;                       radial-gradient(ellipse 60% 40% at 80% 60%, rgba(168, 85, 247, 0.1), transparent);

&#x20;       }

&#x20;       

&#x20;       .btn-primary {

&#x20;           background: linear-gradient(135deg, var(--accent), var(--ai-purple));

&#x20;           border: none; cursor: pointer; color: white; transition: all 0.3s;

&#x20;       }

&#x20;       .btn-primary:hover { transform: translateY(-2px); box-shadow: 0 10px 30px rgba(249, 115, 22, 0.3); }

&#x20;       

&#x20;       .card { background: var(--card); border: 1px solid var(--border); transition: all 0.3s; }

&#x20;       .card:hover { border-color: var(--accent); transform: translateY(-2px); }

&#x20;       

&#x20;       .input-field {

&#x20;           background: var(--card); border: 1px solid var(--border); color: var(--fg);

&#x20;           transition: all 0.3s; padding: 12px 16px; border-radius: 8px; width: 100%;

&#x20;       }

&#x20;       .input-field:focus { border-color: var(--accent); outline: none; box-shadow: 0 0 0 3px rgba(249, 115, 22, 0.1); }

&#x20;       

&#x20;       .modal-overlay { background: rgba(0, 0, 0, 0.85); backdrop-filter: blur(10px); }

&#x20;       

&#x20;       .sidebar { background: linear-gradient(180deg, var(--card), var(--bg)); border-right: 1px solid var(--border); }

&#x20;       .nav-item { border-left: 3px solid transparent; transition: all 0.2s; color: var(--muted); }

&#x20;       .nav-item:hover, .nav-item.active { 

&#x20;           background: linear-gradient(90deg, rgba(249, 115, 22, 0.1), transparent); 

&#x20;           border-left-color: var(--accent); color: var(--fg);

&#x20;       }

&#x20;       

&#x20;       .progress-bar { background: var(--border); border-radius: 9999px; overflow: hidden; height: 8px; }

&#x20;       .progress-fill { background: linear-gradient(90deg, var(--accent), var(--ai-purple)); transition: width 1s ease; }

&#x20;       

&#x20;       .code-block { background: #1a1b26; border-radius: 8px; font-family: 'Courier New', monospace; font-size: 13px; }

&#x20;       

&#x20;       .hidden { display: none !important; }

&#x20;       

&#x20;       ::-webkit-scrollbar { width: 6px; height: 6px; }

&#x20;       ::-webkit-scrollbar-track { background: var(--bg); }

&#x20;       ::-webkit-scrollbar-thumb { background: var(--border); border-radius: 3px; }

&#x20;       

&#x20;       @media (max-width: 768px) {

&#x20;           .sidebar { transform: translateX(-100%); position: fixed; z-index: 50; height: 100vh; width: 280px; }

&#x20;           .sidebar.open { transform: translateX(0); }

&#x20;       }

&#x20;       

&#x20;       .code-block { background: #1a1b26; border-radius: 8px; font-family: 'Courier New', monospace; font-size: 13px; overflow-x: auto; }

&#x20;       .code-block pre { margin: 0; padding: 16px; }

&#x20;       .kw { color: #c678dd; }

&#x20;       .fn { color: #61afef; }

&#x20;       .str { color: #98c379; }

&#x20;       .cmt { color: #5c6370; font-style: italic; }

&#x20;       .num { color: #d19a66; }

&#x20;   </style>

</head>

<body>

&#x20;   <div id="app">

&#x20;       <!-- ==================== LANDING PAGE ==================== -->

&#x20;       <div id="landingPage">

&#x20;           <!-- Navigation -->

&#x20;           <nav class="fixed top-0 left-0 right-0 z-40 bg-\[var(--bg)]/95 backdrop-blur-xl border-b border-\[var(--border)]">

&#x20;               <div class="max-w-7xl mx-auto px-4 h-16 flex items-center justify-between">

&#x20;                   <div class="flex items-center gap-2">

&#x20;                       <div class="w-10 h-10 rounded-lg bg-gradient-to-br from-\[var(--accent)] to-\[var(--ai-purple)] flex items-center justify-center">

&#x20;                           <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"/></svg>

&#x20;                       </div>

&#x20;                       <span class="font-display font-bold text-xl">EduSphere<span class="text-\[var(--ai-purple)]">AI</span></span>

&#x20;                   </div>

&#x20;                   <div class="hidden md:flex items-center gap-6 text-sm">

&#x20;                       <a href="#courses" class="text-\[var(--muted)] hover:text-\[var(--fg)] transition-colors">Courses</a>

&#x20;                       <a href="#features" class="text-\[var(--muted)] hover:text-\[var(--fg)] transition-colors">Features</a>

&#x20;                       <a href="#pricing" class="text-\[var(--muted)] hover:text-\[var(--fg)] transition-colors">Pricing</a>

&#x20;                       <a href="#download" class="text-\[var(--muted)] hover:text-\[var(--fg)] transition-colors">App</a>

&#x20;                   </div>

&#x20;                   <div class="flex items-center gap-3">

&#x20;                       <button onclick="App.openModal('login')" class="px-4 py-2 text-\[var(--muted)] hover:text-\[var(--fg)] text-sm transition-colors">Login</button>

&#x20;                       <button onclick="App.openModal('signup')" class="px-5 py-2.5 btn-primary rounded-lg text-sm font-medium">Get Started</button>

&#x20;                   </div>

&#x20;               </div>

&#x20;           </nav>



&#x20;           <!-- Hero Section -->

&#x20;           <section class="hero-gradient pt-24 pb-16 min-h-screen flex items-center">

&#x20;               <div class="max-w-7xl mx-auto px-4">

&#x20;                   <div class="grid lg:grid-cols-2 gap-12 items-center">

&#x20;                       <div class="fade-in">

&#x20;                           <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-\[var(--success)]/20 border border-\[var(--success)]/30 mb-6">

&#x20;                               <span class="w-2 h-2 rounded-full bg-\[var(--success)] pulse"></span>

&#x20;                               <span class="text-sm text-\[var(--success)]">🎉 Launch Offer: ₹499/year for ALL 200+ Courses!</span>

&#x20;                           </div>

&#x20;                           <h1 class="font-display text-4xl sm:text-5xl lg:text-6xl font-bold leading-tight mb-6">

&#x20;                               Learn <span class="bg-gradient-to-r from-\[var(--accent)] via-\[var(--ai-purple)] to-\[var(--info)] bg-clip-text text-transparent">Everything</span> with AI

&#x20;                           </h1>

&#x20;                           <p class="text-lg text-\[var(--muted)] mb-8">Python, Java, AI/ML, UPSC, JEE, NEET - 200+ courses with AI Tutor, animated videos \& 50K+ notes. One price = ALL courses!</p>

&#x20;                           <div class="flex flex-wrap gap-4 mb-8">

&#x20;                               <button onclick="App.openModal('signup')" class="px-8 py-4 btn-primary rounded-xl font-semibold flex items-center gap-2">

&#x20;                                   <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/></svg>

&#x20;                                   Start Free Trial

&#x20;                               </button>

&#x20;                               <button onclick="document.getElementById('pricing').scrollIntoView({behavior:'smooth'})" class="px-8 py-4 bg-\[var(--card)] border border-\[var(--border)] rounded-xl font-semibold hover:border-\[var(--accent)] transition-all">

&#x20;                                   View Pricing

&#x20;                               </button>

&#x20;                           </div>

&#x20;                           <div class="grid grid-cols-4 gap-4">

&#x20;                               <div class="text-center"><div class="font-display text-2xl font-bold text-\[var(--accent)]">200+</div><div class="text-xs text-\[var(--muted)]">Courses</div></div>

&#x20;                               <div class="text-center"><div class="font-display text-2xl font-bold text-\[var(--ai-purple)]">15K+</div><div class="text-xs text-\[var(--muted)]">Videos</div></div>

&#x20;                               <div class="text-center"><div class="font-display text-2xl font-bold text-\[var(--info)]">50K+</div><div class="text-xs text-\[var(--muted)]">Notes</div></div>

&#x20;                               <div class="text-center"><div class="font-display text-2xl font-bold text-\[var(--success)]">2M+</div><div class="text-xs text-\[var(--muted)]">Students</div></div>

&#x20;                           </div>

&#x20;                       </div>

&#x20;                       <div class="card p-6 rounded-2xl glow fade-in" style="animation-delay: 0.2s">

&#x20;                           <div class="flex items-center gap-2 mb-4">

&#x20;                               <div class="w-3 h-3 rounded-full bg-red-500"></div>

&#x20;                               <div class="w-3 h-3 rounded-full bg-yellow-500"></div>

&#x20;                               <div class="w-3 h-3 rounded-full bg-green-500"></div>

&#x20;                               <span class="ml-2 text-xs text-\[var(--muted)]">Learn with AI Animation</span>

&#x20;                           </div>

&#x20;                           <div class="code-block p-4 mb-4">

<pre><span class="kw">class</span> <span class="fn">LearnPython</span>:

&#x20;   <span class="kw">def</span> <span class="fn">\_\_init\_\_</span>(self):

&#x20;       self.topics = \[

&#x20;           <span class="str">"Basics"</span>, <span class="str">"OOP"</span>, <span class="str">"AI"</span>

&#x20;       ]

&#x20;   

&#x20;   <span class="kw">def</span> <span class="fn">start</span>(self):

&#x20;       <span class="kw">return</span> <span class="str">"🚀 Let's learn!"</span>



<span class="cmt"># Start your journey</span>

student = LearnPython()

print(student.start())</pre>

&#x20;                           </div>

&#x20;                           <div class="flex items-center justify-between text-sm">

&#x20;                               <span class="text-\[var(--muted)]">75% Complete</span>

&#x20;                               <div class="flex-1 mx-4 progress-bar"><div class="progress-fill" style="width:75%"></div></div>

&#x20;                               <span class="text-\[var(--accent)] font-medium cursor-pointer hover:underline">Continue</span>

&#x20;                           </div>

&#x20;                       </div>

&#x20;                   </div>

&#x20;               </div>

&#x20;           </section>



&#x20;           <!-- Courses Section -->

&#x20;           <section id="courses" class="py-20 bg-\[var(--bg-light)]">

&#x20;               <div class="max-w-7xl mx-auto px-4">

&#x20;                   <div class="text-center mb-12">

&#x20;                       <h2 class="font-display text-3xl sm:text-4xl font-bold mb-4">All Courses - ₹499/Year</h2>

&#x20;                       <p class="text-\[var(--muted)]">200+ courses included. No extra charges!</p>

&#x20;                   </div>

&#x20;                   <div class="flex flex-wrap justify-center gap-3 mb-10" id="courseTabs">

&#x20;                       <button onclick="App.filterCourses('all')" class="course-tab px-6 py-2 rounded-full bg-\[var(--accent)] text-white text-sm font-medium">All</button>

&#x20;                       <button onclick="App.filterCourses('coding')" class="course-tab px-6 py-2 rounded-full bg-\[var(--card)] border border-\[var(--border)] text-sm">Coding</button>

&#x20;                       <button onclick="App.filterCourses('ai')" class="course-tab px-6 py-2 rounded-full bg-\[var(--card)] border border-\[var(--border)] text-sm">AI/ML</button>

&#x20;                       <button onclick="App.filterCourses('school')" class="course-tab px-6 py-2 rounded-full bg-\[var(--card)] border border-\[var(--border)] text-sm">School</button>

&#x20;                       <button onclick="App.filterCourses('competitive')" class="course-tab px-6 py-2 rounded-full bg-\[var(--card)] border border-\[var(--border)] text-sm">Competitive</button>

&#x20;                   </div>

&#x20;                   <div id="courseGrid" class="grid sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6"></div>

&#x20;               </div>

&#x20;           </section>



&#x20;           <!-- Features Section -->

&#x20;           <section id="features" class="py-20">

&#x20;               <div class="max-w-7xl mx-auto px-4">

&#x20;                   <div class="text-center mb-12">

&#x20;                       <h2 class="font-display text-3xl sm:text-4xl font-bold mb-4">What's Included in ₹499?</h2>

&#x20;                       <p class="text-\[var(--muted)]">Everything! No hidden charges.</p>

&#x20;                   </div>

&#x20;                   <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">

&#x20;                       <div class="card p-6 rounded-2xl text-center">

&#x20;                           <div class="w-16 h-16 mx-auto mb-4 rounded-2xl bg-purple-500/20 flex items-center justify-center"><svg class="w-8 h-8 text-purple-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z"/></svg></div>

&#x20;                           <h3 class="font-semibold mb-2">15,000+ Videos</h3>

&#x20;                           <p class="text-sm text-\[var(--muted)]">Detailed + Quick revision</p>

&#x20;                       </div>

&#x20;                       <div class="card p-6 rounded-2xl text-center glow">

&#x20;                           <div class="w-16 h-16 mx-auto mb-4 rounded-2xl bg-\[var(--ai-purple)]/20 flex items-center justify-center float"><svg class="w-8 h-8 text-\[var(--ai-purple)]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"/></svg></div>

&#x20;                           <h3 class="font-semibold mb-2">AI Tutor 24x7</h3>

&#x20;                           <p class="text-sm text-\[var(--muted)]">Hindi + English</p>

&#x20;                       </div>

&#x20;                       <div class="card p-6 rounded-2xl text-center">

&#x20;                           <div class="w-16 h-16 mx-auto mb-4 rounded-2xl bg-green-500/20 flex items-center justify-center"><svg class="w-8 h-8 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"/></svg></div>

&#x20;                           <h3 class="font-semibold mb-2">Unlimited Mock Tests</h3>

&#x20;                           <p class="text-sm text-\[var(--muted)]">All exams covered</p>

&#x20;                       </div>

&#x20;                       <div class="card p-6 rounded-2xl text-center">

&#x20;                           <div class="w-16 h-16 mx-auto mb-4 rounded-2xl bg-orange-500/20 flex items-center justify-center"><svg class="w-8 h-8 text-orange-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z"/></svg></div>

&#x20;                           <h3 class="font-semibold mb-2">50,000+ PDFs</h3>

&#x20;                           <p class="text-sm text-\[var(--muted)]">Download \& print</p>

&#x20;                       </div>

&#x20;                   </div>

&#x20;               </div>

&#x20;           </section>



&#x20;           <!-- Pricing Section -->

&#x20;           <section id="pricing" class="py-20 bg-\[var(--bg-light)]">

&#x20;               <div class="max-w-7xl mx-auto px-4">

&#x20;                   <div class="text-center mb-12">

&#x20;                       <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-\[var(--success)]/20 border border-\[var(--success)]/30 mb-4">

&#x20;                           <svg class="w-5 h-5 text-\[var(--success)]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>

&#x20;                           <span class="text-sm text-\[var(--success)]">🎉 Special Launch Offer - Limited Time!</span>

&#x20;                       </div>

&#x20;                       <h2 class="font-display text-3xl sm:text-4xl font-bold mb-4">Simple Pricing</h2>

&#x20;                       <p class="text-\[var(--muted)]">One price for ALL courses!</p>

&#x20;                   </div>

&#x20;                   

&#x20;                   <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">

&#x20;                       <!-- Free Plan -->

&#x20;                       <div class="card rounded-2xl p-6">

&#x20;                           <div class="mb-6">

&#x20;                               <h3 class="font-display text-xl font-bold mb-2">Free</h3>

&#x20;                               <p class="text-sm text-\[var(--muted)]">Get started</p>

&#x20;                           </div>

&#x20;                           <div class="mb-6"><span class="font-display text-4xl font-bold">₹0</span><span class="text-\[var(--muted)]">/forever</span></div>

&#x20;                           <ul class="space-y-3 mb-6 text-sm">

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span>5,000+ Videos</span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span>AI Tutor (5/day)</span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span>2 Mock Tests/Month</span></li>

&#x20;                           </ul>

&#x20;                           <button onclick="App.openModal('signup')" class="w-full py-3 bg-\[var(--card)] border border-\[var(--border)] rounded-lg font-medium hover:border-\[var(--accent)] transition-all">Get Started Free</button>

&#x20;                       </div>

&#x20;                       

&#x20;                       <!-- Premium Plan -->

&#x20;                       <div class="card rounded-2xl p-6 relative border-2 border-\[var(--accent)] glow">

&#x20;                           <div class="absolute -top-3 left-1/2 -translate-x-1/2"><span class="px-4 py-1 bg-\[var(--accent)] text-white text-sm font-semibold rounded-full">MOST POPULAR</span></div>

&#x20;                           <div class="mb-6"><h3 class="font-display text-xl font-bold mb-2">Premium</h3><p class="text-sm text-\[var(--muted)]">ALL Courses Included!</p></div>

&#x20;                           <div class="mb-2"><span class="text-\[var(--muted)] line-through text-lg">₹2,999</span><span class="ml-2 px-2 py-1 bg-\[var(--success)]/20 text-\[var(--success)] text-xs font-semibold rounded">83% OFF</span></div>

&#x20;                           <div class="mb-6"><span class="font-display text-5xl font-bold text-\[var(--accent)]">₹499</span><span class="text-\[var(--muted)]">/year</span><div class="text-sm text-\[var(--success)] mt-1">Only ₹41.58/month</div></div>

&#x20;                           <ul class="space-y-3 mb-6 text-sm">

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>ALL 200+ Courses</strong></span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>15,000+ Videos</strong></span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>AI Tutor Unlimited</strong></span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>50,000+ PDFs</strong></span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>Unlimited Mock Tests</strong></span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>Live Classes</strong></span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>Doubt Solving 24x7</strong></span></li>

&#x20;                           </ul>

&#x20;                           <button onclick="App.openModal('signup')" class="btn-primary w-full py-3 rounded-lg font-semibold flex items-center justify-center gap-2">

&#x20;                               <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/></svg>

&#x20;                               Get Premium - ₹499/year

&#x20;                           </button>

&#x20;                           <p class="text-center text-xs text-\[var(--muted)] mt-3">7-day refund policy</p>

&#x20;                       </div>

&#x20;                       

&#x20;                       <!-- Lifetime Plan -->

&#x20;                       <div class="card rounded-2xl p-6 relative">

&#x20;                           <div class="absolute -top-3 left-1/2 -translate-x-1/2"><span class="px-3 py-1 bg-gradient-to-r from-\[var(--ai-purple)] to-\[var(--info)] text-white text-xs font-semibold rounded-full">BEST VALUE</span></div>

&#x20;                           <div class="mb-6"><h3 class="font-display text-xl font-bold mb-2">Lifetime</h3><p class="text-sm text-\[var(--muted)]">Pay once, use forever</p></div>

&#x20;                           <div class="mb-2"><span class="text-\[var(--muted)] line-through text-lg">₹9,999</span><span class="ml-2 px-2 py-1 bg-\[var(--ai-purple)]/20 text-\[var(--ai-purple)] text-xs font-semibold rounded">70% OFF</span></div>

&#x20;                           <div class="mb-6"><span class="font-display text-5xl font-bold bg-gradient-to-r from-\[var(--ai-purple)] to-\[var(--info)] bg-clip-text text-transparent">₹2,999</span><span class="text-\[var(--muted)]">/lifetime</span></div>

&#x20;                           <ul class="space-y-3 mb-6 text-sm">

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--ai-purple)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>Everything in Premium</strong></span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--ai-purple)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>Pay Once, Forever</strong></span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--ai-purple)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>All Future Updates FREE</strong></span></li>

&#x20;                               <li class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--ai-purple)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg><span><strong>Priority Support</strong></span></li>

&#x20;                           </ul>

&#x20;                           <button onclick="App.openModal('signup')" class="w-full py-3 bg-gradient-to-r from-\[var(--ai-purple)] to-\[var(--info)] text-white rounded-lg font-semibold">Get Lifetime Access</button>

&#x20;                       </div>

&#x20;                   </div>

&#x20;                   

&#x20;                   <div class="mt-12 text-center">

&#x20;                       <p class="text-sm text-\[var(--muted)] mb-4">Trusted by 2 million+ students across India</p>

&#x20;                       <div class="flex flex-wrap justify-center gap-6">

&#x20;                           <div class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg><span class="text-sm">100% Secure</span></div>

&#x20;                           <div class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 10h18M7 15h1m4 0h1m-7 4h12a3 3 0 003-3V8a3 3 0 00-3-3H6a3 3 0 00-3 3v8a3 3 0 003 3z"/></svg><span class="text-sm">UPI, Card, NetBanking</span></div>

&#x20;                           <div class="flex items-center gap-2"><svg class="w-5 h-5 text-\[var(--success)]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 15v-1a4 4 0 00-4-4H8m0 0l3 3m-3-3l3-3m9 1V9a4 4 0 00-3-3l-4 4"/></svg><span class="text-sm">7-Day Refund</span></div>

&#x20;                       </div>

&#x20;                   </div>

&#x20;               </div>

&#x20;           </section>



&#x20;           <!-- Download Section -->

&#x20;           <section id="download" class="py-20">

&#x20;               <div class="max-w-7xl mx-auto px-4">

&#x20;                   <div class="text-center mb-12"><h2 class="font-display text-3xl font-bold mb-4">Download App</h2><p class="text-\[var(--muted)]">Available on all platforms</p></div>

&#x20;                   <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6 max-w-4xl mx-auto">

&#x20;                       <div class="card p-6 rounded-2xl text-center">

&#x20;                           <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-green-500/20 flex items-center justify-center"><svg class="w-8 h-8 text-green-500" viewBox="0 0 24 24" fill="currentColor"><path d="M3.609 1.814L13.792 12 3.61 22.186a.996.996 0 01-.61-.92V2.734a1 1 0 01.609-.92zm10.89 10.893l2.302 2.302-10.937 6.333 8.635-8.635zm3.199-3.198l2.807 1.626a1 1 0 010 1.73l-2.808 1.626L15.206 12l2.492-2.491z"/></svg></div>

&#x20;                           <h3 class="font-semibold mb-2">Android</h3>

&#x20;                           <button onclick="App.downloadApp('android')" class="w-full py-2 mt-2 bg-green-500 text-white rounded-lg text-sm font-medium">Download APK</button>

&#x20;                       </div>

&#x20;                       <div class="card p-6 rounded-2xl text-center">

&#x20;                           <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-blue-500/20 flex items-center justify-center"><svg class="w-8 h-8 text-blue-500" fill="currentColor" viewBox="0 0 24 24"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.81-1.31.05-2.31-1.32-3.14-2.56C4.25 16.96 3 12.45 4.69 9.39c.84-1.54 2.36-2.52 4.01-2.55 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.81-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.05 2.68 4.07-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg></div>

&#x20;                           <h3 class="font-semibold mb-2">iOS</h3>

&#x20;                           <button onclick="App.downloadApp('ios')" class="w-full py-2 mt-2 bg-blue-500 text-white rounded-lg text-sm font-medium">Download</button>

&#x20;                       </div>

&#x20;                       <div class="card p-6 rounded-2xl text-center">

&#x20;                           <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-cyan-500/20 flex items-center justify-center"><svg class="w-8 h-8 text-cyan-500" fill="currentColor" viewBox="0 0 24 24"><path d="M3 12V6.75L9 5.43V11.91L3 12M20 3V11.75L10 11.9V5.21L20 3M3 13L9 13.09V19.9L3 18.75V13M20 13.25V22L10 20.09V13.1L20 13.25Z"/></svg></div>

&#x20;                           <h3 class="font-semibold mb-2">Windows</h3>

&#x20;                           <button onclick="App.downloadApp('windows')" class="w-full py-2 mt-2 bg-cyan-500 text-white rounded-lg text-sm font-medium">Download</button>

&#x20;                       </div>

&#x20;                       <div class="card p-6 rounded-2xl text-center glow">

&#x20;                           <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-\[var(--accent)]/20 flex items-center justify-center"><svg class="w-8 h-8 text-\[var(--accent)]" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"/></svg></div>

&#x20;                           <h3 class="font-semibold mb-2">Web (PWA)</h3>

&#x20;                           <button onclick="App.downloadApp('web')" class="w-full py-2 mt-2 bg-\[var(--accent)] text-white rounded-lg text-sm font-medium">Open App</button>

&#x20;                       </div>

&#x20;                   </div>

&#x20;               </div>

&#x20;           </section>



&#x20;           <!-- Footer -->

&#x20;           <footer class="py-12 border-t border-\[var(--border)]">

&#x20;               <div class="max-w-7xl mx-auto px-4">

&#x20;                   <div class="grid md:grid-cols-4 gap-8 mb-8">

&#x20;                       <div>

&#x20;                           <div class="flex items-center gap-2 mb-4">

&#x20;                               <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-\[var(--accent)] to-\[var(--ai-purple)] flex items-center justify-center"><svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"/></svg></div>

&#x20;                               <span class="font-display font-bold">EduSphere<span class="text-\[var(--ai-purple)]">AI</span></span>

&#x20;                           </div>

&#x20;                           <p class="text-sm text-\[var(--muted)]">World's most affordable learning platform. 200+ courses at ₹499/year.</p>

&#x20;                       </div>

&#x20;                       <div><h4 class="font-semibold mb-4">Courses</h4><ul class="space-y-2 text-sm text-\[var(--muted)]"><li><a href="#" class="hover:text-\[var(--fg)]">Python</a></li><li><a href="#" class="hover:text-\[var(--fg)]">Java</a></li><li><a href="#" class="hover:text-\[var(--fg)]">AI/ML</a></li><li><a href="#" class="hover:text-\[var(--fg)]">Web Dev</a></li></ul></div>

&#x20;                       <div><h4 class="font-semibold mb-4">Competitive</h4><ul class="space-y-2 text-sm text-\[var(--muted)]"><li><a href="#" class="hover:text-\[var(--fg)]">UPSC</a></li><li><a href="#" class="hover:text-\[var(--fg)]">JEE/NEET</a></li><li><a href="#" class="hover:text-\[var(--fg)]">SSC/Bank</a></li><li><a href="#" class="hover:text-\[var(--fg)]">GATE</a></li></ul></div>

&#x20;                       <div><h4 class="font-semibold mb-4">Support</h4><ul class="space-y-2 text-sm text-\[var(--muted)]"><li><a href="#" class="hover:text-\[var(--fg)]">Contact</a></li><li><a href="#" class="hover:text-\[var(--fg)]">FAQ</a></li><li><a href="#" class="hover:text-\[var(--fg)]">Privacy</a></li></ul></div>

&#x20;                   </div>

&#x20;                   <div class="pt-8 border-t border-\[var(--border)] text-center text-sm text-\[var(--muted)]"><p>© 2024 EduSphere AI. All rights reserved. Made in India 🇮🇳</p></div>

&#x20;               </div>

&#x20;           </footer>

&#x20;       </div>



&#x20;       <!-- ==================== LOGIN MODAL ==================== -->

&#x20;       <div id="loginModal" class="fixed inset-0 z-50 hidden">

&#x20;           <div class="modal-overlay absolute inset-0" onclick="App.closeModal('login')"></div>

&#x20;           <div class="relative z-10 flex items-center justify-center min-h-screen p-4">

&#x20;               <div class="card w-full max-w-md rounded-2xl p-8 fade-in">

&#x20;                   <div class="text-center mb-8">

&#x20;                       <div class="w-16 h-16 mx-auto mb-4 rounded-2xl bg-gradient-to-br from-\[var(--accent)] to-\[var(--ai-purple)] flex items-center justify-center"><svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"/></svg></div>

&#x20;                       <h2 class="font-display text-2xl font-bold">Welcome Back!</h2>

&#x20;                       <p class="text-\[var(--muted)] mt-2">Login to access all courses</p>

&#x20;                   </div>

&#x20;                   <form onsubmit="App.handleLogin(event)">

&#x20;                       <div class="space-y-4">

&#x20;                           <div><label class="block text-sm font-medium mb-2">Email</label><input type="email" id="loginEmail" class="input-field rounded-lg" placeholder="Enter email" required></div>

&#x20;                           <div><label class="block text-sm font-medium mb-2">Password</label><input type="password" id="loginPassword" class="input-field rounded-lg" placeholder="Enter password" required></div>

&#x20;                           <button type="submit" class="btn-primary w-full py-3 rounded-lg font-semibold">Login</button>

&#x20;                       </div>

&#x20;                   </form>

&#x20;                   <p class="mt-6 text-center text-sm text-\[var(--muted)]">Don't have account? <button onclick="App.openModal('signup'); App.closeModal('login');" class="text-\[var(--accent)]">Sign up</button></p>

&#x20;               </div>

&#x20;           </div>

&#x20;       </div>



&#x20;       <!-- ==================== SIGNUP MODAL ==================== -->

&#x20;       <div id="signupModal" class="fixed inset-0 z-50 hidden">

&#x20;           <div class="modal-overlay absolute inset-0" onclick="App.closeModal('signup')"></div>

&#x20;           <div class="relative z-10 flex items-center justify-center min-h-screen p-4">

&#x20;               <div class="card w-full max-w-md rounded-2xl p-8 max-h-\[90vh] overflow-y-auto fade-in">

&#x20;                   <div class="text-center mb-6">

&#x20;                       <div class="w-16 h-16 mx-auto mb-4 rounded-2xl bg-gradient-to-br from-\[var(--accent)] to-\[var(--ai-purple)] flex items-center justify-center"><svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18 9v3m0 0v3m0-3h3m-3 0h-3m-2-5a4 4 0 11-8 0 4 4 0 018 0zM3 20a6 6 0 0112 0v1H3v-1z"/></svg></div>

&#x20;                       <h2 class="font-display text-2xl font-bold">Create Account</h2>

&#x20;                       <p class="text-\[var(--muted)] mt-2">Join 2M+ students - ₹499/year for ALL!</p>

&#x20;                   </div>

&#x20;                   <form onsubmit="App.handleSignup(event)">

&#x20;                       <div class="space-y-4">

&#x20;                           <div><label class="block text-sm font-medium mb-2">Full Name</label><input type="text" id="signupName" class="input-field rounded-lg" placeholder="Enter name" required></div>

&#x20;                           <div><label class="block text-sm font-medium mb-2">Email</label><input type="email" id="signupEmail" class="input-field rounded-lg" placeholder="Enter email" required></div>

&#x20;                           <div><label class="block text-sm font-medium mb-2">Phone</label><input type="tel" id="signupPhone" class="input-field rounded-lg" placeholder="+91 9876543210" required></div>

&#x20;                           <div>

&#x20;                               <label class="block text-sm font-medium mb-2">Select Course</label>

&#x20;                               <select id="signupCourse" class="input-field rounded-lg" required>

&#x20;                                   <option value="">Select course</option>

&#x20;                                   <optgroup label="Coding"><option value="python">Python</option><option value="java">Java</option><option value="js">JavaScript</option><option value="aiml">AI/ML</option></optgroup>

&#x20;                                   <optgroup label="School"><option value="class1-5">Class 1-5</option><option value="class6-8">Class 6-8</option><option value="class9-10">Class 9-10</option><option value="class11-12">Class 11-12</option></optgroup>

&#x20;                                   <optgroup label="Competitive"><option value="upsc">UPSC</option><option value="jee">JEE</option><option value="neet">NEET</option><option value="ssc">SSC</option></optgroup>

&#x20;                               </select>

&#x20;                           </div>

&#x20;                           <div><label class="block text-sm font-medium mb-2">Password</label><input type="password" id="signupPassword" class="input-field rounded-lg" placeholder="Create password" required></div>

&#x20;                           <button type="submit" class="btn-primary w-full py-3 rounded-lg font-semibold">Create Account</button>

&#x20;                       </div>

&#x20;                   </form>

&#x20;                   <p class="mt-6 text-center text-sm text-\[var(--muted)]">Have account? <button onclick="App.openModal('login'); App.closeModal('signup');" class="text-\[var(--accent)]">Login</button></p>

&#x20;               </div>

&#x20;           </div>

&#x20;       </div>



&#x20;       <!-- ==================== STUDENT DASHBOARD ==================== -->

&#x20;       <div id="studentDashboard" class="hidden min-h-screen flex">

&#x20;           <!-- Sidebar -->

&#x20;           <aside id="sidebar" class="sidebar w-64 fixed left-0 top-0 h-full overflow-y-auto z-30">

&#x20;               <div class="p-4 border-b border-\[var(--border)]">

&#x20;                   <div class="flex items-center gap-2">

&#x20;                       <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-\[var(--accent)] to-\[var(--ai-purple)] flex items-center justify-center"><svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"/></svg></div>

&#x20;                       <span class="font-display font-bold text-sm">EduSphere</span>

&#x20;                   </div>

&#x20;               </div>

&#x20;               <nav class="p-4 space-y-1">

&#x20;                   <a href="#" onclick="App.showPage('home')" class="nav-item active flex items-center gap-3 px-4 py-3 rounded-lg text-sm"><svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/></svg>Home</a>

&#x20;                   <a href="#" onclick="App.showPage('courses')" class="nav-item flex items-center gap-3 px-4 py-3 rounded-lg text-sm"><svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z"/></svg>My Courses</a>

&#x20;                   <a href="#" onclick="App.showPage('aitutor')" class="nav-item flex items-center gap-3 px-4 py-3 rounded-lg text-sm"><svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"/></svg>AI Tutor</a>

&#x20;                   <a href="#" onclick="App.showPage('mocktest')" class="nav-item flex items-center gap-3 px-4 py-3 rounded-lg text-sm"><svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"/></svg>Mock Tests</a>

&#x20;                   <a href="#" onclick="App.showPage('notes')" class="nav-item flex items-center gap-3 px-4 py-3 rounded-lg text-sm"><svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z"/></svg>Notes/PDFs</a>

&#x20;                   <div class="border-t border-\[var(--border)] my-4"></div>

&#x20;                   <a href="#" onclick="App.logout()" class="nav-item flex items-center gap-3 px-4 py-3 rounded-lg text-sm text-\[var(--error)]"><svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 16l4-4m0 0l-4-4m4 4H7m6 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h4a3 3 0 013 3v1"/></svg>Logout</a>

&#x20;               </nav>

&#x20;           </aside>



&#x20;           <!-- Main Content -->

&#x20;           <main class="flex-1 lg:ml-64">

&#x20;               <header class="sticky top-0 z-20 bg-\[var(--bg)]/95 backdrop-blur-xl border-b border-\[var(--border)]">

&#x20;                   <div class="flex items-center justify-between px-4 py-3">

&#x20;                       <div class="flex items-center gap-4">

&#x20;                           <button onclick="App.toggleSidebar()" class="lg:hidden p-2 rounded-lg bg-\[var(--card)]"><svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/></svg></button>

&#x20;                           <input type="text" placeholder="Search..." class="input-field w-64 rounded-lg text-sm">

&#x20;                       </div>

&#x20;                       <div class="w-10 h-10 rounded-full bg-gradient-to-br from-\[var(--accent)] to-\[var(--ai-purple)] flex items-center justify-center cursor-pointer" onclick="App.showPage('profile')"><span id="userInitial" class="text-white font-semibold text-sm">U</span></div>

&#x20;                   </div>

&#x20;               </header>



&#x20;               <div id="dashboardContent" class="p-6">

&#x20;                   <!-- Home -->

&#x20;                   <div id="pageHome">

&#x20;                       <h1 class="font-display text-2xl font-bold mb-6">Welcome, <span id="userName">Student</span>!</h1>

&#x20;                       <div class="grid sm:grid-cols-4 gap-4 mb-8">

&#x20;                           <div class="card p-4 rounded-xl"><div class="text-sm text-\[var(--muted)]">Courses</div><div class="text-2xl font-bold text-\[var(--accent)]">12</div></div>

&#x20;                           <div class="card p-4 rounded-xl"><div class="text-sm text-\[var(--muted)]">Videos</div><div class="text-2xl font-bold text-\[var(--info)]">156</div></div>

&#x20;                           <div class="card p-4 rounded-xl"><div class="text-sm text-\[var(--muted)]">Tests</div><div class="text-2xl font-bold text-\[var(--success)]">24</div></div>

&#x20;                           <div class="card p-4 rounded-xl"><div class="text-sm text-\[var(--muted)]">Hours</div><div class="text-2xl font-bold text-\[var(--ai-purple)]">48h</div></div>

&#x20;                       </div>

&#x20;                       <h2 class="font-semibold mb-4">Continue Learning</h2>

&#x20;                       <div class="grid md:grid-cols-3 gap-4 mb-8" id="continueLearning"></div>

&#x20;                   </div>

&#x20;                   

&#x20;                   <!-- AI Tutor -->

&#x20;                   <div id="pageAitutor" class="hidden">

&#x20;                       <h1 class="font-display text-2xl font-bold mb-6">AI Tutor - Ask Anything!</h1>

&#x20;                       <div class="card p-6 rounded-2xl min-h-\[500px] flex flex-col">

&#x20;                           <div id="chatMessages" class="flex-1 overflow-y-auto space-y-4 mb-4"></div>

&#x20;                           <div class="flex gap-2">

&#x20;                               <input type="text" id="chatInput" placeholder="Ask AI in Hindi or English..." class="input-field flex-1 rounded-lg" onkeypress="if(event.key==='Enter')App.sendMessage()">

&#x20;                               <button onclick="App.sendMessage()" class="btn-primary px-6 rounded-lg"><svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"/></svg></button>

&#x20;                           </div>

&#x20;                       </div>

&#x20;                   </div>

&#x20;                   

&#x20;                   <!-- Mock Tests -->

&#x20;                   <div id="pageMocktest" class="hidden">

&#x20;                       <h1 class="font-display text-2xl font-bold mb-6">Mock Tests</h1>

&#x20;                       <div class="grid sm:grid-cols-3 gap-4">

&#x20;                           <div class="card p-6 rounded-xl"><h3 class="font-semibold mb-2">JEE Mock Test</h3><p class="text-sm text-\[var(--muted)] mb-4">75 Q • 180 mins</p><button class="btn-primary w-full py-2 rounded-lg text-sm">Start</button></div>

&#x20;                           <div class="card p-6 rounded-xl"><h3 class="font-semibold mb-2">NEET Mock</h3><p class="text-sm text-\[var(--muted)] mb-4">200 Q • 200 mins</p><button class="btn-primary w-full py-2 rounded-lg text-sm">Start</button></div>

&#x20;                           <div class="card p-6 rounded-xl"><h3 class="font-semibold mb-2">Python Quiz</h3><p class="text-sm text-\[var(--muted)] mb-4">50 Q • 60 mins</p><button class="btn-primary w-full py-2 rounded-lg text-sm">Start</button></div>

&#x20;                       </div>

&#x20;                   </div>

&#x20;                   

&#x20;                   <!-- Notes -->

&#x20;                   <div id="pageNotes" class="hidden">

&#x20;                       <h1 class="font-display text-2xl font-bold mb-6">Notes \& PDFs</h1>

&#x20;                       <div class="grid sm:grid-cols-3 gap-4">

&#x20;                           <div class="card p-6 rounded-xl"><h3 class="font-semibold mb-2">Physics Notes</h3><p class="text-sm text-\[var(--muted)] mb-4">120 pages</p><button class="w-full py-2 bg-\[var(--error)] text-white rounded-lg text-sm">Download PDF</button></div>

&#x20;                           <div class="card p-6 rounded-xl"><h3 class="font-semibold mb-2">Chemistry Formula</h3><p class="text-sm text-\[var(--muted)] mb-4">45 pages</p><button class="w-full py-2 bg-\[var(--error)] text-white rounded-lg text-sm">Download PDF</button></div>

&#x20;                           <div class="card p-6 rounded-xl"><h3 class="font-semibold mb-2">Maths Short Tricks</h3><p class="text-sm text-\[var(--muted)] mb-4">80 pages</p><button class="w-full py-2 bg-\[var(--error)] text-white rounded-lg text-sm">Download PDF</button></div>

&#x20;                       </div>

&#x20;                   </div>

&#x20;                   

&#x20;                   <!-- My Courses -->

&#x20;                   <div id="pageCourses" class="hidden">

&#x20;                       <h1 class="font-display text-2xl font-bold mb-6">My Courses</h1>

&#x20;                       <div id="myCourses" class="grid sm:grid-cols-3 gap-4"></div>

&#x20;                   </div>

&#x20;                   

&#x20;                   <!-- Profile -->

&#x20;                   <div id="pageProfile" class="hidden">

&#x20;                       <h1 class="font-display text-2xl font-bold mb-6">Profile</h1>

&#x20;                       <div class="card p-6 rounded-2xl max-w-lg">

&#x20;                           <div class="space-y-4">

&#x20;                               <div class="flex items-center gap-4 mb-6">

&#x20;                                   <div class="w-16 h-16 rounded-full bg-gradient-to-br from-\[var(--accent)] to-\[var(--ai-purple)] flex items-center justify-center text-2xl font-bold text-white" id="profileInitial">U</div>

&#x20;                                   <div><h3 class="font-semibold" id="profileName">Student</h3><p class="text-sm text-\[var(--muted)]" id="profileEmail">email@example.com</p></div>

&#x20;                               </div>

&#x20;                               <div><label class="text-sm">Name</label><input type="text" class="input-field rounded-lg mt-1" id="editName"></div>

&#x20;                               <div><label class="text-sm">Phone</label><input type="text" class="input-field rounded-lg mt-1" id="editPhone"></div>

&#x20;                               <button class="btn-primary px-6 py-2 rounded-lg font-medium">Save Changes</button>

&#x20;                           </div>

&#x20;                       </div>

&#x20;                   </div>

&#x20;               </div>

&#x20;           </main>

&#x20;       </div>

&#x20;   </div>



&#x20;   <!-- ==================== JAVASCRIPT ==================== -->

&#x20;   <script>

&#x20;       // ============ DATA ============

&#x20;       const COURSES = \[

&#x20;           {id:1, title:'Python Complete', category:'coding', lang:'Python', videos:150, hours:45, rating:4.9, students:'125K', icon:'🐍'},

&#x20;           {id:2, title:'Java Full Stack', category:'coding', lang:'Java', videos:200, hours:60, rating:4.8, students:'89K', icon:'☕'},

&#x20;           {id:3, title:'JavaScript Mastery', category:'coding', lang:'JS', videos:120, hours:35, rating:4.9, students:'156K', icon:'🟨'},

&#x20;           {id:4, title:'React \& Node.js', category:'coding', lang:'JS', videos:180, hours:55, rating:4.8, students:'78K', icon:'⚛️'},

&#x20;           {id:5, title:'Machine Learning', category:'ai', lang:'Python', videos:180, hours:50, rating:4.9, students:'145K', icon:'🤖'},

&#x20;           {id:6, title:'Deep Learning', category:'ai', lang:'Python', videos:150, hours:45, rating:4.8, students:'89K', icon:'🧠'},

&#x20;           {id:7, title:'NLP Complete', category:'ai', lang:'Python', videos:100, hours:30, rating:4.7, students:'56K', icon:'💬'},

&#x20;           {id:8, title:'Class 10 Complete', category:'school', lang:'Hindi+English', videos:500, hours:150, rating:4.9, students:'450K', icon:'📚'},

&#x20;           {id:9, title:'Class 12 Science', category:'school', lang:'Hindi+English', videos:600, hours:180, rating:4.9, students:'380K', icon:'🔬'},

&#x20;           {id:10, title:'Class 12 Commerce', category:'school', lang:'Hindi+English', videos:400, hours:120, rating:4.8, students:'220K', icon:'📊'},

&#x20;           {id:11, title:'JEE Main + Advanced', category:'competitive', lang:'Hindi+English', videos:800, hours:250, rating:4.9, students:'520K', icon:'🎯'},

&#x20;           {id:12, title:'NEET Preparation', category:'competitive', lang:'Hindi+English', videos:700, hours:200, rating:4.9, students:'480K', icon:'⚕️'},

&#x20;           {id:13, title:'UPSC CSE Complete', category:'competitive', lang:'Hindi+English', videos:900, hours:300, rating:4.9, students:'320K', icon:'🏛️'},

&#x20;           {id:14, title:'SSC CGL/CHSL', category:'competitive', lang:'Hindi+English', videos:400, hours:120, rating:4.8, students:'280K', icon:'📝'},

&#x20;           {id:15, title:'GATE Preparation', category:'competitive', lang:'Hindi+English', videos:500, hours:150, rating:4.9, students:'145K', icon:'🚪'},

&#x20;           {id:16, title:'Bank PO/Clerk', category:'competitive', lang:'Hindi+English', videos:350, hours:100, rating:4.8, students:'190K', icon:'🏦'},

&#x20;       ];



&#x20;       const App = {

&#x20;           user: null,



&#x20;           init() {

&#x20;               this.renderCourses();

&#x20;               this.checkAuth();

&#x20;           },



&#x20;           checkAuth() {

&#x20;               const u = localStorage.getItem('edu\_user');

&#x20;               if(u) {

&#x20;                   this.user = JSON.parse(u);

&#x20;                   this.showDashboard();

&#x20;               }

&#x20;           },



&#x20;           openModal(type) {

&#x20;               document.getElementById(type+'Modal').classList.remove('hidden');

&#x20;           },



&#x20;           closeModal(type) {

&#x20;               document.getElementById(type+'Modal').classList.add('hidden');

&#x20;           },



&#x20;           handleLogin(e) {

&#x20;               e.preventDefault();

&#x20;               const email = document.getElementById('loginEmail').value;

&#x20;               this.user = {name: email.split('@')\[0], email, course:'Python'};

&#x20;               localStorage.setItem('edu\_user', JSON.stringify(this.user));

&#x20;               this.closeModal('login');

&#x20;               this.showDashboard();

&#x20;           },



&#x20;           handleSignup(e) {

&#x20;               e.preventDefault();

&#x20;               const name = document.getElementById('signupName').value;

&#x20;               const email = document.getElementById('signupEmail').value;

&#x20;               const phone = document.getElementById('signupPhone').value;

&#x20;               const course = document.getElementById('signupCourse').value;

&#x20;               this.user = {name, email, phone, course};

&#x20;               localStorage.setItem('edu\_user', JSON.stringify(this.user));

&#x20;               this.closeModal('signup');

&#x20;               this.showDashboard();

&#x20;           },



&#x20;           logout() {

&#x20;               localStorage.removeItem('edu\_user');

&#x20;               this.user = null;

&#x20;               document.getElementById('studentDashboard').classList.add('hidden');

&#x20;               document.getElementById('landingPage').classList.remove('hidden');

&#x20;           },



&#x20;           showDashboard() {

&#x20;               document.getElementById('landingPage').classList.add('hidden');

&#x20;               document.getElementById('studentDashboard').classList.remove('hidden');

&#x20;               document.getElementById('userName').textContent = this.user?.name || 'Student';

&#x20;               document.getElementById('userInitial').textContent = (this.user?.name||'U')\[0].toUpperCase();

&#x20;               this.renderDashboard();

&#x20;           },



&#x20;           showPage(page) {

&#x20;               \['Home','Aitutor','Mocktest','Notes','Courses','Profile'].forEach(p => {

&#x20;                   const el = document.getElementById('page'+p);

&#x20;                   if(el) el.classList.add('hidden');

&#x20;               });

&#x20;               const active = document.getElementById('page'+page.charAt(0).toUpperCase()+page.slice(1));

&#x20;               if(active) active.classList.remove('hidden');

&#x20;               document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));

&#x20;           },



&#x20;           toggleSidebar() {

&#x20;               document.getElementById('sidebar').classList.toggle('open');

&#x20;           },



&#x20;           renderCourses(filter='all') {

&#x20;               const grid = document.getElementById('courseGrid');

&#x20;               const filtered = filter==='all' ? COURSES : COURSES.filter(c => c.category===filter);

&#x20;               grid.innerHTML = filtered.map(c => `

&#x20;                   <div class="card p-5 rounded-xl cursor-pointer" onclick="App.openModal('signup')">

&#x20;                       <div class="flex items-center gap-2 mb-3">

&#x20;                           <span class="text-2xl">${c.icon}</span>

&#x20;                           <span class="text-xs px-2 py-1 rounded bg-\[var(--accent)]/20 text-\[var(--accent)]">${c.lang}</span>

&#x20;                       </div>

&#x20;                       <h3 class="font-semibold mb-1">${c.title}</h3>

&#x20;                       <p class="text-xs text-\[var(--muted)] mb-3">${c.videos} videos • ${c.hours}h</p>

&#x20;                       <div class="flex justify-between items-center text-sm">

&#x20;                           <span class="flex items-center gap-1">

&#x20;                               <svg class="w-4 h-4 text-yellow-500" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>

&#x20;                               ${c.rating}

&#x20;                           </span>

&#x20;                           <span class="text-\[var(--muted)]">${c.students}</span>

&#x20;                       </div>

&#x20;                   </div>

&#x20;               `).join('');

&#x20;           },



&#x20;           filterCourses(cat) {

&#x20;               document.querySelectorAll('.course-tab').forEach(t => {

&#x20;                   t.classList.remove('bg-\[var(--accent)]','text-white');

&#x20;                   t.classList.add('bg-\[var(--card)]');

&#x20;               });

&#x20;               event.target.classList.add('bg-\[var(--accent)]','text-white');

&#x20;               event.target.classList.remove('bg-\[var(--card)]');

&#x20;               this.renderCourses(cat);

&#x20;           },



&#x20;           renderDashboard() {

&#x20;               // Continue learning

&#x20;               document.getElementById('continueLearning').innerHTML = COURSES.slice(0,3).map(c => `

&#x20;                   <div class="card p-4 rounded-xl">

&#x20;                       <div class="flex items-center gap-3 mb-3">

&#x20;                           <span class="text-2xl">${c.icon}</span>

&#x20;                           <div class="flex-1">

&#x20;                               <h4 class="font-medium text-sm">${c.title}</h4>

&#x20;                               <p class="text-xs text-\[var(--muted)]">${c.hours}h total</p>

&#x20;                           </div>

&#x20;                       </div>

&#x20;                       <div class="progress-bar mb-2"><div class="progress-fill" style="width:${Math.random()\*80+10}%"></div></div>

&#x20;                       <div class="flex justify-between text-xs">

&#x20;                           <span class="text-\[var(--muted)]">65%</span>

&#x20;                           <span class="text-\[var(--accent)]">Continue</span>

&#x20;                       </div>

&#x20;                   </div>

&#x20;               `).join('');

&#x20;               

&#x20;               // My courses

&#x20;               document.getElementById('myCourses').innerHTML = COURSES.slice(0,6).map(c => `

&#x20;                   <div class="card p-4 rounded-xl">

&#x20;                       <span class="text-3xl mb-2 block">${c.icon}</span>

&#x20;                       <h4 class="font-medium">${c.title}</h4>

&#x20;                       <p class="text-xs text-\[var(--muted)]">${c.videos} videos</p>

&#x20;                   </div>

&#x20;               `).join('');

&#x20;               

&#x20;               // Chat messages

&#x20;               document.getElementById('chatMessages').innerHTML = `

&#x20;                   <div class="flex justify-end"><div class="px-4 py-2 rounded-xl bg-\[var(--accent)] text-white max-w-\[80%]">Explain Python loops</div></div>

&#x20;                   <div class="flex justify-start"><div class="px-4 py-3 rounded-xl bg-\[var(--ai-purple)]/20 border border-\[var(--ai-purple)]/30 max-w-\[85%]">

&#x20;                       <p class="text-sm mb-2">Great question! Python loops repeat code. Here's an example:</p>

&#x20;                       <div class="code-block p-2 text-xs"><pre><span class="kw">for</span> i <span class="kw">in</span> <span class="fn">range</span>(<span class="num">5</span>):\\n    <span class="fn">print</span>(i)</pre></div>

&#x20;                   </div></div>

&#x20;               `;

&#x20;           },



&#x20;           sendMessage() {

&#x20;               const input = document.getElementById('chatInput');

&#x20;               const msg = input.value.trim();

&#x20;               if(!msg) return;

&#x20;               const chat = document.getElementById('chatMessages');

&#x20;               chat.innerHTML += `<div class="flex justify-end fade-in"><div class="px-4 py-2 rounded-xl bg-\[var(--accent)] text-white max-w-\[80%]">${msg}</div></div>`;

&#x20;               setTimeout(() => {

&#x20;                   chat.innerHTML += `<div class="flex justify-start fade-in"><div class="px-4 py-3 rounded-xl bg-\[var(--ai-purple)]/20 border border-\[var(--ai-purple)]/30 max-w-\[85%]">

&#x20;                       <p class="text-sm">I'll explain "${msg}" with an animation...</p>

&#x20;                       <div class="code-block p-2 text-xs mt-2"><pre><span class="cmt">// Loading animation...</span></pre></div>

&#x20;                   </div></div>`;

&#x20;                   chat.scrollTop = chat.scrollHeight;

&#x20;               }, 500);

&#x20;               input.value = '';

&#x20;               chat.scrollTop = chat.scrollHeight;

&#x20;           },



&#x20;           downloadApp(platform) {

&#x20;               alert(`Downloading ${platform} app... (Connect to app stores in production)`);

&#x20;           }

&#x20;       };



&#x20;       // Init

&#x20;       document.addEventListener('DOMContentLoaded', () => App.init());

&#x20;   </script>

</body>

</html>



