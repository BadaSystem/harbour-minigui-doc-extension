# 🚀 harbour-minigui-doc-extension

🌐 <b>Select Language:</b> 🇺🇸 <a href="README.md">English</a>  · 🇪🇸 <b>Español</b>

---

Una extensión potenciada para **Visual Studio Code** que mejora el soporte para los lenguajes de programación **Harbour** y **xHarbour**, basada originalmente en el excelente trabajo de Antonino Perricone (`harbourCodeExtension`).

---

## ✨ Características Principales (Features)

### 🌟 Nuevas Características Añadidas
* **Soporte para MiniGUI Extended:** Autocompletado, resaltado de sintaxis y herramientas específicas para el desarrollo con la librería gráfica MiniGUI Extended.
* **Sistema de Documentación harbour-doc:** Soporte completo y formateo para comentarios de documentación al estilo `harbour-doc` (totalmente compatible con el formato **Javadoc**).

### 🛠️ Características Heredadas de la Extensión Original
* **Resaltado de sintaxis:** Configuración robusta en colaboración con Edgard Lorraine Messias.
* **Soporte de Depuración (Debug):** Herramientas para depurar tu código directamente.
* **Información de Diagnóstico:** Validación de errores en tiempo real.
* **Proveedor de Símbolos en Documento:** Acceso rápido presionando `CTRL + SHIFT + O` (o `CTRL + P` seguido de `@`).
* **Proveedor de Símbolos en Espacio de Trabajo:** Acceso global presionando `CTRL + T` (o `CTRL + P` seguido de `#`).

---

## ⚙️ Configuración de la Extensión (Settings)

Esta extensión aporta las siguientes configuraciones en VS Code:

* `harbour.validating`: Activa/desactiva la validación cada vez que abres o guardas archivos Harbour.
* `harbour.compilerExecutable`: Ruta completa al ejecutable del compilador Harbour (necesario si la validación automática falla).
* `harbour.extraIncludePaths`: Rutas adicionales para buscar archivos de cabecera (`.ch` / `.h`) y evitar errores de archivo no encontrado.
* `harbour.extraOptions`: Parámetros u opciones extra para pasar directamente al compilador.
* `harbour.warningLevel`: Define el nivel de alertas (*warnings*) para la validación de código.
* `harbour.decorator`: Si se activa (`true`), habilita la decoración visual de bloques correspondientes (`if/endif`, `for/next`, `while/endwhile`, etc.).

---

## 🐞 ¿Cómo usar el Depurador?

Puedes ejecutar el comando **"Harbour: Get debugger code"** para obtener el código fuente del depurador. Guarda el resultado en un archivo (por ejemplo, `dbg_lib.prg`). 
* Puedes incluir este archivo directamente en tu proyecto.
* **RECOMENDADO:** Compilar este archivo como una librería externa y enlazarla en los archivos de configuración de tu proyecto.

> ⚠️ **Nota Importante:** Recuerda compilar siempre tus archivos Harbour usando el parámetro `-b` para incluir la información de depuración.

---

## 📜 Créditos, Licencia y Agradecimientos

Este proyecto se distribuye bajo la **Licencia MIT**. 

Esta extensión es un fork mejorado que extiende el código original creado por **Antonino Perricone** (`APerricone/harbourCodeExtension`). Agradecemos enormemente su contribución inicial y la de todos los colaboradores del proyecto base.
