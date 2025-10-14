# Next.js — DevOps Assessment

## Includes
- Next.js app
- Dockerfile (multi-stage)
- GitHub Actions CI/CD for GHCR
- Kubernetes manifests (deployment + service)

## Local test
```bash
docker build -t nextjs-app:latest .
docker run -p 3000:3000 nextjs-app:latest
