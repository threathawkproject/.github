![Banner](https://user-images.githubusercontent.com/82387424/215805164-1d236cc5-ef1a-475a-a5da-15e142fedc09.png)

## Welcome!
ThreatHawk is an investigative threat intelligence platform that empowers cyberthreat analysts by placing at the power of open-source tools at their fingertips. It allows them to collect meaningful intelligence data about **IP addresses**, **domains**, **emails**, and **file hashes** through a single click.

**Note:** We've kept the repositories private since this project is still under development. 

## Tools and Technologies
- Python (Django and FastAPI)
- PostgreSQL
- Kafka
- React (Next.js and MaterialUI)
- Docker and Docker Compose
- Meilisearch

## Main Features
- Aggregation of different kinds of Indicators of Compromise (IOCs) from open-source threat intelligence feeds such as AbuseIPDB and Darklist, with support for paid feeds as well.
- Enrichment of the collected IOCs using open-source threat intelligence tools such as EmailRep (for email reputation scores) and MaxMind GeoIP (for IP address geolocation data). This enrichment module is incredibly scalable and new tools can easily be integrated in the future.
- Iterative, drill-down investigations on a specified IOC. This allows us to dig deeper and actually understand the threat landscape (by drawing links between the IOC, the attacker, and the techniques that were used by the attacker). 

## Contributors
- [Hussain Khan](https://github.com/fear-the-reaper)
- [Zohaib Adnan](https://github.com/zohaibadnan137)
- [Huzaifa Siddiqui](https://github.com/mhuzaifa-2000)
