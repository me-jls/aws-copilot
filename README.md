# aws-copilot
Test Aws Copilot Pipeline

Execute :
- create file : `copilot/pgw-github/manifest.yml`
- `copilot svc init -n pgw-github --port 9091 -t "Load Balanced Web Service" -i prom/pushgateway:v1.4.1`
- `copilot svc deploy --name pgw-github`
