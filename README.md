# PickGo — Buyback Calculator

Internal pricing tool for PickGo customer service.

**Live:** https://xavierh03.github.io/pickgo-buyback-calculator/

Enter today's price per gram from the daily price sheet, pick the gold type, weight and
order type. The tool returns the buyback price per gram and the total the customer receives.

**Formula:** price/gram × pricing purity − margin (by order type and weight band).
Consignment = pickup main-area price × 70%.

Margins are the **15.9.2026 PickGo** set. When the margin sheet changes, `index.html`
must be updated to match.
