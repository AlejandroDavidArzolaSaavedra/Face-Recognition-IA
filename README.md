<h1 align="center"> 🤖 Reconocimiento facial</h1>

Nuestro objetivo ha sido poder **reconocer personas** y **identificarlas**, ya sea de manera individual o en grupos, explorando distintas técnicas, librerías y tecnologías que nos permitieran investigar. Durante el proceso, nos enfocamos en experimentar con diversas herramientas y enfoques, con la intención de maximizar el rendimiento y obtener resultados óptimos.

*Realizado por*:

[![GitHub](https://img.shields.io/badge/GitHub-Alejandro%20D.%20Arzola%20Saavedra%20-purple?style=flat-square&logo=github)](https://github.com/AlejandroDavidArzolaSaavedra)
[![GitHub](https://img.shields.io/badge/GitHub-Heliot%20J.%20Segura%20Gonzalez-darkblue?style=flat-square&logo=github)](https://github.com/kratoscordoba7)

## Cómo empezar


### Paso 1: Abrir Anaconda prompt y activar el environment:
   ```bash
   conda activate NombreDeTuEnvironment
   ```

### Paso 2: Instalación
Para instalar estas librerías, ejecuta los siguientes comandos:

```bash
pip install opencv-contrib-python numpy scipy imutils pyttsx3 mysql-connector-python deap
```
o

```bash
pip install -r requirements.txt
```

### Uso/Controles

Al iniciar el programa, este nos dará la bienvenida y nos ofrecerá dos opciones para seleccionar. Estas opciones están diseñadas pensando en la flexibilidad del usuario:  

1️⃣ **Modo 1:** Capturar, entrenar y reconocer el rostro.  
2️⃣ **Modo 2:** Reconocer el rostro directamente, sin necesidad de un entrenamiento previo.  

Esta separación permite que el usuario pueda elegir lo que necesita sin tener que seguir pasos secuenciales innecesarios. Si solo deseas reconocer tu rostro sin haberlo entrenado antes, ¡no hay problema! Puedes seleccionar directamente el Modo 2.  


