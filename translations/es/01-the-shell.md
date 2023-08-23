---
theme: default
title: Usar la Terminal
info: |
  Usar Git - Lección 1: Usar la terminal
  Ver https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 01-la-terminal.pdf
---

# Usar la Terminal

## con Capi Etheriel

[@barraponto](https://github.com/barraponto)

---
layout: statement
---

# ¿Qué es la terminal?

<div class="max-w-prose mx-auto">
<v-clicks>

La terminal es un programa que proporciona una interfaz de línea de comandos al usuario final.

</v-clicks>
</div>

---
layout: statement
---

# ¿Qué es un shell?

<div class="max-w-prose mx-auto">
<v-clicks>

En general, un shell es una interfaz hacia la computadora.

Un shell gráfico permite hacer clic en íconos y ver salidas gráficas como ventanas.

Un shell de línea de comandos permite ingresar texto (comandos) y recibir líneas de texto como salida (la mayoría de las veces).

</v-clicks>
</div>

---
layout: statement
---

# ¿Qué es un comando?

<div class="max-w-prose mx-auto">
<v-clicks>

Un comando es una representación textual de lo que se le pide a la computadora. Si desea enviar un correo electrónico a su jefe para solicitar un aumento, ya redactado en un archivo específico, podría hacerlo de la siguiente manera:
mail --subject="necesito un aumento" jefe@empresa.com < ./contents.txt

</v-clicks>
</div>

---
layout: intro
---

# Abrir la terminal

---
layout: intro
---

# Configurar la terminal

---
layout: intro
---

# ¿Hay algún programa en ejecución en este momento?

---
layout: statement
---

# ¿Qué es un intérprete?

<div class="max-w-prose mx-auto">
<v-clicks>

Un intérprete es un programa que toma su entrada y ejecuta los programas necesarios para procesarla, _compilando_ los programas si es necesario.

También permite lógica como condiciones y bucles.

Por cierto, el intérprete es también un REPL (entorno de ejecución de lectura-evaluación-impresión) para un lenguaje de scripting llamado **script shell**.

</v-clicks>
</div>

---
layout: intro
---

# ¿Cómo encuentra el shell los programas?

---
layout: statement
---

# ¿Qué es el PATH?

<div class="max-w-prose mx-auto">
<v-clicks>

La variable `PATH` es una variable de entorno estándar que enumera los directorios donde el intérprete debe buscar los programas. El primer directorio que contiene un programa con ese nombre se utilizará.

</v-clicks>
</div>

---
layout: statement
---

# ¿Qué es una variable de entorno?

<div class="max-w-prose mx-auto">
<v-clicks>

Una variable de entorno es un valor con un nombre.

Están disponibles para sus comandos.

Algunas son convencionales, como `PWD`, `PATH`, `PS1`.

También puede crear sus propias variables.

</v-clicks>
</div>

---
layout: intro
---

# ¿Cómo puedo ver las variables de entorno?

Respuesta: `env`

---
layout: intro
---

# ¿Cómo puedo configurar estas variables?

Respuesta: `.bashrc` o `.zshrc` o dependiendo de su shell.

---
layout: intro
---

# ¿Qué shell estoy usando?

Respuesta: `echo $0`

---
---

# Pongámoslo en práctica
<br>

Objetivo: instalar tealdeer 

1. Crear un directorio `Descargas`
2. Acceder a este directorio (navegar a él con cd)
3. Descargar tealdeer desde https://github.com/dbrgn/tealdeer/releases
4. Ejecutar tealdeer con `./tealdeer`
   4.1. Cambiar permisos si es necesario
5. Colocar tealdeer en el `PATH`
6. Renombrar tealdeer (opcional)
7. Usar `tldr` para todo
