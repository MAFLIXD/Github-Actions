# Simulacion de un deploy

Es un ejemplo de un flujo de trabajo o algo que hacemos todos los dias
y que queremos automatizar para que se haga automaticamente.


- Un trigger hace que cuando se haga el push en la rama main, el ejecutara el workflow
- Nombre del job y un job puede tener muchos pasos o "steps"
- "runs-on: ubuntu-latest" Maquina virtual donde se ejecutara el job
- "uses: actions/checkout@v4" Va a tomar el codigo y lo va a clonar en el repo