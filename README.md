# unav_mint
Repositorio para llevar a cabo el ejercicio práctico del master MINT (unav). Para ello será necesario realizar la siguiente instalacion

En primer lugar instalar anaconda indivitual edition en la siguiente direccion: https://www.anaconda.com/products/individual

En segundo lugar, una vez instalado satisfactoriamente el conda, abrimos la terminal para instalar los paquetes y crear el environment. 

conda create -n unav_mint python=3.8

conda activate unav_mint

pip install --upgrade pip

pip install -r requirements.txt

python -m ipykernel install --user --name unav_mint --display-name "unav_mint"

Una vez creado el enviroment, instalado los paquetes y mostrado en jupyter, abrimos el jupyter desde la terminal con el siguiente comando:

jupyter notebook

Ejecutamos el jupyter notebook llamado: churn_prediction_nn_mint.ipynb

A disfrutar!!!
