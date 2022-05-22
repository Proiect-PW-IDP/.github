# .github

Link Figma:
https://www.figma.com/file/CHhyFAR4K6bVAu4rdG4qGj/PW%2BIDP?node-id=1%3A4
Aici se pot gasi Requirements, Wireframes si Prototypes.

In documentul User Stories Pweb.pdf se pot gasi urmatoarele: 
- User stories
- Arhitectura de domeniu, la nivel de date
- Arhitectura macro, la nivel de sistem

In acest repository am atasat fisierele yaml de configuratie:
- docker-compose.yml
- kong.yml
- loki.yml
- prometheus.yml

Monitorizarea starii nodurilor, folosind Prometheus:
http://localhost:9090/targets

<img width="473" alt="image" src="https://user-images.githubusercontent.com/62909789/169713986-dc0363a5-a649-4872-a1f4-f3e387f05921.png">


Link Grafana:
http://localhost:3001/d/E52FpSu7z/pw-ipd-project-dashboard?from=now-30m&to=now&orgId=1

<img width="958" alt="image" src="https://user-images.githubusercontent.com/62909789/169714131-23917c63-812c-45b8-9272-1819a106bd83.png">


Aici am creat un dashboard cu logurile de pe backend si email-service, dar am importat si un doua metrici cu ajutorul loki:
- Counter: calculeaza numarul de cereri la unul dintre endpointuri
- Gauge pentru offers: cate oferte exista in baza de date


Link repositories:

- https://github.com/Proiect-PW-IDP/backend
- https://github.com/Proiect-PW-IDP/frontend
- https://github.com/Proiect-PW-IDP/email-service




