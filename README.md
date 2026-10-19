# Nguyen Vu Truong Phuc

**Backend and data developer.** .NET APIs, Python data pipelines, and the Docker
stack underneath them.

---

## About me

I am a second-year Computer Science student in Ho Chi Minh City, and the
co-founder of **VANG LAI**, a community sports platform — .NET 10 / ASP.NET Core
on PostgreSQL and Redis, Blazor Server web and admin, Expo / React Native mobile,
Docker Compose and Traefik.

On VANG LAI I review and merge the code that goes into the main branch, and I ran
the security and correctness pass: moving the admin token out of
`sessionStorage` into an HttpOnly cookie, adding auth guards to the Blazor admin,
removing a broken access-token gate that was bouncing signed-in users, making the
health checks surface the real provider error instead of a generic failure, and
bringing status colours up to WCAG AA.

The projects below are mine alone. They taught me the part tutorials skip: real
data arrives broken, and the job is to notice. In the job-market pipeline every
posting declared its currency as USD, including the ones whose text read *14 – 16
million VND/month*. An early version keyed on each posting's trailing number,
which turned out not to be unique and silently dropped about fifty jobs. Finding
that mattered more than any chart I drew afterwards.

I write things down. Every repository here explains what was decided and why, so
the next person — often me, three months later — does not have to guess.

Educated in English for twelve years, so I work comfortably with English-speaking
teams and clients.

---

## Data analysis

| Project | What it does | Stack |
|---|---|---|
| **[vn-it-job-market](https://github.com/pn849222-hub/vn-it-job-market)** | Collects 672 live job postings and finds what Vietnamese IT employers actually ask for — 73% never name a salary, English outranks every technology | Python, SQLite, matplotlib |
| [sales-data-analysis](https://github.com/pn849222-hub/sales-data-analysis) | EDA on 9,994 retail orders: category profit, regional mix, discount losses, YoY growth | Python, pandas, matplotlib |
| [sql-query-portfolio](https://github.com/pn849222-hub/sql-query-portfolio) | 10 business queries, basic aggregation through a region × category matrix | SQL, SQLite, pandas |
| [powerbi-dashboard](https://github.com/pn849222-hub/powerbi-dashboard) | Interactive sales dashboard: KPI cards, trend line, category and region breakdown | Power BI Desktop |
| [vietnam-stock-analysis](https://github.com/pn849222-hub/vietnam-stock-analysis) | VN-Index 2020–2024: price trend, volatility, trading volume | Python, vnstock |
| [vietnam-market-brief](https://github.com/pn849222-hub/vietnam-market-brief) | Did five large HOSE stocks beat the VN30 ETF, 2024–2026? Stitches unadjusted dividend gaps the price feed leaves in | Python, pandas, matplotlib |
| [auto-report-generator](https://github.com/pn849222-hub/auto-report-generator) | Generates a formatted PDF sales report from raw CSV, charts included | Python, fpdf2 |

## Backend and infrastructure

| Project | What it does | Stack |
|---|---|---|
| **[job-market-api](https://github.com/pn849222-hub/job-market-api)** | REST API serving the job market dataset: filtering, paging, split health probes, Swagger, 11 tests, non-root container | C#, ASP.NET Core, Dapper, Docker |
| [nginx-docker-ssl-sample](https://github.com/pn849222-hub/nginx-docker-ssl-sample) | Static app behind Nginx with HTTP to HTTPS redirect, built as a practice stack | Docker Compose, Nginx, TLS |
| [it-support-portfolio](https://github.com/pn849222-hub/it-support-portfolio) | One-page portfolio covering servers, networking, and virtualization work | HTML, CSS, JS |

---

## Toolbox

**Backend** C# / .NET 10 · ASP.NET Core · Minimal APIs · EF Core · Dapper · REST API design
**Data** Python (pandas, matplotlib) · SQL · PostgreSQL · SQLite · Redis · Power BI
**Frontend** Blazor Server · React Native / Expo · HTML, CSS, JS
**Infrastructure** Docker · Docker Compose · Traefik · Nginx · MinIO · Linux / Ubuntu · Proxmox VE
**Network** VLAN, DHCP, NAT, firewall, DNS · MikroTik · SSH, Tailscale
**Testing** xUnit · pytest · end-to-end

---

## How I work

Understand the problem first. Change only what needs changing. Test the result.
Write down what was done so the next person does not have to guess.

---

**Available for freelance work** — backend APIs, data pipelines, dashboards, automation.
📧 pn849222@gmail.com
