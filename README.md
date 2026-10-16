# Finger-Press
Cuantificación de fuerza e individuación digital en rehabilitación de mano post-ACV
Dispositivo interactivo para la rehabilitación y evaluación de la fuerza de los dedos en pacientes post-ACV

1. Descripción del proyecto

Finger-Press es un proyecto de desarrollo tecnológico que busca diseñar e implementar un dispositivo electrónico para apoyar la rehabilitación de la mano en pacientes que han sufrido un accidente cerebrovascular (ACV).

El dispositivo consiste en un piano en miniatura, fabricado mediante impresión 3D, que incorpora sensores de fuerza (FSR) en cada una de sus cinco teclas, permitiendo medir de manera independiente la fuerza ejercida por cada dedo.

El sistema contará con luces LED que se encenderán siguiendo secuencias de activación, indicando al usuario qué tecla debe presionar. Durante cada ejercicio, se registrará la fuerza aplicada en la tecla indicada y se evaluará si existe presión involuntaria sobre las demás teclas.

Además, se incorporarán estímulos sonoros asociados a las pulsaciones, con el propósito de desarrollar una experiencia interactiva y didáctica que favorezca la participación del paciente durante los ejercicios.

2. Objetivo general del proyecto
Diseñar e implementar un prototipo electrónico interactivo capaz de medir, registrar y visualizar de manera independiente la fuerza ejercida por los dedos durante ejercicios guiados de pulsación, con el propósito de apoyar la evaluación y rehabilitación funcional de la mano en pacientes post-ACV.

3. Objetivos especificos del proyecto
--> Medir la fuerza ejercida por cada dedo mediante sensores FSR.
--> Registrar la fuerza instantánea y máxima alcanzada durante los ejercicios.
--> Detectar posibles activaciones involuntarias de otros dedos durante una pulsación dirigida.
--> Implementar una secuencia de luces LED que indique al usuario qué tecla debe presionar.
--> Incorporar estímulos sonoros para desarrollar una experiencia interactiva.
--> Visualizar los resultados obtenidos durante cada sesión para evaluar el desempeño del usuario.

5. ¿Cómo buscamos que funcione el dispositivo?
--> El sistema enciende una luz LED que indica qué tecla debe presionar el paciente (post_ACV).
--> El usuario identifica la tecla y la presiona con el dedo correspondiente.
--> El sensor FSR registra la presión ejercida sobre la tecla.
--> El microcontrolador procesa las señales de los sensores y determina la fuerza aplicada.
--> El sistema registra simultáneamente las señales de las demás teclas para identificar posibles activaciones involuntarias.
--> Se genera una respuesta sonora asociada a la pulsación.
--> Los resultados se registran y visualizan mediante una interfaz para evaluar el desempeño durante la sesión.

5. Componentes principales
Cinco sensores de fuerza FSR.
Microcontrolador para adquisición y procesamiento de señales.
Luces LED para indicar las teclas objetivo.
Buzzer
Resistencias
Estructura mecánica de piano en miniatura fabricada mediante impresión 3D.
Interfaz de visualización de resultados.

6. ¿En qué parte del proyecto estamos?
Estamos en el proceso de desarrollar la placa y poder empezar a incorporar los elementos elctrciso. Además, estamos tomando en consideración las modificaciones que han surgido a lo largo del proceso.

7. Conclusión
Finalmente, Finger-Press es prototipo orientado a complementar las herramientas de evaluación y rehabilitación de la mano para pacientes post-ACV.

