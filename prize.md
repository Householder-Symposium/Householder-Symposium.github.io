---
layout: page
title: Householder Prize
permalink: /prize/
---

[Donations for the Householder Prize at HH XXIII are now being accepted!](https://www.leetchi.com/en/c/householder-xxiii-prize-2070489)

The Alston S. Householder Prize is awarded to the the author of the best dissertation in numerical linear algebra and is awarded at the symposium for dissertations submitted over the previous three years.

## Prize nominations

Nominations are solicited for the Alston S. Householder Prize. The award will be presented to the author of the best dissertation in numerical linear algebra submitted between 1 January 2022, and 31 December 2024. 

The submission process for the Householder Prize is now open. The supervisor of a candidate recipient of a PhD, earned between January 1, 2022 and December 31, 2024, must submit a copy of the PhD dissertation and an appraisal. One or more external letters of recommendation supporting the nomination are also required. Nominations may be submitted online using the form available [here](https://forms.gle/dniHd1f6eZuhFAoNA). Nominations must be submitted by February 16, 2025.



Entries will be assesed by the Householder Prize committee consisting of:

<ul style="list-style: none; padding-left: 0;">
  {% for member in site.data.committees.prize %}
  <li>{{ member.name }}{% if member.role %} ({{ member.role }}){% endif %}, {{ member.where }}</li>
  {% endfor %}
</ul>

## Prize details

The term numerical linear algebra is intended to describe those parts of mathematical research that have both linear algebraic aspects and numerical content or implications. Thus, for example, a dissertation concerned with the numerical solution of differential equations or the numerical solution of an optimization problem would be eligible if linear algebra is central to the research contribution.

To qualify, the dissertation must have been examined and deemed to have passed during the period of the prize. However, the PhD degree or equivalent need not have been officially awarded during this period.

Candidates from countries in which a formal dissertation is not normally written at that level may submit an equivalent piece of work. The Householder Prize, given every three years, was established at the 1969 Gatlinburg Symposium (now renamed the Householder Symposium) to recognize the outstanding contributions of Alston S. Householder, 1904-1993, to numerical analysis and linear algebra.

## Previous Householder Prize winners

<table>
    <thead>
        <tr>
            <th>Year</th>
            <th>Winner(s)</th>
            <th>Institution</th>
        </tr>
    </thead>
    <tbody>
    {% for prize in site.data.prizes reversed %}{% for winner in prize.winners %}
    <tr>
      <td>{% if forloop.first %}{{ prize.year }}{% endif %}</td>
      <td>{{ winner.name }}</td>
      <td>{{ winner.where }}</td>
    </tr>
    {% endfor %}{% endfor %}
    </tbody>
</table>


