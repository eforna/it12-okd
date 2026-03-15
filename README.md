# it12-okd

Fitxers de configuració del servidor OKD (IT12-OKD, 192.168.2.4).

Conté els manifests Kubernetes/OKD, scripts d'instal·lació i configuracions
del sistema que s'apliquen directament al servidor.

## Estructura

```
it12-okd/
├── manifests/       ← YAMLs de desplegament (Deployments, Routes, PVCs...)
├── scripts/         ← scripts d'instal·lació i manteniment OKD
└── config/          ← configuracions del sistema (xarxa, DNS...)
```

## Documentació

Consulta el repo [okd-lab-doc](https://github.com/efornaguera/okd-lab-doc)
per a guies pas a pas, notes d'instal·lació i resolució d'errors.
