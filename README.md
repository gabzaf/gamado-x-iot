# gamado-x-iot

GitOps source for part 3 of [Inception-of-Things](https://github.com/gabzaf/Inception-of-Things). Argo CD syncs `manifests/` into the `dev` namespace.

- `manifests/deployment.yaml`: `wil42/playground`, port 8888
- `manifests/service.yaml`: Service on port 8888

Change the version by switching the image tag (`v1` ↔ `v2`) and pushing to `main`.
