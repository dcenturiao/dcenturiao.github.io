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

<br>

**Hi, welcome to my website!** 👋

<br>

I am a Postdoctoral Scholar at the [Northeast Regional Center for Rural Development](https://nercrd.psu.edu/) at Penn State University. I earned my Ph.D. in Economics from West Virginia University in 2026.

I am an applied economist whose research lies at the intersection of regional and urban economics, public economics, and macroeconomics. My work combines applied econometrics, spatial analysis, and economic modeling to study economic growth and development, public policy, transportation, and the spatial dimensions of economic activity. My research often draws on large geospatial datasets and causal inference methods.

Before pursuing my doctoral studies, I gained professional experience in both the private and public sectors.

📩 **Contact:** [dfc5823@psu.edu](mailto:dfc5823@psu.edu)

<br>

---

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
          Reverse commuting has a familiar monocentric meaning: travel from a central res-
          idential area toward suburban employment. Yet an origin–destination matrix does
          not identify a commute as reverse without first specifying the metropolitan hierarchy
          relative to which its direction is judged. We develop a network-based measure that
          uses the stationary structure of the full tract-to-tract commuting system to identify
          counter-directional flows. Under a conventional near-monocentric configuration with
          predominantly inward commuting, the measure recovers the familiar classification of
          outward trips as reverse. In polycentric systems, the same rule remains operational
          without requiring a unique CBD or a predetermined core–periphery boundary. Applying 
          the method to U.S. Census LODES data, we show that network, distance-based,
          and local inflow–outflow classifications imply substantially different levels and geographies 
          of reverse commuting across metropolitan areas. These differences demonstrate
          that empirical conclusions about commute direction depend materially on the urban
          hierarchy embedded in the measurement rule.
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
      Does Off-Farm Work Help Farms Survive? Evidence from U.S. Counties
    </div>
    <div class="home-paper-authors">
      With Zheng Tian and Stephan Goetz.
      <span class="home-paper-status">Submitted.</span>
    </div>
    <div class="home-paper-actions">
      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          Using county-level Census of Agriculture panels from 2002 to 2022, this paper studies
          whether off-farm work stabilizes U.S. farm counts or accelerates the net loss of farms.
          We estimate county and Census-year fixed-effects models and instrument off-farm work
          with predicted private-sector labor demand accessible through commuting links. The IV
          results support a channel in which off-farm work stabilizes farm numbers. In the preferred
          specification, a one percentage-point increase in instrumented off-farm work raises five-
          year log farm-count change by 0.052 log points, equivalent to an implied 5.3 percent
          increase in farm counts over the Census interval and lowers the net loss of farm by 15.5
          percentage points. The estimates imply that off-farm employment induced by commuting-
          linked labor-market access helps farms persist rather than facilitating exit. Policies that
          expand off-farm job access may therefore complement agricultural policy by supporting
          farm household viability.
        </div>
      </details>
      <a class="home-paper-pdf"
         href="https://dcenturiao.github.io/research-papers/off-farm-work/paper.pdf"
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
          We examine the effects of New York City’s Vision Zero program, which expanded
          the use of traffic calming and enforcement measures across the city. Combining
          geocoded policy locations with street-level collision data, we use spatial difference-
          in-differences to estimate local and spillover effects of automated speed enforcement
          cameras, speed humps, and Slow Neighborhood Zones. We find limited evidence
          of broad safety improvements within treated areas. The clearest effect is an increase
          in collisions on street segments surrounding automated speed enforcement cameras,
          while speed humps show no robust effects and Slow Neighborhood Zones exhibit
          suggestive increases in injuries just outside zone boundaries. These findings highlight
          the importance of accounting for spatial spillovers when evaluating urban traffic-safety
          policies.
        </div>
      </details>
      <!-- DRAFT PDF BUTTON - Uncomment when ready
    <a class="home-paper-pdf"
       href="{{ '/assets/pdf/paper_speed_enforcement.pdf' | relative_url }}"
       target="_blank" rel="noopener noreferrer">
      <i class="far fa-file-pdf"></i> Draft PDF
    </a>
    -->

    <!-- TEMPORARY TEXT - Comment out when draft is ready -->
    <span class="home-paper-status">Draft Coming Soon</span>
    </div>
  </div>

  <h3 class="home-research-category">
    Macroeconomics
  </h3>

  <!-- PAPER 4 -->
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
          This paper re-examines the aggregate modeling framework that captures both national
          markets (monetary and financial) and heterogeneous regional housing markets by re-
          specifying the macro-housing VAR in the HAVAR model of Fratantoni and Schuh
          (2003). Both the original (levels) and revised (rates) specifications of the 6-variable
          model affirm that housing remains more cyclically and interest sensitive than non-
          housing activity and capture the major developments in monetary policy and housing
          that altered timing and transmission since 1998. However, the rates specification is
          preferable on several dimensions and is consistent with an SVAR specification of a New
          Keynesian model with two heterogeneous sectors. An expanded macro VAR model that
          adds a financial variable and two more housing variables also fits the data well, thereby
          providing a solid foundation for an updated, revised, and expanded HAVAR model in
          future research.
        </div>
      </details>
      <a class="home-paper-pdf"
         href="https://dcenturiao.github.io/research-papers/macro-housing/paper.pdf"
         target="_blank" rel="noopener noreferrer">
        <i class="far fa-file-pdf"></i> Draft PDF
      </a>
    </div>
  </div>

  <!-- PAPER 5 -->
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
          Official outdoor recreation accounts are rarely available at the local scale, although
          land, infrastructure, and development decisions are often local. We develop a portable
          accounting method that recovers local outdoor recreation GDP, employment, and labor
          income from standard regional production accounts plus an explicit activity classification. 
          Relative to full satellite-account construction, the method requires fewer data
          inputs and fewer unobserved allocation assumptions. Applied to West Virginia, the
          estimates are of the same order as the official state benchmark and reveal large county
          differences. The same accounting structure can be transferred to other countries or
          regions with sufficiently disaggregated regional accounts.
        </div>
      </details>
      <a class="home-paper-pdf"
         href="{{ '/assets/pdf/paper_outdoor_recreation.pdf' | relative_url }}"
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
      With Timothy Zuahng and Caroline Welter.
      <span class="home-paper-status">Work in progress.</span>
    </div>
    <div class="home-paper-actions">
      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          We study whether pre-existing social capital shapes local labor-market adjustment to
          the COVID-19 shock. We combine a pre-pandemic county social-capital index with a
          shift-share measure of COVID-19 exposure based on pre-pandemic industry structure
          and national industry employment declines. We find little evidence that social capital
          cushioned the initial employment shock. Instead, for a one-standard-deviation adverse
          shock, one standard deviation higher social capital improves the relative employment
          response by about 0.39 percent between impact and 2022–2023. Business dynamics
          point to lower job destruction, greater retention at continuing establishments, and less
          reallocation rather than stronger job creation at new establishments. Social capital
          appears to operate more as adaptive capacity than shock insulation.
        </div>
      </details>
      <!-- DRAFT PDF BUTTON - Uncomment when ready
    <a class="home-paper-pdf"
       href="{{ '/assets/pdf/paper_speed_enforcement.pdf' | relative_url }}"
       target="_blank" rel="noopener noreferrer">
      <i class="far fa-file-pdf"></i> Draft PDF
    </a>
    -->

    <!-- TEMPORARY TEXT - Comment out when draft is ready -->
    <span class="home-paper-status">Draft Coming Soon</span>
    </div>
  </div>

  <!-- PAPER 7 -->
  <div class="home-paper">
    <div class="home-paper-title">
      On the government growth: a partial equilibrium macroeconomic growth model to explain cross-country government expenditure
    </div>
    <div class="home-paper-authors">
      With Vinicius Cicero.
      <span class="home-paper-status">Work in progress.</span>
    </div>
    <div class="home-paper-actions">
      <details class="home-abstract">
        <summary>Abstract</summary>
        <div class="home-abstract-text">
          Government expenditure has risen substantially over the past two centuries, but its
          long-run level and trajectory differ markedly across countries. This paper develops
          a dynamic political-economy model in which fiscal capacity is an accumulated state
          variable and current expenditure competes with investment in the government’s
          future ability to mobilize revenue. Institutional quality affects this tradeoff through
          two channels: it raises the productivity of fiscal-capacity investment, but it also
          strengthens the political discipline applied to expenditure choices that depart from
          fiscally sustainable benchmark. The model characterizes the interior expenditure
          policy, the steady-state equilibrium, and the locally stable transition path. It shows
          that stronger institutions unambiguously raise the expenditure level consistent with
          maintaining fiscal capacity, while their effect on equilibrium government size is
          generally ambiguous because the fiscal-capacity and political-discipline channels need
          not operate in the same direction. Initial fiscal capacity affects transition paths when
          the policy rule along the stable arm is monotone, and the model provides explicit
          conditions under which fiscal-capacity erosion produces a decline in government
          expenditure.
        </div>
      </details>
      <!-- DRAFT PDF BUTTON - Uncomment when ready
    <a class="home-paper-pdf"
       href="{{ '/assets/pdf/paper_speed_enforcement.pdf' | relative_url }}"
       target="_blank" rel="noopener noreferrer">
      <i class="far fa-file-pdf"></i> Draft PDF
    </a>
    -->

    <!-- TEMPORARY TEXT - Comment out when draft is ready -->
    <span class="home-paper-status">Draft Coming Soon</span>
    </div>
  </div>

</div>

---

<style>
/* Conference section: clean layout, no separators */
.home-conferences {
  margin-top: 1.2rem;
}

.home-conference {
  margin-bottom: 1.5rem;
  padding: 0;
  border: none !important;
}

.home-conference-name {
  font-size: 1.02rem;
  font-weight: 600;
  margin-bottom: 0.15rem;
}

.home-conference-date {
  font-size: 0.92rem;
  color: var(--global-text-color-light, #777);
  margin-bottom: 0.3rem;
}

.home-conference-paper {
  font-size: 0.95rem;
  line-height: 1.5;
}

.home-conference-authors {
  font-size: 0.9rem;
  margin-top: 0.1rem;
}
</style>

<h2>Conference Presentations (2026–2027)</h2>

<div class="home-conferences">

  <!-- URBAN ECONOMICS ASSOCIATION -->
  <div class="home-conference">
    <div class="home-conference-name">
      <a href="https://urbaneconomics.org/meetings/uea2026/program.html"
         target="_blank" rel="noopener noreferrer">
        Urban Economics Association (UEA)
      </a>
    </div>
    <div class="home-conference-date">
      September 25–26, 2026 | Chicago, IL
    </div>
    <div class="home-conference-paper">
      <em>The Effectiveness of Speed Enforcement Policies in Congested Cities</em>
    </div>
    <div class="home-conference-authors">
      With Palak Suri
    </div>
  </div>

  <!-- NARSC -->
  <div class="home-conference">
    <div class="home-conference-name">
      <a href="https://narsc.mymeetingsavvy.net/program"
         target="_blank" rel="noopener noreferrer">
        North American Regional Science Council (NARSC)
      </a>
    </div>
    <div class="home-conference-date">
      November 11–14, 2026 | Philadelphia, PA
    </div>
    <div class="home-conference-paper">
      <em>Can Off-Farm Work Keep Farms Alive? Evidence from U.S. Counties</em>
    </div>
    <div class="home-conference-authors">
      With Stephan Goetz and Zheng Tian
    </div>
  </div>

  <!-- SOUTHERN ECONOMIC ASSOCIATION -->
  <div class="home-conference">
    <div class="home-conference-name">
      <a href="https://sea.mymeetingsavvy.net/program"
         target="_blank" rel="noopener noreferrer">
        Southern Economic Association (SEA)
      </a>
    </div>
    <div class="home-conference-date">
      November 21–23, 2026 | Houston, TX
    </div>
    <div class="home-conference-paper">
      <em>On Government Growth: A Partial Equilibrium Macroeconomic
      Growth Model to Explain Cross-Country Government Expenditure</em>
    </div>
  </div>

  <!-- ASSA -->
  <div class="home-conference">
    <div class="home-conference-name">
      <a href="https://www.aeaweb.org/conference/2027/preliminary"
         target="_blank" rel="noopener noreferrer">
        Allied Social Science Associations (ASSA)
      </a>
    </div>
    <div class="home-conference-date">
      January 3–5, 2027 | Washington, DC
    </div>
    <div class="home-conference-paper">
      <em>Measuring the Outdoor Recreation Economy at the Sub-State Level</em>
    </div>
    <div class="home-conference-authors">
      With Heather Stephens, Caroline Welter, and Matthew Fredriksson
    </div>
  </div>

</div>


---
