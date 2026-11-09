
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Marketing English | Practical Vocabulary & Speaking</title>
<style>
:root {
  --navy:#172b4d;
  --blue:#315efb;
  --pale:#edf2ff;
  --ink:#202b3c;
  --muted:#667085;
  --line:#e5eaf2;
  --green:#16845b;
  --bg:#f5f7fb;
  --white:#fff;
}
* { box-sizing:border-box; }
body {
  margin:0;
  background:var(--bg);
  color:var(--ink);
  font-family:Arial,sans-serif;
  line-height:1.55;
}
header {
  background:var(--navy);
  color:white;
  padding:18px 24px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:12px;
  flex-wrap:wrap;
}
header strong { letter-spacing:.3px; }
header span { color:#cbd6ee; font-size:13px; }
.app {
  max-width:980px;
  margin:28px auto;
  padding:0 18px 30px;
}
.topline {
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:12px;
  margin-bottom:12px;
  color:var(--muted);
  font-size:13px;
}
.progress {
  height:6px;
  background:#e3e8f1;
  border-radius:10px;
  overflow:hidden;
}
.progress div {
  height:100%;
  width:0;
  background:var(--blue);
  transition:.2s;
}
.slide {
  display:none;
  background:var(--white);
  border:1px solid var(--line);
  border-radius:20px;
  padding:clamp(22px,5vw,48px);
  margin-top:22px;
  min-height:480px;
  box-shadow:0 10px 35px #1d35570b;
}
.slide.active { display:block; }
.eyebrow {
  color:var(--blue);
  text-transform:uppercase;
  font-size:12px;
  letter-spacing:1.4px;
  font-weight:750;
  margin-bottom:12px;
}
h1,h2 {
  color:var(--navy);
  line-height:1.2;
  margin:0 0 16px;
}
h1 { font-size:clamp(32px,5vw,48px); }
h2 { font-size:clamp(27px,4vw,36px); }
p { margin:10px 0 16px; }
.lead {
  color:var(--muted);
  font-size:18px;
  max-width:700px;
}
.phrase {
  font-size:clamp(27px,5vw,40px);
  color:var(--blue);
  font-weight:800;
  margin:20px 0;
}
.definition {
  background:var(--pale);
  border-left:4px solid var(--blue);
  padding:17px 20px;
  border-radius:10px;
  margin:22px 0;
}
.example {
  background:#f8fafc;
  border:1px solid var(--line);
  border-radius:12px;
  padding:18px;
  margin:16px 0;
}
.example small {
  color:var(--muted);
  display:block;
  margin-bottom:6px;
}
.tip {
  color:var(--green);
  font-size:14px;
  font-weight:650;
}
.pill {
  display:inline-block;
  padding:5px 10px;
  border-radius:20px;
  background:#eaf7f1;
  color:#14744f;
  font-size:12px;
  font-weight:700;
}
ul { padding-left:22px; }
li { margin:9px 0; }
.exercise {
  background:#f8fafc;
  border:1px solid var(--line);
  padding:18px;
  border-radius:12px;
  margin:16px 0;
}
input[type=text] {
  border:0;
  border-bottom:2px solid #9aa8bd;
  background:transparent;
  width:160px;
  max-width:100%;
  padding:5px;
  font:inherit;
  color:var(--navy);
  outline:none;
}
input[type=text]:focus { border-color:var(--blue); }
.word-bank {
  background:#edf2ff;
  border:1px solid #d5dfff;
  border-radius:12px;
  padding:16px 18px;
  margin:18px 0 22px;
}
.word-bank strong {
  display:block;
  color:#172b4d;
  font-size:13px;
  text-transform:uppercase;
  letter-spacing:.8px;
  margin-bottom:10px;
}
.word-list {
  display:flex;
  flex-wrap:wrap;
  gap:8px;
}
.word-item {
  background:white;
  color:#315efb;
  border:1px solid #d5dfff;
  border-radius:20px;
  padding:6px 11px;
  font-size:13px;
  font-weight:700;
}
button {
  border:0;
  cursor:pointer;
  border-radius:10px;
  padding:11px 16px;
  font-weight:700;
  font-size:14px;
  transition:.15s;
}
button:hover { transform:translateY(-1px); }
.primary { background:var(--blue); color:white; }
.secondary { background:#edf1f7; color:var(--navy); }
.outline { background:white; color:var(--blue); border:1px solid #cbd6ff; }
.controls {
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:10px;
  margin-top:22px;
  flex-wrap:wrap;
}
.controls .right { display:flex; gap:8px; }
.jump {
  display:flex;
  flex-wrap:wrap;
  gap:7px;
  margin-top:20px;
}
.jump button {
  padding:7px 10px;
  font-size:12px;
  background:#e9edf5;
  color:#42516a;
}
.jump button.current {
  background:var(--navy);
  color:white;
}
.feedback {
  font-size:14px;
  font-weight:650;
  margin-top:12px;
}
.good { color:var(--green); }
.bad { color:#b54736; }
.prompt {
  border:1px solid var(--line);
  border-radius:12px;
  padding:16px;
  margin:12px 0;
  background:#fff;
}
.prompt strong { color:var(--navy); }
.question {
  color:var(--muted);
  font-size:14px;
}
.teacher-note {
  margin-top:22px;
  padding:14px 16px;
  background:#fff8e8;
  border-radius:10px;
  color:#76551a;
  font-size:13px;
}
footer {
  text-align:center;
  color:var(--muted);
  font-size:12px;
  padding:20px;
}
@media(max-width:600px) {
  .app { margin-top:18px; }
  .slide { min-height:500px; }
  .controls { align-items:stretch; }
  .controls button { flex:1; }
}
</style>
</head>
<body>

<header>
  <strong>MARKETING ENGLISH</strong>
  <span>Practical vocabulary · B1 level · Speaking practice</span>
</header>

<main class="app">
  <div class="topline">
    <span id="sectionLabel">Introduction</span>
    <span id="counter">Slide 1 of 11</span>
  </div>
  <div class="progress"><div id="progressBar"></div></div>

  <!-- SLIDE 1 -->
  <section class="slide active" data-section="Introduction">
    <div class="eyebrow">Your practical English session</div>
    <h1>Speak English with confidence at work.</h1>
    <p class="lead">
      Today we'll explore six useful expressions for marketing
      professionals and practise using them in realistic work situations.
    </p>
    <div class="definition">
      <strong>Our plan</strong>
      <ul>
        <li>Learn six useful marketing expressions.</li>
        <li>Practise them in short sentences.</li>
        <li>Use them in a marketing meeting simulation.</li>
        <li>Develop your own ideas in an open conversation.</li>
      </ul>
    </div>
    <p class="tip">
      Don't worry about making mistakes. The goal is to communicate
      clearly and naturally.
    </p>
    <div class="teacher-note">
      Tutor note: Ask about her current role and the kind of marketing
      activities she works on before starting.
    </div>
  </section>

  <!-- SLIDE 2 -->
  <section class="slide" data-section="Vocabulary">
    <div class="eyebrow">Vocabulary 1 of 6</div>
    <span class="pill">Campaigns</span>
    <div class="phrase">Launch a campaign</div>
    <div class="definition">
      <strong>Meaning</strong>
      To officially start a marketing campaign or promotional activity.
    </div>
    <div class="example">
      <small>Example</small>
      "We're planning to launch a new advertising campaign in Germany
      next month."
    </div>
    <p><strong>Useful question:</strong> Have you recently launched a
      marketing campaign at work?</p>
    <p class="tip">
      Remember: We usually say "launch a campaign", not "open a campaign".
    </p>
  </section>

  <!-- SLIDE 3 -->
  <section class="slide" data-section="Vocabulary">
    <div class="eyebrow">Vocabulary 2 of 6</div>
    <span class="pill">Customers</span>
    <div class="phrase">Target audience</div>
    <div class="definition">
      <strong>Meaning</strong>
      The particular group of people a product, service or campaign
      is designed for.
    </div>
    <div class="example">
      <small>Example</small>
      "Our target audience is young professionals between 25 and 35."
    </div>
    <p><strong>Useful question:</strong> Who is the target audience for
      your company's main products?</p>
    <p class="tip">
      You can also say: "Our campaign targets young professionals."
    </p>
  </section>

  <!-- SLIDE 4 -->
  <section class="slide" data-section="Vocabulary">
    <div class="eyebrow">Vocabulary 3 of 6</div>
    <span class="pill">Branding</span>
    <div class="phrase">Raise brand awareness</div>
    <div class="definition">
      <strong>Meaning</strong>
      To help more people recognise and know about a brand.
    </div>
    <div class="example">
      <small>Example</small>
      "We want to raise brand awareness in the German market."
    </div>
    <p><strong>Useful question:</strong> What can a company do to make
      more people aware of its brand?</p>
    <p class="tip">A useful alternative is "increase brand recognition".</p>
  </section>

  <!-- SLIDE 5 -->
  <section class="slide" data-section="Vocabulary">
    <div class="eyebrow">Vocabulary 4 of 6</div>
    <span class="pill">Sales & growth</span>
    <div class="phrase">Generate leads</div>
    <div class="definition">
      <strong>Meaning</strong>
      To attract potential customers who may be interested in buying
      a product or service.
    </div>
    <div class="example">
      <small>Example</small>
      "The main goal of this campaign is to generate more qualified leads."
    </div>
    <p><strong>Useful question:</strong> How does your company find
      potential new customers?</p>
    <p class="tip">
      A "lead" is a potential customer who has shown interest in a business.
    </p>
  </section>

  <!-- SLIDE 6 -->
  <section class="slide" data-section="Vocabulary">
    <div class="eyebrow">Vocabulary 5 of 6</div>
    <span class="pill">Planning</span>
    <div class="phrase">Meet a deadline</div>
    <div class="definition">
      <strong>Meaning</strong>
      To finish a task or project by the agreed date or time.
    </div>
    <div class="example">
      <small>Example</small>
      "We need to meet the deadline because the campaign goes live on Friday."
    </div>
    <p><strong>Useful question:</strong> What happens if your team doesn't
      meet an important deadline?</p>
    <p class="tip">
      You can also say: "We're working towards a Friday deadline."
    </p>
  </section>

  <!-- SLIDE 7 -->
  <section class="slide" data-section="Vocabulary">
    <div class="eyebrow">Vocabulary 6 of 6</div>
    <span class="pill">Social media</span>
    <div class="phrase">Increase engagement</div>
    <div class="definition">
      <strong>Meaning</strong>
      To encourage more people to interact with content, for example
      by commenting, sharing or clicking.
    </div>
    <div class="example">
      <small>Example</small>
      "We need to increase engagement on our social media channels."
    </div>
    <p><strong>Useful question:</strong> What kind of content gets the
      most engagement in your industry?</p>
    <p class="tip">
      Engagement can include likes, comments, shares and other interactions.
    </p>
  </section>

  <!-- SLIDE 8 -->
  <section class="slide" data-section="Practice">
    <div class="eyebrow">Practice 1 · Fill in the gaps</div>
    <h2>Choose the correct expression.</h2>
    <p class="lead">
      Complete each sentence using the vocabulary from the previous slides.
      Type your answers in the gaps.
    </p>

    <div class="word-bank">
      <strong>Word Bank · Choose from these expressions</strong>
      <div class="word-list">
        <span class="word-item">Launch a campaign</span>
        <span class="word-item">Target audience</span>
        <span class="word-item">Raise brand awareness</span>
        <span class="word-item">Generate leads</span>
        <span class="word-item">Meet a deadline</span>
        <span class="word-item">Increase engagement</span>
      </div>
    </div>

    <div class="exercise">
      1. We want to __________ brand awareness in the Italian market.
      <br><input type="text" id="a1" placeholder="Your answer">
    </div>
    <div class="exercise">
      2. Our __________ is mainly young professionals.
      <br><input type="text" id="a2" placeholder="Your answer">
    </div>
    <div class="exercise">
      3. The marketing team needs to __________ a new campaign next week.
      <br><input type="text" id="a3" placeholder="Your answer">
    </div>
    <div class="exercise">
      4. We need to __________ more leads through our website.
      <br><input type="text" id="a4" placeholder="Your answer">
    </div>
    <div class="exercise">
      5. The team is working hard to __________ the deadline.
      <br><input type="text" id="a5" placeholder="Your answer">
    </div>
    <div class="exercise">
      6. Interesting posts can help us __________ engagement.
      <br><input type="text" id="a6" placeholder="Your answer">
    </div>

    <button class="primary" onclick="checkAnswers()">Check my answers</button>
    <button class="secondary" onclick="revealAnswers()">Show answers</button>
    <div id="feedback1" class="feedback" aria-live="polite"></div>

    <div class="teacher-note">
      Tutor note: Accept grammatically correct variations. Encourage
      her to say each completed sentence aloud.
    </div>
  </section>

  <!-- SLIDE 9 -->
  <section class="slide" data-section="Practice">
    <div class="eyebrow">Practice 2 · Marketing in context</div>
    <h2>Complete the marketing update.</h2>
    <p>
      Imagine you're giving an update to your international colleagues
      during a team meeting.
    </p>

    <div class="word-bank">
      <strong>Word Bank · Useful expressions</strong>
      <div class="word-list">
        <span class="word-item">Launch a campaign</span>
        <span class="word-item">Target audience</span>
        <span class="word-item">Raise brand awareness</span>
        <span class="word-item">Generate leads</span>
        <span class="word-item">Meet a deadline</span>
        <span class="word-item">Increase engagement</span>
      </div>
    </div>

    <div class="example">
      "Next month, we're planning to
      <strong>1.</strong>
      <input type="text" id="b1" placeholder="expression">
      for our new product. Our main
      <strong>2.</strong>
      <input type="text" id="b2" placeholder="expression">
      is young professionals in Germany. We also want to
      <strong>3.</strong>
      <input type="text" id="b3" placeholder="expression">
      and attract potential customers. The team is working hard to
      <strong>4.</strong>
      <input type="text" id="b4" placeholder="expression">
      before the launch date."
    </div>

    <button class="primary" onclick="checkContext()">Check answers</button>
    <button class="secondary" onclick="showContext()">Show answers</button>
    <div id="feedback2" class="feedback" aria-live="polite"></div>

    <div class="teacher-note">
      Tutor note: Ask her to explain the marketing plan again without
      reading the completed paragraph.
    </div>
  </section>

  <!-- SLIDE 10 -->
  <section class="slide" data-section="Speaking">
    <div class="eyebrow">Speaking 1 · A marketing meeting</div>
    <h2>Let's have a team meeting.</h2>
    <span class="pill">Guided role-play</span>
    <p class="lead">
      Imagine you work in the same international marketing team.
      You are discussing a new product launch in Germany.
    </p>

    <div class="word-bank">
      <strong>Word Bank · Try to use these expressions</strong>
      <div class="word-list">
        <span class="word-item">Launch a campaign</span>
        <span class="word-item">Target audience</span>
        <span class="word-item">Raise brand awareness</span>
        <span class="word-item">Generate leads</span>
        <span class="word-item">Meet a deadline</span>
        <span class="word-item">Increase engagement</span>
      </div>
    </div>

    <div class="prompt">
      <strong>Your role: Marketing team member</strong>
      <p>
        Explain your ideas to a colleague. Try to use at least four
        expressions from today's lesson.
      </p>
    </div>
    <div class="prompt">
      <strong>Discuss these points:</strong>
      <ul>
        <li>What product or service are you going to promote?</li>
        <li>Who is your target audience?</li>
        <li>How will you raise brand awareness?</li>
        <li>How could the campaign generate leads?</li>
        <li>What is the deadline?</li>
        <li>How will you increase engagement?</li>
      </ul>
    </div>
    <p class="question">
      Tutor prompt: "We're planning a new campaign. Could you tell me
      who we should target and what our main objectives should be?"
    </p>
    <div class="teacher-note">
      Tutor note: Play the colleague. Ask follow-up questions, introduce
      a small challenge and encourage her to respond spontaneously.
    </div>
  </section>

  <!-- SLIDE 11 -->
  <section class="slide" data-section="Speaking">
    <div class="eyebrow">Speaking 2 · Open conversation</div>
    <h2>Your ideas, your experience.</h2>
    <span class="pill">Open discussion</span>
    <p class="lead">
      Now let's move beyond the example. Talk about your own work
      and opinions. There are no fixed answers.
    </p>

    <div class="word-bank">
      <strong>Useful expressions · Try to use them naturally</strong>
      <div class="word-list">
        <span class="word-item">Launch a campaign</span>
        <span class="word-item">Target audience</span>
        <span class="word-item">Raise brand awareness</span>
        <span class="word-item">Generate leads</span>
        <span class="word-item">Meet a deadline</span>
        <span class="word-item">Increase engagement</span>
      </div>
    </div>

    <div class="prompt">
      <strong>1. Your company</strong>
      <p>What makes a marketing campaign successful in your industry?</p>
    </div>
    <div class="prompt">
      <strong>2. Your experience</strong>
      <p>
        Can you describe a campaign that worked particularly well?
        What was its target audience?
      </p>
    </div>
    <div class="prompt">
      <strong>3. Your opinion</strong>
      <p>
        Do you think social media is the best way to raise brand awareness
        today? Why or why not?
      </p>
    </div>
    <div class="prompt">
      <strong>4. A challenge</strong>
      <p>
        Imagine your team is behind schedule and might miss an important
        deadline. What would you say in the meeting?
      </p>
    </div>
    <div class="prompt">
      <strong>5. Looking ahead</strong>
      <p>
        If you could improve one thing about your company's marketing
        strategy, what would it be?
      </p>
    </div>
    <p class="tip">
      Challenge: Try to use at least four of today's expressions
      naturally in your answers.
    </p>
    <div class="teacher-note">
      Tutor note: Let the student lead the conversation. Correct selectively,
      note recurring language needs and finish by highlighting what she
      communicated successfully.
    </div>
  </section>

  <div class="controls">
    <button class="secondary" onclick="previousSlide()">← Previous</button>
    <div class="right">
      <button class="outline" onclick="toggleJump()">All slides</button>
      <button class="primary" onclick="nextSlide()">Next →</button>
    </div>
  </div>
  <div class="jump" id="jumpMenu" style="display:none"></div>
</main>

<footer>
  Marketing English · Practical vocabulary and speaking practice
</footer>

<script>
const slides = [...document.querySelectorAll('.slide')];
let current = 0;
const jumpMenu = document.getElementById('jumpMenu');

const labels = [
  "Introduction",
  "1 · Launch a campaign",
  "2 · Target audience",
  "3 · Raise brand awareness",
  "4 · Generate leads",
  "5 · Meet a deadline",
  "6 · Increase engagement",
  "Practice · Gap fill",
  "Practice · In context",
  "Speaking · Meeting",
  "Speaking · Open discussion"
];

function showSlide(index) {
  current = Math.max(0, Math.min(index, slides.length - 1));

  slides.forEach((s,i) =>
    s.classList.toggle('active', i === current)
  );

  document.getElementById('counter').textContent =
    `Slide ${current + 1} of ${slides.length}`;

  document.getElementById('sectionLabel').textContent =
    slides[current].dataset.section;

  document.getElementById('progressBar').style.width =
    `${((current + 1) / slides.length) * 100}%`;

  [...jumpMenu.children].forEach((b,i) =>
    b.classList.toggle('current', i === current)
  );

  window.scrollTo({top:0, behavior:'smooth'});
}

function nextSlide() {
  showSlide(current + 1);
}

function previousSlide() {
  showSlide(current - 1);
}

function toggleJump() {
  jumpMenu.style.display =
    jumpMenu.style.display === 'none' ? 'flex' : 'none';
}

labels.forEach((label,i) => {
  const button = document.createElement('button');
  button.textContent = `${i+1}. ${label}`;
  button.onclick = () => showSlide(i);
  jumpMenu.appendChild(button);
});

document.addEventListener('keydown', e => {
  if (e.key === 'ArrowRight') nextSlide();
  if (e.key === 'ArrowLeft') previousSlide();
});

function normalise(s) {
  return s.toLowerCase().trim()
    .replace(/[.!?]/g,'')
    .replace(/\s+/g,' ');
}

function checkGroup(ids, answers, outputId) {
  let score = 0;

  ids.forEach((id,i) => {
    const input = document.getElementById(id);
    const correct = answers[i].some(
      answer => normalise(input.value) === normalise(answer)
    );

    input.style.borderBottomColor =
      correct ? '#16845b' : '#c65345';

    if (correct) score++;
  });

  const output = document.getElementById(outputId);
  output.className =
    'feedback ' + (score === ids.length ? 'good' : 'bad');

  output.textContent =
    `${score} out of ${ids.length} correct. ` +
    (score === ids.length
      ? 'Excellent work!'
      : 'Review the expressions and try again.');
}

function checkAnswers() {
  checkGroup(
    ['a1','a2','a3','a4','a5','a6'],
    [
      ['raise','raise brand awareness'],
      ['target audience'],
      ['launch','launch a campaign'],
      ['generate','generate leads'],
      ['meet','meet a deadline'],
      ['increase','increase engagement']
    ],
    'feedback1'
  );
}

function revealAnswers() {
  const values = [
    'raise brand awareness',
    'target audience',
    'launch a campaign',
    'generate leads',
    'meet a deadline',
    'increase engagement'
  ];

  values.forEach((value,i) => {
    const input = document.getElementById('a'+(i+1));
    input.value = value;
    input.style.borderBottomColor = '#16845b';
  });

  const output = document.getElementById('feedback1');
  output.textContent =
    'Answers revealed. Now read each sentence aloud.';
  output.className = 'feedback good';
}

function checkContext() {
  checkGroup(
    ['b1','b2','b3','b4'],
    [
      ['launch a campaign','launch'],
      ['target audience'],
      ['raise brand awareness','generate leads'],
      ['meet a deadline']
    ],
    'feedback2'
  );
}

function showContext() {
  const values = [
    'launch a campaign',
    'target audience',
    'generate leads',
    'meet a deadline'
  ];

  values.forEach((value,i) => {
    document.getElementById('b'+(i+1)).value = value;
  });

  const output = document.getElementById('feedback2');
  output.textContent =
    'Suggested answers shown. Other logical answers may also work.';
  output.className = 'feedback good';
}

showSlide(0);
</script>
</body>
</html>
