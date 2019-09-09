![](dvbern.png?raw=true)

[www.dvbern.ch](http://www.dvbern.ch)

**Client projects on GitHub:**
  * [Ki-Tax](https://github.com/StadtBern/Ki-Tax)
  
   System for the management of external childcare subsidies (Kita Betreuungsgutscheine) - City of Berne
   
  * [KiBon] (https://github.com/dvbern/kiBon)
   
   System for the management of external childcare subsidies (Kita Betreuungsgutscheine) - Canton Berne
   KiBon is a fork of Ki-Tax.
   
**Our GitHub Repositories:**

{% for repository in site.github.public_repositories %}

  * [{{ repository.name }}]({{ repository.html_url }})
  
   {{ repository.description }}

{% endfor %}
