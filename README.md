<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Social Media, College Students & Mental Health</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      line-height: 1.6;
      color: #222;
      background: #0f172a;
    }
    a { color: #2563eb; }
    header {
      background: linear-gradient(135deg,#e11d48,#7c3aed,#0ea5e9);
      color: white;
      padding: 3rem 1.5rem 4rem;
      text-align: center;
    }
    header h1 { font-size: clamp(2.1rem, 4vw, 3rem); margin-bottom: 0.75rem; }
    header p { max-width: 700px; margin: 0.25rem auto; }
    header .tagline { font-weight: 600; margin-top: 0.75rem; }

    nav {
      position: sticky;
      top: 0;
      z-index: 20;
      background: rgba(15,23,42,0.96);
      border-bottom: 1px solid rgba(148,163,184,0.35);
      backdrop-filter: blur(10px);
    }
    nav ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      padding: 0.75rem 1.5rem;
      justify-content: center;
      font-size: 0.9rem;
    }
    nav a {
      text-decoration: none;
      color: #e5e7eb;
      padding: 0.35rem 0.75rem;
      border-radius: 999px;
    }
    nav a:hover {
      background: rgba(148,163,184,0.2);
    }

    main {
      max-width: 1080px;
      margin: 0 auto;
      padding: 2.5rem 1.5rem 4rem;
      display: grid;
      gap: 2.5rem;
    }

    section {
      background: rgba(15,23,42,0.9);
      border-radius: 1.3rem;
      padding: 1.75rem 1.5rem;
      border: 1px solid rgba(148,163,184,0.35);
      box-shadow: 0 20px 35px rgba(15,23,42,0.7);
    }
    section h2 {
      color: #e5e7eb;
      font-size: 1.4rem;
      margin-bottom: 0.75rem;
    }
    section h3 {
      color: #e5e7eb;
      font-size: 1.05rem;
      margin: 1rem 0 0.35rem;
    }
    section p, section li {
      color: #cbd5f5;
      font-size: 0.95rem;
    }
    ul { padding-left: 1.2rem; margin-top: 0.35rem; }
    li + li { margin-top: 0.15rem; }

    .pill {
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      font-size: 0.8rem;
      padding: 0.25rem 0.7rem;
      border-radius: 999px;
      background: rgba(59,130,246,0.12);
      color: #bfdbfe;
      margin-bottom: 0.6rem;
    }

    .grid-2 {
      display: grid;
      gap: 1.5rem;
    }
    @media (min-width: 768px) {
      .grid-2 { grid-template-columns: minmax(0,1.4fr) minmax(0,1fr); }
    }

    .card {
      background: rgba(15,23,42,0.85);
      border-radius: 1rem;
      border: 1px solid rgba(148,163,184,0.35);
      padding: 1rem 1.1rem;
    }
    .card h3 { margin-top: 0; }

    .stat {
      font-size: 1.1rem;
      font-weight: 600;
      color: #f9fafb;
    }
    .stat span {
      font-size: 0.8rem;
      font-weight: 400;
      color: #9ca3af;
      display: block;
    }

    .tips-list li {
      margin-bottom: 0.45rem;
    }

    .media-embed {
      margin-top: 0.75rem;
      border-radius: 1rem;
      overflow: hidden;
      border: 1px solid rgba(148,163,184,0.4);
    }
    iframe {
      width: 100%;
      aspect-ratio: 16 / 9;
      border: none;
      display: block;
    }

    .refs ol {
      padding-left: 1.3rem;
      font-size: 0.85rem;
      color: #d1d5db;
    }
    .refs li + li { margin-top: 0.4rem; }

    footer {
      text-align: center;
      padding: 1.5rem 1rem 2rem;
      color: #9ca3af;
      font-size: 0.8rem;
    }
  </style>
</head>
<body>
<header>
  <h1>The Impact of Social Media on College Students</h1>
  <p class="tagline">Mental Health • Academic Performance • Personal Discipline</p>
  <p>
    Social media is powerful — but it isn’t automatically good or bad.
    For college students, the real question is: <strong>how are we using it?</strong>
  </p>
</header>

<nav>
  <ul>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#helps-hurts">Helps & Harms</a></li>
    <li><a href="#discipline">Why the Person Matters</a></li>
    <li><a href="#research">Research</a></li>
    <li><a href="#media">Videos</a></li>
    <li><a href="#tips">Healthy Habits</a></li>
    <li><a href="#references">Sources</a></li>
  </ul>
</nav>

<main>
  <!-- OVERVIEW -->
  <section id="overview">
    <div class="pill">College Focus • Surveys • Real Student Experiences</div>
    <h2>Overview</h2>
    <p>
      Our project explores how social media affects college students’ mental health
      and academic performance. In our own focus group and surveys, most students
      reported spending <strong>3–6 hours per day</strong> on platforms like Instagram,
      TikTok, and Snapchat. Many admitted that notifications pull them away from
      homework, lead to procrastination, and sometimes cause them to stay up late
      scrolling instead of sleeping.
    </p>
    <p>
      At the same time, students also talked about the positives: staying connected
      with friends and family, finding motivation, building small businesses, and
      expressing themselves creatively. So the story is more complicated than
      “social media is bad.” Current research agrees that the impact depends a lot
      on <strong>how</strong> and <strong>why</strong> we use these apps, not just
      how many hours we’re online.
    </p>
  </section>

  <!-- HELPS & HARMS -->
  <section id="helps-hurts">
    <div class="grid-2">
      <div>
        <h2>How Social Media Can Help Students</h2>
        <p>
          Studies and campus mental-health resources show that social media can
          support students when it’s used intentionally:
        </p>
        <ul>
          <li>Helps students <strong>stay connected</strong> to friends, family, and campus groups, which can reduce loneliness when moving away to college. [1]</li>
          <li>Provides quick access to information about <strong>mental health resources, study tips, and campus events</strong>. [1][2]</li>
          <li>Online communities can offer <strong>peer support</strong>, especially around shared identities or struggles. [3][4]</li>
          <li>Platforms like TikTok and YouTube are used by some professionals to spread <strong>accurate mental-health and study advice</strong>. [4][5]</li>
        </ul>
        <p>
          In one study, researchers even found that TikTok could improve students’
          <strong>mental-health awareness</strong> and support positive behavior changes
          when used for educational content rather than endless scrolling. [6]
        </p>
      </div>

      <div>
        <h2>Where Things Go Wrong</h2>
        <p>
          The problems usually come from <em>how</em> we use social media:
        </p>
        <ul>
          <li>Heavy social media use is linked to <strong>higher anxiety, depression, and stress</strong>, especially when it fuels social comparison or fear of missing out (FoMO). [2][7][8]</li>
          <li>Research with college students shows that FoMO and social anxiety can explain how social media overuse hurts <strong>academic performance</strong>. [9][10]</li>
          <li>Late-night scrolling is tied to <strong>sleep disruption</strong>, which then lowers focus, memory, and grades. [1][7]</li>
          <li>Short-form apps like TikTok can encourage “doom-scrolling,” where students lose track of time and feel mentally drained afterwards. [11][12]</li>
        </ul>
        <p>
          So the risk isn’t just “screen time” — it’s **compulsive, emotionally-driven use**
          that interrupts sleep, studying, and real-life relationships.
        </p>
      </div>
    </div>
  </section>

  <!-- DISCIPLINE / PERSONAL RESPONSIBILITY -->
  <section id="discipline">
    <h2>It’s Not Just the App: Why the Person Matters</h2>
    <p>
      A growing number of researchers and mental-health organizations stress that social
      media is not automatically good or bad. Instead, what matters is
      <strong>how we engage with it</strong>:
    </p>
    <ul>
      <li>The American Psychological Association notes that using social media is <em>not inherently beneficial or harmful</em>; impact depends on individual vulnerabilities and how the platforms are used. [13]</li>
      <li>Researchers at the University of Michigan argue that there’s “nothing inherently good or bad” about social media — the effects depend on how people use it and what they are doing online. [14][15]</li>
      <li>Other work shows we see the most harm in people who already struggle with low self-esteem, depression, or constant negative comparison, while more intentional users can see positive effects. [3]</li>
    </ul>
    <p>
      This is where <strong>discipline and responsibility</strong> come in. The app
      may be designed to grab our attention, but we still have choices:
    </p>
    <ul>
      <li>Do we keep notifications on while studying, or turn them off?</li>
      <li>Do we scroll in bed at 2 a.m., or protect our sleep?</li>
      <li>Do we follow accounts that make us compare and feel worse, or ones that educate and inspire us?</li>
    </ul>
    <p>
      Developing “digital discipline” means taking control of those decisions so
      that <strong>we use social media on purpose, not by accident</strong>.
    </p>
  </section>

  <!-- RESEARCH CALLOUTS -->
  <section id="research">
    <h2>Key Research on College Students</h2>
    <div class="grid-2">
      <div class="card">
        <h3>Mental Health & Grades</h3>
        <p class="stat">
          Social anxiety & FoMO
          <span>can explain how social media hurts academic performance.</span>
        </p>
        <p>
          A 2025 study of college students found that heavy social media use was linked
          to poorer grades partly because it increased social anxiety and fear of missing
          out, which then made it harder for students to focus on schoolwork. [9]
        </p>
      </div>

      <div class="card">
        <h3>Psychological Distress</h3>
        <p class="stat">
          Coping style matters
          <span>more avoidant use = more distress.</span>
        </p>
        <p>
          Research with medical students showed that the relationship between social media
          use and psychological distress depended on coping strategies: using social media
          to escape problems was linked to worse mental health and academic outcomes. [10]
        </p>
      </div>

      <div class="card">
        <h3>TikTok & Well-Being</h3>
        <p class="stat">
          Not just entertainment
          <span>can raise mental-health awareness.</span>
        </p>
        <p>
          A recent study on TikTok found that, when used intentionally, the platform
          could increase students’ awareness of mental-health topics and support positive
          behavior change — but excessive, mindless scrolling still created risks. [6]
        </p>
      </div>

      <div class="card">
        <h3>Our Own Campus Data</h3>
        <p class="stat">
          3–6 hours daily
          <span>typical student social media use in our survey.</span>
        </p>
        <p>
          In our focus group and surveys, most students reported 3–6 hours of daily use.
          Many said notifications pulled them off task, leading to procrastination and
          late assignments. A few students used social media mainly for business or
          creative projects, showing that <strong>purposeful use feels very different
          from endless scrolling.</strong>
        </p>
      </div>
    </div>
  </section>

  <!-- MEDIA -->
  <section id="media">
    <h2>Videos & Talks About Using Social Media Better</h2>
    <p>
      These videos and platforms talk directly about using social media more
      intentionally instead of letting it control you:
    </p>

    <h3>YouTube / TEDx</h3>
    <p>
      <strong>“Social media isn’t bad: you’re just using it wrong” – Eva Amin (TEDx)</strong><br />
      This talk argues that social media can be a positive tool if we curate our feeds,
      set boundaries, and stop blaming the apps for choices we can control. [16]
    </p>
    <div class="media-embed">
      <!-- YouTube embed -->
      <iframe
        src="https://www.youtube.com/embed/CxCsk-rvfTQ"
        title="Social media isn't bad: you're just using it wrong | Eva Amin | TEDxCherryCreekWomen"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p style="margin-top:1rem;">
      <strong>“Harnessing social media to be a force for good” – Luan Wise</strong>  
      Another talk showing how social media can amplify positive messages,
      community projects, and learning when we use it with intention instead of
      impulse. [17]
    </p>
    <div class="media-embed">
      <iframe
        src="https://www.youtube.com/embed/uqvP8375bdE"
        title="Harnessing social media to be a force for good | Luan Wise"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <h3 style="margin-top:1.25rem;">TikTok & Digital Well-Being</h3>
    <p>
      TikTok now includes digital-well-being tools like daily screen-time limits,
      sleep-hour reminders, and “Time and Well-Being” features that reward users for
      using the app within healthy boundaries. [18][19][20] You can:
    </p>
    <ul>
      <li>Set a daily screen-time limit inside TikTok settings.</li>
      <li>Turn on sleep-hour reminders so late-night scrolling doesn’t kill your rest.</li>
      <li>Follow creators who talk about digital balance, study tips, and mental health.</li>
    </ul>
    <p>
      When you build your own TikTok feed around <strong>learning, growth, and
      community</strong>, the app becomes a tool — not a trap.
    </p>
  </section>

  <!-- TIPS -->
  <section id="tips">
    <h2>Practical Tips for Digital Discipline</h2>
    <p>
      You don’t have to quit social media to protect your mental health and GPA.
      Instead, try treating it like any other powerful tool: use it with boundaries.
    </p>
    <ul class="tips-list">
      <li><strong>Study in “Do Not Disturb” mode.</strong> Turn off notifications or put your phone in another room while working.</li>
      <li><strong>Set app limits.</strong> Use built-in tools on TikTok, Instagram, and your phone to cap daily use.</li>
      <li><strong>Protect your sleep.</strong> No social media in bed; charge your phone across the room.</li>
      <li><strong>Curate your feed.</strong> Unfollow accounts that trigger comparison or anxiety; follow ones that educate, inspire, or support you.</li>
      <li><strong>Practice “intentional opening.”</strong> Before you tap an app, ask: “Why am I opening this, and what do I want to get out of it?”</li>
      <li><strong>Schedule offline time.</strong> Plan phone-free blocks for workouts, hobbies, or hanging out with friends.</li>
    </ul>
    <p style="margin-top:0.75rem;">
      Over time, these small habits build the kind of self-control that lets
      <strong>you</strong> be in charge — not your For You Page.
    </p>
  </section>

  <!-- REFERENCES -->
  <section id="references" class="refs">
    <h2>References & Further Reading</h2>
    <ol>
      <li>[1] Capital University. “The Impact of Social Media on Mental Health in Students.”</li>
      <li>[2] Insights Psychology. “Mental Health Impact of Social Media.”</li>
      <li>[3] Maastricht University. “Social media also have a positive impact on mental health.”</li>
      <li>[4] McCashin, D. et al. “Using TikTok for public and youth mental health.”</li>
      <li>[5] Parentandteen.com. “TikTok and Mental Health: A Youth Perspective.”</li>
      <li>[6] Ramsden, E. “The Role of TikTok in Students’ Health and Wellbeing.”</li>
      <li>[7] Braghieri, L. et al. “Social Media and Mental Health.” American Economic Review.</li>
      <li>[8] UNC College of Arts & Sciences. “Social media’s impact on college students’ mental health.”</li>
      <li>[9] Gong, Z. “Social media use and academic performance among college students.” Frontiers in Psychology.</li>
      <li>[10] Shiraly, R. “Psychological distress, social media use, and academic performance of medical students.” BMC Medical Education.</li>
      <li>[11] Virós-Martín, C. “TikTok use and digital well-being.” Humanities & Social Sciences Communications.</li>
      <li>[12] Nexus Teen Academy. “Social Media Anxiety in Teen Boys: TikTok & Doom-scrolling.”</li>
      <li>[13] American Psychological Association. “Health advisory on social media use in adolescence.”</li>
      <li>[14] Kross, E. “Social Media and Well-Being: Pitfalls, Progress, and Next Steps.”</li>
      <li>[15] University of Michigan Ross School of Business. “It’s Not All Bad: Effects of Social Media Depend on How It’s Used.”</li>
      <li>[16] Eva Amin. “Social media isn’t bad: you’re just using it wrong.” TEDxCherryCreekWomen (YouTube).</li>
      <li>[17] Luan Wise. “Harnessing social media to be a force for good.” TEDx (YouTube).</li>
      <li>[18] TikTok Newsroom. “Introducing a new way to unwind, reset, and recharge on TikTok.”</li>
      <li>[19] TikTok Newsroom. “New ways we’re helping our community build balanced digital habits.”</li>
      <li>[20] TechCrunch. “TikTok will now give you badges for limiting your doomscrolling.”</li>
    </ol>
  </section>
</main>

<footer>
  Built for a college symposium project on social media, mental health, academic performance, and digital discipline.
</footer>
</body>
</html>
