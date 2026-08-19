# Alexandru-Marian Galea

Full stack engineer · AI / computer vision. I build video and image analytics products
end-to-end — React and Django/DRF on the product side, PyTorch and SAM-family models on the
vision side. M.Sc. in Artificial Intelligence.

## Publications

- **The Fourth Visual Object Tracking Segmentation VOTS2026 Challenge Results** —
  M. Kristan, J. Matas, P. Tokmakov et al. (incl. A.-M. Galea), *ECCV 2026 Workshops*, 2026.
  [OpenReview](https://openreview.net/forum?id=zGOan36xpF)
  <br>Co-authorship earned through six sole-author tracker entries in the main sub-challenge; all
  six exceeded the results-paper baseline.
- **Automatic Detection of Chromatic Components in Images** — A.-M. Galea, B. Sebacher,
  *Journal of Military Technology*, vol. 8, no. 2, pp. 5–12, Dec. 2025.
  [DOI: 10.32754/JMT.2025.2.01](https://doi.org/10.32754/JMT.2025.2.01)
  <br>First author. Developed from my M.Sc. dissertation; the colour-extraction methodology was
  subsequently integrated into a production video-analytics platform.
- **Automatic Detection of Objects Chromatic Components in Images** — A.-M. Galea, B. Sebacher,
  S. Marzavan, *ISIM & ISWIM 2024*, University Politehnica of Bucharest, Jun. 2024.
  Book of Abstracts vol. III, ISSN-L 2821-8779.

## Selected work

**[dam4sam-vots2026](https://github.com/alexxgalea/dam4sam-vots2026)** — six training-free
trackers extending DAM4SAM on SAM 2.1 and SAM 3 backbones, entered in the VOTS2026 challenge.
All six beat the results-paper baseline; the best ranked **9th of 25** (Q=0.639), above the
committee's own DAM4SAM entry, via backbone scaling and full-dataset runs on preemptible cloud
GPUs. A post-challenge knock-out ablation, scored on the sequestered evaluation set, then showed
that the motion module these trackers were designed around **never executed**: removing the entire
motion pathway leaves the output masks byte-identical on all 375 target-sequences, and the measured
gain belongs to a bounded memory window that had been added for unrelated engineering reasons.
Both halves are documented, with the verification script that separates *"contributes nothing"*
from *"never ran"*.

**[oaktimize](https://github.com/alexxgalea/oaktimize)** — class-scheduling platform for sports
studios: scheduling, subscriptions and participant management, with a Celery + Redis alerting
pipeline whose retry/backoff semantics are covered by regression tests. Django + DRF, React (Vite),
Keycloak SSO, full Docker stack behind Traefik, CI with linting and deploy checks, mobile packaging
via Capacitor.

**[ProductManagement](https://github.com/alexxgalea/ProductManagement)** — event-driven restaurant
inventory platform: order ingestion from Glovo/Bolt/Wolt over HMAC-signed webhooks, three-layer
idempotency, recipe-based stock deduction against an immutable inventory ledger.
Django, Celery/RabbitMQ, PostgreSQL.

## Tech

**Python** (PyTorch, Django/DRF, Celery) · **JavaScript/TypeScript** (React, Vite, TanStack Query)
· PostgreSQL · Elasticsearch/OpenSearch · Docker & Docker Swarm · Keycloak (OIDC) · Traefik

## Contact

📫 alexandru.galea2000@gmail.com · [LinkedIn](https://www.linkedin.com/in/alexandru-galea)
