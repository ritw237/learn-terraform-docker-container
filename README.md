# learn-terraform-docker-container

## Provisioned nginx server in docker using terraform

After writing the main.tf file, execute these commands in terminal:

1) `terraform init`


This is to initialize the project, it downloads a plugin that allows Terraform to interact with Docker

2) `terraform apply`

Provision NGINX server container with `apply` command . When Terraform asks you "Enter a value": Type `yes` and press ENTER

3) Now if you run `docker ps` command you will see your nginx container

4) Visit localhost:8000 on your web browser to see whether your server is up and running

## Result:

localhost:8000 works!

<img width="818" alt="image" src="https://user-images.githubusercontent.com/58885463/175804808-c9bb3023-9cc2-4adf-aaa2-04b7efc5365a.png">

## Stopping container

`terraform destroy` command to destroy your NGINX webserver.
