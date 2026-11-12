# Ideas

Ideas for future improvements and development.

Not in any particular order.

## Documentation

* Publish book on VanHex
* Document how to setup GitHub Actions to publish

## Raspberry Pi prototype

* Document hardware setup
* Wireguard
* Raspbian modifications
* Kubernetes
* VanHex publishing pipeline
* VanHex IPFS Cluster

## Hexagon ID Tool

* Improve base map

## Community database

* Store community footprints
* Hierarchy of communities and sub-communities
* Hexagon ID to community lookup
* API

## Publishing Improvments

* Ability to watch progress of publishing pipeline

## VanHex News Experiments

* Switch to custom feed instead of using Graze
* Resume archiving of curated news
* Use curated feed to autogenerate a new static website
* Cross-reference locations in articles using NLP, migrate WACZ archives to nearby hexagons

## Add UI to static web pages

* Shows where hexagon address is on map
* Shows health information for infrastructure
* Provides access to credentials wallet (login/logout feature)
* Discoverability for other locally published websites and data

## Static Website publishing

* provide a Neocities style experience for self-publishing
* markdown-editor (replace HackMD) ... possibly with Automerge
* investigate ATProto publishing solutions

## Privacy

* research crypto-first solutions for providing apps (eg. PeerGOS, CryptPad)

## Search

* local search for archived news
* search for new areas
* auto-download and archive from Common Crawl

## Wikipedia

* query local Wikipedia articles and archive

## AI

* experiment with Ollama, OpenWebUI, OpenCode and [RAG](https://docs.openwebui.com/features/chat-conversations/rag/)
* see if some parts of [qipu-vancouver](https://github.com/AbstractsMachine/qipu-vancouver) can be duplicated using data on VanHex and local LLMs

## Backups

* Use [Velero](https://velero.io/) and possibly [Minio](https://www.min.io/) to archive to the IPFS Cluster
* Monitoring for IPFS Cluster disk space
* Pruning IPFS Cluster history

## Monitoring

* Figure out how to publish static snapshots of the Grafana charts for public use

## Logging and Observability

* Investigate ways of exposing and saving logs from within Kubernetes
* Possibly OpenTelemetry too

## WASM

* investigate how to use WASM in the publishing pipeline (in conjunction with Knative)

## git repos

* possibly tangled knots?

## docker repos

* self-host docker images so pulls don't come across the internet

## Communities

### VanHex

* collect vector tiles from OpenStreetMap (prototyped on VicHex photos demo)

### CDMXHex

* Publish Jupyter notebook with neighbourhood names

### PeerHex

* emea.peerhex.org
* asia.peerhex.org

### New communities

* Toronto
* Montreal
* London
* Paris
* Munich
* Austin
* Philadelphia

### Privacy

* use EFF Privacy Badger and remove CDN links from mkdocs generated sites
* replace Graze.Social embed that has Google links

### Bring-Your-Own-Domain-Name

For Neocities-style self-publishing, many people won't want to use the Hexagon ID DNS names, and would prefer to have a human-friendly name instead.

We could build a system where people could bring their own domain names. Also, it might be possible to share domain names and have crowd funding mechanisms in place to pay for the annual domain name fees.

For example, we could start with yvr.whims.io as an option for VanHex (already in use for the AT Proto PDS), and people could have a website name such as my-web-site.yvr.whims.io. This would be in addition to having a hexagon-id style name such as 6kg6rvgjqguq.vanhex.ca.

# Search

* make Stract search engine backends persist data to disk so that it can "scale to zero" using Knative

# Jupyter Notebooks

* make it so that client-side hosted notebooks can publish

# Contact Manager

* investigate how to use private data to maintain lists of people (possibly using ATProto)

# Identity

* investigate how to make client-side wallets that sync
* unlock using Passkeys
* integrate with secrets management (OpenBao?)

# Endowments

* look at using Ethereum and StableCoins to setup small endowments that can be funded to save up for things like domain name fees and cloud hosting expenses per community
* text-based accounting
* possibly use OpenCollective for larger communities

# Discovery

* service discovery to find publishing endpoints