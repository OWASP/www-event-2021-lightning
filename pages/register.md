---

title: Event Registration
layout: event_noheader
permalink: /register/

---

## Registration 
{% if site.data.event-details.registration_open %}
Welcome to the Lightning Event presented by the OWASP Foundation. Please note that this a fully virtual event. Upon completion of your registration you will receive a confirmation. Three days prior to the event you receive detailed instruction on how to log-on to the virtual platform. 

{% else %}
<br>
### Please join us and register [here](https://www.eventbrite.com/e/how-to-turn-your-cybersecurity-hobby-into-a-career-an-intro-to-bugbounties-tickets-137621959987?aff=OWASPwebsiteregistrationlink)
<br>
{% endif %}

{% if site.data.event-details.registration_open %}
### **Please note: All courses take place simultaneously over two days, only register for one.**

{% include registration_form.md show_dietary_restrictions="false" primary_color="#0079a7" %}

Also, **[check out our sponsors for a chance to win some cool prizes](/sponsors/swag/)**
{% endif %}


Questions? [events@owasp.com](mailto:events@owasp.com?subject=Lightning%20Event%20Inquiry)
