# Open Backlog

Deduplicated from notebook pages. Spelling normalized; intent preserved.  
See [`sources/`](./sources/) for verbatim transcriptions.

---

## Backend / App platform

- [ ] Real IP usage
- [ ] Rate-limit template + pipeline + config template
- [ ] Add rate-limit to all endpoints
- [ ] Feature-flag capability for Go apps
- [ ] Backend new endpoint / ADP (or APP) flow
- [ ] Web app API gateway
- [ ] Hot-reload pipeline instead (of current approach)
- [ ] Redis keys request / requirements
- [ ] Redis single-instance work
- [ ] Upgrade Redis
- [ ] MongoDB credentials
- [ ] Add password to MongoDB
- [ ] Formbrick production

## GitOps / Kubernetes

- [ ] App chart (internal)
- [ ] Stg_nap → production (GitOps)
- [ ] Argo access documentation
- [ ] k8s capacity plan dashboard
- [ ] Change Ingress of k8s teh-1 and teh-2
- [ ] Make Jenkins on k8s production-ready
- [ ] Migrate pipeline runners to k8s
- [ ] Migrate Grafana to k8s
- [ ] Move Llama to k8s
- [ ] k8s internal Argo *(also listed done on planning page — confirm)*
- [ ] Argo Rollouts *(also listed done on planning page — confirm)*
- [ ] Helm starter

## Infrastructure / Bare metal / OpenNebula

- [ ] Add 2× BM (bare metal)
- [ ] Add new BM (II / 11)
- [ ] Add new OSP
- [ ] BM maintenance
- [ ] Throughput / net capacity alert
- [ ] One audit log (infra)
- [ ] Failure-scenario maneuver
- [ ] Unify OpenNebula VM template
- [ ] Limit bandwidth on OpenNebula NIC / VM limit BW
- [ ] Update OpenNebula audit logs
- [ ] Pino prod → OpenNebula
- [ ] KVM server UFW + management network
- [ ] Auto inventory update (Ansible) — DADP/DAPP node
- [ ] DR site active/passive
- [ ] DC IP change
- [ ] Operation team migration to teh-2
- [ ] Internal NTP
- [ ] Sync NTP with DC team (switch NTP)
- [ ] Ceph cluster production-ready (incl. NTP alerts)
- [ ] Ceph Dashboard SSO
- [ ] Enable RadosGW on Ceph and migrate MinIO
- [ ] Also migrate assets to S3
- [ ] Ubuntu repo mirror
- [ ] Think about Harbor (registry)
- [ ] All registries + repo / cloud mirror
- [ ] DNS server for proxy *(struck on one page — confirm)*

## Edge / HAProxy / Ingress traffic

- [ ] HAProxy deprecate
- [ ] Remove old HAProxy
- [ ] Remove extra domain in R1 and remove HAProxy
- [ ] Edge LB logs structure
- [ ] TCP logs / HAProxy top logs
- [ ] HAProxy ban-traffic pipeline
- [ ] HAProxy BGP (or OCP) log
- [ ] HAProxy alert on error
- [ ] API-GW alert on error
- [ ] Per-city / location rate-error alert
- [ ] B2B domain changes
- [ ] Biz Box domain + deploy on prod *(marked done on Plan page — confirm if still needed)*

## Pipelines / CI-CD / Registries

- [ ] Update and tune/run Nexus
- [ ] Fix Nexus and Nexus proxy
- [ ] Nexus proxy
- [ ] Remove old Nexus
- [ ] GitLab exporter
- [ ] Unify Docker pull secret
- [ ] Java native pipeline
- [ ] Multi-version Golang pipeline
- [ ] Front nx monorepo / nx CI pipeline
- [ ] Shelby pipeline improve
- [ ] FMS improve pipeline
- [ ] Go trunk-based
- [ ] API pipeline remove
- [ ] Android pipeline redesign
- [ ] Android cache server on pipeline
- [ ] Front CI
- [ ] Security pipeline / AppSec integration
- [ ] Integrate pipeline with QA tests
- [ ] Remove CI/CD dependency on MinIO (or clean up)
- [ ] Block on Arvan pipeline and automation
- [ ] Auto-update Arvan IPs
- [ ] Add AI to pipelines
- [ ] Change and remove system token from manifests
- [ ] Remove OpenShift image stream
- [ ] Jenkins — remove pipeline
- [ ] Docker Compose on git + change image
- [ ] Automatic revert of new deploy (Khasky / related SRE)
- [ ] All repos in-house

## Observability / SRE / Ops

- [ ] Remove unused label on Prometheus job (~19)
- [ ] Change VictoriaMetrics — need to mount data
- [ ] Locust load-test infrastructure
- [ ] Jupyter usage details
- [ ] TV wall monitoring
- [ ] Calculate error budget (SRE)
- [ ] Plan for logs from SRE
- [ ] Ajan alert (semi done)
- [ ] Database disk-full alert — root cause *(marked done on Plan — confirm)*
- [ ] Send message to B2B channel — automate (SRE)
- [ ] Incidents weekly email
- [ ] Cloud issue reports
- [ ] Update plan of infra components
- [ ] Review SRE book
- [ ] SRE change management + change-request flow
- [ ] Operation team calls
- [ ] QA panel *(struck on planning page — confirm)*

## Data / CDC / Messaging

- [ ] CDC nxp table → ClickHouse
- [ ] CDC wp data → ClickHouse
- [ ] CDC all data with new way (DBA)
- [ ] New project for Data team (CF CD / CFCD, …)
- [ ] Remove proxy from NATS shipment logs
- [ ] Remove Filebeat; use Fluent Bit if possible
- [ ] What is Biker streaming issue (Mehrdad: ~60 of issue)
- [ ] MirrorMaker alter
- [ ] Calculate the lost orders *(struck — confirm)*
- [ ] Data team alert *(struck — confirm)*

## AI Hub / Developer platform

- [ ] AI platform for developers
- [ ] AI Hub — determine BK provider
- [ ] AI Hub — gateway tools
- [ ] AI Hub — RAG and memory solution
- [ ] AI Hub — guard solution
- [ ] AI Hub (general)
- [ ] DevOps Agent
- [ ] IDP (Internal Developer Platform)
- [ ] Anahita team VM (Airflow)

## Identity / Access / Docs

- [ ] LDAP restructure
- [ ] Change emails in LDAP *(marked done on Plan — confirm)*
- [ ] Host Figma on local / offline Figma
- [ ] Update hab.snph.app and onboarding doc in Confluence
- [ ] Sentry self-hosted (Android team)
- [ ] Deploy Sentry
- [ ] Migrate Box_production → prod
- [ ] KrakenD pipeline plan
- [ ] R1 and CF Terraform
- [ ] Unify Terraform modules
- [ ] Terraform / Runner Terraform
- [ ] Temp test env
- [ ] Test ENV plan *(explicit: “I need plan”)*

## People / process

- [ ] Talk with SRE — manage Mehrdad role; need plan of everyone *(marked done on Plan — confirm)*
- [ ] RESI / ESI and Yousef hiring *(marked done on Plan — confirm)*
- [ ] On-call voting — talk with HR *(marked done on Plan — confirm)*
- [ ] Proper roadmap for Reza *(marked done on Plan — confirm)*
- [ ] Automate Jira requests
- [ ] Task on Jira

## Notes / mottos from notebook

- “As you do anything have always a safety car!”
- Planning page date: **1403-05-17**
