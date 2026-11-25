# Historizador GPM

Visualizador de tendencias de variables SCADA del Gasoducto Perito Francisco Pascasio Moreno (O&M Energía Argentina – TGS).

Publicado en: https://gestionoperativa-tgs.github.io/Historizador/

## Uso
- **Cargar CSV…** o arrastrar los archivos exportados del SCADA (HistoryView): separador `;`, fila 1 con nombres, fila 2 con IDs de tag (opcional), fecha `MM/DD/YY hh:mm:ss`.
- Los archivos con los mismos tags se acumulan en una sola fuente (se ordenan por fecha y se descartan horas repetidas). Los datos quedan guardados solo en el navegador de quien los carga.
- Hasta 16 tags a la vez; modos eje común, escala propia y apiladas.
- Rueda: zoom · Arrastrar: zoom a la selección · Shift + arrastrar: desplazar · Doble clic: tramo completo · ← →: mover.
- **Copiar** (para pegar en Excel) y **CSV** exportan el tramo visible.
