# hedged-risk-portfolio

# 📊 Hedged Risk Portfolio

🧠 Многоуровневый портфель с активной защитой от падения и волатильности, построенный на базе BTC, ETH, XRP и золота.

## 📦 Структура:
- 95% spot portfolio (BTC, ETH, XRP, XAU/USD)
- 3% protective puts (BTC, ETH)
- 2% volatility hedge (BTC strangle, адаптивный вес на основе VIX proxy)

## ⚙️ Методы:
- Rolling 30-дневные опционы
- Black-Scholes model
- Rolling historical volatility = VIX proxy
- Dynamic strangle weight (1–3%) в зависимости от z-score волатильности

## 🧮 Риски:
- VaR (95%)
- Expected Shortfall (CVaR)
- Max Drawdown
- PnL визуализация

## 🧾 Инструкция:
1. Установи зависимости:
```bash
pip install -r requirements.txt


## 💻 Запуск проекта:

1. Установите зависимости:

```bash
pip install -r requirements.txt
