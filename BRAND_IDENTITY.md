# 🌿 DSIG - Brand Identity & Guidelines 🔍

> **DSIG** | GESTIÓN DE SEMILLEROS
> *Innovación, investigación y desarrollo estructurado de proyectos.*

---

## 💡 Concepto de la Marca

El isotipo fusiona dos conceptos clave para la aplicación:
1. **La Lupa (🔍):** Representa el enfoque, la investigación y el análisis profundo.
2. **El Brote (🌱):** Representa el semillero, el crecimiento, el ciclo de vida de un proyecto y la incubación de nuevas ideas.

---

## 🔠 Tipografía (Implementación UI)

Para asegurar compatibilidad nativa en entornos Windows manteniendo una estética geométrica, limpia y minimalista, la aplicación utiliza la familia tipográfica **Century Gothic**.

### 📌 Tipografía Principal (Títulos y Logotipo)
Utilizada para la sigla **DSIG**, encabezados principales, títulos de secciones y elementos destacados de la interfaz para transmitir solidez.
* **Fuente:** `Century Gothic`
* **Estilo:** `Bold`
* **Código C#/XAML:** `FontFamily="Century Gothic" FontWeight="Bold"`
* **Caracteres:** `A B C D E F G H I J K L M N Ñ O P Q R S T U V W X Y Z`

### 📝 Tipografía Secundaria (Textos Generales y Descriptivos)
Utilizada para el texto "GESTIÓN DE SEMILLEROS", cuerpos de texto, descripciones, botones secundarios y controles estándar de la UI. Mantiene la ligereza visual.
* **Fuente:** `Century Gothic`
* **Estilo:** `Regular` (Normal)
* **Código C#/XAML:** `FontFamily="Century Gothic" FontWeight="Normal"` *(o omitiendo el atributo FontWeight)*
* **Caracteres:** `a b c d e f g h i j k l m n ñ o p q r s t u v w x y z`
* **Números:** `0 1 2 3 4 5 6 7 8 9`

---

## 🎨 Paleta de Colores

A continuación, los códigos de color corporativos para su implementación. 

### 🟩 Verde Orgánico (Crecimiento)
Aplicado en las hojas y el arco superior del isotipo. Representa la vitalidad de los proyectos.
* **HEX:** `#3C7A4A`
* **RGB:** `60, 122, 74`

### 🟦 Azul Profundo (Tecnología y Foco)
Aplicado en el arco inferior de la lupa. Representa la base tecnológica y la seriedad investigativa.
* **HEX:** `#1D4F7C`
* **RGB:** `29, 79, 124`

### ⬛ Gris Antracita (Elegancia y Texto)
Aplicado en la tipografía y el mango de la lupa. Proporciona un contraste excelente sin la dureza del negro puro.
* **HEX:** `#4A4A4A`
* **RGB:** `74, 74, 74`

### ⬜ Blanco Hueso (Fondo y Espacio Negativo)
Utilizado para los fondos de la aplicación, permitiendo que la interfaz respire.
* **HEX:** `#F4F4F4`
* **RGB:** `244, 244, 244`

---

## 📱 Notas de Implementación UI
* **Jerarquía Tipográfica:** Mantén estricta la regla de aplicar `Bold` solo para títulos y elementos de primer nivel. El resto de la interfaz debe respirar con la variante regular.
* **Área de Respeto:** Mantén siempre un margen generoso alrededor del logotipo para evitar saturación visual en las ventanas de la aplicación.
* **Dark Mode:** Si implementas un tema oscuro, asegúrate de invertir el Gris Antracita (`#4A4A4A`) por un gris muy claro o blanco humo para que el texto mantenga un contraste óptimo.
