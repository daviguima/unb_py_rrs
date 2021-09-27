# Sobre este repositório
Scripts em python para apoio à disciplina de monitoramento por drones e satélites da qualidade da água de rios e reservatórios na UnB.

Se você não é familiarizado com a utilização de notebooks [Jupyter](https://jupyterlab.readthedocs.io/en/stable/), a instalação do pacote [Anaconda](https://www.anaconda.com/products/individual) é fortemente recomendada.

Se você não tiver nenhuma experiência anterior com Python, siga os procedimentos abaixo, caso contrário basta clonar o repositório e usar os scripts do arquivo `trabalho_disciplina.ipynb`.

Instalar o pacote Anaconda seguindo as instruções do site através do link:
[https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual)
<br><br>
Criar um ambiente virtual Python:
```
conda create --name unb 
```
Ativar o ambiente virtual:
```
conda activate unb 
```
Instalar as dependências do projeto:
```
conda install -c anaconda pandas
conda install -c anaconda numpy
conda install -c anaconda matplotlib
```
Por último, instalar o Jupyter Lab no mesmo ambiente:
```
conda install -c conda-forge jupyterlab
```
Uma vez instalado, abra o prompt do anaconda com o seu ambiente ativo (o mesmo que foi utilizado para instalar os pacotes acima), navegue até a pasta desse projeto e digite:
```
jupyter lab
```
