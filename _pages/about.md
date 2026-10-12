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
/* Selected research section */
.home-research {
  margin-top: 1.5rem;
}

.home-paper {
  padding: 1.3rem 0;
  border-bottom: 1px solid var(--global-divider-color, #ddd);
}

.home-paper:last-child {
  border-bottom: none;
}

.home-paper-title {
  font-size: 1.05rem;
  font-weight: 600;
  line-height: 1.5;
  margin-bottom: 0.25rem;
}

.home-paper-authors {
  font-size: 0.95rem;
  margin-bottom: 0.15rem;
}

.home-paper-status {
  font-size: 0.9rem;
  color: var(--global-text-color-light, #777);
  font-style: italic;
  margin-bottom: 0.65rem;
}

.home-paper-actions {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.65rem;
}

.home-abstract {
  width: 100%;
}

.home-abstract summary {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  border: 1px solid var(--global-text-color, #555);
  border-radius: 3px;
  padding: 0.35rem 0.85rem;
  cursor: pointer;
  font-size: 0.82rem;
  font-weight: 500;
  user-select: none;
  list-style: none;
}

.home-abstract summary::-webkit-details-marker {
  display: none;
}

.home-abstract summary::after {
  content: "▼";
  font-size: 0.65rem;
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
  font-size: 0.92rem;
  line-height: 1.7;
  padding: 0.9rem 0.2rem 0.3rem;
  text-align: justify;
}

.home-paper-pdf {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  border: 1px solid var(--global-text-color, #555);
  border-radius: 3px;
  padding: 0.35rem 0.85rem;
  color: var(--global-text-color, #333);
  text-decoration: none !important;
  font-size: 0.82rem;
  font-weight: 500;
  transition: all 0.2s ease;
}

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

<br>

**Hi, welcome to my website!** 👋

<br>

I am a Postdoctoral Scholar at the [Northeast Regional Center for Rural Development](https://nercrd.psu.edu/) at Penn State University. I earned my Ph.D. in Economics from West Virginia University in 2026.

I am an applied economist whose research lies at the intersection of regional and urban economics, public economics, and macroeconomics. My work combines applied econometrics, spatial analysis, and economic modeling to study economic growth and development, public policy, transportation, and the spatial dimensions of economic activity. My research often draws on large geospatial datasets and causal inference methods.

Before pursuing my doctoral studies, I gained professional experience in both the private and public sectors.

📩 **Contact:** [dfc5823@psu.edu](mailto:dfc5823@psu.edu)

<br>

---

## Selected Working Papers

<div class="home-research">

  <!-- PAPER 1 -->
  <div class="home-paper">
    <div class="home-paper-title">
      When Is a Commute "Reverse"? Network Centrality and the Geography of Urban Labor Markets
    </div>
    <div class="home-paper-authors">
      With Eli Kochersperger
    </div>
    <div class="home-paper-status">
      Under review, Urban Studies
    </div>

    <div class="home-paper-actions">
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_commute.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>

      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the reverse commuting paper here.]
        </div>
      </details>
    </div>
  </div>

  <!-- PAPER 2 -->
  <div class="home-paper">
    <div class="home-paper-title">
      Re-examining the Framework for Macro Modeling of Monetary Policy and Regional Housing
    </div>
    <div class="home-paper-authors">
      With Scott Schuh and Michael Duncan
    </div>
    <div class="home-paper-status">
      Under review, Journal of Money, Credit and Banking
    </div>

    <div class="home-paper-actions">
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_macro_housing.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>

      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the monetary policy and regional housing paper here.]
        </div>
      </details>
    </div>
  </div>

  <!-- PAPER 3 -->
  <div class="home-paper">
    <div class="home-paper-title">
      Federal Research Grants and Regional Economic Impact: Evidence from West Virginia University
    </div>
    <div class="home-paper-authors">
      With Heather Stephens
    </div>
    <div class="home-paper-status">
      Under review, Journal of Regional Analysis and Policy
    </div>

    <div class="home-paper-actions">
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_research_grants.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>

      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the federal research grants paper here.]
        </div>
      </details>
    </div>
  </div>

  <!-- PAPER 4 -->
  <div class="home-paper">
    <div class="home-paper-title">
      Can Off-Farm Work Keep Farms Alive? Evidence from U.S. Counties
    </div>
    <div class="home-paper-authors">
      With Stephan Goetz and Zheng Tian
    </div>
    <div class="home-paper-status">
      Submitted to American Journal of Agricultural Economics
    </div>

    <div class="home-paper-actions">
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_off_farm.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>

      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the off-farm employment paper here.]
        </div>
      </details>
    </div>
  </div>

  <!-- PAPER 5 -->
  <div class="home-paper">
    <div class="home-paper-title">
      The Effectiveness of Speed Enforcement Policies in Congested Cities
    </div>
    <div class="home-paper-authors">
      With Palak Suri
    </div>
    <div class="home-paper-status">
      Selected for presentation at the Urban Economics Association Conference
    </div>

    <div class="home-paper-actions">
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_speed_enforcement.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>

      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the speed enforcement paper here.]
        </div>
      </details>
    </div>
  </div>

  <!-- PAPER 6 -->
  <div class="home-paper">
    <div class="home-paper-title">
      Measuring the Outdoor Recreation Economy at the Sub-State Level
    </div>
    <div class="home-paper-authors">
      With Heather Stephens, Caroline Welter, and Matthew Fredriksson
    </div>
    <div class="home-paper-status">
      Selected for presentation at the 2027 ASSA Annual Meeting
    </div>

    <div class="home-paper-actions">
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_outdoor_recreation.pdf' | relative_url }}"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>

      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          [Insert abstract for the outdoor recreation paper here.]
        </div>
      </details>
    </div>
  </div>

</div>

<br>

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