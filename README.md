System Design — 9 Topics in Marathi
Short Description: System Design in Marathi — 9 topics, diagrams, code & real examples. HLD vs LLD, Scaling, Caching, Databases, Queues, Reliability, Security, Architecture & Whole Systems.

Learn System Design topic-wise in Marathi — diagrams, code & real examples.

Live Demo: https://designsystem-....vercel.app
(Vercel var deploy kelyavar tujha khara link ithe tak)

Kay aahe he repo?
Pratyek topic madhe hech 5 points aahet:

Kay aahe? — Basic Concept
Main Goal — Kay sadhya karaycha?
Ka use karaycha? — Why
Kasa kaam karto? — How
Kuthe use hoto? — Where / Real Use
Architecture Diagram (click karun baghaycha)
Code (Python / SQL — concept samjnyasathi simplified)
Real Example (Instagram, WhatsApp, YouTube, Flipkart sarkhe)
9 Topics — Sagla Ekatra
#	Topic	Aat kay aahe?
1	Foundation — How a Request Travels	HLD vs LLD, DNS, Latency & Throughput, Napkin Math Calculator
2	Scaling & Load Balancing	Vertical / Horizontal, Load Balancer, Consistent Hashing, Rate Limiting, Auto Scaling, Traffic Simulator
3	Caching	Cache-Aside, Write-Through / Write-Behind, LRU / LFU, CDN, Cache Stampede
4	Storage & Databases	SQL vs NoSQL, Replication, Sharding Demo, Indexing, Object Storage, ACID
5	Communication — Queues & Real-Time	REST / gRPC / GraphQL, Message Queue, Kafka / Pub-Sub, WebSockets, SSE, Idempotency
6	Reliability	SPOF, Failover, Retry + Backoff + Jitter, Circuit Breaker, Bulkhead, Monitoring, RPO / RTO
7	Security	Authentication, RBAC, JWT / OAuth, Encryption, Password Hashing, OWASP / WAF
8	Architecture Patterns	Monolith, Microservices, Serverless, Event-Driven, CQRS, Saga, Strangler Fig
9	Whole Systems	URL Shortener, News Feed, Chat App + Interview 5-Step Checklist
Project Structure
designsystem/
├── index.html                  ← Home
├── topic-01.html               ← Topic 1
├── topic-02.html               ← Topic 2
├── topic-03.html               ← Topic 3
├── topic-04.html               ← Topic 4
├── topic-05.html               ← Topic 5
├── topic-06.html               ← Topic 6
├── topic-07.html               ← Topic 7
├── topic-08.html               ← Topic 8
├── topic-09.html               ← Topic 9
├── assets/
│   ├── style.css
│   └── app.js
├── .gitignore
├── .nojekyll
└── README.md
Local la kasa chalvaycha?
Node / server / database lagat nahi — fakt static HTML aahe.

# Sopa marg — Python
python3 -m http.server 8000

# Mag browser madhe:
# http://localhost:8000
Ki fakt index.html file var double-click karun pan ughdel.

GitHub var Push kasa karaycha?
git add .
git commit -m "update system design site"
git push origin main
Branch main aahe, master nahi.
Warning LF will be replaced by CRLF — ha error nahi, Windows var normal aahe.

Deploy — Vercel (Recommended)
vercel.com → Log in with GitHub
Add New → Project → OmDoke/designsystem → Import
Kahihi badlu naka:
Framework Preset: Other
Build Command: (rikama)
Output Directory: ./
Deploy daba
Link milel: https://designsystem-....vercel.app

Pudhcha veli badal kelas tar fakt push kara — Vercel aapoaap navin version live karel.

Deploy — GitHub Pages (Alternative)
GitHub Repo → Settings → Pages
Source: Deploy from a branch
Branch: main → Folder: / (root) → Save
Link: https://OmDoke.github.io/designsystem/
Cross-Verified Facts
Online check karun ghetlele, chukicha kahi nahi:

RAM ~100 ns • SSD random read ~100 µs • Same-DC network ~0.5 ms • HDD seek ~10 ms
CAP: Distributed system fakt 2/3 properties guarantee karu shakto — Partition talta yet nahi, mhanun khara choice CP vs AP aste
Cache-Aside: Cache → Miss → DB → Cache set; Write: DB update + Cache delete
Sharding: hash(key) % shards
Replication: Primary var Write, Replica var Read
Retry: Exponential Backoff + Jitter — Jitter nashivay Retry Storm hoto
Password: bcrypt / Argon2 + Salt — kadhihi plain madhe nahi
Code he concept samjnyasathi simplified aahe — production-ready auth / error-handling nahi.

Testing
 Saglya 9 pages che links check — sagle ughadtat
 Diagram buttons → info badalto
 Traffic Simulator + Shard Demo + Napkin Calculator chalto
 Mobile var grid 1-column hoto
 Offline pan chalto — baherchi image / backend nahi
Pudhcha Plan
 Topic-wise PDF notes
 Interview questions per topic
 Dark mode
Banavla: OmDoke • Language: Marathi + English Tech Words • Stack: HTML / CSS / JS

