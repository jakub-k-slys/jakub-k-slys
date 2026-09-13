# 👋 Hi, I'm Jakub Slys

**Backend engineer, 15+ years** in high-performance distributed systems — Cassandra at
scale, Kafka/Flink pipelines, and the cloud-native platforms underneath them.

These days I build **MCP servers and Kubernetes operators**, and write about the failure
modes that only show up in production.

📫 **Email**: [jakub@slys.dev](mailto:jakub@slys.dev)  
🌐 **Website**: [iam.slys.dev](https://iam.slys.dev)

---

## 🚀 Projects

### Substack

A client library, a gateway, and the n8n nodes that sit on top of them.

| Project | | |
|---|---|---|
| [**substack-api**](https://github.com/jakub-k-slys/substack-api) | TypeScript | An entity-based client for the Substack API — publications, posts, comments, profiles. |
| [**substack-gateway-oss**](https://github.com/jakub-k-slys/substack-gateway-oss) | Python | A stateless gateway exposing Substack as **both a REST API and an MCP server**, so the same surface serves scripts and AI agents alike. Extensible through installable capabilities. |
| [**n8n-nodes-substack**](https://github.com/jakub-k-slys/n8n-nodes-substack) | TypeScript | Community n8n nodes for newsletter automation, built directly on `substack-api`. |
| [**n8n-nodes-substack-new**](https://github.com/jakub-k-slys/n8n-nodes-substack-new) | TypeScript | The same idea rebuilt against **Substack Gateway** instead of the client library — the node stops owning API details and talks to a service that already does. |

### n8n on Kubernetes

Two takes on the same operator, a rewrite apart.

| Project | | |
|---|---|---|
| [**n8n-operator**](https://github.com/jakub-k-slys/n8n-operator) | Go | The original. Manages a **single n8n instance** per resource. |
| [**n8n-rustful-operator**](https://github.com/jakub-k-slys/n8n-rustful-operator) | Rust | The rewrite, and the one to use. Handles **single instances and clustered deployments**. |

---

## ✍️ Writing

I publish at [**iam.slys.dev**](https://iam.slys.dev) — system design walked through end to
end, machine learning without the hand-waving, and short notes on the engineering lesson
hiding inside one specific failure.

Recent posts:

- *Statistics for humans — Mean, Variance, and the stories they tell*
- *Median of two sorted arrays: the binary search you will rarely need*
- *Pastebin at scale: lessons from GitHub Gist and Bitly*

---

## 🧠 Tech Stack

### 🛠 Languages  
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2b%2b&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)

### 📦 Infrastructure & Cloud  
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat&logo=istio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat&logo=terraform&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)

### 💾 Databases & Streaming  
![Cassandra](https://img.shields.io/badge/Apache%20Cassandra-1287B1?style=flat&logo=apache-cassandra&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![Flink](https://img.shields.io/badge/Apache%20Flink-E6526F?style=flat&logo=apache-flink&logoColor=white)

---

## 🧭 Currently

Running a homelab Kubernetes cluster as a real platform — ambient service mesh, OIDC end
to end, declarative Postgres, secrets out of Vault — because the interesting problems only
turn up once something is actually in production.

Also: distributed stream processing with Kafka/Flink, low-latency data systems, and
Model Context Protocol as a first-class integration surface.

---

## 👨‍👦 Also...

Learning to be a dad — by far the most complex multi-threaded system I've encountered.

---

> _"Removing the central node doesn't remove the load — it spreads it across every link you forgot was shared."_
