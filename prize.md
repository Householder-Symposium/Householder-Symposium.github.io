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
            <td>Year</td>
            <td>Winner(s)</td>
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

| Year |	Winners (s) |
|-------|--------|
| 1971 | F. Robert (Grenoble) |
| 1974 | Ole Hald (New York University) |
| 1977 | Daniel D. Warner (University of California, San Diego) |
| 1981 | E. Marques de Sa' (Coimbra) and Paul Van Dooren (K. U. Leuven) |
| 1984 | Ralph Byers (Cornell University) and James M. Demmel (University of California, Berkeley) |
| 1987 | Nicholas J. Higham (University of Manchester) |
| 1990 | Alan Edelman (Massachusetts Institute of Technology) and Maria Beth Ong (University of Washington) |
| 1993 | Hong-Guo Xu (Fudan University) and Barry Smith (New York University) |
| 1996 | Ming Gu (Yale University) |
| 1999 | Jorg Liesen (Bielefeld) |
| 2002 | Jing-Rebecca Li (Massachusetts Institute of Technology) |
| 2005 | Jasper van den Eshof (Utrecht University) |
| 2008 | David Bindel (University of California, Berkeley) |
| 2011 | Bart Vandereycken (KU Leuven) and Paul Willems (Bergische Universitat Wuppertal) |
| 2014 | Nicolas Gillis (UC Louvain) and Yuji Nakatsukasa (UC Davis) |
| 2017 | Marcel Schweitzer (Ecole Polytechnique Federale de Lausanne) and Edgar Solomonik (University of Illinois) |
| 2020 | Estelle Massart (UC Louvain) and Stefano Massei (Scuola Normale Superiore di Pisa) |
| 2022 | Heather Wilber (Cornell University) |


