# projectbeskar.github.io

Beskar7 moved to [github.com/beskar7](https://github.com/beskar7).

`beskar7/index.yaml` keeps `helm repo add beskar7 https://projectbeskar.github.io/beskar7` working for the charts published
before the move (up to 0.12.0); its chart URLs point at the new Helm repository. New charts are published only at
`https://beskar7.github.io/beskar7`:

```bash
helm repo add beskar7 https://beskar7.github.io/beskar7
```
