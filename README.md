# Sistema de Reconocimiento de Gestos: Piedra, Papel o Tijera

## Descripción del Proyecto
El presente repositorio contiene el código fuente y los recursos necesarios para la implementación de un sistema de visión computacional basado en inteligencia artificial. Este proyecto fue desarrollado como entrega final para la asignatura de **Big Data**.

El objetivo principal es demostrar la aplicación práctica de **Redes Neuronales Convolucionales (CNN)** en un entorno web, permitiendo la interacción humano-máquina en tiempo real para ejecutar el juego clásico de "Piedra, Papel o Tijera". El sistema es capaz de capturar, procesar y clasificar gestos manuales a través de la cámara web del usuario.

## 🧠 ¿Qué problemas soluciona?
En el ámbito del Big Data y la Inteligencia Artificial, este sistema automatiza procesos críticos que tradicionalmente requieren intervención humana constante:

* **Detección Automatizada de Patrones:** Elimina la necesidad de inspección manual mediante el uso de una red neuronal entrenada para identificar categorías específicas con alta precisión.
* **Procesamiento de Datos No Estructurados:** Soluciona la dificultad de interpretar grandes volúmenes de datos visuales o sensoriales, convirtiéndolos en etiquetas clasificables y procesables para la toma de decisiones.
* **Optimización de Tiempo en Clasificación:** Reduce drásticamente el tiempo de respuesta en tareas de reconocimiento, permitiendo una ejecución fluida en tiempo real desde una interfaz web.
* **Accesibilidad de Modelos de IA:** Facilita el uso de modelos complejos de Machine Learning para usuarios finales a través de una integración sencilla con tecnologías web (HTML/JS).
* **Persistencia y Portabilidad del Conocimiento:** Permite el almacenamiento y carga de pesos de entrenamiento, asegurando que el modelo sea reutilizable y distribuible sin necesidad de reentrenar desde cero.

## Demostración y Despliegue
La aplicación se encuentra desplegada y disponible para su ejecución directa desde el navegador, sin necesidad de instalaciones locales.

* **Acceso al Sistema Web:** [Enlace al Videojuego](https://armandoramirez951.github.io/PF_BigData/)
* **Video Demostrativo:** [Enlace al Video](https://www.youtube.com/watch?v=99DpWhBp8gg)

> **Nota Importante:** Para el correcto funcionamiento del algoritmo de detección, es indispensable otorgar permisos de uso de la cámara web cuando el navegador lo solicite.

## Requisitos Técnicos
Para asegurar la correcta ejecución de la interfaz y el modelo predictivo, el usuario final debe contar con:

1.  **Navegador Web Moderno:** Se recomienda el uso de Google Chrome, Mozilla Firefox, Microsoft Edge o Safari en sus versiones más recientes.
2.  **Dispositivo de Entrada:** Cámara web funcional (integrada o externa).
3.  **Conectividad:** Conexión a internet estable para la carga inicial de las librerías de TensorFlow.js.

## Manual de Uso
La interfaz ha sido diseñada para ser intuitiva. El flujo de operación es el siguiente:

1.  Acceda al enlace de visualización proporcionado anteriormente.
2.  Al cargar la página, el sistema solicitará acceso a la cámara. Es necesario aceptar para continuar.
3.  Una vez activa la cámara, presione el botón **"JUGAR RONDA"** para iniciar el ciclo de juego.
4.  El sistema realizará un conteo regresivo. Antes de finalizar el conteo, el usuario debe mostrar su gesto (Piedra, Papel o Tijera) frente a la cámara.
5.  El modelo evaluará la imagen capturada, la clasificará y la comparará con una elección aleatoria de la CPU para determinar el ganador, actualizando el marcador en tiempo real.

## Arquitectura y Tecnologías
El desarrollo de este proyecto integra diversas tecnologías web y de aprendizaje automático:

* **Google Teachable Machine:** Utilizado para la fase de entrenamiento del modelo, empleando un dataset de imágenes para las clases: *Piedra*, *Papel* y *Tijera*.
* **TensorFlow.js:** Biblioteca de JavaScript que permite la ejecución del modelo de aprendizaje automático directamente en el navegador del cliente (Client-side execution), optimizando la latencia.
* **Frontend (HTML5/CSS3/JS):** Implementación de la lógica de negocio, control de flujo del juego y diseño de interfaz de usuario responsiva.

## Licencia y Uso
Este software fue desarrollado con fines estrictamente académicos y educativos para la Universidad Autónoma de Baja California (UABC). Su distribución es libre para propósitos de aprendizaje.

### Autor
**Ramirez Cardenas Luis Armando**
Licenciatura en Inteligencia de Negocios
Facultad de Contaduría y Administración
**Universidad Autónoma de Baja California**
Grupo: 961
