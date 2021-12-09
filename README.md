# Diabetics-Readmission-Project
## Clasificación de Readmisiones hospitaliarias a pacientes con diabetes
### Realizado por: Estebana Orozco Ramirez

## Descripción del problema

El dataset representa 10 años (1999-2008) de atención clínica en 130 hospitales y redes integradas de prestación de servicios de EE. UU; Y esta asociado al artículo de investigación: *Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records*.(https://downloads.hindawi.com/journals/bmri/2014/781670.pdf)

Mi objetivo, es analizar qué factores están relacionados con los reingresos y estudiar las demás características asociadas a los pacientes para lograr una clasificación que relacione los pacientes y los hospitales.

### Dataset
https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008#

### Data description
https://www.hindawi.com/journals/bmri/2014/781670/tab1/

## Información conocida del Dataset
Se extrajo información de la base de datos para los ingresos que cumplieron con los siguientes criterios.
- Es un ingreso hospitalario (una admisión hospitalaria).
- Es un ingreso diabético, es decir, durante el cual se ingresó al sistema cualquier tipo de diabetes como diagnóstico.
- La duración de la estancia fue de al menos 1 día y como máximo 14 días.
- Se realizaron pruebas de laboratorio durante la estancia.
- Se administraron medicamentos durante la estancia.

Los datos contienen atributos tales como número de paciente, raza, sexo, edad, tipo de admisión, tiempo en el hospital, especialidad médica del médico que lo admite, número de pruebas de laboratorio realizadas, resultado de la prueba de HbA1c, diagnóstico, cantidad de medicación, medicamentos para diabéticos, cantidad de pacientes ambulatorios , visitas hospitalarias y urgentes en el año anterior a la hospitalización, etc. Para cada registro existe uno de los siguientes resultados:

1. No readmisión.

2. Readmisión en menos de 30 días (esta situación no es buena, porque existe la posibilidad de que el tratamiento aplicado no fue apropiado).

3. Readmisión después de 30 días (esta situación tampoco es buena, sin embargo, la razón podría estar relacionada con el estado del paciente).
