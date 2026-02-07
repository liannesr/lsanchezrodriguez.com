---
permalink: /home/
title: ""
layout: archive
redirect_from: 
  - /about.html
---

<style>
/* Aggressively remove all list styling and sidebar artifacts */
.archive ul, 
.archive ol, 
.archive li,
.sidebar ul,
.sidebar li,
.author__urls ul,
.author__urls li {
  list-style: none !important;
  list-style-type: none !important;
  margin: 0 !important;
  padding: 0 !important;
}

/* Remove any before/after pseudo elements that create bullets or arrows */
.archive li::before,
.archive li::after,
ul li::before,
ul li::after {
  content: none !important;
  display: none !important;
}

/* Hide the page title entirely */
.page__title {
  display: none !important;
}

/* Center and style the profile section */
.profile-header {
  text-align: center;
  margin: 3em auto 2em;
  max-width: 800px;
}

.profile-image {
  width: 250px;
  height: 250px;
  border-radius: 50%;
  object-fit: cover;
  box-shadow: 0 8px 16px rgba(0,0,0,0.5);
  margin-bottom: 1.5em;
  display: block;
  margin-left: auto;
  margin-right: auto;
}

.profile-name {
  margin: 0.5em 0 0.2em;
  font-size: 2.5em;
  font-weight: bold;
  color: var(--global-text-color);
}

.profile-institution {
  font-style: italic;
  font-size: 1.2em;
  color: #aaa;
  margin: 0.5em 0 1em;
}

.profile-institution i {
  margin-right: 0.3em;
}

.profile-icons {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 2em;
  margin: 1.5em 0 2em;
  font-size: 2em;
  flex-wrap: wrap;
}

.profile-icons a {
  color: #aaa;
  transition: all 0.3s ease;
  text-decoration: none;
  display: inline-block;
}

.profile-icons a:hover {
  color: #0ea1c5;
  transform: scale(1.2);
  text-decoration: none;
}

/* Content area */
.about-content {
  max-width: 900px;
  margin: 2em auto;
  padding: 0 2em;
  text-align: left;
  line-height: 1.8;
}

.about-content h2 {
  margin-top: 2em;
  margin-bottom: 1em;
  font-size: 1.8em;
  border-bottom: 2px solid var(--global-border-color);
  padding-bottom: 0.5em;
}

.about-content p {
  margin-bottom: 1.5em;
  font-size: 1.05em;
}

/* Remove any stray bullets or markers from content */
.about-content ul,
.about-content ol {
  list-style-position: inside;
  margin-left: 0;
  padding-left: 0;
}

.about-content ul li,
.about-content ol li {
  margin-left: 0;
  padding-left: 0;
}
</style>

<div class="profile-header">
  <img src="{{ site.baseurl }}/images/profile.png" 
       alt="Lianne Sánchez-Rodríguez" 
       class="profile-image">
  
  <h1 class="profile-name">Lianne Sánchez-Rodríguez</h1>
  
  <p class="profile-institution">
    <i class="fas fa-building-columns"></i> University of Houston
  </p>
  
  <div class="profile-icons">
    <a href="mailto:{{ site.author.email }}" title="Email" aria-label="Email">
      <i class="fas fa-envelope"></i>
    </a>
    <a href="{{ site.author.googlescholar }}" title="Google Scholar" aria-label="Google Scholar">
      <i class="ai ai-google-scholar"></i>
    </a>
    <a href="{{ site.author.orcid }}" title="ORCID" aria-label="ORCID">
      <i class="ai ai-orcid"></i>
    </a>
    <a href="https://github.com/{{ site.author.github }}" title="GitHub" aria-label="GitHub">
      <i class="fab fa-github"></i>
    </a>
    <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" title="LinkedIn" aria-label="LinkedIn">
  <i class="fab fa-linkedin"></i>
</a>
  </div>
</div>

<div class="about-content" markdown="1">

I was born and raised in Ponce, Puerto Rico; La Isla del Encanto. 

I am a Ph.D. student in Electrical Engineering at the University of Houston and a member of the Laboratory for Non-invasive Brain-Machine Interface Systems. I completed my M.S. in Applied Biomedical Engineering at Johns Hopkins University and my B.S. in Computer Engineering at the University of Puerto Rico, Mayagüez.

My research focuses on the analysis and decoding of non-invasive electroencephalographic (EEG) signals to better understand brain dynamics and develop human-centered technologies. My work includes developing EEG-based generative AI systems that create personalized music using brain signals, investigating the neural mechanisms behind creativity and artistic expression, and contributing to the development of brain-computer interface systems for neurorehabilitation, particularly for stroke recovery. I have also worked on multimodal neural data acquisition and embedded system optimization for wearable and portable neurotechnology.

My research is inherently multidisciplinary, integrating neuroscience, artificial intelligence, biomedical engineering, and the arts to better understand brain function and translate neural signals into meaningful real-world applications.

## Research Interests

Computational Neuroscience, Brain-Computer Interfaces, Neurorehabilitation, Music-based Interventions, Generative AI, Embedded Systems

🧠 Thanks for stopping by! Keep exploring!

</div>
