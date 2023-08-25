---
tema: predeterminado
título: Usar git
información: |
  Usa Git - Lección 2: Usa git
  Ver https://github.com/barraponto/usegit
transición: deslizar-izquierda
dibujos:
  persistir: falso
exportar Nombre de archivo: 02-use-git.pdf
---

# Usa git

## con Capi Etheriel

[@barraponto](https://github.com/barraponto)

---
diseño: introducción
---

# git inicio

- cree el directorio de su proyecto **desde la línea de comando**
-git init

---
diseño: introducción
---

# configuración de git

- git config --global init.defaultBranch principal
- gato ~/.gitconfig

---
diseño: introducción
---

# rama git

- git rama -m principal
- no necesitas recordar este

---
diseño: introducción
---

# git agregar

- git agregar panqueques.md

---
diseño: introducción
---

#gitcompromiso

- git comprometerse

---
diseño: introducción
---

# git config nuevamente :/

- git config --global usuario.correo electrónico "barraponto@gmail.com"
- git config --global usuario.nombre "Capi Etheriel"

---
diseño: introducción
---

# git ¿qué estaba haciendo?

- estado de git

---
diseño: introducción
---

#gitcompromiso

<v-clics>

- git comprometerse
- Dios mío, ¿qué es esto?
- salir de vim

</v-clics>

---
diseño: introducción
---

# git config (última vez)

- git config --global core.editor "nano"

---
diseño: introducción
---

# git diferencia

<v-clics>

- volver a editar pancakes.md
- ¿Qué cambió? `git diferencia`
- etapa: `git add`
- confirmar: `git commit -m "mensaje"`

</v-clics>

---
diseño: introducción
---

#github

- registrarse (no se muestra)
- crear un repositorio
- ¡Vamos a usar SSH!

---
diseño: declaración
---

# ¿Qué es SSH?

<div class="max-w-prose mx-auto">
<v-clics>

SSH es un protocolo seguro para el acceso remoto a computadoras (servidores).

Admite **autenticación de clave pública** para evitar el envío de contraseñas a través de la red.

También cifra en gran medida todas las comunicaciones que pasan por él, lo que lo hace útil para la administración remota, transferencias de datos e incluso servidores proxy.

</v-clics>
</div>

---
diseño: introducción
---

#SSH

- ~~¿Qué es ssh?~~
- crea tu clave ssh:
  ssh-keygen -t ed25519 -C "barraponto@gmail.com"
- gato ~/.ssh/id_ed25519.pub
- edita tu configuración de Github

<!-- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account -->

---
diseño: introducción
---

# Empujar el repositorio

- git remoto agregar origen git@github.com:barraponto/usegit-recipes.git
- git push -u origen principal
---