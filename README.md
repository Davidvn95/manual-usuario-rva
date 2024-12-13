# Manual de usuario para RiesgoVascularApp
### Resumen de vistas:
- Login.
- Formulario Datos Básicos del paciente.
- Listado Pacientes en cola de atención.
- Formulario Datos Médicos del paciente.
- Resultado Cálculo de riesgo y recomendación Médica

### Descripciones
#### 1. Login:
Encargada de la autenticación del usuario, valida el rol del mismo para dirigir a la pantalla inicial correspondiente según el rol.

<img src="https://github.com/user-attachments/assets/c313fb45-1051-4d46-b924-73f090f07cb8" alt="Ejemplo" width="200" style="margin-x: 0;">

#### 2. Formulario Datos Básicos del paciente:
Vista inicial para el usuario con Rol auxiliar, toma todos los datos básicos del paciente e inicia la atención con el Id de los datos básicos del paiente y la fecha y hora.

<img src="https://github.com/user-attachments/assets/72721437-7646-4e75-bc76-040ed0116125" alt="Ejemplo" width="200" style="margin-x: 0;">

#### 3. Listado Pacientes en cola de atención:
Vista principal del usuario médico, en esta vista puede ver todas las atenciones iniciadas por el auxiliar los cuales están pendientes de atención.
Una vez seleccionado un paciente de la lista, debe redirigir al médico al formulario de datos básicos pero con los datos del paciente llenos, solo para verificación del médico con el paciente, una vez confirmados lo datos continua al formulario de datos médicos.

<img src="https://github.com/user-attachments/assets/2c4a9737-e82e-4ee5-b3e6-9144477c6e42" alt="Ejemplo" width="200" style="margin-x: 0;">

#### 4. Formulario Datos Médicos del paciente:
Una vez en este formulario, se llenan los datos solicitados los cuales serán usados para calcular e nivel de riesgo caridovascular del paciente.

<img src="https://github.com/user-attachments/assets/ff5ff008-0785-4822-9ef9-86824a3fd340" alt="Ejemplo" width="200" style="margin-x: 0;">

#### 5. Resultado Cálculo de riesgo y recomendación Médica:
Por último, esta vista devuelve el resultado de la calculadora de riesgo vascular basados en los datos médicos tomados anteriormente, admás toma la recomendación médica para el resultado obtenido, la cuál es analizada por una api externa para luego retornar si es viable la recomendación médica o no, también toma los datos de medicamenots anteriores que haya tomado el paciente y puedan influir en la mejora de su riesgo.

<img src="https://github.com/user-attachments/assets/48eaa525-5689-4977-8e3b-5784aeafd062" alt="Ejemplo" width="200" style="margin-x: 0;">

