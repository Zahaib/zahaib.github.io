---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
For detailed CV, please get in touch via [LinkedIn](https://www.linkedin.com/in/zahaibakhtar/).

Education
======
* Ph.D in Computer Science, University of Southern California, 2019
* M.S. in Computer Science, University of Southern California, 2017
* M.S. in Computer Engineering, Lahore University of Management Sciences, 2012
* B.S. in Computer Engineering, Lahore University of Management Sciences, 2009

<br>

Work experience
======
<div>
  <div class="custom-counter" id="counter">Loading...</div>

  <script>
    (function () {
      const counterElement = document.getElementById("counter");

      // Start date: September 3rd, 2019
      const startDate = new Date(2019, 8, 3); // Month is 0-indexed (8 = September)

      function calculateElapsedTime() {
        const now = new Date();
        const years = now.getFullYear() - startDate.getFullYear();
        const months = now.getMonth() - startDate.getMonth();
        const days = now.getDate() - startDate.getDate();

        let adjustedYears = years;
        let adjustedMonths = months;
        let adjustedDays = days;

        if (adjustedDays < 0) {
          adjustedMonths -= 1;
          const previousMonth = new Date(now.getFullYear(), now.getMonth(), 0);
          adjustedDays += previousMonth.getDate();
        }

        if (adjustedMonths < 0) {
          adjustedYears -= 1;
          adjustedMonths += 12;
        }

        return `Duration: ${adjustedYears} years, ${adjustedMonths} months`;
      }

      function updateCounter() {
        counterElement.textContent = calculateElapsedTime();
      }

      // Update the counter every day (in case the page is left open)
      setInterval(updateCounter, 24 * 60 * 60 * 1000); // Update every 24 hours
      updateCounter(); // Initial update
    })();
  </script>

  <style>
    .custom-counter {
      display: inline; /* Makes it inline with surrounding text */
      text-align: left; /* Aligns text to the left */
      font-size: 1rem;
      font-weight: bold; /* Makes the font bold */
      color: #333;
  }
    }
  </style>
</div>


<script> initializeElapsedTimeCounter("AmazonCounter", new Date(2020, 0, 1));</script>

* Jul 2024 - Current: Senior Applied Scientist 
  * Amazon Prime Video, Sunnyvale

* Sep 2022 - Jul 2024: Applied Scientist 
  * Amazon Prime Video, Sunnyvale

* Jul 2021 - Sep 2022: Software Engineer 
  * Amazon Prime Video, Sunnyvale

* Sep 2019 - Jul 2021: Software Engineer 
  * Amazon Web Services (AWS), Cupertino

<br>

Academic Service
======

| Conference TPCs            | Workshop/Poster/Other TPCs  |
| ------------------------- | ---------------------------- |
| CoNEXT 2025               | EMS 2024                     |
| NSDI 2025                 | ICSE 2024 (external reviewer)|
| WWW 2024                  | SIGCOMM Poster 2020          |
| CoNEXT 2024               |                              |
| CoNEXT 2022               |                              |



| Journal Reviewer                |
| ------------------------------- |
| IEEE Transactions on Networking                         |
| IEEE Transaction on Multimedia                          |
| IEEE Transactions on Network and Service Management     |
| IEEE Transactions on Parallel and Distributed Systems   |

---


<!-- 
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
