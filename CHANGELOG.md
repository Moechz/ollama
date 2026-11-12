# Changelog

All notable user-visible changes to the Ollama TOS application package.

## 0.24.0-1 — 2026-11-12

### Added
- First release. Ollama (`ollama/ollama:0.24.0`, Docker Hub official image, unmodified)
  packaged as a TOS 7 Docker application, published on port 8094 and running
  as a non-root user (1000:1000).
- Persistent data is kept under `/Volume1/DockerAppData/ollamadocker/`.
