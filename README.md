# Axel's Indicator Strategy

Indicators for TradingView based on PJM Investment Academy


## Grundsätzliches

### Positionsgröße

- Es wird immer das volle Kapital investiert, bei z.B. 100.000 werden 100.000 investiert
- Alle Gewinne oder Verluste werden berücksichtigt, hier ist also auch Zinseszins mitberücksichtigt
- Es wird eine neue Position eröffnet, wenn eine bestehende geschlossen wurde. Es kann keine zwei Positionen gleichzeitig geben.

### Einstiegskriterien

- Fast Stochastic schneidet die 20 von unten
- RSI schneidet die 30 von unten
- Entweder die Slow Stochastic oder der Money Flow schneidet die 20 von unten

### Ausstiegskriterien

- Sell Signal wird angezeigt oder
- Eingestellter Stopp-Loss Prozentsatz wird erreicht
