## Comparación JavaScript vs TypeScript

JavaScript no cuenta con tipado estricto, por lo que no nos avisa cuando ponemos comillas a un número, interpretándolo como un string.

El operador + en prestamo.multa + cargoFijo no funciona aquí como suma, sino como concatenador, dando como resultado '35050'.
Para solucionar lo que pasaba en JS, cambiamos a TypeScript y le agregamos tipo a nuestras variables. Al declarar multa como number e intentar asignarle '350' (con comillas), TypeScript nos avisa del error de tipo. Al corregirlo y usar 350 sin comillas, el resultado final es 400.