# Local_INN_Localization_w_Invertible_Nerual_Network


1. You can use our Dockerfile build and run the container:
    ```
    git clone --recursive git@github.com:zzangupenn/Local_INN.git
    cd Local_INN
    docker build -t local_inn .
    docker run -ti --rm --gpus all --ipc=host --name local_inn
    ```
