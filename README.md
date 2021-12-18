# 1.4Corazon_con_ruido
Es la cuarta tarea del Primer Parcial de mi materia de Análisis y Procesamiento de Imágenes

## *INSTRUCCIONES*

Realizar un programa que limpie el ruido externo al contorno original del corazón. Para ello, se utilizará la siguiente condición:
- Si arriba, abajo, izquierda y derecha tienes un valor igual a uno, entonces el elemento central se convierte en uno.
- Si tengo tres o  menos uno en los vecino, entonces el elemento central se queda con su mismo valor.


Entregar:
1. El programa realizado (*.py)
2. Captura de pantalla con el corazón escrito de forma limpia. Recordar que la impresión se debe hacer rectangular y no en forma de lista (*.jpg o *.png)


Notas de clase:
```
for r in range(1,m-1):
   for c in range(1,n-1):
      if(z[r-1][c]==1 and z[r+1][c]==1 and z[r][c-1]==1 and z[r][c+1]==1):
         z[r][c]=1 #central
      else:
         z[r][c]=z[r][c]
```

