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
    <td>Recommended by Feb 17, but accepted on a rolling basis until all slots are taken</td>
  </tr>
  <tr>
    <td>Beyond-the-Model Meeting 2025</td>
    <td>May 4 - 5, 2025</td>
  </tr>
</table>

## Meeting Format
The meeting consists of short presentations (10-15 minutes) from each participant, followed by ample time for discussion. Presentations can cover:

- Planned research
- Ongoing projects
- Published work


# Attending / Registration
We ask all interested participants to submit a talk abstract. We will accept at most 20 participants. We will usually confirm participation within 1 week of abstract submission, first come first serve. We reserve the right to decline talks that we consider as out of scope or if we run out of capacity to host more talks.

Once the abstract is accepted, no additional registration is required. If you would like to volunteer to sponsor the event by paying an optional registration fee, please contact the organizers.

If you cannot make it after all or want to talk about something else, please email us as soon as possible.

## Participants
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
- Sponsorships may cover group lunches or dinners, tbd.

(If you would like to volunteer to sponsor the event by paying an optional registration fee, please contact the organizers.)

## Hotel Recommendations

- [Delta Chelsea Inn](http://www.deltahotels.com/hotels/hotels.php?hotelId=10)
  - Price per night: [$290CAD+](https://reservation.brilliantbylangham.com/?_gl=1*bqpy8s*_gcl_aw*R0NMLjE3Mzc0ODUwMDEuQ2owS0NRaUFxTDI4QmhDckFSSXNBQ1lKdmtlaDFWZHVsREZTU2JQZEdSaWtPU3drZXI1MF9zZkNjU055ajV3b3BoV0xLT1BCcHhreXIyMGFBb2tFRUFMd193Y0I.*_gcl_dc*R0NMLjE3Mzc0ODUwMDEuQ2owS0NRaUFxTDI4QmhDckFSSXNBQ1lKdmtlaDFWZHVsREZTU2JQZEdSaWtPU3drZXI1MF9zZkNjU055ajV3b3BoV0xLT1BCcHhreXIyMGFBb2tFRUFMd193Y0I.*_gcl_au*MTUyOTMzNzQ1My4xNzM3NDg1MDAx&adobe_mc=MCMID%3D06055212287097977022571148061850131206%7CMCORGID%3D085C2C1653DB0FFF0A490D4B%2540AdobeOrg%7CTS%3D1737485194&adult=1&arrive=2025-05-03&chain=10316&child=0&config=brilliant&currency=CAD&depart=2025-05-05&hotel=59052&level=hotel&locale=en-US&productcurrency=CAD&rooms=1&theme=brilliant)
  - Address: 33 Gerrard St W, Toronto, ON M5G 1Z4 -- [20min walk](https://www.google.com/maps/dir/Bahen+Centre+for+Information+Technology,+Bahen+Centre+for+Information+Technology,+Saint+George+Street,+Toronto,+ON/Chelsea+Hotel,+Toronto,+33+Gerrard+St+W,+Toronto,+ON+M5G+1Z4/@43.6586581,-79.3953102,16z/data=!3m1!4b1!4m14!4m13!1m5!1m1!1s0x882b34c75165c957:0x6459384147b4b67b!2m2!1d-79.397298!2d43.6598045!1m5!1m1!1s0x882b34b57f88aad5:0xa9bf8d18c55906a9!2m2!1d-79.3830973!2d43.6584976!3e2?entry=ttu&g_ep=EgoyMDI1MDExNS4wIKXMDSoASAFQAw%3D%3D)

- [Boutique Toronto Hotel in Annex/Yorkville](https://www.ihg.com/kimptonhotels/hotels/us/en/saint-george-hotel-toronto-on/yyzbs/hoteldetail)
  - Price per night: [$340CAD+](https://www.ihg.com/kimptonhotels/hotels/us/en/find-hotels/select-roomrate?fromRedirect=true&qSrt=sBR&qDest=Kimpton%20Saint%20George%20Hotel&qErm=false&qSlH=YYZBS&qRms=1&qAdlt=1&qChld=0&qCiD=03&qCiMy=042025&qCoD=05&qCoMy=042025&qAAR=6CBARC&qRtP=6CBARC&setPMCookies=true&qSHBrC=KI&qpMbw=0&qpMn=0&srb_u=1&qChAge=&qRmFltr=)
  - Address: 280 Bloor Street West -- [15min walk](https://www.google.com/maps/dir/Bahen+Centre+for+Information+Technology,+Bahen+Centre+for+Information+Technology,+Saint+George+Street,+Toronto,+ON/280+Bloor+St+W,+Toronto,+ON+M5S+1V8/@43.6636413,-79.4043296,16z/data=!3m1!4b1!4m14!4m13!1m5!1m1!1s0x882b34c75165c957:0x6459384147b4b67b!2m2!1d-79.397298!2d43.6598045!1m5!1m1!1s0x882b34bda8212af3:0x5c0430a82b4b5b64!2m2!1d-79.4009166!2d43.6675766!3e2?entry=ttu&g_ep=EgoyMDI1MDExNS4wIKXMDSoASAFQAw%3D%3D)

- [Holiday Inn Toronto Downtown Centre](https://www.ihg.com/holidayinn/hotels/us/en/toronto/yyzct/hoteldetail)
  - Price per night: [$313CAD+](https://www.ihg.com/holidayinn/hotels/us/en/find-hotels/select-roomrate?fromRedirect=true&qSrt=sBR&qDest=Holiday%20Inn%20Toronto%20Downtown%20Centre&qErm=false&qSlH=YYZCT&qRms=1&qAdlt=1&qChld=0&qCiD=03&qCiMy=042025&qCoD=05&qCoMy=042025&qAAR=6CBARC&qRtP=6CBARC&setPMCookies=true&qSHBrC=HI&qpMbw=0&qpMn=0&srb_u=1&qChAge=&qRmFltr=)
  - Address: 30 Carlton Street, Toronto -- [21min walk](https://www.google.com/maps/dir/30+Carlton+Street,+Toronto,+Ontario+M5B+2E9/Bahen+Centre+for+Information+Technology,+40+St+George+St,+Toronto,+ON+M5S+2E4/@43.6608653,-79.3942917,16z/data=!3m2!4b1!5s0x882b34c0acf2fcbb:0xb8e80e849329fc88!4m14!4m13!1m5!1m1!1s0x882b34b4c50a2865:0x67534e831966b080!2m2!1d-79.3810901!2d43.6616807!1m5!1m1!1s0x882b34c75165c957:0x6459384147b4b67b!2m2!1d-79.397298!2d43.6598045!3e2?entry=ttu&g_ep=EgoyMDI1MDExNS4wIKXMDSoASAFQAw%3D%3D)

- [Airbnb around campus](https://www.airbnb.ca/s/University-of-Toronto--Toronto--Ontario--Canada/homes?refinement_paths%5B%5D=%2Fhomes&flexible_trip_lengths%5B%5D=one_week&monthly_start_date=2025-02-01&monthly_length=3&monthly_end_date=2025-05-01&price_filter_input_type=0&channel=EXPLORE&query=University%20of%20Toronto%2C%20Toronto%2C%20ON&place_id=ChIJq_9ZrL80K4gRjkgaYCMz9ok&location_bb=Qi6sxcKex%2B9CLqA9wp7Siw%3D%3D&date_picker_type=calendar&checkin=2025-05-03&checkout=2025-05-05&adults=1&source=structured_search_input_header&search_type=autocomplete_click)

## Food Recommendations

- [Food on campus](https://foodservices.utoronto.ca/where-to-eat/)
- [Coffee near Bahen Centre (BA)](https://www.google.com/maps/search/coffee/@43.6598042,-79.3998729,16z/data=!3m1!4b1![…]3.6598045?entry=ttu&g_ep=EgoyMDI1MDEyMC4wIKXMDSoASAFQAw%3D%3D)
- Quick lunch options
  - [The Arbor Room](https://harthouse.ca/arbor-room) (Gluten-Friendly, Vegetarian, Vegan. Address: 7 Hart House Cir), 5 min walk
  - [Mi’hito Sushi Laboratory](https://maps.app.goo.gl/xhn9BmJpAcCSJPA37), 10min walk
  - [Fresca Pizza and Pasta](https://maps.app.goo.gl/Jg4DVAFoVKHBzbRt7), 10min walk
- Dinner
  - [Prenup Pub](https://maps.app.goo.gl/iKWDS6ZJayfgtqyJ7)
  - [Mercatto](https://maps.app.goo.gl/oQVAGpJ4V33ARMDp6)

# Contact
For questions or further information, please contact us at <email-here>.

## Organizers
- [Christian Kästner](https://www.cs.cmu.edu/~ckaestne/)
- [Shurui Zhou](https://www.eecg.utoronto.ca/~shuruiz/)
- [Chenyang Yang](https://www.cs.cmu.edu/~cyang3/)
