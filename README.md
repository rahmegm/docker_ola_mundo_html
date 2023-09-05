# Como acessar o container do Github
1. abrir o Github desktop e clonar o repositório para área de trabalho
2. se estiver na PUC abrir o docker desktop para instalar o daemon
3. aceitar os termos do docker desktop e esperar o daemon ser instalado
4. abrir o cmd digitar cd desktop (para acessar o desktop)
5. dentro do desktop digitar cd docker_ola_mundo_html
6. dentro da pasta docker_ola_mundo_html digitar cd custom-container
7. dentro da pasta custom-container digitar docker build -t ola_mundo .
8. digite docker images para visualizar o id da imagem
9. digite
    ```sh
    docker run -d -p 8082:80 |id imagem| substituindo |id imagem| pelo id observado no passo 8
    ```
11. digite no browser localhost:8082 para observar a página html
# Para fechar o container
1. digite docker ps para visualizar o id do container
2. digite docker stop |id container| substituindo |id container| pelo id observado no passo 2

