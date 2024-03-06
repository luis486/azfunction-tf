# Proyecto de Infraestructura en Azure con Terraform

Este proyecto utiliza Terraform para aprovisionar y gestionar recursos en la nube de Microsoft Azure.

## Requisitos Previos

1. Tener una cuenta en Azure.
2. Instalar Terraform en tu máquina local. Puedes encontrar instrucciones de instalación en el [sitio web oficial de Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli).
3. Configurar el acceso a tu cuenta de Azure. Puedes hacerlo utilizando la interfaz de línea de comandos de Azure (Azure CLI) con el comando `az login`.

## Configuración del Proyecto

1. Clona este repositorio en tu máquina local:

    ```
    git clone https://github.com/luis486/azfunction-tf.git
    ```

2. Accede al directorio del proyecto:

    ```
    cd proyecto-terraform-azure
    ```


## Inicialización de Terraform

1. Inicializa Terraform en el directorio del proyecto:

    ```
    terraform init
    ```

2. Valida la configuración de Terraform:

    ```
    terraform validate
    ```

## Planificación e Implementación

1. Genera un plan de ejecución de Terraform:

    ```
    terraform plan 
    ```

2. Revisa el plan de ejecución y asegúrate de que estás de acuerdo con los cambios propuestos.

3. Aplica los cambios en tu infraestructura:

    ```
    terraform apply 
    ```

4. Confirma la aplicación de los cambios escribiendo `yes` cuando se te solicite.

