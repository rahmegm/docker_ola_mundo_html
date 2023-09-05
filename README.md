# Como acessar o container do Github
1. clonar o repositório para o desktop
```sh
https://github.com/rahmegm/docker_ola_mundo_html.git
```
2. se estiver na PUC abrir o docker desktop para instalar o daemon
3. aceitar os termos do docker desktop e esperar o daemon ser instalado
4. abrir o cmd
   digitar
   ```sh
   cd desktop
   ```
5. dentro do desktop no cmd
   digitar
   ```sh
   cd docker_ola_mundo_html
    ```
6. dentro da pasta docker_ola_mundo_html no cmd
   digitar
   ```sh
   cd custom-container
   ```
7. dentro da pasta custom-container no cmd
    digitar
    ```sh
    docker build -t ola_mundo .
    ```
8. digite no cmd
     ```sh
     docker images
    ```
    para visualizar o id da imagem
9. digite no cmd
    ```sh
    docker run -d -p 8082:80 |id imagem|
    ```
   substituindo |id imagem| pelo id observado no passo 8
10. digite no browser
    ```sh
    localhost:8082
    ```
    para observar a página html
# Para fechar o container
1. digite no cmd
   ```sh
   docker ps
   ```
   para visualizar o id do container
2. digite no cmd
   ```sh
   docker stop |id container|
   ```
   substituindo |id container| pelo id observado no passo 1

