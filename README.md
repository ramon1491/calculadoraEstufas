# Calculadora de Potencia de Estufa

Herramienta simple para estimar qué potencia de estufa necesitás según el tamaño de tu ambiente.

## Cómo usarlo

1. Descargá o cloná el repositorio
2. Abrí el archivo `index.html` en tu navegador
3. Ingresá los datos y hacé clic en **Calcular**

## Datos que pedimos

- **Superficie** del ambiente en m²
- **Altura del techo** en metros (por defecto 2.5 m)
- **Nivel de aislación:** Buena / Normal / Mala

## Cómo se calcula

```
Volumen = superficie × altura
Potencia (kcal/h) = volumen × coeficiente de aislación
Potencia (W) = kcal/h × 1.163
```

| Aislación | Coeficiente |
|-----------|-------------|
| Buena     | 40 kcal/h por m³ |
| Normal    | 50 kcal/h por m³ |
| Mala      | 60 kcal/h por m³ |

> Esta es una estimación aproximada. El resultado puede variar según ventanas, orientación y clima de la zona.

## Repositorio

[github.com/ramon1491/calculadoraEstufas](https://github.com/ramon1491/calculadoraEstufas)
