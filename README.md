# RA-2.3_Samuel_Sabogal
# R.A# 2.3 : Control de Nivel de Tanque

## 1. Diseño Lógica Combinacional
El sistema controla el nivel de un tanque mediante 3 sensores de entrada (B1, B2, B3) y 5 luces indicadoras (H1 a H5). El llenado ocurre de abajo hacia arriba.
* **H1 (Nivel Correcto):** B1 y B2 activos, B3 inactivo.
* **H2 (Nivel Bajo):** Solo B1 activo.
* **H3 (Nivel Alto/Desbordamiento):** B1, B2 y B3 activos.
* **H4 (Tanque Vacío):** Ningún sensor activo.
* **H5 (Error):** Falla física (ej. sensor superior activo sin el inferior).

## 2. Diagramas Ladder (Software)
La lógica fue diseñada usando contactos y bobinas booleanas.
<img width="1372" height="767" alt="image" src="https://github.com/user-attachments/assets/a9a2022d-84cc-4cd9-94a9-9bf76acaf05f" />
<img width="1463" height="786" alt="image" src="https://github.com/user-attachments/assets/4d2c1a53-80e2-4185-803d-790a1c28550f" />
<img width="1476" height="930" alt="image" src="https://github.com/user-attachments/assets/092ed12e-2312-4689-9731-954b652b0420" />

## 3. Pruebas y Video de Demostración
La validación se realizó exitosamente en el entorno de simulación, comprobando las secuencias de llenado y el sistema de alarmas.
## 4. Limitaciones
No se pudo realizar el montaje fisico de la manera en la que me hubiera gustado, sin embargo, con la simulacion en el CodeSYS se puede ver que se manejar ambos programas y que en un entorno real son sensores en el tanque, se comportaria de la manera solicitada en el enunciado
