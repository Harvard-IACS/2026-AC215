---
layout: page
title: Project Showcase
description: Listing of Project Showcase Information.
nav_order: 7
---

{% comment %}
Generated from the "AC215 2026 - Showcase Info" form responses by
tools/showcase_page.py in the AC215_admin repo. The next run replaces this file,
so change a project through its form response, not here.
{% endcomment %}

<style>
.project-showcase {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(14rem, 1fr));
  gap: 1.25rem;
  margin: 1.5rem 0;
}

.project-card {
  display: flex;
  flex-direction: column;
  padding: 1rem;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  background: #fff;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.07), 0 4px 14px rgba(0, 0, 0, 0.05);
}

/* The whole image shows, letterboxed: most uploads are wide logos or screenshots. */
.project-image {
  display: block;
  width: 100%;
  aspect-ratio: 16 / 9;
  object-fit: contain;
  background: #f5f6fa;
  border-radius: 6px;
  margin-bottom: 0.75rem;
}

.main-content .project-card .project-title {
  margin: 0 0 0.5rem;
  font-size: 1.125rem;
  line-height: 1.3;
  color: #27262b;
}

.main-content .project-card .project-description {
  margin: 0 0 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  color: #5c5962;
}

.project-placeholder {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0 1rem;
  font-size: 1.25rem;
  font-weight: 600;
  text-align: center;
  color: #5c5962;
}

.project-card .anchor-heading {
  display: none !important;
}
</style>

## AC215 Project Showcase

**December 14, 2026 · 9:00 AM – 3:00 PM**

Projects created by AC215 students.

*More projects coming soon.*

<div class="project-showcase">
{% raw %}

<div class="project-card">
  <img src="../assets/projects/All-Weather-Asset-Allocation-Platform.jpg" alt="All-Weather Asset Allocation Platform" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-all-weather-asset-allocation-platform">All-Weather Asset Allocation Platform</h3>
  <p class="project-description">
    All-Weather Portfolio is an intelligent investment platform that automatically generates diversified portfolio allocations based on users' risk tolerance. It offers personalized strategies across asset classes that help users manage risk while pursuing long-term growth.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/CareerGraph.png" alt="CareerGraph" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-careergraph">CareerGraph</h3>
  <p class="project-description">
    CareerGraph helps early-career candidates understand how well their resumes match real data and machine learning job openings. It checks each requirement against the resume and suggests whether to apply, reframe experience, or build missing skills.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/CareOneX.png" alt="CareOneX" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-careonex">CareOneX</h3>
  <p class="project-description">
    Home care Voice Agents
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Crossed-Out-Not-Lost.png" alt="Crossed Out, Not Lost" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-crossed-out-not-lost">Crossed Out, Not Lost</h3>
  <p class="project-description">
    Crossed Out, Not Lost uses document AI to detect crossed-out text in PDFs and scanned documents, making deletions visible and preserving them in structured text output.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/DishMatcher.png" alt="DishMatcher" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-dishmatcher">DishMatcher</h3>
  <p class="project-description">
    Our app helps users to match the picture of a restaurant dish they wish to order with the correct corresponding menu text entry.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Earthgrep.png" alt="Earthgrep" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-earthgrep">Earthgrep</h3>
  <p class="project-description">
    Earthgrep is a search engine for the physical world. You type what you want to find, such as “golf courses in Massachusetts”, and Earthgrep searches Google’s AlphaEarth satellite embeddings and shows the matches on a map. Try it yourself on <a href="https://app.earthgrep.com" target="_blank" rel="noopener">app.earthgrep.com</a>.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/EverFit-AI.jpg" alt="EverFit AI" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-everfit-ai">EverFit AI</h3>
  <p class="project-description">
    An agentic AI platform that monitors ML models, detects drift, and diagnoses performance issues. It recommends fixes and automates retraining to keep models accurate and reliable.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/FurCast.png" alt="FurCast" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-furcast">FurCast</h3>
  <p class="project-description">
    FurCast is a machine-learning platform that helps animal shelters spot animals at risk of long stays and get them adopted sooner. It predicts each animal’s chance of adoption in the next 30 days and flags slow-track animals on a daily dashboard.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Glimpse.jpg" alt="Glimpse" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-glimpse">Glimpse</h3>
  <p class="project-description">
    Glimpse helps people find photos by describing what they remember, such as “sunset by the lake.” We combine fine-tuned vision-language models with a cloud-deployed search service to retrieve relevant images without manually tagging them.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Hall-Monitor.jpg" alt="Hall Monitor" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-hall-monitor">Hall Monitor</h3>
  <p class="project-description">
    Hall Monitor scrapes hours-long city public meetings and makes them searchable. It shows an emotion analysis graph of when things get heated, summarizes the meeting, and as a companion for journalists, it present the top news stories that could come out of the meeting.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/LandmarkersAI-NYC-Landmarks-Preservation-Commission-AI-Agent.png" alt="LandmarkersAI - NYC Landmarks Preservation Commission AI Agent" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-landmarkersai-nyc-landmarks-preservation-commission-ai-agent">LandmarkersAI - NYC Landmarks Preservation Commission AI Agent</h3>
  <p class="project-description">
    Enter a New York City property address and describe your proposed work. The app estimates the landmark permit review pathway and shows relevant Landmarks Preservation Commission rules and similar past permits.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Medical-Assistant-Project-MAP.jpg" alt="Medical Assistant Project (MAP)" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-medical-assistant-project-map">Medical Assistant Project (MAP)</h3>
  <p class="project-description">
    MAP helps patients explore and understand their medical records in plain language. In our demo, users can browse synthetic health records and ask questions about lab results, medications, and health history, with answers that cite the source records.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/PawGuide.jpg" alt="PawGuide" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-pawguide">PawGuide</h3>
  <p class="project-description">
    PawGuide is an AI-powered dog health tracking application that analyzes stool images, records health observations, and provides evidence-based guidance through a veterinary knowledge RAG system.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Poisson.png" alt="Poisson" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-poisson">Poisson</h3>
  <p class="project-description">
    Poisson is an AI-enabled web app that helps recreational fishers know what they are allowed to do with the fish they catch. Upload a photo, and Poisson identifies the species, explains the local regulations that apply, and answers your questions with sources.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/PolyHistor.jpg" alt="PolyHistor" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-polyhistor">PolyHistor</h3>
  <p class="project-description">
    PolyHistor is a web app that lets users explore 2D art across a rich shared embedding space. A text or image prompt produces a small “exhibit” of paintings from more than 104,000 artworks, with an interactive map of their thematic relationships.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/ResearchPulse.png" alt="ResearchPulse" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-researchpulse">ResearchPulse</h3>
  <p class="project-description">
    ResearchPulse helps you spot the next big idea in AI/ML before everyone else does. Every day it scans what researchers and developers are posting, reading and discussing, and points out the topics that are small today but about to grow.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/RoamWise-Your-AI-Powered-Travel-Companion.jpg" alt="RoamWise - Your AI-Powered Travel Companion" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-roamwise-your-ai-powered-travel-companion">RoamWise - Your AI-Powered Travel Companion</h3>
  <p class="project-description">
    RoamWise transforms your travel interests—whether history, museums, food, or nature—into personalized adventures across Greater Boston. Share your preferences, pick your favorite AI-ranked spots, and RoamWise turns them into a customized itinerary.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Rumi.jpg" alt="Rumi" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-rumi">Rumi</h3>
  <p class="project-description">
    Rumi keeps academics up to date with new research and latest news. Every day, Rumi picks the papers and announcements related to your own research that matter most, explaining how such breakthroughs could be integrated in your work.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Triage.png" alt="Triage" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-triage">Triage</h3>
  <p class="project-description">
    Triage helps trial coordinators quickly and accurately match breast cancer patients to eligible clinical trials. By explaining its reasoning for every eligibility criterion, Triage serves as a transparent screening aid that lets coordinators verify each match.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/VantageX.png" alt="VantageX" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-vantagex">VantageX</h3>
  <p class="project-description">
    VantageX helps AI researchers write social posts that resonate with their community. It retrieves similar peer posts from Bluesky, drafts with Claude, and surfaces which emerging AI names are likely to keep gaining attention.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/YardBird.png" alt="YardBird" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-yardbird">YardBird</h3>
  <p class="project-description">
    Yardbird is an event-discovery app. We built a self-expanding, self-healing web crawler to find events, and an addictive swiping interface that learns each user's taste.
  </p>
</div>

{% endraw %}
</div>
