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

/* Groups with no card: up to two columns, one on a phone. */
.project-list {
  columns: 2 18rem;
  column-gap: 2rem;
}

.main-content .project-list li {
  margin: 0 0 0.35rem;          /* no top margin, so both columns start level */
  break-inside: avoid;
}
</style>

## AC215 Project Showcase

**December 14, 2026 · 9:00 AM – 3:00 PM**

Projects created by AC215 students.

<div class="project-showcase">
{% raw %}

<div class="project-card">
  <img src="../assets/projects/Aesop.png" alt="Aesop" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-aesop">Aesop</h3>
  <p class="project-description">
    Aesop lets language learners read any book at their level. It rewrites each chapter to fit the reader without changing the story, updates their level as they read, and works in multiple languages.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Agentic-Interlocking-Brick-Building.png" alt="Agentic Interlocking Brick Building" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-agentic-interlocking-brick-building">Agentic Interlocking Brick Building</h3>
  <p class="project-description">
    Our product generates buildable LEGO models of real buildings: an LLM agent writes a building program, and our compiler turns it into a validated model made of real parts. The web app lets you watch it go together step by step in 3D and download the parts list.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/All-Weather-Asset-Allocation-Platform.jpg" alt="All-Weather Asset Allocation Platform" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-all-weather-asset-allocation-platform">All-Weather Asset Allocation Platform</h3>
  <p class="project-description">
    All-Weather Portfolio is an intelligent investment platform that automatically generates diversified portfolio allocations based on users' risk tolerance. It offers personalized strategies across asset classes that help users manage risk while pursuing long-term growth.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/ArcTrac.png" alt="ArcTrac" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-arctrac">ArcTrac</h3>
  <p class="project-description">
    ArcTrac is a tele-rehab tool for shoulder patients. Patients record prescribed exercises, computer vision measures range of motion, and an LLM agent explains recovery progress against the care plan, alerting the physical therapist when clinical thresholds are crossed.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/ATLAS.jpg" alt="ATLAS" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-atlas">ATLAS</h3>
  <p class="project-description">
    We find where your system breaks. ATLAS is an agentic load-testing platform. Users describe a test in plain English; LLM-powered agents turn it into a plan, provision load generators on GKE, run it against the target, and explain the results.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/BetterPaws.png" alt="BetterPaws" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-betterpaws">BetterPaws</h3>
  <p class="project-description">
    Caring for a pet with a chronic condition shouldn't feel overwhelming. BetterPaws brings caregivers together with an AI-powered companion that turns everyday observations into meaningful health insights, simplifies veterinary visits, and makes better care a team effort.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Beyond-the-ETA-A-Reliability-Aware-Campus-Travel-Agent.png" alt="Beyond the ETA: A Reliability-Aware Campus Travel Agent" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-beyond-the-eta-a-reliability-aware-campus-travel-agent">Beyond the ETA: A Reliability-Aware Campus Travel Agent</h3>
  <p class="project-description">
    Bus schedules say when a bus should come. Beyond the ETA predicts when it actually will. Trained on a year of real MBTA arrivals, it gives Cambridge riders an arrival time with an honest 80% range, through a chat assistant that recommends routes and flags construction.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/CancerOut.jpg" alt="CancerOut" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-cancerout">CancerOut</h3>
  <p class="project-description">
    We developed an AI-powered tool that analyzes lung histopathology slides to detect potential cancer and classify its type. The system flags uncertain predictions and generates visual heatmaps to support pathologists in their review and clinical decision-making.
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
  <img src="../assets/projects/Claim-Ledger.png" alt="Claim Ledger" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-claim-ledger">Claim Ledger</h3>
  <p class="project-description">
    Claim Ledger extracts forward-looking claims from SEC filings and checks them against later disclosures. It estimates the odds that open claims will be fulfilled and compares each company's track record with its peers, with links to the evidence.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Crossed-Out-Not-Lost.jpg" alt="Crossed Out, Not Lost" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-crossed-out-not-lost">Crossed Out, Not Lost</h3>
  <p class="project-description">
    Crossed Out, Not Lost uses document AI to detect crossed-out text in PDFs and scanned documents, making deletions visible and preserving them in structured text output.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Cycleur.jpg" alt="Cycleur" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-cycleur">Cycleur</h3>
  <p class="project-description">
    Cycleur finds the best bike route for the views you want. Tell it “shady, by the water, past historic buildings,” and it scores every block from aerial imagery alone, predicting how each street feels to a rider, then plans the route that suits you best.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/DishMatcher.jpg" alt="DishMatcher" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-dishmatcher">DishMatcher</h3>
  <p class="project-description">
    Dish Match helps diners identify dishes by matching a food photo to a restaurant’s menu. Upload a dish photo and a menu photo, and the app reads the menu and suggests the most likely matches.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Docent.png" alt="Docent" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-docent">Docent</h3>
  <p class="project-description">
    Students waste hours rereading what they already know. Docent, a personal tutor for any course, tracks each student’s mastery all semester, spots the gaps, and points them to the exact slide or lecture moment, with practice problems grounded in how the class was taught.
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
  <img src="../assets/projects/EduTranscribe.jpg" alt="EduTranscribe" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-edutranscribe">EduTranscribe</h3>
  <p class="project-description">
    Little hands, big ideas, messy handwriting! EduTranscribe uses AI to turn young students’ handwritten stories into digital text, flagging tricky words for teacher review so students are assessed on their writing, not their handwriting. Let every idea shine!
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
  <img src="../assets/projects/FOMOsavior.png" alt="FOMOsavior" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-fomosavior">FOMOsavior</h3>
  <p class="project-description">
    FOMOsavior frees developers from the worry of missing what’s actually trending in open source. Ask in plain language, like “Which agentic RL projects are gaining momentum?”, and get a short answer from fresh GitHub and Hacker News data, with the numbers and sources.
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
  <img src="../assets/projects/HealthOps.png" alt="HealthOps" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-healthops">HealthOps</h3>
  <p class="project-description">
    HealthOps is a trust layer for multi-wearable users. It brings Apple Watch and Fitbit data into one store, reconciles disagreeing readings, and lets a verified LLM explain which device to trust and why.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Heimdall.png" alt="Heimdall" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-heimdall">Heimdall</h3>
  <p class="project-description">
    Heimdall delivers atmospheric intelligence for operations that rely on the weather, serving 3D cloud structure anywhere in the Western Hemisphere, now and an hour ahead. It gives pilots, solar operators, and search teams the time and information to act as conditions change.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/IslandFeature.jpg" alt="IslandFeature" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-islandfeature">IslandFeature</h3>
  <p class="project-description">
    IslandFeature is an AI-assisted feature engineering workbench that helps data scientists explore data, generate and review feature ideas, and evaluate candidate features on a development dataset.
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
  <img src="../assets/projects/RefundLens.jpg" alt="RefundLens" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-refundlens">RefundLens</h3>
  <p class="project-description">
    RefundLens helps online merchants detect AI-manipulated damage photos in refund claims. Combining computer vision and multimodal AI, it delivers cost-efficient fraud risk assessments and actionable recommendations to support smarter refund decisions.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Reminisce.jpg" alt="Reminisce" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-reminisce">Reminisce</h3>
  <p class="project-description">
    Reminisce helps people with early-onset Alzheimer's hold on to meaningful memories. It turns family photos and stories into a searchable and verified memory graph, then utilizes a recall prediction model to guide recall sessions that elongate the memory decline process.
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
  <img src="../assets/projects/ScriptCue.png" alt="ScriptCue" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-scriptcue">ScriptCue</h3>
  <p class="project-description">
    ScriptCue helps marketers and creators turn a campaign brief into a ready-to-shoot short-form video script, tailored to their audience, tone and engagement goal using real TikTok data.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/TasteBridge.png" alt="TasteBridge" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-tastebridge">TasteBridge</h3>
  <p class="project-description">
    TasteBridge helps two readers with different tastes agree on a book: each picks five favorites, and it recommends five "bridge books" with a reason for each reader, plus a "taste galaxy" map showing why their tastes overlap. Built on Goodreads data with full MLOps.
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
  <img src="../assets/projects/Undersigned.jpg" alt="Undersigned" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-undersigned">Undersigned</h3>
  <p class="project-description">
    Before a new federal regulation becomes law, the government has to answer the public, but nothing says the answer has to be easy to find. Undersigned finds it, mapping what people asked for, how the agency replied, and whose voices actually changed the law.
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

## Also presenting on December 14

<ul class="project-list">
{% raw %}
  <li>Accelerate the Accelerators</li>
  <li>AeroID Tool-Augmented Aircraft Identification: Making a Low-Cost LLM Expert-Accurate with ViT</li>
  <li>An AI Co-Agent and Knowledge Base for Sustainable Apparel Sourcing</li>
  <li>Bridgewatch API/SDK Migration and Dependency Repair</li>
  <li>Can Software Stop an LLM Agent From P-Hacking? Multi-Agent Orchestration with Enforced Process for Alpha Discovery</li>
  <li>F1 WhyLap: who's winning, and why, every lap</li>
  <li>Fixture: A Scheduling Assistant You Can Trust to Run on Its Own</li>
  <li>[G/M]aze tracking</li>
  <li>InspectBeforeBuy</li>
  <li>InterviewLens: A Multimodal AI Coach for Behavioral Interview Practice</li>
  <li>Knowing When to Trust the Merge: Confidence-Aware Reconciliation of Conflicting Company Records</li>
  <li>Paper2Baseline: From ML Papers to Tested Baselines with AI Agents</li>
  <li>SurveyScout: A Coverage-Tracked Literature-Review Harness</li>
  <li>VetChamp</li>
  <li>Waypoint: A Verified, Adaptive Course-and-Mentor Roadmap for Harvard Data Science Master's Students</li>
{% endraw %}
</ul>
