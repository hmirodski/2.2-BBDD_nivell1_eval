# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 2 correctas de 4 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.38 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 2: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio
-Disco duro SATA3 1TB | 86.99
-Memoria RAM DDR4 8GB | 120.00
-Disco SSD 1 TB | 150.99
-GeForce GTX 1050Ti | 185.00
-GeForce GTX 1080 Xtreme | 755.00
-Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 245.99
-Portátil Yoga 520 | 559.00
-Portátil Ideapd 320 | 444.00
-Impresora HP Deskjet 3720 | 59.99
-Impresora HP Laserjet Pro M26nw | 180.00
+precio | nombre
+86.99 | Disco duro SATA3 1TB
+120.00 | Memoria RAM DDR4 8GB
+150.99 | Disco SSD 1 TB
+185.00 | GeForce GTX 1050Ti
+755.00 | GeForce GTX 1080 Xtreme
+202.00 | Monitor 24 LED Full HD
+245.99 | Monitor 27 LED Full HD
+559.00 | Portátil Yoga 520
+444.00 | Portátil Ideapd 320
+59.99 | Impresora HP Deskjet 3720
+180.00 | Impresora HP Laserjet Pro M26nw
```

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 4: Error
- **Descripción**: 'NoneType' object is not iterable

