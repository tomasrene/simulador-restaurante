# Simulador de restaurante

Falcone era un proyecto de obrador de pasta que finalmente no llegamos a montar. Quería una herramienta para jugar con escenarios de horarios, aforo y cubiertos servidos y ver lo apretados que pueden ser los números en gastronomía.

El simulador permite variar ventas, precios, costos de comida, trabajo y gastos fijos para explorar el resultado mensual. La intención era dimensionar qué pasa si una o dos variables se escapan, antes de abrir.

**Estado: exploración histórica.** Los valores iniciales son supuestos del modelo; no representan resultados de un negocio que haya abierto.

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
