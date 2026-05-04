---
title: The Oral Histories
layout: about
permalink: /oral-history.html
---

# The Oral Histories

“The Gary Project” was not done by Richard Dorson alone. The efforts of multiple graduate students, a project coordinator, and other auxiliary staff culminated into the documented fieldwork and published monograph still preserved and discoverable within various IU Archive repositories. Their efforts resulted in the production of a multitude of materials, such as field notes, photographs, or audio-visual recordings.

Below is a collection of oral histories conducted for this project in 2026 of some members of Dorson’s “Gary Gang” from when the project was conducted in the 1970s in the Calumet region. The interviewees speak about their own life stories, their work on the Gary Project, and their interactions and impressions of Richard Dorson himself. The students' recount of their ability to engage with the local community and the vibrant stories they collected allow them to be an excellent reference to frame Gary as a multi-cultural hub where a multitude of cultural diasporas and traditions lived and prospered.

Their recollections comment on what it meant to be part of a larger project that catapulted folklore studies into new directions during that time frame, both in academic scope and with the usage of brand new audio-visual technology. Conducting interviews with the graduate students today also allows individuals to see how their contributions to the project and the skills they learned led them into careers that actively utilized folklore ethnographic fieldwork methodologies and practices.

All interviews conducted were deposited into the _Richard M. Dorson Papers_ Collection within Indiana University Archives with the interviewees consent. Please refer to the contact page for more information on the interviews and how to cite them.

Select “Learn More” on a particular interviewee to view their personally-written autobiography.

<div class="card-group">
    <div class="row justify-content-center g-4">
    {% for card in site.data.oral-history-cards %}
      <div class="col-sm-6 col-12">
          {% assign normalized_name = card.name | downcase | replace: " ", "-" %}
          {% assign dest = normalized_name | prepend: "/oral-history/" %}
          {% assign img = normalized_name | append: ".jpg" | prepend: "/assets/img/oral-history/" %}
          {% include personcard.html header=card.name brief=card.brief img=img btn-dest=dest color="red" %}
      </div>
    {% endfor %}
    </div>
</div>
