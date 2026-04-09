# FlagBridge Helm Charts

Official Kubernetes Helm charts for deploying [FlagBridge](https://github.com/flagbridge/flagbridge).

## Usage

```bash
helm repo add flagbridge https://flagbridge.github.io/helm-charts
helm repo update

helm install flagbridge flagbridge/flagbridge
```

## Charts

| Chart | Description |
|-------|-------------|
| `flagbridge` | FlagBridge API + PostgreSQL deployment |

The admin dashboard is deployed separately (Vercel) and is not included in this chart.

## Configuration

See [values.yaml](charts/flagbridge/values.yaml) for all available configuration options.

## Documentation

Full docs at [flagbridge.io/docs/guides/kubernetes](https://flagbridge.io/docs/guides/kubernetes)

## License

Apache 2.0
