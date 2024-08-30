# About
The Meeting on Feature-Oriented Software Development (FOSD Meeting) is a yearly informal meeting to bring together the community of researchers working on feature-oriented software development, including, but not limited to:

- Product lines
- Software variability
- Configuration management
- Software architecture

The meeting series started 16 years ago to bring several research groups with common interests closer together. It has successfully been repeated 15 times with 20 to 50 participants each, and has established countless collaborations since. For example, see the recent past FOSD meetings: [FOSD 2024 in Eindhoven](https://set.win.tue.nl/event/fosd-meeting-2024/), [FOSD 2023 in Ulm](https://fosd23.uni-ulm.de/), and [FOSD 2022 in Vienna](https://fosd2022.wu.ac.at/).

The main objective is that researchers at different career stages (including undergraduate and early-career graduate students) come together to present their research, to get feedback from peers, to discuss new directions, and to initiate collaborations.

The format of an FOSD meeting consists of short presentations from each participant with plenty of time for discussion. Young researchers (graduate and undergraduate students), as well as more senior community members, present their research, provide and get feedback from others, engage into discussions and establish new collaborations. FOSD is a place for discussion, not a publication venue. Participants can present previously published work as well as unpublished work, including early ideas and work in progress. The key is to encourage discussions, to receive feedback and to grow the network of collaborating researchers.

## Important Dates
<table>
  <tr>
    <td>Abstract Submission Deadline</td>
    <td>December 4, 2024 </td>
  </tr>
  <tr>
    <td>Notification of Acceptance</td>
    <td>December 12, 2024 </td>
  </tr>
  <tr>
    <td>Registration Deadline</td>
    <td>TBD (estimated: February 2025) </td>
  </tr>
  <tr>
    <td>FOSD Meeting 2025</td>
    <td>March 25 - 28, 2025</td>
  </tr>
</table>

# Participants
TBD

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
The FOSD Meeting 2025 will take place at the Anhalt University of Applied Sciences in Köthen, Germany.

TODO: Venue information and images

## Arrival by Train

Köthen is located between Magdeburg and Leipzig, and thus, well-connected by regional as well as Intercity train:

* from Leipzig Airport: ~35-50 minutes
* from Halle (Saale): ~20-25 minutes
* from Magdeburg: ~25-40 minutes
* from Hanover: ~2 hours
* from BER airport: ~2,5 hours
* from Frankfurt/Main airport: ~ 4,5-5 hours

## Arrival by Plane
Since there is no airport in Köthen, we recommend that you book a flight to one of the airports below and find a connection by train.

* Leipzig/Halle Airport has regular flights to several major European cities. Arriving there, you can reach Köthen by train in around 35-50 minutes.
* Frankfurt Airport can also be reached from non-european countries. Taking the train to Köthen will take around 4,5 to 5 hours.

# Contact
For questions and abstract submissions, please send an email to <fosd25@hs-anhalt.de>.

## Organizers
- [Sandro Schulze](https://www.hs-anhalt.de/hochschule-anhalt/service/personenverzeichnis/person/prof-dr-sandro-schulze.html)
- [Tobias Dick](https://www.se.cs.uni-saarland.de/people/dick.php)

## Steering Committee
- [Sven Apel](https://www.se.cs.uni-saarland.de/apel/)
- [Thomas Thüm](https://www.uni-paderborn.de/person/102807)
