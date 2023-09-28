Instalação

```bash
yarn install
make develop
yarn start
```


Gerar o build da imagem do frontend

```bash
sudo docker build . -t veridianobarroso/front-ufac:latest -f Dockerfile
```
```bash
sudo docker image push veridianobarroso/front-ufac
```
