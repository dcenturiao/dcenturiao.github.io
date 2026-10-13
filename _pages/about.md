---
layout: about
title: About
permalink: /
subtitle:

profile:
  align: right
  image: daniel_centuriao.jpg
  image_circular: false
  address: >

news: false
latest_posts: false
selected_papers: false
social: true
---


<style>
/* Research sections */
.home-research {
  margin-top: 1.25rem;
}

.home-research-category {
  font-size: 1.2rem;
  font-weight: 500;
  margin-top: 1.8rem;
  margin-bottom: 1rem;
}

/* Individual papers - no separators */
.home-paper {
  margin-bottom: 1.6rem;
  padding: 0;
  border: none;
}

.home-paper-title {
  font-size: 1.02rem;
  font-weight: 600;
  line-height: 1.5;
  margin-bottom: 0.2rem;
}

.home-paper-authors {
  font-size: 0.92rem;
  line-height: 1.5;
  margin-bottom: 0.55rem;
}

.home-paper-status {
  color: var(--global-text-color-light, #777);
  font-style: italic;
}

/* Buttons on the same line */
.home-paper-actions {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 0.6rem;
}

.home-abstract {
  display: contents;
}

.home-abstract summary,
.home-paper-pdf {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 0.45rem;
  padding: 0.3rem 0.75rem;
  border: 1px solid var(--global-text-color, #555);
  border-radius: 3px;
  background: transparent;
  color: var(--global-text-color, #333);
  font-size: 0.8rem;
  font-weight: 500;
  line-height: 1.4;
  cursor: pointer;
  text-decoration: none !important;
  transition: all 0.2s ease;
}

.home-abstract summary {
  list-style: none;
}

.home-abstract summary::-webkit-details-marker {
  display: none;
}

.home-abstract summary::after {
  content: "▼";
  font-size: 0.6rem;
  margin-left: 0.2rem;
  transition: transform 0.2s ease;
}

.home-abstract[open] summary::after {
  transform: rotate(180deg);
}

.home-abstract summary:hover,
.home-paper-pdf:hover {
  color: var(--global-theme-color, #007bff);
  border-color: var(--global-theme-color, #007bff);
}

.home-abstract-text {
  flex-basis: 100%;
  width: 100%;
  padding: 0.8rem 0 0.3rem;
  font-size: 0.92rem;
  line-height: 1.7;
  text-align: justify;
}

/* Conference section */
.home-conferences {
  margin-top: 1rem;
}

.home-conference {
  padding: 0.5rem 0;
  font-size: 0.95rem;
  border-bottom: 1px solid var(--global-divider-color, #eee);
}

.home-conference:last-child {
  border-bottom: none;
}

.home-conference-year {
  float: right;
  color: var(--global-text-color-light, #777);
  font-size: 0.9rem;
}
</style>

<h2>Selected Working Papers</h2>

<div class="home-research">

  <h3 class="home-research-category">
    Regional, Urban, and Public Economics
  </h3>

  <!-- PAPER 1 -->
  <div class="home-paper">
    <div class="home-paper-title">
      When Is a Commute "Reverse"? Network Centrality and the Geography of Urban Labor Markets
    </div>
    <div class="home-paper-authors">
      With Eli Kochersperger.
      <span class="home-paper-status">Under review.</span>
    </div>
    <div class="home-paper-actions">
      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the reverse commuting paper here.]
        </div>
      </details>
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_commute.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>
    </div>
  </div>

  <!-- PAPER 2 -->
  <div class="home-paper">
    <div class="home-paper-title">
      Can Off-Farm Work Keep Farms Alive? Evidence from U.S. Counties
    </div>
    <div class="home-paper-authors">
      With Stephan Goetz and Zheng Tian.
      <span class="home-paper-status">Submitted.</span>
    </div>
    <div class="home-paper-actions">
      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the off-farm work paper here.]
        </div>
      </details>
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_off_farm.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>
    </div>
  </div>

  <!-- PAPER 3 -->
  <div class="home-paper">
    <div class="home-paper-title">
      The Effectiveness of Speed Enforcement Policies in Congested Cities
    </div>
    <div class="home-paper-authors">
      With Palak Suri.
      <span class="home-paper-status">Working paper.</span>
    </div>
    <div class="home-paper-actions">
      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the speed enforcement paper here.]
        </div>
      </details>
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_speed_enforcement.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>
    </div>
  </div>

  <!-- PAPER 4 -->
  <div class="home-paper">
    <div class="home-paper-title">
      Measuring the Outdoor Recreation Economy at the Sub-State Level
    </div>
    <div class="home-paper-authors">
      With Heather Stephens, Caroline Welter, and Matthew Fredriksson.
      <span class="home-paper-status">Working paper.</span>
    </div>
    <div class="home-paper-actions">
      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the outdoor recreation paper here.]
        </div>
      </details>
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_outdoor_recreation.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>
    </div>
  </div>

  <h3 class="home-research-category">
    Macroeconomics
  </h3>

  <!-- PAPER 5 -->
  <div class="home-paper">
    <div class="home-paper-title">
      Re-examining the Framework for Macro Modeling of Monetary Policy and Regional Housing
    </div>
    <div class="home-paper-authors">
      With Scott Schuh and Michael Duncan.
      <span class="home-paper-status">Under review.</span>
    </div>
    <div class="home-paper-actions">
      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the monetary policy and housing paper here.]
        </div>
      </details>
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_macro_housing.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>
    </div>
  </div>

  <!-- PAPER 6 -->
  <div class="home-paper">
    <div class="home-paper-title">
      Social Capital and Local Economic Recovery: Evidence from the COVID-19 Shock
    </div>
    <div class="home-paper-authors">
      With Stephan Goetz and Timothy Zuahng.
      <span class="home-paper-status">Work in progress.</span>
    </div>
    <div class="home-paper-actions">
      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the social capital paper here.]
        </div>
      </details>
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_social_capital.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>
    </div>
  </div>

</div>

---

## Upcoming Conferences

<div class="home-conferences">

  <div class="home-conference">
    <span class="home-conference-year">2026</span>
    <strong>Urban Economics Association (UEA)</strong>
    <div>Annual Conference</div>
  </div>

  <div class="home-conference">
    <span class="home-conference-year">2026</span>
    <strong>North American Regional Science Council (NARSC)</strong>
    <div>Annual Conference</div>
  </div>

  <div class="home-conference">
    <span class="home-conference-year">2026</span>
    <strong>Southern Economic Association (SEA)</strong>
    <div>Annual Conference</div>
  </div>

  <div class="home-conference">
    <span class="home-conference-year">2027</span>
    <strong>Allied Social Science Associations (ASSA)</strong>
    <div>Annual Meeting</div>
  </div>

</div>

<br>

---