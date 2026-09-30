# CodingDatafy

> **On a mission to build the world's largest reference and knowledge base for coding.**

---

### About CodingDatafy
**CodingDatafy** is an open-source organization dedicated to mapping the programming landscape with ultimate precision and structural clarity. We adopt a **highly-structured data approach** to technical writing, ensuring that developers worldwide have access to a comprehensive, version-controlled knowledge base.

### Architecture & Tech Stack
Our ecosystem is engineered as a decoupled, zero-dependency architecture designed for sub-millisecond edge rendering, maximum cost efficiency, and global performance:

* **Core Engine:** Native [Cloudflare Workers](https://workers.cloudflare.com/) built with **Pure TypeScript** (Native `workerd` runtime, zero external framework dependencies).
* **Storage & Content:** [Cloudflare R2](https://www.cloudflare.com/developer-platform/r2/) object storage hosting markdown documentation synced via automated CI/CD workflows.
* **Edge & Infrastructure:** Deployed via **Wrangler CLI** in GitHub Actions across [Cloudflare's Global Edge Network](https://www.cloudflare.com/) with edge caching and custom security headers.

### Ecosystem Repositories
To maintain clean operational separation and zero vendor lock-in, our architecture is split into targeted hubs:
* **[`.github`](https://github.com/codingdatafy/.github):** Organization profile, global configurations, and health files.
* **[`centroidium`](https://github.com/codingdatafy/centroidium):** The high-performance Cloudflare Worker engine and rendering core.
* **[`content`](https://github.com/codingdatafy/content):** The raw markdown documentation repository synced directly to Cloudflare R2.

---

### Global Contributions
We operate with the strict discipline of a global engineering team. Every commit is linked to a specific issue, and every issue tracks back to an active project roadmap.

* **Branch Strategy:** We protect production integrity using a protected `main` branch with automated path-based deployments and static validation tests in GitHub Actions.
* **Commit Standard:** Strict Conventional Commits (`<type>(<scope>): <description> #issuenumber`).
* **Become a Contributor:** Read our comprehensive workflow rules on the [Contribute Page](https://www.codingdatafy.com/contribute).
* **Report or Suggest:** Found a syntax error or want to map a new language? Open a [Formal Issue](https://github.com/codingdatafy/content/issues).

### Licensing
To guarantee open access to information while guarding core engineering efforts, we apply a strict dual-licensing policy:
* **Software & Tooling (`centroidium`):** Licensed under the permissive [MIT License](https://github.com/codingdatafy/.github/blob/main/LICENSE).
* **Technical Content (`content`):** All documentation and structural data files follow the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) international license.

---

<p align="center">
  <a href="https://www.codingdatafy.com">Official Website</a> • 
  <a href="https://x.com/codingdatafy">Twitter/X</a> • 
  <a href="https://github.com/orgs/codingdatafy/projects">Organization Roadmap</a>
</p>