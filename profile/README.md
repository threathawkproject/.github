![Banner](https://user-images.githubusercontent.com/82387424/215805164-1d236cc5-ef1a-475a-a5da-15e142fedc09.png)

## Welcome!
ThreatHawk is an investigative threat intelligence platform that empowers cyberthreat analysts by placing at the power of open-source tools at their fingertips. It allows them to collect meaningful intelligence data about **IP addresses**, **domains**, **emails**, and **file hashes** through a single click.

## Tools and Technologies
- Python (Django and FastAPI)
- PostgreSQL
- Kafka
- React (Next.js and MaterialUI)
- Docker and Docker Compose
- Meilisearch

## Main Features
- Aggregation of different kinds of Indicators of Compromise (IOCs) from open-source threat intelligence feeds such as AbuseIPDB and Darklist, with support for paid feeds as well. An IOC is any **IP address**, **domain**, **email**, or **file hash** that has been deemed malicious. 
- Enrichment of the collected IOCs using open-source threat intelligence tools such as EmailRep (for email reputation scores) and MaxMind GeoIP (for IP address geolocation data). This enrichment module is incredibly scalable and new tools can easily be integrated in the future.
- Iterative, drill-down investigations on a specified IOC. This allows us to dig deeper and actually understand the threat landscape (by drawing links between the IOC, the attacker, and the techniques that were used by the attacker).
- All data is converted to the industry-recognized STIX standard. This means that any external systems can access ThreatHawk's data too.
- ThreatHawk is incredibly fault-tolerant and scalable since **each** feature is a separate microservice. This means that future contributions to this project can also be made very easily.

## Significance
- Cyber threats have become increasingly globalized, which is why it is essential to move towards open-source threat intelligence.
- Traditionally, analyzing a single IOC with multiple tools is an incredibly painful process, since analysts must **manually** configure each tool separately. This is very difficult because different tools work differently (some use REST APIs, whereas others use client libraries or SDKs). ThreatHawk automates the usage of these different tools through one click.
- Investigating an IOC iteratively (beyond the first level) is a relatively novel approach since most competing solutions only provide data for the first layer. With ThreatHawk, analysts can drill-down to deeper layers until they find satisfactory insights. 

## Contributors
- [Hussain Khan](https://github.com/fear-the-reaper)
- [Zohaib Adnan](https://github.com/zohaibadnan137)
- [Huzaifa Siddiqui](https://github.com/mhuzaifa-2000)
