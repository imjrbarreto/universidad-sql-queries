# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 13 correctas de 22 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.40 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,10 @@
 apellido1 | apellido2 | nombre | departamento
-Fahey | Considine | Antonio | Economía y Empresa
-Hamill | Kozey | Manolo | Informática
-Kohler | Schoen | Alejandro | Matemáticas
-Lemke | Rutherford | Cristina | Economía y Empresa
-Monahan | Murray | Micaela | Agronomía
-Ramirez | Gea | Zoe | Informática
-Ruecker | Upton | Guillermo | Educación
-Schmidt | Fisher | David | Matemáticas
-Schowalter | Muller | Francesca | Química y Física
-Spencer | Lakin | Esther | Educación
-Stiedemann | Morissette | Alfredo | Química y Física
-Streich | Hirthe | Carmen | Educación
+Heller | Pagac | Pedro | Educación
+Herzog | Tremblay | Ramón | Biología y Geología
+Koss | Bayer | José | Química y Física
+Lemke | Rutherford | Cristina | Derecho
+Ramirez | Gea | Zoe | Economía y Empresa
+Saez | Vega | Juan | Matemáticas
+Sánchez | Pérez | Salvador | Informática
+Schmidt | Fisher | David | Agronomía
+Strosin | Turcotte | Ismael | Filología
```

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.56 ms
✅ Se usó índice(s) en la consulta: PRIMARY,nif, PRIMARY, PRIMARY,id_asignatura,id_curso_escolar

---

## ❌ Query 8: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,22 @@
-nombre
-Informática
+nombre_departamento | nombre_asignatura
+Informática | Álgegra lineal y matemática discreta
+Informática | Cálculo
+Informática | Física para informática
+Informática | Introducción a la programación
+Informática | Organización y gestión de empresas
+Informática | Estadística
+Informática | Estructura y tecnología de computadores
+Informática | Fundamentos de electrónica
+Informática | Lógica y algorítmica
+Informática | Metodología de la programación
+Informática | Arquitectura de Computadores
+Informática | Estructura de Datos y Algoritmos I
+Informática | Ingeniería del Software
+Informática | Sistemas Inteligentes
+Informática | Sistemas Operativos
+Informática | Bases de Datos
+Informática | Estructura de Datos y Algoritmos II
+Informática | Fundamentos de Redes de Computadores
+Informática | Planificación y Gestión de Proyectos Informáticos
+Informática | Programación de Servicios Software
+Informática | Desarrollo de interfaces de usuario
```

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento, id_profesor,id_grado

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_departamento, id_profesor, id_asignatura

---

## ❌ Query 16: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-total
+total_alumnos
 12.00
```

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 17: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-total
+total_alumnos_nacidos_1999
 2.00
```

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-departamento | total
+departamento | total_profesores
 Educación | 3.00
 Informática | 2.00
 Matemáticas | 2.00
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_departamento

---

## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
-departamento | total
+departamento | total_profesores
+Educación | 3.00
 Informática | 2.00
 Matemáticas | 2.00
 Economía y Empresa | 2.00
-Educación | 3.00
+Química y Física | 2.00
 Agronomía | 1.00
-Química y Física | 2.00
 Filología | 0.00
 Derecho | 0.00
 Biología y Geología | 0.00
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-grau | total
+grado | total_asignaturas
 Grado en Ingeniería Informática (Plan 2015) | 51.00
 Grado en Biotecnología (Plan 2015) | 32.00
 Grado en Ingeniería Agrícola (Plan 2015) | 0.00
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-grau | total
+grado | total_asignaturas
 Grado en Ingeniería Informática (Plan 2015) | 51.00
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_grado

---

## ❌ Query 22: Error
- **Descripción**: 'NoneType' object is not iterable

