---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% raw %}
<style>
/* ======= GLOBAL STYLING ======= */

h2 {
  margin-top: 40px;
  border-bottom: 2px solid #ddd;
  padding-bottom: 4px;
  color: #222;
  font-size: 1.4em;
  font-weight: 600;
}

/* ======= ENTRY SPACING ======= */

.pub-entry, .wp-entry {
  margin-bottom: 20px;
  line-height: 1.55;
}

/* ======= TITLE & LINKS ======= */

.pub-entry a strong,
.wp-entry a strong {
  color: #1a73e8;
  font-size: 1.05em;
  text-decoration: none;
  transition: color 0.2s ease;
  quotes: "“" "”";
}

.pub-entry a strong::before,
.wp-entry a strong::before {
  content: open-quote;
}

.pub-entry a strong::after,
.wp-entry a strong::after {
  content: close-quote;
}

.pub-entry a strong:hover,
.wp-entry a strong:hover {
  color: #1257b0;
  text-decoration: underline;
}

/* ======= COAUTHORS & JOURNAL ======= */

.coauthors {
  margin-top: 4px;
  color: #444;
  font-size: 0.95rem;
}

.journal {
  margin-top: 2px;
  font-style: italic;
  color: #333;
}

/* ======= LINKS ======= */

.pub-links,
.pub-links a {
  color: #1a73e8;
  text-decoration: none;
  font-weight: 500;
  font-size: 0.95rem;
}

.pub-links a:hover {
  text-decoration: underline;
  color: #1257b0;
}

/* ======= BUTTON ======= */

.toggle-button {
  display: inline-block;
  margin-left: 6px;
  background: #f8f8f8;
  border: 1px solid #b0c4de;
  border-radius: 4px;
  color: #1a73e8;
  cursor: pointer;
  font-size: 0.85em;
  padding: 2px 6px;
}

.toggle-button:hover {
  background: #e8f0ff;
  border-color: #1a73e8;
}

/* ======= ABSTRACTS ======= */

.abstract {
  display: none;
  margin-top: 6px;
  color: #333;
  line-height: 1.55;
  max-width: 800px;
}

/* ======= LISTS ======= */

ul.dash-list {
  list-style: none;
  padding-left: 0;
  margin-left: 10px;
  line-height: 1.6;
  color: #000;
}

ul.dash-list li::before {
  content: "– ";
  color: #555;
}

section {
  margin-bottom: 45px;
}
</style>
{% endraw %}

<!-- ===================== -->
<!-- 💅 Compact Layout Tweaks -->
<!-- ===================== -->
<style>
/* Slightly tighter spacing between entries */
.pub-entry, .wp-entry {
  margin-bottom: 14px;
}

/* Spacing for inline buttons and links */
.coauthors .toggle-button,
.journal .toggle-button {
  margin-left: 8px;
}

.coauthors .pub-links,
.journal .pub-links {
  margin-left: 8px;
}

/* Ensure Ungated links are not italicized */
.pub-links {
  font-style: normal !important;
}
</style>

<!-- ===================== -->
<!--     PUBLICATIONS      -->
<!-- ===================== -->

<section>
<h2>Publications</h2>

<div class="pub-entry">
  <a href="https://www.aeaweb.org/articles?id=10.1257/pol.20230640" target="_blank">
    <strong>Disrupting Drug Markets: The Effects of Crackdowns on Rogue Opioid Suppliers</strong>
  </a>
  <div class="journal">
    <em>American Economic Journal: Economic Policy</em>, 2025
    <button class="toggle-button" onclick="toggleText('abstractdocs', this)">Show Abstract</button>
    <span class="pub-links">
      [<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4266020" target="_blank">Ungated Version</a>]
      [<a href="https://www.aeaweb.org/research/drug-markets-supplier-crackdowns" target="_blank">AEA Research Highlight</a>]
    </span>
  </div>
  <div id="abstractdocs" class="abstract">
    This paper estimates the impacts of doctor crackdowns on the quantity demanded of prescription opioids, across-market substitution, and across-product substitution. Exploiting plausibly exogenous variation in the timing and location of administrative actions, I find that cracking down on a single doctor decreases county-level opioid dispensing by 10%. This decline persists across space and grows over time. Additionally, significant heroin substitution occurs, yet overall overdose mortality decreases. These results highlight a critical tradeoff policymakers should consider with targeted crackdowns: reductions in the flow of new users must be balanced against the harm that arises when existing users substitute to more dangerous drugs.
  </div>
</div>


<div class="pub-entry">
  <a href="https://www.journals.uchicago.edu/doi/10.1086/721292" target="_blank">
    <strong>Crime and (a Preference for) Punishment: The Effects of Drug Policy Reform on Policing Activity</strong>
  </a>
  <div class="journal">
    <em>The Journal of Law and Economics</em>, 2022
    <button class="toggle-button" onclick="toggleText('abstractdfsz', this)">Show Abstract</button>
    <span class="pub-links">
      [<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3795758" target="_blank">Ungated Version</a>]
    </span>
  </div>
  <div id="abstractdfsz" class="abstract">
    Using geocoded crime data and a novel source of within-city variation in punishment severity, I find that in parts of a city where drug sale penalties were weakened, there is a 13% decrease in all drug arrests. There is no displacement of non-drug offenses. My results are consistent with police treating enforcement effort and punishment severity as complements. City-wide crime and drug use do not increase after the reform, suggesting that certain enforcement can be reduced without large public safety costs.
  </div>
</div>

<div class="pub-entry">
  <a href="https://www.sciencedirect.com/science/article/pii/S092180092200091X?dgcid=author" target="_blank">
    <strong>Prescriptive Drought Policy and Water Supplier Compliance</strong>
  </a>
  <div class="journal">
    <em>Ecological Economics</em>, 2022
    <button class="toggle-button" onclick="toggleText('abstractwater', this)">Show Abstract</button>
  </div>
  <div id="abstractwater" class="abstract">
    Governments often cannot use prices to induce water conservation, and the need to understand the impacts of alternate methods is growing due to increased variability in water resources. During the 2012–2016 drought in California, the state attempted to manage water use through a set of mandatory restrictions that assigned each of California's 412 largest urban water suppliers to one of nine conservation tiers. I find that even though significant statewide savings occurred, only half of all suppliers complied with their conservation target. Moreover, the increased savings were not caused by the tiered design of the mandate: suppliers that just missed a stricter conservation tier actually conserved more. Water use rebounded after the regulation was removed, implying that variable adjustments in demand contributed more to water use savings than fixed-cost investments.
  </div>
</div>

</section>

<!-- ===================== -->
<!--     WORKING PAPERS    -->
<!-- ===================== -->

<section>
<h2>Working Papers</h2>

<div class="wp-entry">
  <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5169572" target="_blank">
    <strong>Better Stealing than Dealing: How do Felony Theft Thresholds Impact Crime?</strong>
  </a>
  <div class="coauthors">
    with Steve Billings, Mike Makowsky, and Kevin Schnepel
    <button class="toggle-button" onclick="toggleText('abstracttheft', this)">Show Abstract</button>
  </div>
  <div id="abstracttheft" class="abstract">
    From 2005 to 2019, forty US states increased the dollar value threshold delineating misdemeanor and felony theft, reducing the expected punishment for a subset of property crimes. Using an event study framework, we observe significant and growing increases in theft after a state reform is passed. We then show that reduced sanctions for theft have broader effects in the market for illegal activity. Consistent with a mechanism of substitution across income-generating crimes, we find decreases in both drug distribution crimes and the probability that a released offender previously convicted of drug distribution is reincarcerated for a new drug conviction.
  </div>
</div>

<div class="wp-entry">
  <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6221120" target="_blank">
    <strong>Cocaine Goes Bananas: Global Spillovers from an Illicit Supply Shock</strong>
  </a>
  <div class="coauthors">
    with Gianmarco Daniele and Juan Vargas
    <button class="toggle-button" onclick="toggleText('abstractcocaine', this)">Show Abstract</button>
  </div>
  <div id="abstractcocaine" class="abstract">
We study how a sharp expansion in Colombian cocaine production propagated internationally through global trade networks, generating substantial social costs. In Colombia, the production surge increased homicide rates by 41% in port areas and by 26% in cocaine-producing municipalities. Violence then spilled across the border into Ecuador, a transit hub with negligible cocaine production but dense maritime trade links, contributing to a nearly five-fold increase in homicide rates. The shock traveled through criminal supply chains that exploit legitimate perishable export routes, notably bananas, concentrating activity at maritime chokepoints. In Europe, countries with stronger pre-shock trade ties to Colombia and Ecuador experienced sharp increases in cocaine seizures linked to these origins, lower retail prices, a 60% rise in cocaine consumption in port cities, and 5% higher violent crime in port provinces. Together, these results show that shocks in illicit markets propagate internationally through the same trade networks as legal trade shocks, concentrating violence at contested logistical bottlenecks and expanding downstream drug markets.
  </div>
</div>

<div class="wp-entry">
  <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5114929" target="_blank">
    <strong>Illicit Drug Supply Shocks and Overdose Mortality</strong>
  </a>
  <div class="coauthors">
    with Travis Donahoe
    <button class="toggle-button" onclick="toggleText('abstracttakeover', this)">Show Abstract</button>
  </div>
  <span style="display:block; margin-top:2px; font-size:90%; color:#555;">
    Previously circulated as “What Fueled the Illicit Opioid Epidemic?”
  </span>
  <div id="abstracttakeover" class="abstract">
We study the effects of supply-side changes in illicit drug purity and composition on overdose mortality in the United States. Beginning around 2012, white powder heroin markets experienced sharp increases in purity variability and adulteration with highly potent fentanyl, while black tar heroin markets did not. Exploiting a pre-existing geographic divide between heroin market types, we find that exposure to these shocks increased overdose death rates by 53 percent through 2019, implying roughly 105,000 excess deaths. These effects persist as fentanyl replaced heroin as the dominant opioid involved in overdoses. The findings also revise interpretations of the early-2010s acceleration in heroin mortality rates, shifting emphasis away from demand-side substitution following legal opioid restrictions and toward shocks to heroin supply. More broadly, the results show that in unregulated drug markets, unobservable changes in purity and composition can sharply increase fatality risk, generating rapid escalation in overdose mortality even when demand evolves gradually. 
  </div>
</div>


<div class="wp-entry">
  <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4649479" target="_blank">
    <strong>The Social Spillovers of Homeownership: Evidence from Institutional Investors</strong>
  </a>
  <div class="coauthors">
    with Steve Billings
    <button class="toggle-button" onclick="toggleText('abstracthomes', this)">Show Abstract</button>
  </div>
  <div id="abstracthomes" class="abstract">
    We provide novel evidence on the social spillovers of homeownership by exploiting the recent rise of institutional investors purchasing single-family homes and converting them into permanent rentals. Using a granular difference-in-differences design based on proximity to each investor-purchased property, we find that neighboring property values decline by 1% relative to those slightly farther away. This decline grows over time yet decays across space, and these same properties experience increases in crime and decreases in property maintenance and voter registration. Supplemental analysis suggests these externalities arise from both landlord practices and tenant composition.
  </div>
</div>

</section>

<!-- ===================== -->
<!--  WORK IN PROGRESS     -->
<!-- ===================== -->

<section>
<h2>Selected Work in Progress</h2>
<ul class="dash-list">
  <li><strong>Methadone treatment, overdoses, and crime</strong> (with Travis Donahoe and Analisa Packham)</li>
  <li><strong>Policing behavior and crime</strong> (with Mike Makowsky, Matt Ross, and CarlyWill Sloan)</li>
  <li><strong>Prosecutorial discretion</strong> (with Spencer Cooper)</li>
  <li><strong>The effects of ShotSpotter on shooting fatality rates</strong> (with Terence Chau, Phil Cook, and Jens Ludwig)</li>
</ul>
</section>

<!-- ===================== -->
<!--    OTHER WRITING      -->
<!-- ===================== -->

<section>
<h2>Other Writing</h2>
<ul class="dash-list">
  <li><a href="https://www.niskanencenter.org/americas-overdose-blindspot/" target="_blank">America’s Overdose Blindspot</a>, Niskanen Center, April 2025</li>
  <li><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4808698" target="_blank">Evaluation of Durham's ShotSpotter Installation: Results of a 12-Month Pilot Project</a> (with Phil Cook), Wilson Center for Science and Justice at Duke Law, February 2024</li>
  <li><a href="https://blogs.lse.ac.uk/usappblog/2023/12/18/corporate-landlords-are-eroding-the-american-dream-of-homeownership-especially-in-black-neighborhoods/" target="_blank">Corporate landlords are eroding the American Dream of homeownership</a>, London School of Economics, Phelan US Centre, December 2023</li>
</ul>
</section>

<script>
function toggleText(sectionId, button) {
  const section = document.getElementById(sectionId);
  if (section.style.display === "none" || section.style.display === "") {
    section.style.display = "block";
    button.textContent = "Hide Abstract";
  } else {
    section.style.display = "none";
    button.textContent = "Show Abstract";
  }
}
</script>
