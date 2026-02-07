---
permalink: /home/
title: "About Me"
layout: single
classes: wide
---

<style>
.about-header {
  text-align: center;
  margin: 3em auto 2em;
  max-width: 800px;
}

.about-header img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  box-shadow: 0 6px 12px rgba(0,0,0,0.4);
  margin-bottom: 1.5em;
}

.about-header h1 {
  margin: 0.5em 0 0.2em;
  font-size: 2em;
}

.about-subtitle {
  font-style: italic;
  font-size: 1.1em;
  color: var(--global-text-color-light);
  margin: 0.5em 0 1em;
}

.about-icons {
  display: flex;
  justify-content: center;
  gap: 1.5em;
  margin: 1em 0 2em;
  font-size: 1.5em;
}

.about-icons a {
  color: var(--global-text-color-light);
  transition: all 0.3s ease;
}

.about-icons a:hover {
  color: var(--global-link-color);
  transform: scale(1.15);
}

.about-content {
  max-width: 800px;
  margin: 0 auto;
  text-align: left;
}
</style>

<div class="about-header">
  <img src="{{ site.baseurl }}/images/profile.png" alt="Lianne Sánchez-Rodríguez">
  <h1>{{ site.author.name }}</h1>
  <p class="about-subtitle">
    <i class="fas fa-building-columns"></i> {{ site.author.employer }}
  </p>
  
  <div class="about-icons">
    {% if site.author.email %}
      <a href="mailto:{{ site.author.email }}" title="Email" aria-label="Email">
        <i class="fas fa-envelope"></i>
      </a>
    {% endif %}
    
    {% if site.author.googlescholar %}
      <a href="{{ site.author.googlescholar }}" title="Google Scholar" aria-label="Google Scholar">
        <i class="ai ai-google-scholar"></i>
      </a>
    {% endif %}
    
    {% if site.author.orcid %}
      <a href="{{ site.author.orcid }}" title="ORCID" aria-label="ORCID">
        <i class="ai ai-orcid"></i>
      </a>
    {% endif %}
    
    {% if site.author.github %}
      <a href="https://github.com/{{ site.author.github }}" title="GitHub" aria-label="GitHub">
        <i class="fab fa-github"></i>
      </a>
    {% endif %}
  </div>
</div>

<div class="about-content">

## Short Bio
I was born and raised in Ponce, Puerto Rico; La Isla del Encanto. 

I am a Ph.D. student in Electrical Engineering at the University of Houston and a member of the Laboratory for Non-invasive Brain-Machine Interface Systems. I completed my M.S. in Applied Biomedical Engineering at Johns Hopkins University and my B.S. in Computer Engineering at the University of Puerto Rico, Mayagüez.

My research focuses on the analysis and decoding of non-invasive electroencephalographic (EEG) signals to better understand brain dynamics and develop human-centered technologies. My work includes developing EEG-based generative AI systems that create personalized music using brain signals, investigating the neural mechanisms behind creativity and artistic expression, and contributing to the development of brain-computer interface systems for neurorehabilitation, particularly for stroke recovery. I have also worked on multimodal neural data acquisition and embedded system optimization for wearable and portable neurotechnology.

My research is inherently multidisciplinary, integrating neuroscience, artificial intelligence, biomedical engineering, and the arts to better understand brain function and translate neural signals into meaningful real-world applications.

## Research Interests

Computational Neuroscience, Brain-Computer Interfaces, Neurorehabilitation, Music-based Interventions, Generative AI, Embedded Systems

🧠 Thanks for stopping by! Keep exploring!

</div>
