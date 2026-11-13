<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fredrick Kioko | Consumer & SME Banking Advisor & Fintech Researcher</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Plus+Jakarta+Sans:wght@600;700;800&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            display: ['Plus Jakarta Sans', 'sans-serif'],
          },
          colors: {
            navy: {
              900: '#0B192C',
              800: '#132743',
              700: '#1E3E62',
            },
            emerald: {
              600: '#059669',
              500: '#10B981',
            },
            amber: {
              500: '#F59E0B',
              600: '#D97706',
            }
          }
        }
      }
    }
  </script>
  <style>
    .tab-active {
      background-color: #0B192C;
      color: #ffffff;
      border-color: #0B192C;
    }
    .node-active {
      border-color: #059669;
      background-color: #ECFDF5;
      box-shadow: 0 4px 14px rgba(5, 150, 105, 0.15);
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-emerald-600 selection:text-white">

  <!-- Sticky Navigation -->
  <header class="sticky top-0 z-50 bg-white/90 backdrop-blur-md border-b border-slate-200">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
      <a href="#" class="flex items-center gap-3 group">
        <div class="w-10 h-10 rounded-xl bg-navy-900 text-white font-display font-bold flex items-center justify-center tracking-tight group-hover:bg-emerald-600 transition-colors">
          FK
        </div>
        <span class="font-display font-bold text-navy-900 text-lg hidden sm:inline">Fredrick Kioko</span>
      </a>
      <nav class="flex items-center gap-1 sm:gap-6 text-sm font-medium text-slate-600">
        <a href="#about" class="px-2.5 py-1.5 rounded-lg hover:text-navy-900 hover:bg-slate-100 transition">About</a>
        <a href="#research" class="px-2.5 py-1.5 rounded-lg hover:text-navy-900 hover:bg-slate-100 transition text-emerald-700 font-semibold">SCF Research</a>
        <a href="#experience" class="px-2.5 py-1.5 rounded-lg hover:text-navy-900 hover:bg-slate-100 transition">Experience</a>
        <a href="#education-sessions" class="px-2.5 py-1.5 rounded-lg hover:text-navy-900 hover:bg-slate-100 transition">Free Sessions</a>
        <a href="#skills" class="px-2.5 py-1.5 rounded-lg hover:text-navy-900 hover:bg-slate-100 transition">Skills</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-gradient-to-br from-navy-900 via-navy-800 to-navy-900 text-white py-16 sm:py-24">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex flex-col md:flex-row items-start md:items-center justify-between gap-10">
        <div class="max-w-3xl">
          <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/10 border border-white/15 text-emerald-300 text-xs font-semibold uppercase tracking-wider mb-6">
            <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
            Nairobi, Kenya · Banking &amp; Fintech Innovation
          </div>
          <h1 class="font-display text-4xl sm:text-5xl font-extrabold tracking-tight leading-tight mb-4">
            Fredrick Kioko
          </h1>
          <p class="text-xl sm:text-2xl text-slate-200 font-medium mb-3">
            Consumer &amp; SME Banking Advisor at NCBA Group <span class="text-emerald-400">|</span> Financial Literacy Educator
          </p>
          <p class="text-slate-300 text-sm sm:text-base mb-8">
            Former Head of School of Social Sciences, Machakos Institute of Technology
          </p>

          <!-- Focus Tags -->
          <div class="flex flex-wrap gap-2.5 mb-8">
            <span class="px-3.5 py-1.5 rounded-lg bg-white/10 text-white text-xs sm:text-sm font-medium border border-white/10">Financial Inclusion</span>
            <span class="px-3.5 py-1.5 rounded-lg bg-white/10 text-white text-xs sm:text-sm font-medium border border-white/10">SME Advisory</span>
            <span class="px-3.5 py-1.5 rounded-lg bg-white/10 text-white text-xs sm:text-sm font-medium border border-white/10">Smart Supply Chain Finance</span>
            <span class="px-3.5 py-1.5 rounded-lg bg-white/10 text-white text-xs sm:text-sm font-medium border border-white/10">Community Education</span>
          </div>

          <div class="flex flex-wrap items-center gap-4">
            <a href="#research" class="px-6 py-3 rounded-xl bg-emerald-600 hover:bg-emerald-500 text-white font-semibold text-sm shadow-lg shadow-emerald-950/40 transition">
              Explore Uhuru Market SCF Case Study
            </a>
            <a href="https://www.linkedin.com/in/fkkioko" target="_blank" rel="noopener noreferrer" class="px-6 py-3 rounded-xl bg-white/10 hover:bg-white/20 text-white font-semibold text-sm border border-white/20 transition inline-flex items-center gap-2">
              <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M19 3a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14m-.5 15.5v-5.3a3.26 3.26 0 0 0-3.26-3.26c-.85 0-1.84.52-2.28 1.3v-1.11h-2.79v8.37h2.79v-4.93c0-.77.62-1.4 1.39-1.4a1.4 1.4 0 0 1 1.4 1.4v4.93h2.75M6.88 8.56a1.68 1.68 0 0 0 1.68-1.68c0-.93-.75-1.69-1.68-1.69a1.69 1.69 0 0 0-1.69 1.69c0 .93.76 1.68 1.69 1.68m1.39 9.94v-8.37H5.5v8.37h2.77z"/></svg>
              View LinkedIn Profile
            </a>
            <a href="mailto:Fredk2070@gmail.com?subject=Advisory%20%26%20Research%20Inquiry" class="px-6 py-3 rounded-xl bg-white/10 hover:bg-white/20 text-white font-semibold text-sm border border-white/20 transition inline-flex items-center gap-2">
              <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4-8 5-8-5V6l8 5 8-5v2z"/></svg>
              Email Me
            </a>
          </div>
        </div>

        <!-- Monogram Card -->
        <div class="hidden lg:flex flex-col items-center justify-center w-64 h-64 rounded-3xl bg-white/5 border border-white/10 backdrop-blur-sm p-6 text-center shrink-0">
          <div class="w-24 h-24 rounded-2xl bg-gradient-to-br from-emerald-500 to-emerald-700 text-white font-display font-extrabold text-3xl flex items-center justify-center shadow-xl mb-4">
            FK
          </div>
          <p class="font-display font-bold text-white text-base">People-First Banking</p>
          <p class="text-xs text-slate-300 mt-1 leading-relaxed">
            Bridging community development &amp; fintech-enabled SME credit architecture.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16 sm:py-20 bg-white border-b border-slate-200">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 items-start">
        <div class="lg:col-span-4">
          <span class="text-xs font-bold uppercase tracking-widest text-emerald-600">Background &amp; Philosophy</span>
          <h2 class="font-display text-3xl font-bold text-navy-900 mt-2">About Me</h2>
          <div class="mt-6 p-5 rounded-2xl bg-slate-50 border border-slate-200">
            <p class="text-sm font-semibold text-navy-900">Academic Foundation</p>
            <p class="text-sm text-slate-600 mt-1">Bachelor of Arts in Development Studies</p>
            <p class="text-xs font-medium text-emerald-700 mt-0.5">Kisii University</p>
          </div>
        </div>
        <div class="lg:col-span-8 space-y-4 text-slate-600 leading-relaxed text-base">
          <p>
            I am a banker with a background in community development, dedicated to making financial literacy accessible to everyone. Before joining <strong class="text-navy-900">NCBA Group</strong>, I worked as a trainer and Head of School at <strong class="text-navy-900">Machakos Institute of Technology</strong>. My experience in the classroom sparked a deep interest in the root causes of financial strain and debt among individuals and businesses.
          </p>
          <p>
            Today, my focus at NCBA goes beyond standard products like loans, mortgages, and savings accounts. I conduct thorough needs assessments so every financial solution matches my clients’ long-term goals—whether that means helping an individual buy a first home or guiding an SME owner toward sustainable growth.
          </p>
          <blockquote class="p-5 rounded-2xl bg-emerald-50/70 border-l-4 border-emerald-600 text-navy-900 font-medium">
            “Strong financial outcomes are built on trust and education, not just transactions.”
          </blockquote>
        </div>
      </div>
    </div>
  </section>

  <!-- Featured Fintech & Supply Chain Finance Research Section -->
  <section id="research" class="py-16 sm:py-24 bg-slate-50 border-b border-slate-200">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <!-- Header -->
      <div class="max-w-3xl mb-12">
        <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-emerald-100 text-emerald-800 text-xs font-bold uppercase tracking-wider mb-3">
          Featured Fintech &amp; Banking Research
        </div>
        <h2 class="font-display text-3xl sm:text-4xl font-extrabold text-navy-900 leading-tight">
          Smart Supply Chain Finance Architecture: Uhuru Market Textile Ecosystem
        </h2>
        <p class="text-slate-600 mt-4 text-base sm:text-lg leading-relaxed">
          Venturing into uncharted waters to unlock trapped SME cash flow across Kenya’s school uniform manufacturing and vocational value chain—bridging the liquidity gap created by three-term school fee collection cycles across <strong class="text-navy-900">35,000+ private schools</strong>.
        </p>
      </div>

      <!-- Macro Context Metrics -->
      <div class="grid grid-cols-1 sm:grid-cols-3 gap-5 mb-12">
        <div class="bg-white p-6 rounded-2xl border border-slate-200 shadow-sm">
          <p class="text-xs font-bold uppercase tracking-wider text-slate-400">Addressable Institutional Demand</p>
          <p class="font-display text-3xl font-extrabold text-navy-900 mt-2">35,000+</p>
          <p class="text-sm text-slate-600 mt-1">Rapidly expanding private schools in Kenya driving year-round uniform procurement.</p>
        </div>
        <div class="bg-white p-6 rounded-2xl border border-slate-200 shadow-sm">
          <p class="text-xs font-bold uppercase tracking-wider text-slate-400">Core Liquidity Bottleneck</p>
          <p class="font-display text-3xl font-extrabold text-amber-600 mt-2">3-Term Cycle</p>
          <p class="text-sm text-slate-600 mt-1">Staggered school fee inflows delay supplier settlements for 60–120 days post-delivery.</p>
        </div>
        <div class="bg-white p-6 rounded-2xl border border-slate-200 shadow-sm">
          <p class="text-xs font-bold uppercase tracking-wider text-slate-400">Architecture Mechanism</p>
          <p class="font-display text-3xl font-extrabold text-emerald-600 mt-2">Tripartite B2B</p>
          <p class="text-sm text-slate-600 mt-1">Commercial Bank + Fintech B2B rails + verified LPO &amp; invoice discounting.</p>
        </div>
      </div>

      <!-- Interactive Ecosystem Node Explorer -->
      <div class="bg-white rounded-3xl border border-slate-200 shadow-sm p-6 sm:p-8 mb-10">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 pb-6 border-b border-slate-100">
          <div>
            <h3 class="font-display text-xl font-bold text-navy-900">Interactive Value Chain &amp; Cash-Flow Node Explorer</h3>
            <p class="text-sm text-slate-500">Select a stakeholder node below to inspect their working capital bottleneck and fintech credit solution.</p>
          </div>
          <span class="text-xs font-semibold text-emerald-700 bg-emerald-50 px-3 py-1 rounded-full self-start sm:self-auto">
            Click any node to inspect
          </span>
        </div>

        <!-- 4 Value Chain Nodes -->
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 mt-6" id="node-buttons">
          <button onclick="selectNode('manufacturers')" id="btn-manufacturers" class="node-btn node-active text-left p-4 rounded-2xl border-2 border-slate-200 transition cursor-pointer">
            <span class="text-xs font-bold uppercase tracking-wider text-emerald-700">Node 01 · Production</span>
            <h4 class="font-display font-bold text-navy-900 text-base mt-1">Uhuru Market Uniform Manufacturers</h4>
            <p class="text-xs text-slate-500 mt-1">Bulk tailoring &amp; garment assembly SMEs</p>
          </button>

          <button onclick="selectNode('distributors')" id="btn-distributors" class="node-btn text-left p-4 rounded-2xl border-2 border-slate-200 hover:border-slate-300 transition cursor-pointer">
            <span class="text-xs font-bold uppercase tracking-wider text-navy-700">Node 02 · Fulfillment</span>
            <h4 class="font-display font-bold text-navy-900 text-base mt-1">School Uniform Distributors</h4>
            <p class="text-xs text-slate-500 mt-1">Wholesalers supplying 35,000+ private schools</p>
          </button>

          <button onclick="selectNode('tvet')" id="btn-tvet" class="node-btn text-left p-4 rounded-2xl border-2 border-slate-200 hover:border-slate-300 transition cursor-pointer">
            <span class="text-xs font-bold uppercase tracking-wider text-amber-600">Node 03 · Talent Pipeline</span>
            <h4 class="font-display font-bold text-navy-900 text-base mt-1">Skill Development TVET Schools</h4>
            <p class="text-xs text-slate-500 mt-1">Technical tailoring &amp; garment production institutes</p>
          </button>

          <button onclick="selectNode('machinery')" id="btn-machinery" class="node-btn text-left p-4 rounded-2xl border-2 border-slate-200 hover:border-slate-300 transition cursor-pointer">
            <span class="text-xs font-bold uppercase tracking-wider text-purple-700">Node 04 · CapEx &amp; Upkeep</span>
            <h4 class="font-display font-bold text-navy-900 text-base mt-1">Machines &amp; Spare-Parts Firms</h4>
            <p class="text-xs text-slate-500 mt-1">Industrial sewing, overlock &amp; embroidery vendors</p>
          </button>
        </div>

        <!-- Dynamic Node Detail Panel -->
        <div id="node-detail" class="mt-6 p-6 rounded-2xl bg-slate-50 border border-slate-200">
          <!-- Populated via JS -->
        </div>
      </div>

      <!-- 3-Pillar Risk & Fintech Architecture -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded-2xl border border-slate-200">
          <div class="w-10 h-10 rounded-xl bg-navy-900 text-white flex items-center justify-center font-display font-bold mb-4">01</div>
          <h4 class="font-display font-bold text-navy-900 text-lg">Fintech &amp; B2B Cash-Flow Rails</h4>
          <p class="text-sm text-slate-600 mt-2 leading-relaxed">
            Digitizes purchase orders and delivery notes across Uhuru Market suppliers, linking school fee collection schedules directly to automated escrow and split-payment settlements.
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl border border-slate-200">
          <div class="w-10 h-10 rounded-xl bg-emerald-600 text-white flex items-center justify-center font-display font-bold mb-4">02</div>
          <h4 class="font-display font-bold text-navy-900 text-lg">Fraud Prevention &amp; AML Controls</h4>
          <p class="text-sm text-slate-600 mt-2 leading-relaxed">
            Eliminates duplicate invoicing and ghost LPOs through three-way digital matching (School LPO + Delivery Note + E-TIMS Invoice) paired with closed-loop supplier disbursements.
          </p>
        </div>

        <div class="bg-white p-6 rounded-2xl border border-slate-200">
          <div class="w-10 h-10 rounded-xl bg-amber-500 text-white flex items-center justify-center font-display font-bold mb-4">03</div>
          <h4 class="font-display font-bold text-navy-900 text-lg">Predictive Cash-Flow Credit Scoring</h4>
          <p class="text-sm text-slate-600 mt-2 leading-relaxed">
            Replaces rigid fixed-asset collateral with dynamic underwriting powered by historical transaction velocity, repeat school contract retention, and term-by-term cash-flow projections.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience Section -->
  <section id="experience" class="py-16 sm:py-20 bg-white border-b border-slate-200">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <span class="text-xs font-bold uppercase tracking-widest text-emerald-600">Career Track Record</span>
      <h2 class="font-display text-3xl font-bold text-navy-900 mt-2 mb-10">Experience</h2>

      <div class="space-y-8 relative before:absolute before:inset-0 before:ml-5 before:-translate-x-px md:before:mx-auto md:before:translate-x-0 before:h-full before:w-0.5 before:bg-slate-200">
        <!-- Role 1 -->
        <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group">
          <div class="flex items-center justify-center w-10 h-10 rounded-full border-4 border-white bg-emerald-600 text-white shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
            <span class="w-2.5 h-2.5 rounded-full bg-white"></span>
          </div>
          <div class="w-[calc(100%-3.5rem)] md:w-[calc(50%-2.5rem)] bg-slate-50 p-6 rounded-2xl border border-slate-200 shadow-sm">
            <div class="flex flex-wrap items-center justify-between gap-2 mb-2">
              <span class="text-xs font-bold uppercase tracking-wider text-emerald-700 bg-emerald-100 px-2.5 py-1 rounded-md">2024 – Present</span>
              <span class="text-xs font-medium text-slate-500">Nairobi, Kenya</span>
            </div>
            <h3 class="font-display text-xl font-bold text-navy-900">Consumer &amp; SME Banking Advisor</h3>
            <p class="text-sm font-semibold text-navy-700 mb-4">NCBA Group</p>
            <ul class="space-y-2 text-sm text-slate-600 list-disc pl-4">
              <li>Advise Consumer and SME clients on lending, savings, and transactional solutions, including the total cost of credit.</li>
              <li>Run financial needs assessments tied to short-term liquidity and long-term growth.</li>
              <li>Exceed monthly, quarterly, and annual targets through needs-based cross-selling, product campaigns, and deposit mobilisation.</li>
              <li>Lead free community sessions on investing, wealth transition, and debt management.</li>
              <li>Share market insights with leadership to support product innovation.</li>
            </ul>
          </div>
        </div>

        <!-- Role 2 -->
        <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group">
          <div class="flex items-center justify-center w-10 h-10 rounded-full border-4 border-white bg-navy-900 text-white shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
            <span class="w-2.5 h-2.5 rounded-full bg-white"></span>
          </div>
          <div class="w-[calc(100%-3.5rem)] md:w-[calc(50%-2.5rem)] bg-slate-50 p-6 rounded-2xl border border-slate-200 shadow-sm">
            <div class="flex flex-wrap items-center justify-between gap-2 mb-2">
              <span class="text-xs font-bold uppercase tracking-wider text-navy-800 bg-slate-200 px-2.5 py-1 rounded-md">2018 – 2024</span>
              <span class="text-xs font-medium text-slate-500">Machakos, Kenya</span>
            </div>
            <h3 class="font-display text-xl font-bold text-navy-900">Head, School of Social Sciences | Lecturer &amp; Training Manager</h3>
            <p class="text-sm font-semibold text-navy-700 mb-4">Machakos Institute of Technology</p>
            <ul class="space-y-2 text-sm text-slate-600 list-disc pl-4">
              <li>Directed training, quality assurance, and curriculum compliance with national standards.</li>
              <li>Led a team of trainers to record-breaking national examination results.</li>
              <li>Named <strong>Best Trainer Institution-Wide</strong> for performance and innovative teaching.</li>
              <li>Coordinated mentorship programmes for faculty and students.</li>
              <li>Headed Co-Curricular Activities, raising student engagement and the institution’s profile.</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Interactive Free Financial Education Section -->
  <section id="education-sessions" class="py-16 sm:py-20 bg-navy-900 text-white">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-2xl mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-emerald-400">Community Impact</span>
        <h2 class="font-display text-3xl font-bold mt-2">Free Financial Education</h2>
        <p class="text-slate-300 mt-2">
          I offer voluntary sessions to support our community, chamas, and SMEs. Tap a topic below to see what it covers.
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
        <!-- Topic Selector Tabs -->
        <div class="lg:col-span-5 flex flex-col gap-3" id="edu-tabs">
          <button onclick="selectEduTopic('health')" id="edu-btn-health" class="edu-tab text-left p-4 rounded-2xl bg-emerald-600 text-white border border-emerald-500 font-display font-bold text-base transition flex items-center justify-between cursor-pointer">
            <span>1. Financial Health Checks</span>
            <span>&rarr;</span>
          </button>
          <button onclick="selectEduTopic('borrowing')" id="edu-btn-borrowing" class="edu-tab text-left p-4 rounded-2xl bg-white/5 hover:bg-white/10 text-slate-200 border border-white/10 font-display font-bold text-base transition flex items-center justify-between cursor-pointer">
            <span>2. Borrowing Guidance</span>
            <span>&rarr;</span>
          </button>
          <button onclick="selectEduTopic('debt')" id="edu-btn-debt" class="edu-tab text-left p-4 rounded-2xl bg-white/5 hover:bg-white/10 text-slate-200 border border-white/10 font-display font-bold text-base transition flex items-center justify-between cursor-pointer">
            <span>3. Debt &amp; Credit Management</span>
            <span>&rarr;</span>
          </button>
          <button onclick="selectEduTopic('savings')" id="edu-btn-savings" class="edu-tab text-left p-4 rounded-2xl bg-white/5 hover:bg-white/10 text-slate-200 border border-white/10 font-display font-bold text-base transition flex items-center justify-between cursor-pointer">
            <span>4. Smart Savings</span>
            <span>&rarr;</span>
          </button>
        </div>

        <!-- Topic Content Display -->
        <div class="lg:col-span-7 bg-white/10 border border-white/15 rounded-3xl p-6 sm:p-8 backdrop-blur-sm" id="edu-content">
          <!-- Populated via JS -->
        </div>
      </div>
    </div>
  </section>

  <!-- Core Skills Section -->
  <section id="skills" class="py-16 sm:py-20 bg-white">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-2xl mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-emerald-600">Capabilities</span>
        <h2 class="font-display text-3xl font-bold text-navy-900 mt-2">Core Skills</h2>
        <p class="text-slate-600 mt-2">
          Combining social development expertise with banking and fintech research to build stronger communities through inclusive financial solutions.
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Featured Skill -->
        <div class="p-6 rounded-2xl bg-emerald-50/70 border-2 border-emerald-600/30 shadow-sm">
          <div class="inline-block px-2.5 py-0.5 rounded-md bg-emerald-600 text-white text-[11px] font-bold uppercase tracking-wider mb-3">
            Fintech &amp; Credit Architecture
          </div>
          <h3 class="font-display text-lg font-bold text-navy-900">Financial &amp; Fintech Research</h3>
          <p class="text-sm text-slate-700 mt-2 leading-relaxed">
            Designing smart supply chain finance architectures to unlock trapped SME cash flow in African markets through fintech and B2B solutions. Integrates fraud prevention and AML controls via LPO/invoice discounting alongside cash-flow predictive credit risk modeling.
          </p>
        </div>

        <div class="p-6 rounded-2xl bg-slate-50 border border-slate-200">
          <h3 class="font-display text-lg font-bold text-navy-900">Community Mobilisation</h3>
          <p class="text-sm text-slate-600 mt-2 leading-relaxed">
            Supporting groups, chamas, and SMEs to adopt financial solutions that improve livelihoods.
          </p>
        </div>

        <div class="p-6 rounded-2xl bg-slate-50 border border-slate-200">
          <h3 class="font-display text-lg font-bold text-navy-900">Financial Literacy</h3>
          <p class="text-sm text-slate-600 mt-2 leading-relaxed">
            Simplifying financial concepts and promoting wellness among clients.
          </p>
        </div>

        <div class="p-6 rounded-2xl bg-slate-50 border border-slate-200">
          <h3 class="font-display text-lg font-bold text-navy-900">Business Development</h3>
          <p class="text-sm text-slate-600 mt-2 leading-relaxed">
            Project planning, entrepreneurship, and business management for SME growth.
          </p>
        </div>

        <div class="p-6 rounded-2xl bg-slate-50 border border-slate-200">
          <h3 class="font-display text-lg font-bold text-navy-900">Relationship Management</h3>
          <p class="text-sm text-slate-600 mt-2 leading-relaxed">
            Building trust through active listening, empathy, and client-centred advisory.
          </p>
        </div>

        <div class="p-6 rounded-2xl bg-slate-50 border border-slate-200">
          <h3 class="font-display text-lg font-bold text-navy-900">Problem Solving</h3>
          <p class="text-sm text-slate-600 mt-2 leading-relaxed">
            Helping clients work through financial challenges and make informed decisions.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-slate-900 text-slate-400 py-10 border-t border-slate-800">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-4">
      <div class="text-center sm:text-left">
        <p class="font-display font-bold text-white">Fredrick Kioko</p>
        <p class="text-xs mt-1">Consumer &amp; SME Banking Advisor at NCBA Group · Nairobi, Kenya</p>
      </div>
      <div class="flex flex-wrap items-center justify-center gap-5 text-xs font-medium">
        <a href="mailto:Fredk2070@gmail.com" class="text-emerald-400 hover:text-emerald-300 transition">
          Fredk2070@gmail.com
        </a>
        <span class="text-slate-600">|</span>
        <a href="https://www.linkedin.com/in/fkkioko" target="_blank" rel="noopener noreferrer" class="text-slate-300 hover:text-white transition">
          LinkedIn Profile
        </a>
      </div>
    </div>
  </footer>

  <!-- Interactive JavaScript -->
  <script>
    // Supply Chain Finance Node Data
    const scfNodes = {
      manufacturers: {
        badge: "Node 01 · Garment Production (Uhuru Market)",
        title: "Kenyan School Uniform Manufacturers",
        bottleneck: "Must procure bulk fabric, threads, and dyes 60–90 days ahead of school opening dates, yet face severe working capital lockup while waiting for distributors and schools to remit fees across three academic terms.",
        solution: "Pre-shipment LPO financing backed by verified distributor purchase orders, paired with automated B2B supplier payments directly to textile mills to prevent fund diversion.",
        riskControl: "Historical batch-output verification + E-TIMS digital invoice validation + closed-loop raw material disbursement."
      },
      distributors: {
        badge: "Node 02 · Institutional Distribution (35,000+ Private Schools)",
        title: "School Uniform Distributors & Wholesalers",
        bottleneck: "Private schools order uniforms in bulk at the start of Terms 1, 2, and 3, but settle invoices incrementally as parents pay school fees over the 13-week term.",
        solution: "Dynamic invoice discounting linked to school fee collection inflows, converting 90-day receivables into immediate liquidity within 24–48 hours of school delivery confirmation.",
        riskControl: "Tripartite escrow settlement agreements with partner private schools + AML screening on high-volume termly receivables."
      },
      tvet: {
        badge: "Node 03 · Technical Workforce & Incubation",
        title: "Skill Development TVET Schools",
        bottleneck: "Technical vocational institutes training garment technicians and master tailors struggle with delayed capitation/tuition inflows and lack structured transition financing for graduating artisan cooperatives.",
        solution: "Structured fee-collection bridge facilities for TVET institutions combined with order-backed micro-working capital for TVET-incubated tailoring workshops supplying Uhuru Market overflow orders.",
        riskControl: "Performance-tiered credit limits tied to quality assurance pass rates and subcontracted LPO fulfillment history."
      },
      machinery: {
        badge: "Node 04 · Industrial Equipment & Maintenance",
        title: "Machines & Spare-Parts Companies",
        bottleneck: "Suppliers of industrial lockstitch, overlock, and computerized embroidery machines face seasonal order spikes before Term 1, while SME workshops lack lump-sum CapEx to upgrade equipment.",
        solution: "Pay-as-you-produce asset financing and spare-parts trade credit where repayments flex with the workshop's termly invoice discounting cash flows.",
        riskControl: "IoT/usage-aligned repayment schedules + direct vendor settlement + predictive cash-flow stress testing across off-peak school holidays."
      }
    };

    function selectNode(key) {
      const data = scfNodes[key];
      document.querySelectorAll('.node-btn').forEach(btn => {
        btn.classList.remove('node-active');
      });
      document.getElementById('btn-' + key).classList.add('node-active');

      document.getElementById('node-detail').innerHTML = `
        <span class="inline-block text-xs font-bold uppercase tracking-wider text-emerald-700 bg-emerald-100 px-3 py-1 rounded-full mb-3">
          ${data.badge}
        </span>
        <h4 class="font-display text-2xl font-bold text-navy-900 mb-4">${data.title}</h4>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-5">
          <div class="bg-white p-4 rounded-xl border border-slate-200">
            <p class="text-xs font-bold uppercase tracking-wider text-amber-600 mb-1">Three-Term Cash-Flow Bottleneck</p>
            <p class="text-sm text-slate-600 leading-relaxed">${data.bottleneck}</p>
          </div>
          <div class="bg-white p-4 rounded-xl border border-slate-200">
            <p class="text-xs font-bold uppercase tracking-wider text-emerald-600 mb-1">Fintech &amp; B2B Finance Mechanism</p>
            <p class="text-sm text-slate-600 leading-relaxed">${data.solution}</p>
          </div>
          <div class="bg-white p-4 rounded-xl border border-slate-200">
            <p class="text-xs font-bold uppercase tracking-wider text-navy-800 mb-1">Fraud, AML &amp; Credit Risk Shield</p>
            <p class="text-sm text-slate-600 leading-relaxed">${data.riskControl}</p>
          </div>
        </div>
      `;
    }

    // Free Financial Education Tab Data
    const eduTopics = {
      health: {
        tag: "Session 01 · Diagnostic",
        title: "Financial Health Checks",
        summary: "Reviewing business structure and cash flow to maintain creditworthiness.",
        bullets: [
          "Auditing cash-in vs. cash-out cycles to spot hidden liquidity leaks early.",
          "Aligning business legal registration, banking records, and tax compliance for bankability.",
          "Preparing SMEs for formal credit assessments before urgent funding needs arise."
        ]
      },
      borrowing: {
        tag: "Session 02 · Credit Strategy",
        title: "Borrowing Guidance",
        summary: "Identifying which credit facilities to avoid and how to prevent over-leverage in high-rate environments.",
        bullets: [
          "Understanding the true total cost of credit beyond headline interest rates.",
          "Matching loan tenure to asset life or receivables cycle (avoiding short-term mobile debt for long-term CapEx).",
          "Evaluating working capital options such as LPO financing and invoice discounting."
        ]
      },
      debt: {
        tag: "Session 03 · Resilience",
        title: "Debt and Credit Management",
        summary: "Practical strategies for building credit scores, separating personal and business finances, and managing debt responsibly.",
        bullets: [
          "Establishing clean separation between owner drawings and SME operating accounts.",
          "Restructuring strained obligations early through proactive lender engagement.",
          "Building a verifiable credit profile that unlocks lower-cost financing over time."
        ]
      },
      savings: {
        tag: "Session 04 · Wealth Creation",
        title: "Smart Savings",
        summary: "Actionable approaches to personal wealth creation and disciplined saving.",
        bullets: [
          "Structuring emergency reserves for both households and seasonal businesses.",
          "Leveraging group savings vehicles (chamas) and goal-based investment accounts.",
          "Transitioning from active income to sustainable, long-term wealth preservation."
        ]
      }
    };

    function selectEduTopic(key) {
      const topic = eduTopics[key];
      document.querySelectorAll('.edu-tab').forEach(btn => {
        btn.classList.remove('bg-emerald-600', 'text-white', 'border-emerald-500');
        btn.classList.add('bg-white/5', 'text-slate-200', 'border-white/10');
      });
      const activeBtn = document.getElementById('edu-btn-' + key);
      activeBtn.classList.remove('bg-white/5', 'text-slate-200', 'border-white/10');
      activeBtn.classList.add('bg-emerald-600', 'text-white', 'border-emerald-500');

      document.getElementById('edu-content').innerHTML = `
        <span class="inline-block text-xs font-bold uppercase tracking-wider text-emerald-300 bg-emerald-500/20 px-3 py-1 rounded-full mb-3">
          ${topic.tag}
        </span>
        <h3 class="font-display text-2xl font-bold text-white mb-2">${topic.title}</h3>
        <p class="text-slate-200 text-base mb-5">${topic.summary}</p>
        <div class="border-t border-white/15 pt-4">
          <p class="text-xs font-bold uppercase tracking-wider text-slate-300 mb-3">Key Takeaways Covered:</p>
          <ul class="space-y-2.5 text-sm text-slate-200">
            ${topic.bullets.map(item => `
              <li class="flex items-start gap-2.5">
                <span class="text-emerald-400 font-bold mt-0.5">&#10003;</span>
                <span>${item}</span>
              </li>
            `).join('')}
          </ul>
        </div>
      `;
    }

    // Initialize default interactive panels on load
    selectNode('manufacturers');
    selectEduTopic('health');
  </script>
</body>
</html>
