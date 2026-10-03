# RA-2.3_Samuel_Sabogal
# R.A# 2.3 : Control de Nivel de Tanque

## 1. Diseño Lógica Combinacional
El sistema controla el nivel de un tanque mediante 3 interruptores de entrada (B1, B2, B3) que reprentarian los 3 sensores que estarian en el tanque y 5 luces indicadoras, (H1 a H5). El llenado ocurre de abajo hacia arriba.
* **H1 (Nivel Bajo):** B1 activo y B2 y B3 inactivos.
* **H2 (Nivel bajo- medio):** B1 y B2 activo.
* **H3 (Nivel medio):** B2 activo.
* **H4 (Nivel medio-alto):** B2 y B3 activos.
* **H5 (Error):** Falla física B3 activo).

## 2. Diagramas Ladder (Software)
La lógica fue diseñada usando contactos y bobinas booleanas.
<img width="1372" height="767" alt="image" src="https://github.com/user-attachments/assets/a9a2022d-84cc-4cd9-94a9-9bf76acaf05f" />
<img width="1463" height="786" alt="image" src="https://github.com/user-attachments/assets/4d2c1a53-80e2-4185-803d-790a1c28550f" />
<img width="1476" height="930" alt="image" src="https://github.com/user-attachments/assets/092ed12e-2312-4689-9731-954b652b0420" />
## 3. Limitaciones
No se pudo realizar el montaje fisico de la manera en la que me hubiera gustado, sin embargo, con la simulacion en el CodeSYS se puede ver que se manejar ambos programas y que en un entorno real son sensores en el tanque, se comportaria de la manera solicitada en el enunciado, entiendo que el no tener el montaje fisico podra bajar la nota , pero teniendo la logica y demostrando el conocimiento es mas que suficiente para este R.A
