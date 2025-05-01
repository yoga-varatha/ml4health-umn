---
layout: home
title: ML4H
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Machine Learning for Health Care, ML4H UMN
---

# CSCI 5526: Machine Learning for Healthcare 
<span style="font-weight: lighter; font-size: 20px">University of Minnesota, Twin Cities, Fall 2025</span>.

## Logistics

  <ul>
        <li><strong>Location:</strong> 	TBD</li>
        <li><strong>Time:</strong> Tuesdays and Thursdays, 9:45 AM – 11:00 AM</li>
        <li><strong>Links:</strong> 
          <a href="https://canvas.umn.edu/courses/" target="_blank">Canvas</a>, 
          <a href="https://piazza.com/class/" target="_blank">Piazza</a>
        </li>
  </ul>


## Overview

Machine Learning is transforming healthcare. This course will introduce students to a range of healthcare problems that can be tackled using machine learning, different health data modalities, relevant machine learning paradigms, and the unique challenges presented by healthcare applications. Applications we will cover include risk stratification, disease progression modeling, precision medicine, diagnosis, prognosis, subtype discovery, and improving clinical workflows. We will also cover research topics such as explainability, causality, trust, robustness, and fairness.

The prerequisite for this class is CSCI 5521 or an equivalent course. Experience with Python is recommended. Graduate and upper-level undergraduate students with introductory machine learning knowledge are also welcome. Please contact the instructor, if you are unsure whether you meet the prerequisites.


## Instructor

<div>

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}

</div>

