---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% assign meeting_url = site.author.meeting | default: "mailto:zixinw@umich.edu?subject=Short%20meeting%20request" %}

<div id='about-me'>

<p>I am a Ph.D. student in the <strong><a href="https://www.si.umich.edu/">School of Information</a></strong> at the <strong><a href="https://umich.edu/">University of Michigan, Ann Arbor</a></strong>, where I am fortunate to be advised by Prof. <strong><a href="https://www.si.umich.edu/people/florian-schaub">Florian Schaub</a></strong> and Prof. <strong><a href="https://www.si.umich.edu/people/christopher-brooks">Christopher Brooks</a></strong>.</p>

<p>My research sits at the intersection of <strong>human-centered security, human-AI interaction, and usable privacy and security</strong>. I am especially interested in how people make sense of complex systems, negotiate privacy and control with other stakeholders, and adapt their behavior as AI systems become more autonomous. Methodologically, I use mixed methods including large-scale surveys, vignette experiments, statistical modeling, and qualitative analysis.</p>

<p>I hold an M.Sc. in Applied Psychology from <strong><a href="https://www.zju.edu.cn/english/">Zhejiang University</a></strong> and a B.Sc. in Psychology from <strong><a href="https://admissions.swu.edu.cn/">Southwest University</a></strong>. Previously I was a research assistant at <strong><a href="https://www.jhu.edu/">Johns Hopkins University</a></strong> with Prof. <strong><a href="https://yaxingyao.github.io/">Yaxing Yao</a></strong>. I have also been fortunate to work alongside Prof. <strong><a href="https://www.dannyhuang.net/">Danny Yuxing Huang</a></strong> (<a href="https://www.nyu.edu/">New York University</a>) and Prof. <strong><a href="https://haojianj.in/">Haojian Jin</a></strong> (<a href="https://ucsd.edu/">UC San Diego</a>).</p>

<div class="ro-label" id="research-overview">Research Overview</div>

<div class="research-overview">
  <div class="ro-item">
    <div class="ro-num">01</div>
    <div class="ro-body">
      <div class="ro-h">Human-Centered Security</div>
      <p>How people perceive, reason about, and respond to security and privacy threats in everyday and multi-stakeholder settings such as smart homes, short-term rentals, and shared devices, and how those perceptions shape the protections they actually adopt.</p>
    </div>
  </div>
  <div class="ro-item">
    <div class="ro-num">02</div>
    <div class="ro-body">
      <div class="ro-h">Human-AI Interaction</div>
      <p>How people understand, trust, disclose to, and make decisions with conversational and agentic AI systems, and how they keep awareness, agency, and meaningful control as AI moves from answering prompts to acting on their behalf.</p>
    </div>
  </div>
  <div class="ro-item">
    <div class="ro-num">03</div>
    <div class="ro-body">
      <div class="ro-h">Usable Privacy and Security</div>
      <p>Designing privacy notices, controls, and negotiation mechanisms that people can actually use, grounded in large-scale surveys, vignette experiments, and qualitative studies so that protections fit real practices rather than idealized ones.</p>
    </div>
  </div>
</div>

</div>

<aside class="collaboration-callout" aria-label="Open for collaboration">
  <div class="collaboration-callout__title">Open for collaboration</div>
  <p>I am always happy to talk about <span>human-centered security, human-AI interaction, and usable privacy and security</span>, and I am open to academic collaborations and research internship opportunities. Get in touch by <a href="mailto:{{ site.author.email }}">email</a> or <a href="{{ meeting_url }}">schedule a short meeting</a>.</p>
</aside>

# News

<div class="news-scroll-container">
<ul class="news-list">
<li><span class="news-date">2026.08</span><span>Presented our paper on privacy negotiation for camera-equipped smart-home devices at <strong>USENIX Security 2026</strong> in Baltimore, MD, USA.</span></li>
<li><span class="news-date">2026.01</span><span>Our paper on the adoption of institutional vs. commercial AI assistants among university users was accepted to <strong>CHI 2026</strong> (Barcelona, Spain).</span></li>
<li><span class="news-date">2025.12</span><span>Presented <strong>TunTun Diary</strong>, on AI-generated storytelling and virtual companionship for nightmare relief, at <strong>SIGGRAPH Asia 2025 Posters</strong> in Hong Kong.</span></li>
<li><span class="news-date">2025.08</span><span>Our poster on privacy perceptions in commercial vs. university-specific ChatGPT deployments was accepted to <strong>SOUPS 2025</strong> (Seattle, WA, USA).</span></li>
<li><span class="news-date">2025</span><span>Received the <strong>Rackham Graduate Student Research Grant</strong> from the University of Michigan.</span></li>
<li><span class="news-date">2024.08</span><span>Started my Ph.D. at the University of Michigan School of Information.</span></li>
</ul>
</div>

# Selected Publications

<div class="publication-list">

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/usenix26-routes.png" onerror="this.src='images/pub/placeholder.svg'" alt="Privacy negotiation routes for camera-equipped smart home devices in Airbnb"></div>
<div class="pub-body">
<div class="pub-venue-label">USENIX Security 2026</div>
<div class="pub-title"><a href="https://www.usenix.org/conference/usenixsecurity26/presentation/wang-zixin">Exploring Privacy Negotiation Strategies for Camera-Equipped Smart Home Devices in Airbnb</a></div>
<div class="pub-authors"><strong>Zixin Wang</strong>, Sunyup Park, Haojian Jin, Yaxing Yao.</div>
<div class="pub-venue">35th USENIX Security Symposium (USENIX Security 2026).</div>
<div class="pub-links"><a href="https://www.usenix.org/conference/usenixsecurity26/presentation/wang-zixin">USENIX</a> <a href="https://www.usenix.org/system/files/usenixsecurity26-wang-zixin.pdf">PDF</a> <a href="https://www.usenix.org/conference/usenixsecurity26/presentation/wang-zixin">Video</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/chi26-ai-assistants.png" onerror="this.src='images/pub/placeholder.svg'" alt="AI assistants adoption"></div>
<div class="pub-body">
<div class="pub-venue-label">CHI 2026</div>
<div class="pub-title"><a href="https://dl.acm.org/doi/full/10.1145/3772318.3790881">Privacy and Trust vs. Utility: Adoption of Commercial vs. Institutional AI Assistants Among University Users</a></div>
<div class="pub-authors">Yuting Yang, <strong>Zixin Wang</strong>, Rongjun Ma, Florian Schaub.</div>
<div class="pub-venue">ACM Conference on Human Factors in Computing Systems (CHI 2026).</div>
<div class="pub-links"><a href="https://dl.acm.org/doi/full/10.1145/3772318.3790881">ACM DL</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/usenix23-heatmap.png" onerror="this.src='images/pub/placeholder.svg'" alt="Heatmap of participants' comfort levels across smart home devices"></div>
<div class="pub-body">
<div class="pub-venue-label">USENIX Security 2023</div>
<div class="pub-title"><a href="https://www.usenix.org/conference/usenixsecurity23/presentation/wang-zixin">Exploring Tenants' Preferences of Privacy Negotiation in Airbnb</a></div>
<div class="pub-authors"><strong>Zixin Wang</strong>, Danny Yuxing Huang, Yaxing Yao.</div>
<div class="pub-venue">32nd USENIX Security Symposium (USENIX Security 2023), pp. 535–551.</div>
<div class="pub-links"><a href="https://www.usenix.org/conference/usenixsecurity23/presentation/wang-zixin">USENIX</a> <a href="https://www.usenix.org/system/files/usenixsecurity23-wang-zixin.pdf">PDF</a> <a href="https://www.usenix.org/conference/usenixsecurity23/presentation/wang-zixin">Video</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-thumb"><img src="images/pub/usec24-vpawatcher.png" onerror="this.src='images/pub/placeholder.svg'" alt="VPAWatcher browser extension interface in idle and monitoring states"></div>
<div class="pub-body">
<div class="pub-venue-label">USEC 2024</div>
<div class="pub-title"><a href="https://www.ndss-symposium.org/wp-content/uploads/usec2024-39-paper.pdf">Towards Real-Time Voice Interaction Data Collection Monitoring and Ambient Light Privacy Notification for Voice-Controlled Services</a></div>
<div class="pub-authors">Tu Le, <strong>Zixin Wang</strong>, Danny Yuxing Huang, Yaxing Yao, Yuan Tian.</div>
<div class="pub-venue">Symposium on Usable Security and Privacy (USEC 2024).</div>
<div class="pub-links"><a href="https://www.ndss-symposium.org/wp-content/uploads/usec2024-39-paper.pdf">PDF</a></div>
</div>
</div>

</div>

<p class="all-publications-link"><a href="{{ site.author.googlescholar }}">View the complete publication list on Google Scholar →</a></p>

# Education

<div class="education-item">
  <div class="logo-container"><img src="images/logos/umich-seal.svg" alt="University of Michigan seal"></div>
  <div class="content">
    <div class="title">University of Michigan, Ann Arbor</div>
    <div class="subtitle">Ph.D. in Information Science</div>
    <div class="date">2024.08 - Present</div>
    <div class="description">Advised by Prof. <a href="https://www.si.umich.edu/people/florian-schaub">Florian Schaub</a> and Prof. <a href="https://www.si.umich.edu/people/christopher-brooks">Christopher Brooks</a>, <a href="https://www.si.umich.edu/">School of Information</a></div>
  </div>
</div>

<div class="education-item">
  <div class="logo-container"><img src="images/logos/zju-emblem.svg" alt="Zhejiang University emblem"></div>
  <div class="content">
    <div class="title">Zhejiang University</div>
    <div class="subtitle">M.Sc. in Applied Psychology</div>
    <div class="date">2021.09 - 2024.06</div>
    <div class="description">Thesis: <em>Empowering Users to Navigate Privacy in Self-Disclosure with Large Language Models</em></div>
  </div>
</div>

<div class="education-item">
  <div class="logo-container"><img src="images/logos/swu-emblem.svg" alt="Southwest University emblem"></div>
  <div class="content">
    <div class="title">Southwest University</div>
    <div class="subtitle">B.Sc. in Psychology</div>
    <div class="date">2017.09 - 2021.06</div>
    <div class="description">Thesis: <em>Socioeconomic Status and Financial Literacy Among High School Students</em></div>
  </div>
</div>

# Teaching

* **Fall 2026:** Graduate Student Instructor for **SI 544: Introduction to Statistics and Data Analysis**, <strong><a href="https://www.si.umich.edu/">University of Michigan School of Information</a></strong>

# Awards

* **2025:** Rackham Graduate Student Research Grant (~\$1,500), University of Michigan
* **2024:** Excellent Graduate, Zhejiang University
* **2021:** Excellent Graduate (City-Level), Chongqing
* **2020:** Science Scholarship (~\$3,000), Southwest University
* **2020:** National Scholarship (~\$1,200), Southwest University

# Academic Service

* **Conference reviewer:** CHI 2026, CHI LBW 2023–2025, CSCW 2024
* **Journal reviewer:** *Information, Communication & Society*
* **Recognition:** Two Special Recognitions for Outstanding Reviews

<p class="last-updated">Last updated: 30 August 2026</p>
