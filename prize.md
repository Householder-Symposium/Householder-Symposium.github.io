---
layout: page
title: Householder Prize
permalink: /prize/
---

The Alston S. Householder Prize is awarded to the the author of the best dissertation in numerical linear algebra and is awarded at the symposium for dissertations submitted over the previous three years.

## Prize details

The term numerical linear algebra is intended to describe those parts of mathematical research that have both linear algebraic aspects and numerical content or implications. Thus, for example, a dissertation concerned with the numerical solution of differential equations or the numerical solution of an optimization problem would be eligible if linear algebra is central to the research contribution.

To qualify, the dissertation must have been examined and deemed to have passed during the period of the prize. However, the PhD degree or equivalent need not have been officially awarded during this period.

Candidates from countries in which a formal dissertation is not normally written at that level may submit an equivalent piece of work. The Householder Prize, given every three years, was established at the 1969 Gatlinburg Symposium (now renamed the Householder Symposium) to recognize the outstanding contributions of Alston S. Householder, 1904-1993, to numerical analysis and linear algebra.

Entries will be assessed by an international committee consisting of:


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


