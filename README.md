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
- Para el desarrollo de este munú se debe de hacer uso del witget de **Menú** https://coderslegacy.com/python/python-gui/python-tkinter-menu/ 

## Módulo de Registro

### Registro de Pre-Matrícula
Debe solicitar información de:
- Carné (solo valores numéricos y no permitir valores vacios)
- Nombre del estudiante (No permitir valores vacios)
- Carrera (Un combobox con los datos; Ingeniera Computación, Ingeniería Producción y Administración de Empresas)
- Sede (Un combobox con los datos; Cartago, San José, Alajuela, San Carlos y Limón)
- Semestre (Datos numéricos de 1 y 2)
- Año: (Valor numérico: 2021, 2022 y 2023) Pueden usar un spibox o combobox

- Materias: será un combobox con al menos 10 materias en orden alfabético donde el estudiante puede escoger
- Debe existir el botón "Agregar", "Regresar", "Limpiar campos"
- Hacer uso del MessageBox para mensajes de guardado exitoso y errores de validación de los campos


