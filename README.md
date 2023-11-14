# Máquina de Turing en Python
Este es un simple simulador de Máquina de Turing implementado en Python. La Máquina de Turing (MT) es un
modelo teórico de cómputo que manipula símbolos en una cinta de acuerdo con un conjunto de reglas.
## Requisitos
Asegúrate de tener Python instalado en tu máquina. Puedes descargarlo desde
[python.org](https://www.python.org/).
## Uso
1. Clona o descarga el código fuente.
2. Ejecuta el archivo proporcionado (`turing_machine.py`).
3. El programa solicitará la ruta del archivo de definición de la MT.
## Archivo de Definición de la Máquina de Turing
El programa espera un archivo de definición siguiendo un formato específico. Aquí hay un ejemplo (`regla.txt`):
Estados: q0, q1, q2
Inicial: q0
Aceptación: q2
Rechazo: q1
Alfabeto: 0, 1, _
Transiciones:
q0, 0 -> q1, 1, D
q1, 1 -> q2, 1, N
- **Estados**: Lista de estados separados por comas.
- **Inicial**: Estado inicial.
- **Aceptación**: Estados de aceptación.
- **Rechazo**: Estados de rechazo.
- **Alfabeto**: Símbolos del alfabeto separados por comas.
- **Transiciones**: Reglas de transición en el formato `estado actual, símbolo leído -> próximo estado, símbolo
escrito, dirección`.
