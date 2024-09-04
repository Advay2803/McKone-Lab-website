---
layout: page
title: People
permalink: /people/
---

## Principal Investigator

{% for person in site.data.people.PI %}
### ![{{ person.name }}]({{ person.image }}) {{ person.name }}
**{{ person.title }}**  
{{ person.bio }}  
[Website]({{ person.website }})  
[ORCID]({{ person.orcid }}) | [LinkedIn]({{ person.linkedin }}) | [Google Scholar]({{ person.scholar }})
{% endfor %}

## Current Members

### Post-Docs
{% for person in site.data.people.Current_members.Post_docs %}
### ![{{ person.name }}]({{ person.image }}) {{ person.name }}
**{{ person.title }}**  
{{ person.bio }}  
[Website]({{ person.website }})  
[ORCID]({{ person.orcid }}) | [LinkedIn]({{ person.linkedin }}) | [Google Scholar]({{ person.scholar }})
{% endfor %}

### Graduate Students
{% for person in site.data.people.Current_members.Grad_students %}
### ![{{ person.name }}]({{ person.image }}) {{ person.name }}
**{{ person.title }}**  
{{ person.bio }}  
[Website]({{ person.website }})  
[ORCID]({{ person.orcid }}) | [LinkedIn]({{ person.linkedin }}) | [Google Scholar]({{ person.scholar }})
{% endfor %}

### Undergraduate Students
{% for person in site.data.people.Current_members.Undergrad_students %}
### ![{{ person.name }}]({{ person.image }}) {{ person.name }}
**{{ person.title }}**  
{{ person.bio }}  
[Website]({{ person.website }})
{% endfor %}

## Alumni

### Post-Docs
{% for person in site.data.people.Alumni.Post_docs %}
### ![{{ person.name }}]({{ person.image }}) {{ person.name }}
**{{ person.title }}**  
{{ person.bio }}  
[Website]({{ person.website }})  
[ORCID]({{ person.orcid }}) | [LinkedIn]({{ person.linkedin }}) | [Google Scholar]({{ person.scholar }})
{% endfor %}

### Graduate Students
{% for person in site.data.people.Alumni.Grad_students %}
### ![{{ person.name }}]({{ person.image }}) {{ person.name }}
**{{ person.title }}**  
{{ person.bio }}  
[Website]({{ person.website }})  
[ORCID]({{ person.orcid }}) | [LinkedIn]({{ person.linkedin }}) | [Google Scholar]({{ person.scholar }})
{% endfor %}

### Undergraduate Students
{% for person in site.data.people.Alumni.Undergrad_students %}
### ![{{ person.name }}]({{ person.image }}) {{ person.name }}
**{{ person.title }}**  
{{ person.bio }}  
[Website]({{ person.website }})
{% endfor %}
