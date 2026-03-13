# About
The **Beyond the Model Meeting (BTMM)** is an informal gathering focused on software engineering for building applications with machine-learning components. The meeting aims to foster collaboration and exchange ideas among researchers working on various aspects of integrating ML components into software systems. Topics of interest include, but are not limited to:

- Process and requirements for ML-powered systems
- User-interaction design for ML-powered systems
- Quality assurance and safety engineering for ML-powered systems
- Operations for ML-powered systems
- Regulatory oversight for ML-powered systems

The meeting is modeled after the [Feature-Oriented Software Development (FOSD)](https://fosd.github.io/FOSD2025/) meetings. It features a supportive environment where participants present their research, receive feedback, and engage in discussions. The primary objective is to bring together researchers at different career stages, including undergraduate and early-career graduate students, to share ideas and initiate collaborations.

**Note:** This meeting is not a publication venue. Participants can present previously published work or work in progress, with an emphasis on fostering discussions and collaborations rather than producing proceedings.

## Scope
The BTMM focuses on software engineering activities relevant to building software applications with ML components (including LLMs). It adopts a system view, considering the entire system and its environment beyond the model. Both technical and empirical work is welcome. The following topics are in scope:

- Work considering ML components in the context of a system
- Activities across the software lifecycle related to ML component integration

The following are **out of scope**:

- Exclusively model-centric work (e.g., fairness testing of models without system consideration)
- Work using ML to support software engineering tasks (e.g., LLMs for code generation)

## Important Dates

<table>
  <tr>
    <td>Abstract Submission Deadline</td>
    <td>Recommended by March 31st, 2026, but accepted on a rolling basis until all slots are taken</td>
  </tr>
  <tr>
    <td>Beyond-the-Model Meeting 2026</td>
    <td>July 10 - 11, 2026</td>
  </tr>
</table>

## Meeting Format
The meeting consists of short presentations (10-15 minutes) from each participant, followed by ample time for discussion. Presentations can cover:

- Planned research
- Ongoing projects
- Published work

___

# Attending / Registration

[Participant Registration](https://forms.cloud.microsoft/r/asPwU2Z2XJ)

We ask all interested participants to submit the form above. You may submit your talk title and abstract now, or we will ask for this information closer to the time of the event.

We will accept at most 20 participants. We will usually confirm participation within 1 week of abstract submission, first come first serve. We reserve the right to decline talks that we consider as out of scope or if we run out of capacity to host more talks.

No additional registration is required. If you would be willing to volunteer to sponsor the event by paying an optional registration fee, please contact the organizers.

If you cannot make it after all or want to talk about something else, please email us as soon as possible.

## Participants

<!-- _To be announced!_ -->

<table>
  <tr>
    <th>Name</th>
    <!-- <th>Title</th> -->
    <th>University</th>
  </tr>
  {% for item in site.data.participants %}
  <tr>
    <td width="20%">
      {% if item.homelink %}
        <a href="{{ item.homelink }}" target="_blank">{{ item.name }} </a>
      {% else %}
        {{ item.name }} 
      {% endif %}
    </td>
    <!-- <td width="60%">
      {% if item.link %}
        <a href="{{ item.link }}" target="_blank">{{ item.title }} </a>
      {% else %}
        {{ item.title }} 
      {% endif %}
    </td> -->
    <td width="20%">{{item.university}}</td>
  </tr>
 {% endfor %}

</table>
___

# Schedule
_To be announced!_

{% for conf_day in site.data.schedule %}
## Schedule {{ conf_day.day | date: "%A, %b %e" }}
{% for session in conf_day.sessions %}
### {{ session.name }}: {{ session.from | date: "%R" }} - {{ session.to | date: "%R" }}
{% for talk in session.talks %}
* **{{ talk.speaking }}**: {{ talk.title }}
{% endfor %}
{% endfor %}
{% endfor %}

___


# Venue & Travel Information
BTMM 2026 will take place at McGill University, Montreal, Canada.

## Meeting Location

_To be announced!_

## Accommodation and Costs
- No registration fees.
- Participants cover their own transportation, accommodation, and meals.
- Sponsorships may cover group lunches or dinners, tbd.

(If you would like to volunteer to sponsor the event by paying an optional registration fee, please contact the organizers.)

___

# Contact
For questions or further information, please contact the organizers.

## Organizers
- [Christian Kästner](https://www.cs.cmu.edu/~ckaestne/)
- [Jin Guo](https://www.cs.mcgill.ca/~jguo/)
- [Veronica Xia](https://veronicayx.notion.site/Veronica-Xia-21562e9fbefd806ebdc7e0bbd87f9c47)
