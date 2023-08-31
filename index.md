![](dvbern.png?raw=true)

[www.dvbern.ch](http://www.dvbern.ch)\
[github.com/dvbern](http://github.com/dvbern)


# Projects on GitHub:
  ## VacMe
[VacMe BE](https://github.com/dvbern/vacme-be-oss)\
[VacMe ZH](https://github.com/dvbern/vacme-zh-oss)

System for administrating vaccinations (registration, appointments, planning and documentation).
    
## [KiBon](https://github.com/dvbern/kiBon)
   
System for the management of external childcare subsidies (Kita Betreuungsgutscheine) - Canton Berne\
KiBon is based on Ki-Tax.
   
## [Ki-Tax](https://github.com/StadtBern/Ki-Tax)
  
System for the management of external childcare subsidies (Kita Betreuungsgutscheine) - City of Berne\
   
## STIP online
   
[STIP frontend](https://github.com/dvbern/stip-frontend)\
[STIP API](https://github.com/dvbern/stip-api)
   
System for scholarship management - Canton Berne\
STIP online is based on KiBon.
   
# Our GitHub Repositories:

{% for repository in site.github.public_repositories %}

  * [{{ repository.name }}]({{ repository.html_url }})
  
   {{ repository.description }}

{% endfor %}
