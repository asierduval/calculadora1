# 🧮 Calculadora Web - Guía de Usuario

**Versión:** 1.0.0  
**Fecha:** 03 de febrero de 2026

---

## 📋 Descripción General

Esta es una calculadora web interactiva y moderna que te permite realizar operaciones matemáticas básicas directamente desde tu navegador. Con un diseño elegante y funcional, incluye todas las operaciones esenciales que necesitas en tu día a día.

---

## ✨ Características Principales

- ➕ **Operaciones básicas:** Suma, resta, multiplicación y división
- 🎨 **Diseño moderno:** Interfaz atractiva con degradado de colores
- ⌨️ **Soporte de teclado:** Puedes usar tanto el ratón como el teclado
- 🔄 **Animaciones suaves:** Efectos visuales en los botones
- ⚠️ **Manejo de errores:** Detecta y notifica operaciones inválidas
- 📱 **Responsive:** Se adapta a diferentes tamaños de pantalla

---

## 🎯 Cómo Usar la Calculadora

### Con el Ratón 🖱️

1. **Introducir números:** Haz clic en los botones numéricos (0-9)
2. **Punto decimal:** Usa el botón "." para números decimales
3. **Operaciones:** Selecciona +, -, ×, o / según la operación deseada
4. **Calcular resultado:** Presiona el botón "=" para obtener el resultado
5. **Borrar:** Usa "←" para borrar el último carácter o "C" para limpiar todo

### Con el Teclado ⌨️

- **Números:** Teclas 0-9
- **Punto decimal:** Tecla "."
- **Operaciones:** Teclas +, -, *, /
- **Calcular:** Tecla "Enter" o "="
- **Limpiar:** Tecla "Escape" o letra "C"
- **Borrar:** Tecla "Backspace" (retroceso)

---

## 🔧 Funciones Explicadas

### 📺 `actualizarPantalla()`
**¿Qué hace?** Actualiza el display de la calculadora mostrando el valor actual.

**Cuándo se usa:** Cada vez que introduces un número, realizas una operación o borras algo.

---

### 🔢 `agregarNumero(num)`
**¿Qué hace?** Añade un número o punto decimal a la pantalla.

**Características especiales:**
- Previene múltiples puntos decimales
- Reemplaza el "0" inicial cuando introduces el primer número
- Inicia un nuevo número después de calcular un resultado

---

### ➗ `agregarOperador(op)`
**¿Qué hace?** Añade un operador matemático (+, -, ×, /)

**Inteligencia incorporada:**
- Si ya hay una operación pendiente, la calcula automáticamente antes de añadir el nuevo operador
- Añade espacios para mejor legibilidad

---

### 🎯 `calcular()`
**¿Qué hace?** Ejecuta la operación matemática y muestra el resultado.

**Seguridad:**
- Convierte el símbolo "×" en "*" para el cálculo
- Captura errores de operaciones inválidas
- Muestra "Error" si algo sale mal y limpia automáticamente después de 1.5 segundos

---

### 🧹 `limpiar()`
**¿Qué hace?** Resetea la calculadora completamente.

**Efecto:** Vuelve todo a su estado inicial (pantalla en "0", sin operadores pendientes)

---

### ⬅️ `borrar()`
**¿Qué hace?** Elimina el último carácter introducido.

**Comportamiento:**
- Si hay más de un carácter, elimina el último
- Si solo hay un carácter, lo reemplaza por "0"

---

## 🎨 Elementos Visuales

### Colores y Estilo

- **🟦 Fondo:** Degradado morado-azul elegante
- **⬛ Calculadora:** Fondo gris oscuro con bordes redondeados
- **📟 Pantalla:** Fondo negro con texto blanco grande
- **🔵 Números:** Botones grises con hover interactivo
- **🟠 Operadores:** Botones naranjas destacados
- **🟢 Igual:** Botón verde grande (ocupa 2 espacios)
- **🔴 Limpiar:** Botón rojo para resetear

---

## 💡 Consejos de Uso

1. **Operaciones en cadena:** Puedes realizar varias operaciones seguidas sin necesidad de presionar "=" entre cada una
2. **Corrección rápida:** Usa la tecla Backspace para corregir errores sin tener que empezar de nuevo
3. **Decimales:** Solo puedes añadir un punto decimal por número
4. **Atajo rápido:** Presiona "Escape" para limpiar todo rápidamente

---

## ⚠️ Limitaciones

- La calculadora usa operaciones básicas y no incluye funciones científicas
- Los resultados muy largos pueden salirse de la pantalla
- No soporta paréntesis para priorizar operaciones (calcula de izquierda a derecha)

---

## 🎓 Para Estudiantes

Esta calculadora es un excelente ejemplo para aprender:

- **HTML:** Estructura de elementos y botones
- **CSS:** Diseño responsive, grid layout, animaciones
- **JavaScript:** Manipulación del DOM, eventos, lógica de operaciones
- **Buenas prácticas:** Manejo de errores, validación de entrada

---

## 📞 Soporte

Si encuentras algún problema o tienes sugerencias de mejora, esta guía te ayudará a entender cómo funciona la calculadora internamente.

---

**¡Disfruta calculando! 🎉**

# Tareas pendientes:
- [x] Añadir funciones de memoria
- [ ] Incluir conversión de binario a hex
- [ ] Añadir pin de usuario

# Imagen desde una URL:
![Imagen microprocesador] (https://www.adslzone.net/app/uploads-adslzone.net/2018/05/mos-6502.jpg)
