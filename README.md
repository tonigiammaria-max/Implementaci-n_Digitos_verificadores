# Implementaci-n_Digitos_verificadores

Integrantes: Antonella Giammaria Sánchez, Paulina Valencia Ceballos\
Tema: tema no. 8, dígitos verificadores\
Instrucciones: (Lenguage python). Debajo de la línea que inicia el main se ingresa el número a verificar, si el algoritmo Luhn lo procesa y el cálculo lo reconoce correcto, entonces sale 'This is a valid card'\
Resultados: Se comprueba que un código así solo tiene como barrera de seguridad el algorítmo, y aquí se verifican 2 de los mayores problemas de nuestro tema Dígitos de verificación:
1. El código es predecible, si quien quiere engañar el sistema ya conoce las condiciones es solo cuestión de que encuentre un valor valido para pasar esa barrera
2. Fallo por casualidad, si de casuailidad se digita 123 en vez de 321 a pesar de que '123' no es correcto, este código no avisará de este error
Herramientas utilizadas: Código original tomado de 'geeks for geeks': https://www.geeksforgeeks.org/dsa/luhn-algorithm/#:~:text=obtained%20after%20doubling.-,Implementation%3A,-C%2B%2B
