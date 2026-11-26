# FINDEC · Sistema de decisiones financieras

**Universidad Regional de Guatemala** · Sede Boca del Monte
Facultad de Ingeniería · Carrera de Sistemas · Cuarto ciclo · Segundo semestre 2026
**Curso:** Matemática Financiera
**Catedrático:** Lic. José Stuardo Alonzo Pacheco

**Autor:** Diego Alejandro Jauregui López · Carné 2525191

## ¿Qué hace?

Interpreta los datos de un caso y dice si **aplica o no** proceder con una **compra**, un **alquiler** o una **venta**. Muestra el dictamen (SÍ APLICA / NO APLICA / INDIFERENTE), la razón escrita, los valores presentes, el procedimiento matemático y una tabla de flujos.

| Operación | Pregunta | Aplica cuando |
|---|---|---|
| Compra | ¿Los beneficios futuros justifican la inversión? | El VAN es positivo. También muestra la TIR |
| Alquiler | ¿Conviene alquilar en lugar de comprar? | Alquilar cuesta menos que comprar en valor presente |
| Venta | ¿Conviene vender hoy o conservar? | Lo que se recibe vendiendo hoy supera el valor presente de conservar |

Si los flujos cambian cada periodo, en Compra y Venta se pueden escribir en el campo *Flujos netos por periodo*, separados por coma. En ese caso el número de periodos es la cantidad de montos escritos.

## Cómo abrirla

**Opción 1:** doble clic en `ABRIR_FINDEC.bat` o en `index.html`. Se abre en el navegador. No requiere instalar nada ni internet.

**Opción 2 (Visual Studio Code):** *Archivo > Abrir carpeta* y elegir `FINDEC`. Con la extensión **Live Server**, clic derecho sobre `index.html` y *Open with Live Server*.

## Cómo usarla

1. Elegir la operación en el menú de la izquierda.
2. Escribir los datos del caso, o usar *Cargar ejemplo*.
3. Tocar *Evaluar operación* y leer el dictamen. *Limpiar* vacía los campos.

Supuestos: montos en quetzales, tasa efectiva por periodo, flujos al cierre de cada periodo, sin financiamiento ni impuestos adicionales.

## Estructura

```
FINDEC/
├── index.html          # la aplicación completa
├── ABRIR_FINDEC.bat    # acceso directo para Windows
├── README.md
└── .vscode/extensions.json
```
