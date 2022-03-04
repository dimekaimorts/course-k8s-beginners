
# Crear un Pod

- Para poder crear un POD a partir de un archivo de configuracion:

    ```bash
    kubectl create|apply -f pod-definition.yaml
    ```

- Para visualizar la correcta creacion del POD:

    ```bash
    kubectl get pods
    ```

- Para ver mayor detalle del POD:

    ```bash
    #kubectl describe pod <NAME_POD>
    kubectl describe pod myapp-pod
    ```