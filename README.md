# aws-copilot
Test Aws Copilot Pipeline

Execute :
- create file : `copilot/helloworld/manifest.yml`
- `copilot svc init --name helloworld -t "Load Balanced Web Service" -d ./services/helloworld/Dockerfile --port 5000`
- `copilot svc deploy --name helloworld`
