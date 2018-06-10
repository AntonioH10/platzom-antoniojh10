# Platzom

Platzom es un idioma inventado para el [curso de fundamentos de Javascript](https://platzi.com/js) de [Platzi](https://platzi.com).

## Descripción del idioma

- Si la palabra termina con "ar" se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por último, si la palabra original es un palindromo ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayusculas y minusculas

## Instalación

```
npm install platzom-antoniojh10
```

# Uso

```
import platzom from 'platzom'

console.log(platzom("Programar")) // Program
console.log(platzom("Zorro")) // Zorrope
console.log(platzom("Zarpar")) // Zarppe
console.log(platzom("abecedario")) // abece-dario
console.log(platzom("sometemos")) // SoMeTeMoS
```

## Créditos
- [Antonio Hernandez](https://twitter.com/antoniojh)

## Licencia

[MIT](https://opensource.org/licenses/MIT)