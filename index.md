![](dvbern.png?raw=true)

[www.dvbern.ch](http://www.dvbern.ch)\
[github.com/dvbern](http://github.com/dvbern)


# Projects on GitHub:
## VacMe
[https://github.com/dvbern/vacme-be-oss](https://github.com/dvbern/vacme-be-oss)\
[https://github.com/dvbern/vacme-zh-oss](https://github.com/dvbern/vacme-zh-oss)

WebApp for administrating vaccinations\
(registration, appointments, planning and documentation).
    
## KiBon
[www.kibon.ch](https://kibon.ch){:target="_blank"}\
[https://github.com/dvbern/kiBon](https://github.com/dvbern/kiBon)

WebApp for the management of external childcare subsidies for Swiss cantons\
(Kita Betreuungsgutscheine)\
KiBon is based on Ki-Tax.
   
## Ki-Tax
[https://github.com/StadtBern/Ki-Tax](https://github.com/StadtBern/Ki-Tax)

WebApp for the management of external childcare subsidies\
(Kita Betreuungsgutscheine)\
Pilot project City of Berne
   
## STIP online
   
[https://github.com/dvbern/stip-frontend](https://github.com/dvbern/stip-frontend)\
[https://github.com/dvbern/stip-api](https://github.com/dvbern/stip-api)
   
WebApp for scholarship management (Stipendien) - Canton Berne\
STIP online is based on KiBon.


# Our GitHub Repositories:

{% for repository in site.github.public_repositories %}

  * [{{ repository.name }}]({{ repository.html_url }})
  
   {{ repository.description }}

{% endfor %}
