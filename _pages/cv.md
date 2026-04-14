layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 3
cv_pdf: /assets/pdf/ElaheHosseini_Resume_Spring2026.pdf # you can also use external links here
description: Curriculum vitae

---

<p>
  <a href="{{ page.cv_pdf | relative_url }}" target="_blank" rel="noopener noreferrer">Download CV (PDF)</a>
</p>

<iframe
  src="{{ page.cv_pdf | relative_url }}"
  width="100%"
  height="1200"
  style="border: 1px solid #ddd; border-radius: 8px;"
  title="Elahe Hosseini CV"
></iframe>
