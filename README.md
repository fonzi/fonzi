<!-- <p align="center">
  <a href="https://fonzi.xyz">
    <img src="https://github.com/fonzi/fonzi.xyz/raw/main/fonzi.gif"/>
  </a>
</p> -->


<p align="center">
  <a href="https://fonzi.xyz" target="_blank" class="neon-text startup-flicker">
    FO<span class="flicker-n">N</span>ZI.<span class="flicker-x">X</span>YZ
  </a>
</p>

<style>
.neon-text {
  font-family: 'Lucida Console', 'Courier New', monospace;
  font-size: 6rem;
  font-weight: bold;
  color: #00f;
  text-decoration: none;
  background: linear-gradient(90deg, #00f, #33f);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  display: inline-block;
  animation: glow-breath 6s ease-in-out infinite;
  text-shadow:
    -0.5px -0.5px 0 #66f,
     0.5px -0.5px 0 #66f,
    -0.5px  0.5px 0 #66f,
     0.5px  0.5px 0 #66f,
    0 0 4px #00f,
    0 0 8px #00f,
    0 0 12px #33f,
    0 0 18px #33f,
    0 0 25px #66f,
    0 0 35px #66f;
  transition: text-shadow 0.3s ease-in-out;
}

.startup-flicker {
  animation: startup 2s ease-in-out 1, glow-breath 6s ease-in-out infinite;
}

.neon-text:hover {
  text-shadow:
    -0.5px -0.5px 0 #33f,
     0.5px -0.5px 0 #33f,
    -0.5px  0.5px 0 #33f,
     0.5px  0.5px 0 #33f,
    0 0 8px #00f,
    0 0 16px #00f,
    0 0 24px #33f,
    0 0 32px #33f,
    0 0 40px #66f,
    0 0 55px #66f;
}

.flicker-n {
  animation: flicker-n 20s infinite;
  display: inline-block;
}

.flicker-x {
  animation: flicker-x 20s infinite;
  display: inline-block;
}

@keyframes startup {
  0%   { opacity: 0; }
  10%  { opacity: 1; }
  15%  { opacity: 0.1; }
  20%  { opacity: 1; }
  25%  { opacity: 0.2; }
  30%  { opacity: 1; }
  35%  { opacity: 0.5; }
  45%  { opacity: 1; }
  50%  { opacity: 0.6; }
  55%  { opacity: 1; }
  70%  { opacity: 0.8; }
  85%  { opacity: 1; }
  100% { opacity: 1; }
}

@keyframes flicker-n {
  0%, 10%   { opacity: 1; }
  0.5%      { opacity: 0.2; }
  1%        { opacity: 1; }
  1.5%      { opacity: 0.1; }
  2%        { opacity: 1; }
  2.5%      { opacity: 0.4; }
  3%        { opacity: 1; }
  100%      { opacity: 1; }
}

@keyframes flicker-x {
  0%, 10%   { opacity: 1; }
  0.7%      { opacity: 0.3; }
  1.2%      { opacity: 1; }
  1.7%      { opacity: 0.2; }
  2.2%      { opacity: 1; }
  2.7%      { opacity: 0.1; }
  3.2%      { opacity: 1; }
  100%      { opacity: 1; }
}

@keyframes glow-breath {
  0%, 100% {
    text-shadow:
      -0.5px -0.5px 0 #66f,
       0.5px -0.5px 0 #66f,
      -0.5px  0.5px 0 #66f,
       0.5px  0.5px 0 #66f,
      0 0 4px #00f,
      0 0 8px #00f,
      0 0 12px #33f,
      0 0 18px #33f,
      0 0 25px #66f,
      0 0 35px #66f;
  }
  50% {
    text-shadow:
      -0.5px -0.5px 0 #33f,
       0.5px -0.5px 0 #33f,
      -0.5px  0.5px 0 #33f,
       0.5px  0.5px 0 #33f,
      0 0 2px #00f,
      0 0 4px #33f,
      0 0 6px #33f,
      0 0 10px #66f;
  }
}
</style>


### Hi there — I'm Fonzi

Thanks for stopping by. I’m a **Software Engineer in Test** with a love for automation, minimalism, and shipping things that actually work.

Most of my time is spent writing automated tests using **Playwright**, and doing API testing with **RestSharp**, **Postman**, or **Newman** — basically any OOP-friendly tool that gets the job done.

Lately, I’ve also been diving deeper into **DevOps**, infrastructure, and the pipeline life.

---

### What I'm Into

I love tech — even though I think most of it is bloat.  
That’s why I challenged myself to build a minimalist website using **only HTML and CSS** (no JavaScript).  
You can check it out here → [fonzi.xyz](https://fonzi.xyz)

Also, if you're privacy-minded, I run my own [Searx instance](https://searx.fonzi.xyz) —  
no logs, no tracking, no gimmicks.

---

### Things I’m Working On / Learning

- Currently learning **C** and **Python**  
  > (Python’s awful. I’m doing it anyway.)
- Working toward a self-built stack:  
  `Assembly → C → Python`
- Looking to **collaborate on FOSS** projects where I can bring my QA/DevOps skills to the table
- Trying to get better at **Assembly**  
  > (Built a Pascal → MIPS compiler once. It was rough. My code’s public — feel free to laugh.)

---

### Get in Touch

Ask me about **software testing**, **automation**, or anything that breaks in CI/CD.  
me@fonzi.xyz


<p align="center" style="
  font-family: monospace;
  font-size: 1rem;
  color: #00f;
  text-shadow: 0 0 2px #00f, 0 0 4px #33f;
  animation: footer-glow 4s ease-in-out infinite;
">
  [🔍] · [🐛] · [🚢]
</p>

<style>
@keyframes footer-glow {
  0%, 100% { opacity: 0.8; transform: scale(1); }
  50%      { opacity: 1; transform: scale(1.03); }
}
</style>



