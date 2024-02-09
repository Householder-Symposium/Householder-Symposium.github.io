---
layout: page
title: History
permalink: /history/
---

The Householder Symposia originated in a series of meetings organized by Alston Householder, Director of the Mathematics Division of Oak Ridge National Laboratory and Ford Professor at the University of Tennessee. These international meetings were devoted to matrix computations and linear algebra and were held in Gatlinburg, Tennessee. They had a profound influence on the subject.

The last "Gatlinburg" conference held at Gatlinburg was in 1969 on the occasion of Householder's retirement. At the time, it was decided to continue the meetings but vary the place. Since then meetings have been held at three-year intervals in a variety of venues and the series has been renamed in honor of Alston Householder.

The meetings, which last for five days, are by invitation only. They are intensive, with plenary talks in the day and special sessions in the evenings. To encourage people to talk about work in progress, no proceedings are published, although extended abstracts are circulated. The response of the participants to the meetings has generally been very enthusiastic.

The conferences are run in tandem by a permanent organizing committee and a local arrangements committee. Although attendance is restricted, anyone - including students - can apply. Selection is made by the organizing committee, generally by ballot.

The meeting is also the occasion for the award of the Householder prize for the best thesis in numerical linear algebra. This prize is entirely (and well) supported by contributions solicited at the Symposium banquet. 

## Previous Householder Symposia

<table>
  <thead>
    <tr>
      <th>#</th>
      <th>Year</th>
      <th>Place</th>
      <th>Organizers</th>
      <th>Links</th>
    </tr>
  </thead>
  <tbody>
    {% for hh in site.data.previous reversed %}
    <tr>
      <td>{{ hh.number | upcase }}</td>
      <td>{{ hh.year }}</td>
      <td>{{ hh.place }}</td>
      <td>{{ hh.organizers | join: ", " }}</td>
      <td>{% if hh.links %}<ul>{% for link in hh.links %}
          <li><a href="{{ link.link }}">{{ link.text }}</li>
        {% endfor %}</ul>{% endif %}</td>
    </tr>
    {% endfor %}
  </tbody>
</table>

