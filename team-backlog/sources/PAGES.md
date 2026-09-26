# Source page transcriptions

Verbatim-ish transcriptions from notebook photos. Spelling left as written where ambiguity helps.  
Images live in [`../assets/`](../assets/).

---

## Page 01 — Plan (کمیته فنی + زیر ساخت)

**Image:** `01a0de25-69e1-776b-8be0-3e1e29c76fab.jpg`  
**Same page later:** `01a0de25-6a83-7bec-8ed2-7554960c6b8a.jpg` (more items marked done)

- (Plan) — کمیته فنی + زیر ساخت
- [→] add feature flag capability to go apps — **A**
- **1** Database Disk Full Alert rootcause — **A**
- **1** talk with SRE and ask them to manage mehrdad role and need plan of everyone — **S**
- **10** ceph cluster production ready (why we dont give alert on ntp) — **SD**
  - sync ntp with DC team (switch ntp)
- RESI and yousef hiring
- chang Emails in LDAP (
- **1** Biz Box Domain and Deploy on prod — **D**
- on call votin talk with HR
- roadmap pruper for Reza
- **ⓐ** test ENV plan (I need plan)

---

## Page 02 — Ansible / monitoring / Arvan

**Image:** `01a0de25-6a02-77da-9600-37a7f67bd288.jpg`

- ~~DADP/DAPP node to inventory (Ansible) Auto~~
- ~~KVM server ufw and management network~~ *(struck on some readings)*
- Modify / unify open nebula VM template
- **19** remove unused label on prom job — **s**
- chang victoria metric (?) we need mount data
- Ceph Dashboard SSO
- auto update Arvan IPs
- Block on Arvan pipeline and automation
- remove CI/CD dependency on minio (or clean up)
- Locust load test infrastructure
- Jupyter / Jupiter usage details
- Automate jira Requests
- task on jira

---

## Page 03 — Migrations / Ceph / Sentry

**Image:** `01a0de25-6a24-7b02-a292-4486258294f0.jpg`

- migrat Box_production to prod
- k8s capacity plan Dashboard
- krakend pipelin plan
- Enable Rados gw on ceph and migrate minio
- to that also migrate assets to S3
- remove extra Domain in R1 and Remove Haproxy
- move lama to k8s
- Remove old nexus
- integrat pipline with QA tests
- add password to mongoDB
- Deploy Sentry
- limit Band with on opennebula nic
- Docker Compose on git and change Image

---

## Page 04 — OpenShift / Android / SRE

**Image:** `01a0de25-6a43-7174-b297-e3f342a979c1.jpg`

- Remove openshift Image stream
- Android pipeline Redesign
- Anahita team VM (Airflow)
- offline figma
- Sentry self hosted (Android team)
- Calculate Error budget (SRE)
- CDC All data with new way (DBA)
- what is Biker streaming Issue (which Mehrdad say 60 of Issue)
- send message to B2B Channel Automate (SRE)
- Ajan Alert (semi done)
- DC IP change
- operation team calls
- web app API GW

---

## Page 05 — AI / k8s / Harbor

**Image:** `01a0de25-6a63-735d-b366-f5e2a226f488.jpg`

- ADD AI to piplines
- AI platform for Developer
- migrate grafana to k8s
- make jenkins k8s production ready
- chang Ingres of k8s teh 1 an teh 2
- migrate pipelines runner to k8s
- update plan of infra component
- security pipeline AppSec integration
- change and remove system token from manifest
- B2B Domain Changes
- Host figma on local
- Ubuntu Repo mirror
- think about harbor

---

## Page 06 — Data / SRE / operations

**Image:** `01a0de25-6aa2-7ade-8195-82b1333cff0d.jpg`

- CDC nxp table to clickhouse
- CDC wp Data to clickhouse
- New project for Data team (CF CD, …)
- remove proxy from NATS shipment logs
- remove filebit and use fluentbit if possible
- plan for log from SRE
- operation team migration to teh-2
- SRE change management and change Request flow
- update opennebula Audit logs
- ~~Data team alert~~
- ~~operation migration project~~
- ~~calculate the lost orders~~
- review SRE book
- ~~DNS server for proxy~~ *(or still open — dash mark)*

---

## Page 07 — Planning task for (1403, 5, 17)

**Image:** `01a0de25-6ac2-7e16-ab6a-cd91eaed016a.jpg`

1. **backend task:** Real IP usage — Ratelimit template — pipeline — Configtemp — add Ratelimit to All EP
2. **gitops:** APP chart internal — Stg_napg production — other us — Argo access Document
3. **Infrastructure:** ADD 2 BM — ADD new OSP — throughput net capacity Alert — ADD new BM(11) — one Audit log — failure scenario maneuver
4. **AI HUB:** determine BK provider — gw tools — RAG and memory solution — guard solution
5. **pipeline:** update and tun nexus — gitlab exporter — unify docker pull secret — java native pipeline — multi version golang — front nx mono repo — nxp/nx cli pipeline — shelby pipeline improve — FMS improve pipeline — go trunk base — API pipeline Remove
6. **other:** formbrick production — nexus proxy — All repo inhouse — operation team migration
7. **ingress traffic:** Haproxy deprecate — Edge lb logs structure — toplogs / tcplogs

Bottom:

| Left | Right |
| --- | --- |
| Cloud Issue reports | LDAP Restructure |
| ~~K8S internal Argo~~ | new BM ADD |
| ~~QA panel~~ | BM maintenance |
| ~~Argo Rollout~~ | helm starter |
| ~~Runner terraform~~ | internal NTP |
| ~~Docker compose to git~~ | |

---

## Page 08 — Safety / Nexus / deploy revert

**Image:** `01a0de25-6ae1-7c9d-a2cb-ff0d385f4697.jpg`

- Automatic Revert of new Deploy (Khasky SRE)
- Android cache server on pipeline
- TV wall monitoring
- *Motto:* As you do anything have Always a safety car!
- update hab.snph.app and onboarding doc in Confluence
- fix nexus and nexus proxy
- All thing Registry and repocloud mirror
- terraform runner →
- Remove Old HAproxy
- ~~CA project~~
- incidents weekly email →

---

## Page 09 — Two-column infra list

**Image:** `01a0de25-6b02-7705-9b91-454cb5f622d6.jpg`

| Left | Right |
| --- | --- |
| VM Limit BW | AI Hub |
| Remove old haproxy | Devops Agent |
| Auto inventory update | kvm server ufw |
| Unify terraform module | IDP |
| All Repo in house | mirror maker Alter |
| Redis single | Jenkins Remove pipeline |
| DR site active pass | temp test env |
| upgrade Redis | R1 and CF terra |

---

## Page 10 — HAProxy / alerts / Redis

**Image:** `01a0de25-6b21-7527-b9ff-5db3596d998c.jpg`

- haproxy top logs →
- per city location rate error Alert
- *(numeric note — unclear reference)*
- pino prod to opennebula
- front CI
- haproxy ban traffic pipeline
- haproxy BGP / OCP log
- Haproxy Alert on error
- Api-GW Alert on error
- Hot Reload pipeline insted
- Redis keys Req
- Backend new endpoint APP/ADP flow
- mongo credential
