# Instruções

1. No diretório raiz do projeto, executar o comando abaixo para criar o cluster kubernetes no kind: 
- `kind create cluster --config ./kind-cluster.yaml --name multinodes`

2. Rodar os comandos:
- `kubectl apply -f ./mongodb/`
- `kubectl apply -f ./api/`

3. Acessar url:
- `http://localhost:30000/swagger`