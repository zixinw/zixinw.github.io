---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<div id='about-me'>

<p><em>Last updated: 23 July 2026</em></p>

<p>I am a Ph.D. student in the <strong><a href="https://www.si.umich.edu/">School of Information</a></strong> at the <strong><a href="https://umich.edu/">University of Michigan, Ann Arbor</a></strong>, where I am fortunate to be advised by Prof. <strong><a href="https://www.florianschaub.com/">Florian Schaub</a></strong> and Prof. <strong><a href="https://www.si.umich.edu/people/christopher-brooks">Christopher Brooks</a></strong>.</p>

<p>My research focuses on <strong>privacy and agency for low-control users</strong> — people who are affected by data collection but are not fully in charge of it. This includes tenants in smart homes, bystanders around sensing devices, and blind or low vision individuals navigating social interaction without visual cues. Using <strong>quant-driven mixed methods</strong> (large-scale surveys, vignette experiments, statistical modeling, and thematic analysis), I study how people navigate these situations and design tools that support them: clearer disclosures, safer defaults, and lower-burden interactions.</p>

<p>I hold a B.S. in Psychology from <strong><a href="https://english.swu.edu.cn/">Southwest University</a></strong> and an M.S. from the Department of Psychology and Behavioral Sciences at <strong><a href="https://www.zju.edu.cn/english/">Zhejiang University</a></strong>. Previously I was a research assistant at <strong><a href="https://www.jhu.edu/">Johns Hopkins University</a></strong> with Prof. <strong><a href="https://yaxingyao.github.io/">Yaxing Yao</a></strong>, and at Southwest University with Prof. <strong>Qinghua He</strong>. I have also been fortunate to work alongside Prof. <strong><a href="https://www.dannyhuang.net/">Danny Yuxing Huang</a></strong> (New York University) and Prof. <strong><a href="https://haojianj.in/">Haojian Jin</a></strong> (UC San Diego).</p>

<p>My research interests lie in:</p>

<ul>
<li>(1) usable privacy and security for populations with limited control over data collection</li>
<li>(2) accessibility and social interaction for blind and low vision users</li>
<li>(3) privacy, trust, and adoption of AI assistants in institutional settings</li>
</ul>

</div>

<div style="margin: 2em 0; padding: 1.5em; background: linear-gradient(135deg, #f5f9ff 0%, #eef4ff 100%); border-left: 4px solid #00274c; border-bottom: 1px solid #00274c; border-radius: 8px; box-shadow: 0 2px 8px rgba(0, 39, 76, 0.1);">
    <strong style="color: #00274c; font-size: 1.1em; display: block; margin-bottom: 0.5em;">🤝 Open for Collaboration</strong>
    <p style="margin: 0; color: #1a3a5c; line-height: 1.6;">I am always happy to talk about <span style="background-color: #ffcb05; padding: 2px 6px; border-radius: 4px; font-weight: 700; color: #00274c;">usable privacy</span> and <span style="background-color: #ffcb05; padding: 2px 6px; border-radius: 4px; font-weight: 700; color: #00274c;">accessibility</span> research, and I am open to academic collaborations and research internship opportunities. Please feel free to email me at <a href="mailto:zixinw@umich.edu" style="color: #00274c; font-weight: 600; text-decoration: none; border-bottom: 1px solid #00274c;">zixinw@umich.edu</a>.</p>
</div>

# News

{: #news .section-title .section-title-news}

<div class="news-scroll-container">
<ul class="news-list">
<li><em>2026.02</em>: 🎉🎉 Our paper on the adoption of institutional vs. commercial AI assistants among university users is accepted to <strong>CHI 2026</strong>.</li>
<li><em>2025.12</em>: 📄📄 <strong>TunTun Diary</strong>, on AI-generated storytelling and virtual companionship for nightmare relief, is presented at <strong>SIGGRAPH Asia 2025 Posters</strong>.</li>
<li><em>2025.08</em>: 🗣️🗣️ Presented our survey study of privacy perceptions in commercial vs. university-specific ChatGPT deployments at <strong>SOUPS 2025</strong>.</li>
<li><em>2024.09</em>: 🎓🎓 Started my Ph.D. at the University of Michigan School of Information.</li>
<li><em>2024.02</em>: 🎉🎉 Our work on real-time voice interaction monitoring and ambient light privacy notification is accepted to <strong>USEC 2024</strong>.</li>
<li><em>2023.08</em>: 🎉🎉 <strong>Exploring Tenants' Preferences of Privacy Negotiation in Airbnb</strong> is presented at <strong>USENIX Security 2023</strong>.</li>
</ul>
</div>

# Publications

{: #publications .section-title .section-title-publication}

<p><sup>*</sup> indicates equal contribution.</p>

## Usable Privacy and Security

<div class="publication-list">

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/chi26-ai-assistants.png" onerror="this.src='images/pub/placeholder.svg'" alt="AI assistants adoption"></div>
<div class="pub-body">
<div class="pub-venue-label">CHI 2026</div>
<div class="pub-title">Privacy and Trust versus Utility: Adoption of Institutional and Commercial AI Assistants Among University Users</div>
<div class="pub-authors">Yuting Yang, <strong>Zixin Wang</strong>, Rongjun Ma, Florian Schaub.</div>
<div class="pub-venue">ACM CHI Conference on Human Factors in Computing Systems (CHI '26).</div>
</div>
</div>

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/soups25-chatgpt.png" onerror="this.src='images/pub/placeholder.svg'" alt="ChatGPT privacy perceptions"></div>
<div class="pub-body">
<div class="pub-venue-label">SOUPS 2025</div>
<div class="pub-title">Privacy Perceptions in the Use of ChatGPT Across Different Contexts: A Survey Study of Commercial vs. University-specific Implementations</div>
<div class="pub-authors">Yuting Yang, <strong>Zixin Wang</strong>, Florian Schaub.</div>
<div class="pub-venue">Symposium on Usable Privacy and Security (SOUPS '25).</div>
</div>
</div>

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/usec24-voice.png" onerror="this.src='images/pub/placeholder.svg'" alt="Voice interaction privacy notification"></div>
<div class="pub-body">
<div class="pub-venue-label">USEC 2024</div>
<div class="pub-title">Towards Real-time Voice Interaction Data Collection Monitoring and Ambient Light Privacy Notification for Voice-controlled Services</div>
<div class="pub-authors">Tu Le, <strong>Zixin Wang</strong>, Danny Yuxing Huang, Yaxing Yao, Yuan Tian.</div>
<div class="pub-venue">Symposium on Usable Security and Privacy (USEC '24).</div>
</div>
</div>

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/usenix23-airbnb.png" onerror="this.src='images/pub/placeholder.svg'" alt="Airbnb tenant privacy negotiation"></div>
<div class="pub-body">
<div class="pub-venue-label">USENIX Security 2023</div>
<div class="pub-title"><a href="https://www.usenix.org/conference/usenixsecurity23/presentation/wang-zixin">Exploring Tenants' Preferences of Privacy Negotiation in Airbnb</a></div>
<div class="pub-authors"><strong>Zixin Wang</strong>, Danny Yuxing Huang, Yaxing Yao.</div>
<div class="pub-venue">32nd USENIX Security Symposium (USENIX Security '23).</div>
<div class="pub-links"><a href="https://www.usenix.org/conference/usenixsecurity23/presentation/wang-zixin">Paper PDF</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/usec23-ar.png" onerror="this.src='images/pub/placeholder.svg'" alt="AR home privacy leaks"></div>
<div class="pub-body">
<div class="pub-venue-label">USEC 2023</div>
<div class="pub-title">Augmented Reality's Potential for Identifying and Mitigating Home Privacy Leaks</div>
<div class="pub-authors">Stefany Cruz, Logan Danek, Shinan Liu, Christopher Kraemer, <strong>Zixin Wang</strong>, Nick Feamster, Danny Yuxing Huang, Yaxing Yao, Josiah Hester.</div>
<div class="pub-venue">Workshop on Usable Security and Privacy (USEC '23).</div>
</div>
</div>

</div>

## Social Media and Online Communities

<div class="publication-list">

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/iconf23-censorship.png" onerror="this.src='images/pub/placeholder.svg'" alt="Chinese social media censorship"></div>
<div class="pub-body">
<div class="pub-venue-label">iConference 2023</div>
<div class="pub-title">How We Express Ourselves Freely: Censorship, Self-censorship, and Anti-censorship on a Chinese Social Media</div>
<div class="pub-authors">Xiang Chen, Jiamu Xie, <strong>Zixin Wang</strong>, Bohui Shen, Zhixuan Zhou.</div>
<div class="pub-venue">18th International Conference on Information (iConference '23).</div>
</div>
</div>

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/hicss23-anonymous.png" onerror="this.src='images/pub/placeholder.svg'" alt="Anonymous expression online community"></div>
<div class="pub-body">
<div class="pub-venue-label">HICSS 2023</div>
<div class="pub-title">Anonymous Expression in an Online Community for Women in China</div>
<div class="pub-authors">Zhixuan Zhou, <strong>Zixin Wang</strong>, Franziska Zimmer.</div>
<div class="pub-venue">56th Hawaii International Conference on System Sciences (HICSS '23).</div>
</div>
</div>

</div>

## Other Work

<div class="publication-list">

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/siggraph25-tuntun.png" onerror="this.src='images/pub/placeholder.svg'" alt="TunTun Diary nightmare relief"></div>
<div class="pub-body">
<div class="pub-venue-label">SIGGRAPH Asia 2025 Posters</div>
<div class="pub-title">TunTun Diary: Exploring AI-Generated Storytelling and Virtual Companionship for Nightmare Relief</div>
<div class="pub-authors"><strong>Zixin Wang</strong>, Sirui Luo, Shuning Tian, Yidan Cai, Lin Ling, Mengyao Xu, Jingyu Yu, Guanhua Lu, Jiajun Zhu, Lin Luo.</div>
<div class="pub-venue">SIGGRAPH Asia Posters, 2025.</div>
</div>
</div>

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/icdcs23-crypto.png" onerror="this.src='images/pub/placeholder.svg'" alt="Cryptocurrency energy labelling"></div>
<div class="pub-body">
<div class="pub-venue-label">ICDCS 2023</div>
<div class="pub-title">The More You Know: Energy Labelling Enables More Sustainable Cryptocurrency Investments</div>
<div class="pub-authors">Adriana Elena Drăgnoiu, Moritz Platt, <strong>Zixin Wang</strong>, Zhixuan Zhou.</div>
<div class="pub-venue">IEEE 43rd International Conference on Distributed Computing Systems (ICDCS '23).</div>
</div>
</div>

</div>

# Education

{: #educations .section-title .section-title-education}

<div class="education-item">
  <div class="logo-container">
    <img src="images/umich-logo.png" alt="University of Michigan Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">University of Michigan, Ann Arbor</div>
    <div class="subtitle">Ph.D. in Information</div>
    <div class="date">2024.09 - Present</div>
    <div class="description">Advised by Prof. <a href="https://www.florianschaub.com/">Florian Schaub</a> and Prof. <a href="https://www.si.umich.edu/people/christopher-brooks">Christopher Brooks</a>, <a href="https://www.si.umich.edu/">School of Information</a></div>
  </div>
</div>

<div class="education-item">
  <div class="logo-container">
    <img src="images/zju-logo.png" alt="Zhejiang University Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Zhejiang University</div>
    <div class="subtitle">M.S. in Psychology and Behavioral Sciences</div>
    <div class="date">2021.09 - 2024.06</div>
    <div class="description">Department of Psychology and Behavioral Sciences</div>
  </div>
</div>

<div class="education-item">
  <div class="logo-container">
    <img src="images/swu-logo.png" alt="Southwest University Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Southwest University</div>
    <div class="subtitle">B.S. in Psychology</div>
    <div class="date">2017.09 - 2021.06</div>
    <div class="description">Advised by Prof. Qinghua He</div>
  </div>
</div>

# Research Experience

{: #internships .section-title .section-title-internship}

<div class="internship-item highlight">
  <div class="logo-container">
    <img src="images/umich-logo.png" alt="University of Michigan Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">University of Michigan School of Information</div>
    <div class="subtitle">Graduate Student Research Assistant</div>
    <div class="date">2024.09 - Present</div>
    <div class="description">Privacy and agency for low-control users; privacy and trust in institutional AI assistants.</div>
  </div>
</div>

<div class="internship-item">
  <div class="logo-container">
    <img src="images/jhu-logo.png" alt="Johns Hopkins University Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Johns Hopkins University</div>
    <div class="subtitle">Research Assistant</div>
    <div class="date">2022 - 2024</div>
    <div class="description">Advised by Prof. <a href="https://yaxingyao.github.io/">Yaxing Yao</a>. Smart home and short-term rental privacy; ambient privacy notification for voice assistants.</div>
  </div>
</div>

<div class="internship-item">
  <div class="logo-container">
    <img src="images/swu-logo.png" alt="Southwest University Logo" loading="lazy">
  </div>
  <div class="content">
    <div class="title">Southwest University</div>
    <div class="subtitle">Research Assistant</div>
    <div class="date">2019 - 2021</div>
    <div class="description">Advised by Prof. Qinghua He.</div>
  </div>
</div>

# Academic Service

{: #academic-service .section-title .section-title-service}

**Conference Reviewer**

* **2026:** *CHI 2026* (Papers), *CHI 2026* (Case Studies), *CHI PLAY 2026* (Work-in-Progress), *L@S 2026*, *iConference 2026*
* **2025:** *CHI 2025* (Late-Breaking Work), *iConference 2025*, *HICSS 58*
* **2024:** *CHI 2024* (Late-Breaking Work), *CSCW 2024*, *IMX 2024*
* **2023:** *CHI 2023* (Late-Breaking Work), *HICSS 56*

**Journal Reviewer**

* *Information, Communication & Society*

**Professional Membership**

* ACM / ACM SIGCHI

# Teaching

{: #teaching .section-title .section-title-teaching}

* **[Term, Year]:** Graduate Student Instructor for *[Course Number: Course Title]*, <strong><a href="https://www.si.umich.edu/">University of Michigan School of Information</a></strong>

# More About Me

{: #more-about-me .section-title .section-title-about}

- I came to HCI from psychology, and I still think like a psychologist: I care most about *why* people make the privacy choices they do, not just what they click.
- Outside of research, [add a hobby or two here].
