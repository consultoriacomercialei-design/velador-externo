# 🕯️ Vigía externo — El Velador
Capa externa del monitoreo de [Directorio Santiago](https://directoriosantiago.com) y Hotel El Encino.
Ronda cada ~10 min desde GitHub Actions (independiente de cualquier servidor propio):
- Web y APIs públicas del Directorio (salud profunda: catálogo, DB, pagos)
- Web del hotel
- **Hombre muerto**: latido de la sonda local — si la máquina guardiana se apaga, este vigía lo detecta y avisa.
Las alertas viajan a la recepción del hotel con deduplicación de 6 h. Este repo no contiene secretos.
