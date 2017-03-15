```bash
agostinho@lisbon:~$ whoami
```

# Agostinho Pina Ramos

**Software & platform engineer** · Lisbon, Portugal

[![GitHub](https://img.shields.io/badge/GitHub-agostinhoramos-181717?style=flat&logo=github)](https://github.com/agostinhoramos)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-agostinhoramos-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/agostinhoramos)
[![Medium](https://img.shields.io/badge/Medium-@agostinhoramos-000000?style=flat&logo=medium)](https://agostinhoramos.medium.com/)

```bash
agostinho@lisbon:~$ cat /etc/profile.d/modules.sh
export modules=(devops platform backend fullstack integrations research)
```

```bash
agostinho@lisbon:~$ cat /etc/motd
```

Engineer across production backends, CI/CD (Jenkins, SonarQube, Octopus Deploy), Docker/Linux platforms, Redis, Grafana and AWS. Data work spans PostgreSQL, MongoDB and messaging stacks; side products [NewGus](https://newgus.com/) and [hiDishe](https://www.hidishe.com/) ship containerised previews and Debian/Nginx deployments. Published IoT and indoor-tracking research from classroom evaluations.

```bash
agostinho@lisbon:~$ cat ~/stack/docker-compose.yml
```

```yaml
# excerpt — full stack manifest
services:
  cloud:
    - AWS, Amazon S3, Linux, Kubernetes, Docker, Docker Compose, Nginx
  data:
    - PostgreSQL, MongoDB, MySQL, SQL Server, Oracle SQL, SQL
    - Redis, RabbitMQ, Kafka, Apache Superset, Celery, MQTT
  delivery:
    - Git, CI/CD, Jenkins, Octopus Deploy, SonarQube, microservices, REST API
    - monitoring, Grafana, Node-RED, Shell script
  build:
    - Java, Python, Node.js, Flask, Django, DRF, Laravel
    - ASP.NET, ASP.NET MVC, JavaScript, PHP, C#, C/C++, Perl
    - Next.js, Tailwind CSS, Android Studio
```

```bash
agostinho@lisbon:~$ journalctl --user -n 4 --no-pager
```

- **CI/CD & quality:** Parallel Docker builds, secure secrets, SonarQube coverage gates.
- **Performance:** Redis caching and MongoDB query tuning for legacy APIs.
- **Reliability:** Scheduling re-architecture with strict temporal validation.
- **IoT & edge:** Docker on Linux, TLS, S3; sensor pipelines and field deployments.

```bash
agostinho@lisbon:~$ systemctl status --no-pager
```

| Unit | State | Description |
|------|-------|-------------|
| `newgus.service` | **active (running)** | On-demand Docker previews (WordPress, .NET, Django, Laravel, Next.js, Node, PHP, Python, React, Go) — [newgus.com](https://newgus.com/) |
| `hidishe.service` | **active (running)** | Dish recommendations; Jenkins + Octopus on Debian/Nginx — [hidishe.com](https://www.hidishe.com/) |
| `liptracker.service` | **active (exited)** | Indoor presence (RSSI, Kalman filter); ~95% detection in classroom evaluation |
| `djnext.service` | **enabled** | Django + Next.js boilerplate — [github.com/agostinhoramos/djnext](https://github.com/agostinhoramos/djnext) |
| `airva.service` | **enabled** | Embedded / C++ — [github.com/agostinhoramos/airva](https://github.com/agostinhoramos/airva) |
| `raspiwifirepeater.service` | **enabled** | Wi‑Fi repeater on Raspberry Pi — [github.com/agostinhoramos/raspiwifirepeater](https://github.com/agostinhoramos/raspiwifirepeater) |

```bash
agostinho@lisbon:~$ man liptracker 2>/dev/null | head -3
```

- **LIPTracker (2023–2024)** — People detection and classroom evaluation (~95% detection with Kalman-filtered RSSI).
- **Indoor air quality & occupancy (2023)** — IoT sensors to cloud analytics in authentic classroom settings.

```bash
agostinho@lisbon:~$ cat /etc/os-release
```

```
NAME="Computer Science & Engineering"
VERSION_ID=2024-msc
PRETTY_NAME="MSc — Polytechnic Institute of Guarda"
VARIANT_ID=bsc-2017-2021
VARIANT="Exchange — Politechnika Lubelska, Lublin (2019)"
```

```bash
agostinho@lisbon:~$ locale
```

| Variable | Value |
|----------|-------|
| `LANG` | Portuguese (native) |
| `LC_MESSAGES` | English (CEFR B2) |

```bash
agostinho@lisbon:~$ gh api user --jq .login 2>/dev/null || echo agostinhoramos
```

<img src="https://github-readme-stats.vercel.app/api?username=agostinhoramos&show_icons=true&theme=dark&hide_border=true&include_all_commits=true" alt="GitHub stats" height="165" />

> Arctic Code Vault Contributor — code preserved in the GitHub Arctic Code Vault programme.

```bash
agostinho@lisbon:~$ █
```
