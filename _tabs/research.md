---
layout: page
title: Research
icon: fas fa-stream
order: 2
permalink: /research/
---

<!-- Load the custom stylesheet for this page only -->
<link rel="stylesheet" href="/assets/css/research.css">

<!-- JS for the abstract toggle (place once per page) -->
<script>
function toggleAbstract(btn) {
  const body = document.getElementById(btn.getAttribute('aria-controls'));
  const isOpen = body.classList.toggle('open');
  btn.classList.toggle('open', isOpen);
  btn.setAttribute('aria-expanded', isOpen);
}
</script>

# Publications

# Working paper
{% include paper.html
  title    = "Education, Experience, and Minimum Wage Policy: Reassessing Wage Returns in the UK Labour Market"
  authors  = "Supervised by Prof. Matthias Parey"
  venue    = "University of Surrey's MSc Economics dissertation"
  year     = "2025"
  tags     = "Labour economics, Microeconomics, Return on education"
  pdf      = "https://arxiv.org/abs/0000.00001"
  slides   = "https://example.com/bioner-slides.pdf"
  abstract = "
  This study examines the financial returns to education versus early labour-market entry in the UK, using the Longitudinal Education Outcomes dataset to directly compare wage gains from completed credentials with those from work experience. By analysing returns across gender, field of study, and university group, the research evaluates postgraduate study as an investment choice and identifies disparities in outcomes across different education pathways, providing evidence to support more informed career and education decisions in a context of rising costs and graduate oversupply.
  </p><p>
  The project also investigates how shifts in the UK National Living Wage influence these returns, exploring whether higher minimum wages compress wage differentials and reduce education premiums or alternatively strengthen the value of qualifications through increased labour-market competition. By examining these mechanisms in the post-COVID-19 landscape, the research aims to inform evidence-based policymaking on education, skills, and wage regulation to promote inclusive economic growth.
  "
%}