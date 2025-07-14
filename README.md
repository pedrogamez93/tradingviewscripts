# 📈 SOL/USDT Señales Certeras v6.4 – Pine Script Strategy

> Estrategia automatizada optimizada para operar **SOL/USDT** en Binance con alta precisión.  
> Usa señales basadas en **EMA, RSI, ADX, volumen inusual** y confirmación con tendencia de **BTC**.  
> Soporta **Take Profit dividido**, **Trailing Stop**, y bloqueo inteligente post pérdida.

---

## 🔍 Características principales

- ✅ Entradas **LONG** y **SHORT** inteligentes
- 📊 Confirmación de tendencia con **EMA 100**
- 🔎 Filtro de **volumen inusual** y **momentum (RSI/ADX)**
- 📉 Evita operar en **rangos laterales**
- 🔐 Bloqueo temporal tras Stop Loss
- 🎯 **Split TP + Trailing Stop** opcional
- 🔁 Compatible con **Backtesting** en TradingView

---

## ⚙️ Parámetros configurables

| Parámetro                  | Descripción                                          | Valor por defecto |
|----------------------------|------------------------------------------------------|-------------------|
| `EMA Period`               | Periodo de la media móvil exponencial                | 100               |
| `RSI / ADX Period`         | Periodos para indicadores de momentum                | 14                |
| `Volume Spike`             | Múltiplo sobre volumen promedio                      | 1.5               |
| `TP %` / `SL %`            | Porcentaje fijo de Take Profit y Stop Loss           | 1.5 %             |
| `BTC Filter`               | Confirmación de tendencia BTC                        | Activado          |
| `Split TP + Trailing`      | Cierra el 50% en TP1 y deja correr el resto          | Activado          |
| `Rango lateral`            | Bloqueo de señales en zonas con poca variación       | Activado          |

---

## 🛠 Cómo usar

1. Copia el archivo `.pine` en TradingView → Pine Editor
2. Guarda y haz clic en "Agregar al gráfico"
3. Ajusta los parámetros según tu perfil de riesgo
4. Ejecuta backtesting en temporalidad 1H o 30m

---

## 💡 Recomendaciones

- 🔹 Usar en pares con buena liquidez: `SOL/USDT`, `ETH/USDT`, `LINK/USDT`
- ⏱ Timeframes ideales: 1H y 30m
- ⚠️ Evita operar en rangos estrechos o durante noticias de alto impacto
- 📉 Para operar manualmente: utiliza las señales `LONG`, `SHORT`, `TP1`, y `Trail` visibles en el gráfico

---

## 🧠 Autor

Desarrollado por Pedro para uso propio en Binance Futures.  
Inspirado en múltiples estrategias con confirmación multicapas.  
Se agradecen forks, mejoras y sugerencias.

---

## 📜 Licencia

Este script es de uso personal. Puedes adaptarlo y mejorarlo, pero no redistribuirlo como propio sin atribución.

