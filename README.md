# 2022-S2-Laboratorio-4
# Uso de TK Inter y manejo de archivos

## Objetivo General

Desarrollar una aplicación para el registro de cursos de un periodo lectivo haciendo uso de las biblioteca gráfica de python TKInter

## Descripción

- Con esta actividad invitar al estudiante en investigar de cómo programar una aplicación con interfaz gráfica haciendo uso de esta biblioteca.
- La aplicación consiste en que un estudiante registre cuales cursos desea llevar el siguiente semestre.
- Los datos que se registren debe guardarse en un archivo llamado **matricula.txt**

## Página principal

- Debe  tener un menu que muestre los datos: Registro, Consultas y Salir
- Dentro de **Registro** el sub menú llamado "Registro de Pre-matrícula"
- Dentro de **Consultas** Consultar por Estudiante o Curso
- Para el desarrollo de este munú se debe de hacer uso del widget de **Menú** https://coderslegacy.com/python/python-gui/python-tkinter-menu/ 

## Módulo de Registro

### Registro de Pre-Matrícula
Debe solicitar información de:
- Carné (solo valores numéricos y no permitir valores vacios)
- Nombre del estudiante (No permitir valores vacios)
- Carrera (Un combobox con los datos; Ingeniería Computación, Ingeniería Producción y Administración de Empresas)
- Sede (Un combobox con los datos; Cartago, San José, Alajuela, San Carlos y Limón)
- Semestre (Datos numéricos de 1 y 2)
- Año: (Valor numérico: 2021, 2022 y 2023) Pueden usar un spinbox o combobox

- Materias: será un combobox con al menos 10 materias en orden alfabético donde el estudiante puede escoger
- Debe existir el botón "Agregar", "Regresar", "Limpiar campos"
- Hacer uso del MessageBox para mensajes de guardado exitoso y errores de validación de los campos

## Módulo Consultas

### Estudiante

- Debe existir un campos para ingresar el carné, este solo permitirá valores numéricos y no debe de estar vacío
- Botones de ""Buscar**, **Limpiar datos** y **Regresar**
- El botón buscar, dentro de un listBox mostrará los resultados de la búsqueda
- El botón **Limpiar datos** borrará el valor del listbox y del entry
- El botón **Regresar** retorna a la ventana inicial
- Si el carné digitado no existe en el archivo, debe mostrar un mensaje al usuario haciendo uso del widget de MessageBox

### Curso

- Debe existir un campo para seleccionar el curso, debe ser un combobox con los mismos datos de la ventana de **Registro de Pre-matrícula**
- Botones de ""Buscar**, **Limpiar datos** y **Regresar**
- El botón buscar, dentro de un listBox mostrará los resultados de la búsqueda
- El botón **Limpiar datos** borrará el valor del listbox y del entry
- El botón **Regresar** retorna a la ventana inicial

## Salir

- Finaliza el programa

## Referencias
- https://coderslegacy.com/python/python-gui/python-tkinter-entry/
- https://tkdocs.com/tutorial/widgets.html
- https://www.studytonight.com/tkinter/python-tkinter-widgets
- Y más recursos en la internet ...
