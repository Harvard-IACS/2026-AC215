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
  <img src="../assets/projects/CareerGraph.png" alt="CareerGraph" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-careergraph">CareerGraph</h3>
  <p class="project-description">
    CareerGraph helps early-career candidates understand how well their resumes match real data and machine learning job openings. It checks each requirement against the resume and suggests whether to apply, reframe experience, or build missing skills.
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
  <img src="../assets/projects/PolyHistor.jpg" alt="PolyHistor" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-polyhistor">PolyHistor</h3>
  <p class="project-description">
    PolyHistor is a web app that lets users explore 2D art across a rich shared embedding space. A text or image prompt produces a small “exhibit” of paintings from more than 104,000 artworks, with an interactive map of their thematic relationships.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/VantageX.png" alt="VantageX" class="project-image" loading="lazy">
  <h3 class="project-title" id="project-vantagex">VantageX</h3>
  <p class="project-description">
    VantageX helps AI researchers write social posts that resonate with their community. It retrieves similar peer posts from Bluesky, drafts with Claude, and surfaces which emerging AI names are likely to keep gaining attention.
  </p>
</div>

{% endraw %}
</div>
