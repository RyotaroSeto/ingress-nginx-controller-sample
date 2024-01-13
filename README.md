# ingress-nginx-controller-sample

## Kind SetUp
- `kind create cluster --config infra/multi-node.yaml`

## Add ingress-nginx
- `kubectl apply -f infra/nginx.yaml`
- `kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/main/deploy/static/provider/kind/deploy.yaml`
