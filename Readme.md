# Desafío Alura Store - Análisis de Tiendas

Este proyecto corresponde al desafío de la formación en Data Science de Alura Latam.

## Objetivo

El Sr. Juan está considerando cerrar una de sus cuatro tiendas para invertir en un nuevo negocio. Como analista de datos, mi misión fue ayudarlo a decidir cuál tienda cerrar basándome en:

- Facturación total por tienda
- Categorías más populares por tienda

## Archivos utilizados

- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`
- `alura_store_challenge_2025.ipynb`

## Análisis realizado

### 1. Facturación total por tienda

Se calculó la facturación total multiplicando `Precio * Cantidad de cuotas` para cada registro.

**Resultados:**

- Tienda 1: $3.422.717.700
- Tienda 2: $3.337.189.200
- Tienda 3: $3.243.816.900
- Tienda 4: $3.098.827.200

> **Conclusión:** La tienda con menor rendimiento es la **Tienda 4**.

**Gráfico:**

![Facturación total por tienda](https://github.com/crissancl/Alura-store/blob/main/grafico_facturacion.png)

---

### 2. Categorías más populares por tienda

Se analizaron las 3 categorías de producto más frecuentes en cada tienda.

**Gráfico:**

![Categorías más populares por tienda](https://github.com/crissancl/Alura-store/blob/main/categorias_tiendas.png)

> Las categorías más populares fueron consistentemente **Muebles**, **Electrónicos** y **Juguetes**.

---

## Cómo ejecutar

1. Abrir el archivo `alura_store_challenge_2025.ipynb` en [Google Colab](https://colab.research.google.com/).
2. Subir los archivos `.csv` de cada tienda.
3. Ejecutar las celdas para obtener los resultados y gráficos.

---

## Autor

**Cristian Ignacio Sánchez Ormeño**  
GitHub: [crissancl](https://github.com/crissancl)
