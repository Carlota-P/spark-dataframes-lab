<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1ee50dcd-df71-4f8f-b4e9-45802272fe41" />Incluye aquí capturas o salidas relevantes del cuaderno.

## 1. Entorno levantado
- Captura de JupyterLab
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5d0a41eb-c914-466c-b5b7-9db1d3514c3d" />

- Captura del Spark Master UI
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/29051eb8-6cb9-45fd-b877-77d03b4f85bb" />


## 2. Lectura de datos
- Esquema de `clientes`
- Esquema de `pedidos`
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8713ed38-4a82-40d8-9136-d978d869c0a4" />

- Muestra inicial de datos
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0301b7d6-21dc-483a-85fd-fc8cdfa167cc" />


## 3. Limpieza
- Resultado tras `trim`
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4d004338-3a5d-4b01-a7f9-a1a13afb714a" />

- Eliminación de duplicados
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a8dc976b-cd67-49ab-a259-4a4a2c3474b5" />

- Tratamiento de valores nulos
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/733ee4fb-aeac-4df8-b21c-d603888e16dc" />

## RESULTADO FINAL
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a0a1c2fb-22cf-467e-ace4-93dab75b1f36" />

## 4. Join
- Resultado del join entre clientes y pedidos
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9bd76b2d-8a97-48c6-ae33-cef4b7959137" />

- Explicación breve de los registros perdidos
Los registros que se han perdido son los pedidios que no tiene relacion con clientes, es decir, que se han perdido aquellos en pedidos que no exista ningun id_cliente en la tabla cliente 

## 5. Agregaciones
- Resumen por ciudad y segmento
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/39242780-0ec3-464b-a2f4-859c50cedd90" />

- Interpretación breve de los resultados
En conjunto, se registran 106 pedidos con unos ingresos totales de 61.725 y un importe medio de 582,31.
El segmento Premium presenta un gasto medio superior al Estandar, aunque este último tenga más pedidos.
Por ciudad y segmento, destacan especialmente Granada Premium y Alicante Premium por su importe medio, mientras que Bilbao Estandar sobresale por volumen e ingresos totales.

## 6. SQL
- Consulta SQL realizada
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/50970f33-32e4-41cb-8c24-43aea190b557" />

- Resultado obtenido
La consulta muestran que Bilbao lidera en volumen de pedidos e ingresos totales.
Alicante y Granada destacan por tener importes medios por pedido más elevados, mientras que ciudades como Malaga y Valladolid tienen una actividad muy reducida.

## 7. Parquet
- Escritura del resultado
- Lectura posterior del fichero Parquet
