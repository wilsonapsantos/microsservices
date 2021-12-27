Criação de arquivos YAML:

platforms-depl.yaml
platforms-np-srv.yaml
commands-depl.yaml
ingress-srv.yaml
local-pvc.yaml
mssql-plat-depl.yaml

SQL

comando para criação de credenciais:
kubectl create secret generic mssql --from-literal=SA_PASSWORD="pa55w0rd!"

credenciais do banco SQL

usuario: mssql
senha: pa55w0rd!