# 🚀 Guía de Commits Convencionales

Para mantener nuestro historial de versiones limpio, legible y estandarizado, estructuraremos nuestros mensajes de commit siguiendo la convención de **Conventional Commits**. ✨

---

## 🏗️ Estructura del Mensaje

Todo commit debe seguir estrictamente este formato:

`🧩 <tipo>[ámbito opcional]: <descripción>`

---

## 🏷️ Tipos Permitidos

Solo utilizaremos los siguientes **4 tipos** para clasificar nuestro trabajo en el equipo:

* ✨ **`feat`**: Introduce una nueva característica o funcionalidad.
* 🐛 **`fix`**: Soluciona un error o bug en el código.
* ♻️ **`refactor`**: Un cambio en el código que no corrige un error ni añade funcionalidad (ej. reestructuración, limpieza, aplicación de patrones como Clean Architecture).
* 🧹 **`chore`**: Tareas de mantenimiento, actualización de dependencias o cambios en la configuración que no afectan el código de producción.

---

## 📜 Reglas de Oro

1. 🔤 **Minúsculas**: El `<tipo>` debe ir siempre en minúsculas.
2. 🗣️ **Imperativo**: La `<descripción>` debe escribirse como una orden (ej. "agregar", "corregir", "actualizar"). Completa mentalmente la frase: *"Si aplico este commit, esto va a..."*
3. 🎯 **Brevedad**: Sé directo. No uses punto final al terminar la descripción.

---

## ✅ Ejemplos Correctos

* `feat: agregar pantalla de inicio de sesión con biometría`
* `fix: corregir desbordamiento de texto en tarjetas del home`
* `refactor: simplificar inyección de dependencias en el repositorio`
* `chore: actualizar versiones de paquetes en pubspec.yaml`
