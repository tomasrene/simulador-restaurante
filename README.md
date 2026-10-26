# Simulador de restaurante

Una herramienta para explorar cómo cambian los resultados mensuales de un restaurante al mover supuestos de ventas y costos. El caso de origen es **Falcone**.

Se pueden variar días de apertura, volumen y precios de menú, café y tienda; costos de comida, trabajo y gastos fijos. La aplicación muestra un resultado mensual y una sensibilidad simple al volumen.

**Estado: exploración histórica.** Los valores iniciales son parámetros del modelo, no resultados comerciales verificados. No reemplaza una contabilidad ni incorpora automáticamente información de un negocio.

## Usarlo localmente

Requiere Python y las dependencias de `requirements.txt`.

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
```

## Qué sigue abierto

Qué supuestos cambian una decisión y cómo explicar sus efectos sin dar una falsa precisión al resultado.

[La exploración completa](https://tomasrene.com/experimentos/restaurantes) · [Catálogo de exploraciones](https://github.com/tomasrene/exploraciones)

Nombre anterior del repositorio: `falcone-pnl`. Se conserva su historia.
