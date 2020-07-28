

### Comando para inicializar la solución 

```
mkdir terraform
cd terraform
git clone 
cd wp-terraform
terraform init
cp ~/path/to/your/downloads/aws.pem ./aws.pem
```

### Comando de ejecucion 

```
terraform  plan --out terraform.plan --var-file=./variables.tfvars
terraform apply terraform.plan
```

### Para terminar la ejecucion y eliminarlos recurso creados.

```
terraform destroy
```
