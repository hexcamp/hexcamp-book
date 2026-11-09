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

## Logging

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