# Term Deposit Prediction with ML - Portuguese Bank Dataset

## Visión General
Este conjunto de datos está relacionado con campañas de marketing directo realizadas por una institución bancaria portuguesa. Estas campañas de marketing se basaron principalmente en llamadas telefónicas a los clientes. A menudo, se requerían múltiples contactos con el mismo cliente para determinar si se suscribiría ('sí') o no ('no') a un depósito a plazo bancario.

## Dominio
-  Clasificación, Banca

## Contexto
Aprovechar la información del cliente es fundamental para la mayoría de las empresas, y este conjunto de datos proporciona información valiosa para la estrategia de campañas de marketing de un banco. Atributos relacionados con los clientes del banco, como la edad, el tipo de trabajo, el estado civil, la educación y los comportamientos financieros, pueden desempeñar un papel importante en el diseño de campañas de marketing efectivas al introducir nuevos productos o servicios.

## Objetivo
El objetivo principal de este conjunto de datos es la clasificación. Específicamente, tiene como objetivo predecir si un cliente se suscribirá (sí/no) a un depósito a plazo (variable objetivo 'y') en función de diversas características de entrada.

## Información de los Atributos

### Variables de Entrada
#### Datos del Cliente Bancario:
1. **edad** (numérico): Edad del cliente.
2. **trabajo** (categórico): Tipo de trabajo ('admin.', 'blue-collar', 'emprendedor', 'ama de casa', 'directivo', 'jubilado', 'autónomo', 'servicios', 'estudiante', 'técnico', 'desempleado', 'desconocido').
3. **estado civil** (categórico): Estado civil ('divorciado', 'casado', 'soltero', 'desconocido').
4. **educación** (categórico): Nivel de educación ('primario', 'secundario', 'terciario', 'desconocido').
5. **default** (categórico): Si el cliente tiene crédito en mora ('no', 'sí', 'desconocido').
6. **vivienda** (categórico): Si el cliente tiene un préstamo hipotecario ('no', 'sí', 'desconocido').
7. **saldo** (numérico): Saldo promedio anual en euros.
8. **préstamo** (categórico): Si el cliente tiene un préstamo personal ('no', 'sí', 'desconocido').

#### Relacionados con el Último Contacto de la Campaña Actual:
9. **contacto** (categórico): Tipo de comunicación de contacto ('celular', 'teléfono', 'desconocido').
10. **mes** (categórico): Último mes de contacto del año ('ene', 'feb', 'mar', ..., 'nov', 'dic').
11. **día** (numérico): Último día de contacto del mes (1-31).
12. **duración** (numérico): Duración del último contacto, en segundos.

#### Otros Atributos:
13. **campaña** (numérico): Número de contactos realizados durante esta campaña y para este cliente (numérico, incluye el último contacto).
14. **pdays** (numérico): Número de días transcurridos después de que el cliente fue contactado por última vez en una campaña anterior (numérico; 999 significa que el cliente no fue contactado previamente).
15. **anterior** (numérico): Número de contactos realizados antes de esta campaña y para este cliente (numérico).
16. **resultado_anterior** (categórico): Resultado de la campaña de marketing anterior ('fracaso', 'otro', 'desconocido', 'éxito').

#### Variable de Salida (Objetivo Deseado):
- **objetivo** - ¿El cliente se ha suscrito a un depósito a plazo? (binario: 'sí', 'no')

