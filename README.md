<p align="center">
  <img src="docs/banner.svg" alt="k8s-manifests-starter banner" width="100%" />
</p>

<h1 align="center">k8s-manifests-starter</h1>

<p align="center">
  <strong>EN</strong> Example Deployment, Service, and Ingress manifests.<br/>
  <strong>PT</strong> Exemplos de manifests Deployment, Service e Ingress.
</p>

<p align="center">
  <a href="https://github.com/manansbdb/k8s-manifests-starter/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/type-starter-a855f7?style=for-the-badge" alt="starter" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Example Deployment, Service, and Ingress manifests. | Exemplos de manifests Deployment, Service e Ingress. |

```mermaid
flowchart LR
  A["📦 Clone"] --> B["⚙️ Configure"]
  B --> C["🚀 Use in project"]
  style A fill:#a855f7,stroke:#7e22ce,color:#fff
  style B fill:#0ea5e9,stroke:#0369a1,color:#fff
  style C fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone

```bash
git clone https://github.com/manansbdb/k8s-manifests-starter.git
cd k8s-manifests-starter
```

### Use / Usar

```bash
kubectl apply -f manifests/
```

### Requirements / Requisitos

- `git`
- No paid services required / Sem serviços pagos

---

## What's included / O que inclui

| File | EN | PT |
|------|----|----|
| `manifests/deployment.yaml` | App Deployment | Deployment da app |
| `manifests/service.yaml` | ClusterIP Service | Service ClusterIP |
| `manifests/ingress.yaml` | Ingress example | Exemplo de Ingress |

## Usage / Uso

```bash
kubectl apply -f manifests/
```

**EN:** Replace image, host, and labels for your environment.

**PT:** Substitui image, host e labels para o teu ambiente.

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

**Network / Rede:** BTC (Bech32).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
