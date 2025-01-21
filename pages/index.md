# About
The Beyond the Model Meeting (BTMM) is an informal gathering focused on software engineering for building applications with machine-learning components. The meeting aims to foster collaboration and exchange ideas among researchers working on various aspects of integrating ML components into software systems. Topics of interest include, but are not limited to:

- Process and requirements
- User-interaction design
- Quality assurance and safety engineering
- Operations
- Regulatory oversight

The meeting is modeled after the Feature-Oriented Software Development (FOSD) meetings. It features a supportive environment where participants present their research, receive feedback, and engage in discussions. The primary objective is to bring together researchers at different career stages, including undergraduate and early-career graduate students, to share ideas and initiate collaborations.

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
    <td>TBD </td>
  </tr>
  <tr>
    <td>Notification of Acceptance</td>
    <td>TBD </td>
  </tr>
  <tr>
    <td>Registration Deadline</td>
    <td>TBD (estimated: February 2025) </td>
  </tr>
  <tr>
    <td>BTMM Meeting 2025</td>
    <td>May 4 - 5, 2025</td>
  </tr>
</table>

## Meeting Format
The meeting consists of short presentations (10-15 minutes) from each participant, followed by ample time for discussion. Presentations can cover:

- Planned research
- Ongoing projects
- Published work

No registration fees are required. Participants only need to submit a title and abstract for their talk.

# Participants
TBD

<!-- <table>
  <tr>
    <th>Name</th>
    <th>Title</th>
    <th>University</th>
  </tr>
  {% for item in site.data.participants %}
  <tr>
   <td width="20%">{{item.name}}</td>
   <td width="60%">{{item.title}} {% if item.link != null %}<a href={{item.link}} target="_blank" >[slides]</a>{% endif %}</td>
   <td width="20%">{{item.university}}</td>
  </tr>
 {% endfor %}

</table> -->

# Schedule
TBD

{% for conf_day in site.data.schedule %}
### Schedule {{ conf_day.day | date: "%A, %b %e" }}
Address: **{{conf_day.address}}**
{% for session in conf_day.sessions %}
Session: {{ session.from | date: "%R" }} - {{ session.to | date: "%R" }}, Chair: {{ session.chair }} 
{% for talk in session.talks %}
* **{{ talk.speaking }}**: {{ talk.title }}
{% endfor %}
{% endfor %}
{% endfor %}

# Venue & Travel Information
BTMM 2025 will take place at University of Toronto, Canada.


## Accommodation and Costs
- No registration fees.
- Participants cover their own transportation, accommodation, and meals.
- Sponsorships may cover group lunches and dinners.

## Hotel Recommendations
TBD

# Contact
For questions or further information, please contact us at <email-here>.

## Organizers
- [Christian Kästner](https://www.cs.cmu.edu/~ckaestne/)
- [Shurui Zhou](https://www.eecg.utoronto.ca/~shuruiz/)
- [Chenyang Yang](https://www.cs.cmu.edu/~cyang3/)