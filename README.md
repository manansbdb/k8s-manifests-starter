<p align="center">
  <img src="docs/banner.svg" alt="K8s Manifests Starter banner" width="100%" />
</p>

<h1 align="center">k8s-manifests-starter</h1>

<p align="center">
  <strong>EN</strong> Kubernetes Deployment, Service, and Ingress examples<br/>
  <strong>PT</strong> Exemplos Kubernetes: Deployment, Service e Ingress
</p>

<p align="center">
  <a href="https://github.com/manansbdb/k8s-manifests-starter/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge" alt="Kubernetes" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Starter **Kubernetes manifests**: Deployment, Service, and Ingress YAML. | Manifests **Kubernetes** iniciais: Deployment, Service e Ingress YAML. |
| Copy under `manifests/`, edit names/images, `kubectl apply -f`. | Copia em `manifests/`, edita nomes/imagens, `kubectl apply -f`. |

```mermaid
flowchart LR
  A["📄 manifests/"] --> B["🚀 Deployment"]
  B --> C["🔌 Service"]
  C --> D["🌐 Ingress"]
  style A fill:#326CE5,stroke:#1d4ed8,color:#fff
  style B fill:#9333ea,stroke:#6b21a8,color:#fff
  style C fill:#0ea5e9,stroke:#0369a1,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/k8s-manifests-starter.git
cd k8s-manifests-starter
```

### 2) Copy & apply / Copia e aplica

```bash
mkdir -p /path/to/your-project/k8s
cp manifests/*.yaml /path/to/your-project/k8s/
# edit image, host, names — then:
kubectl apply -f /path/to/your-project/k8s/
```

### Requirements / Requisitos

- `git`
- `kubectl` + a cluster (local kind/minikube are free options)

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/k8s-manifests-starter.git
# edit manifests/*.yaml then: kubectl apply -f manifests/
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `manifests/deployment.yaml` | Deployment example |
| `manifests/service.yaml` | Service example |
| `manifests/ingress.yaml` | Ingress example |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
k8s-manifests-starter/
├── docs/banner.svg
├── manifests/deployment.yaml
├── manifests/service.yaml
├── manifests/ingress.yaml
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
