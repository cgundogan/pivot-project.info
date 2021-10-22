---
layout: default
---

# PIVOT

PIVOT is German-French project in the joint Call on Cybersecurity,
sponsored by the [German Ministry of Education and
Research](https://www.bmbf.de/en/index.html) and the [Agence Nationale de
la Recherche](https://anr.fr/en/).


PIVOT aims for assuring both privacy of data and of identifiers that may
disclose the data sources and contexts in the Internet of Things (IoT). The
secure protection of data and metadata in PIVOT will in particular extend
to low-end devices and low-power radio networks of the ultra-constrained
IoT.  

The fundamental approach taken in the PIVOT project is to secure data
following the concept of content object security on the full path from the
content origins to its destinations.  These content objects are
autonomously authenticated and encrypted independent of transport channels,
and hence can be freely replicated, aggregated, or cached. Content objects
will be accessed by names from the infrastructure---caches, processors, or
clouds at the mobile edge---thereby remaining fully decoupled from their
originators. Meta-information about content creators and operational
contexts will be only distributed if explicitly encoded by the source, and
accessible only by those who hold access rights. 

Together with standardization bodies and based on the popular
[RIOT](https://riot-os.org) open source operating system, the PIVOT team
will prioritize the goal of early deployment.

With its open sustainable perspective PIVOT will contribute to changing the
trend of Internet consolidation by allowing faster adoption of security and
privacy solutions to the IoT, thereby fostering an open, trustworthy
digitizations of our societies.

## News

{% for news in site.data.news limit:3 %}
  * <b>{{ news.date }}:</b> {{ news.text }}
{% endfor %}

<a href="news.html">
<button class="buttonnews">
    More &hellip;
</button></a>

## Contacts

- [Sandoche Balakrichenan](https://www.afnic.fr/en/associating-excellence/who-we-are/team/sandoche-balakrichenan/)
  (French Coordinator)
- [Matthias
  W&auml;hlisch](http://www.mi.fu-berlin.de/en/inf/groups/ilab/members/waehlisch.html) (German Coordinator, Spokesperson)
