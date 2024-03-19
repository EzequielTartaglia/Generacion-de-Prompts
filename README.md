### Instalación

- Miniconda: https://docs.conda.io/projects/miniconda/en/latest/index.html

### Preparar el entorno

Para poder instalar el entorno necesario para poder crear nuestros modelos de IA debemos:

1. Abrir anaconda (prompt), instalado previamente mediante el instalador de Miniconda.
2. Crear nuestro envoirement con el comando `conda create --name generacion-de-prompts python=3.10` (esto debes hacerlo solo la primera vez)
3. Una vez creado nuestro envoirement lo activaremos con el comando `conda activate generacion-de-prompts`
4. Dentro vamos a instalar las dependencias/modulos necesarios:
  - `conda install pip` (poder utilizar tanto `conda install` como `pip install`)
  - `pip install openai==0.28` (mejorar el request)
  - `pip install jupyter notebook` (instalar tanto jupyter como notebook, para poder crear nuestro servidor local)
  - `pip install` "..." seguido de la dependencia necesaria para nuestro proyecto o modelo.
5. Una vez instaladas las dependencias, debemos ejecutar nuestro entorno jupyter notebook con el comando `jupyter notebook`
.
