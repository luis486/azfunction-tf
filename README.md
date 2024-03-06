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



#Evidencias

1. Terraform Plan
   ![image](https://github.com/luis486/azfunction-tf/assets/71047563/a13b8c7c-8cea-4bf2-a406-626b31e61139)
2. Terraform Apply
   ![image](https://github.com/luis486/azfunction-tf/assets/71047563/3733ce04-8ea9-46f3-9906-33823f905a8e)
3. Recursos Creados
   ![image](https://github.com/luis486/azfunction-tf/assets/71047563/083ca137-7546-4d3b-a29f-d91637eab667)
4. Funciona!
   ![image](https://github.com/luis486/azfunction-tf/assets/71047563/6711fb4c-aec5-4727-af53-fbf188ca8f97)


