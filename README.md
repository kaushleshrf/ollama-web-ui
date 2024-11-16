There are 4 .yaml files
backend-ollma.yaml -> yaml to deploy backend of ollama on kubernates cluster - namespace 
backend-service.yaml -> yaml to apply servie -> ClusterIP
ollama-frontend ->  yaml to deploy frontend of ollama on kubernates cluster - namespace 
frontend-service -> yaml to apply servie -> LoadBalancer -> for public issue to access from a webbrowser
