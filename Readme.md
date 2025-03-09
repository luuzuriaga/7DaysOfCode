#7DaysOfCode Dia 1

# Comparaciones en JavaScript

Este proyecto muestra ejemplos de comparaciones en JavaScript usando `==` y `===`.

## Código

```javascript
let numeroUn = 1;
let stringUn = "1";
let numeroTreinta = 30;
let stringTreinta = "30";
let numeroDiez = 10;
let stringDiez = "10";

if (numeroUn == stringUn) {
  console.log("numeroUn y stringUn tienen el mismo valor, pero tipos diferentes");
} else {
  console.log("numeroUn y stringUn no tienen el mismo valor");
}

if (numeroTreinta === stringTreinta) {
  console.log("numeroTreinta y stringTreinta tienen el mismo valor y tipo");
} else {
  console.log("numeroTreinta y stringTreinta no tienen el mismo tipo");
}

if (numeroDiez == stringDiez) {
  console.log("numeroDiez y stringDiez tienen el mismo valor, pero tipos diferentes");
} else {
  console.log("numeroDiez y stringDiez no tienen el mismo valor");
}
```

## Explicación
- `==` compara solo el valor.
- `===` compara valor y tipo.

## Salida esperada
```
numeroUn y stringUn tienen el mismo valor, pero tipos diferentes
numeroTreinta y stringTreinta no tienen el mismo tipo
numeroDiez y stringDiez tienen el mismo valor, pero tipos diferentes
```

Ejecuta el código en la consola para ver los resultados.
