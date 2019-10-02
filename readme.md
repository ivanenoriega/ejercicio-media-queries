# Ejercicios - Media queries

> Sigue los pasos para completar el ejercicio

## 1 -En dispositivos tipo tablets (768px): las columnas, todas, tengan un ancho del 50%.

Ayuda selectores avanzados con pseudo classes para seleccionar todos los elementos que tengan una clase que comience con:

- `[class|="col"]` seria: todas las clases que comiencen con col y luego siga un guión medio (el guión medio lo asume)
- `[class*="col-"]` seria: todas las clases que tengan en algún lado col-
- `[class^="col-"]` seria: todas las clases que comiencen con col-
- `:not()` entre paréntesis le decimos lo que NO queremos que incluya. Por ejemplo: `[class|="col"]:not(.col-12)` seria: todas las clases que comiencen con col- perooo nooo .col-12

## 2 - En la misma media query anterior, debemos crear un selector para nuestras filas (.row), que deberán tener:

- propiedad `display: flex;`
- el contenido deberá justificarse `justify-content` dejando el espacio disponible entre las columnas `space-between`
- y las columnas deberán alinearse `align-items` en el centro `center`.

## 3 - que en dispositivos tipo desktop (960px) las columnas tengan un tamaño de acuerdo a la siguiente tabla:

> ! el important se lo colocamos para que aplique la regla, ya que selector que utilizamos antes es más especifico que el que vamos a utilizar aquí.
> archivo para modificar el tamaño de las columnas: https://docs.google.com/spreadsheets/d/1w-D3KcLGcfwJVMXFUWcQD6AuzZ_SjsvVHNB974qRLgw/edit?usp=sharing

- `col-1: 6.481481481% !important`
- `col-2: 14.81481481% !important`
- `col-3: 23.14814815% !important`
- `col-4: 31.48148148% !important`
- `col-5: 39.81481481% !important`
- `col-6: 48.14814815% !important`
- `col-7: 56.48148148% !important`
- `col-8: 64.81481481% !important`
- `col-9: 73.14814815% !important`
- `col-10: 81.48148148% !important`
- `col-11: 89.81481481% !important`
- `col-12: 100% !important`

## 4 - Edita el contenido HTML para obtener el siguiente resultado:

![alt text](https://github.com/ivanenoriega/ejercicio-media-queries/blob/master/assets/1570045615475.png)

## 5 - Agrega una nueva "row" que contenga tres "col" con los siguientes datos:

- Nombre y apellido.
- Tecnologia favorita (HTML, CSS o Javasctipt).
- Cualquier dato que quieras.

Ejemplo: ![alt text](https://github.com/ivanenoriega/ejercicio-media-queries/blob/master/assets/1570047825711.png)

## 6 - Crear una Pull Request al repo principal
