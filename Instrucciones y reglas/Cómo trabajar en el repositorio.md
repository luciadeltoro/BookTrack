
# 🚀 Cómo crear tu propia rama en Visual Studio Code (VSCode)

### **1. Asegúrate de tener el repositorio abierto**
1. Abre VSCode.
2. Ve al menú `Archivo` > `Abrir Carpeta` y selecciona la carpeta del repositorio en la que vas a trabajar.
3. Confirma que el repositorio está conectado a Git:
   - Ve al icono de **"Source Control"** (Control de Código Fuente, el que parece un ramo de ramas en la barra lateral izquierda).
   - Si el repositorio está conectado, verás un listado con los cambios no guardados.

### **2. Abre el Administrador de Ramas**
1. Ve a la **barra inferior izquierda** de VSCode. Allí verás algo como:

main ✔

Esto indica la rama actual (en este caso, `main`).

2. Haz clic en el nombre de la rama (`main`). Esto abrirá un menú desplegable para gestionar ramas.


### **3. Crea una nueva rama**
1. En el menú desplegable de ramas, selecciona la opción **"Create New Branch"** o **"Crear Nueva Rama"** (dependerá del idioma de tu VSCode).
2. Escribe el nombre de tu nueva rama:
- Ejemplo: `Tu_Nombre`.
1. Una vez creada, VSCode cambiará automáticamente a esa nueva rama.


### **4. Realiza tus cambios en la nueva rama**
1. Trabaja siempre en tu rama: agrega o edita archivos.
2. Cuando termines, guarda los cambios y realiza un **commit**:
- Ve a la barra lateral de **"Source Control"**.
- Escribe un mensaje breve describiendo los cambios (por ejemplo: `Añadí mi primera reseña`).
- Haz clic en el botón de checkmark (✔) para confirmar el commit.


### **5. Sube la nueva rama al repositorio remoto (GitHub)**

**Haz una Pull Request (PR):**  
   Para que tu reseña sea revisada y añadida a la rama principal (`main`), realiza una Pull Request:

   ### Pasos para crear una Pull Request:
   - Asegúrate de tener instalada la extensión **GitHub Pull Request** (la verificada por GitHub).  
   - En la barra lateral izquierda, haz clic en el icono de **GitHub Pull Request**.  
   - Dentro del apartado `Create`, verifica que:  
     - La **rama destino** (arriba) es `main`.  
     - Tu **rama personal** (abajo) es la que se está fusionando con la rama principal.  
   - Sigue las instrucciones para crear la Pull Request.  
   - Si es necesario, haz clic en `Update with merge commit` para sincronizar los cambios.

### **6. Confirma la rama en GitHub**
 1. Ve al repositorio en GitHub.
 2. Haz clic en el menú desplegable de ramas (arriba, donde dice main).
 3. Verifica que tu nueva rama aparece en la lista.

### **Consejo: Usa GitLens para facilitar la gestión de ramas**
Si tienes instalada la extensión GitLens, puedes visualizar y administrar ramas de manera más sencilla:
1. Haz clic en el menú de GitLens en la barra lateral izquierda.
2. Ve a la sección "Branches" para gestionar tus ramas y ver los cambios realizados.

##### ¡Y listo! Ahora tienes tu propia rama creada directamente desde Visual Studio Code y puedes trabajar sin afectar la rama principal (main). 😊

---

# Instrucciones para crear tu carpeta y trabajar en el repositorio BookTrack

## 📂 Crear tu carpeta de usuario
1. **Selecciona la carpeta correcta:** 
   - Navega hasta la carpeta `Usuarios` dentro del repositorio.
   - ¡Asegúrate siempre de estar en tu propia rama y no en la rama de otro usuario ni en `main`! 

2. **Crea tu carpeta personal:**
   - Haz clic en `Usuarios` y después en el icono de carpeta (`New Folder`) ubicado a la derecha de `BookTrack`.
   - Nombra tu carpeta con tu nombre, (si hay ya una carpeta con tu nombre, añade tu apellido o usa un apodo).

## 📝 Crear los archivos necesarios
Dentro de tu carpeta personal debes crear los siguientes archivos:  
- `README.md`: Este archivo será tu presentación personal.  
- `Lecturas.md`: Aquí registrarás tus lecturas.  
> 📄 **Nota:** Puedes encontrar plantillas para estos archivos en la carpeta llamada `Plantillas`.

## 🚀 Subir los cambios al repositorio
1. **Realiza un commit:**  
   Después de crear o modificar un archivo, guarda los cambios con un commit. 
   - Ve a la barra lateral izquierda y clica en `Source Control` Asegúrate de incluir una breve descripción de lo que has añadido o cambiado.  
   - Ejemplo: Si acabas de crear tu archivo `README.md`, el mensaje del commit podría ser:  
     `Creando README - [Tu Nombre]`  
   - Otro ejemplo: Si creas el archivo `Lecturas.md`, el mensaje sería algo como:  
     `Añadiendo archivo Lecturas - [Tu Nombre]`.
   - Una vez realizado lo anterior clicamos Sync commit(sincronizar commit).


2. **Haz una Pull Request (PR):**  
   Una Pull Request es una solicitud para que los cambios que has hecho en tu rama sean revisados y fusionados con la rama principal (`main`). 

   ### Pasos para realizar una Pull Request:
   - Asegúrate de tener instalada la extensión **GitHub Pull Request** (la verificada por GitHub).
   - En la barra lateral izquierda, haz clic en el icono de **GitHub Pull Request**.
   - Dentro del apartado `Create`, verás dos cajas:  
     - La **rama destino** (arriba) debe ser siempre `main`.  
     - Tu **rama personal** (abajo) es la que se está fusionando con la rama principal.
   - Sigue las instrucciones para crear la Pull Request.
   - Si clicamos en `Update with merge commit` sincronizará todo lo que no tengas en tu repositorio.

3. **Espera la aprobación:**  
   Una vez que hayas creado la Pull Request, tus cambios serán revisados y aceptados si cumplen los requisitos.

## 📚 ¡Listo para participar en los clubs!
Una vez que tengas tu carpeta y los archivos `README.md` y `Lecturas.md`, podrás:  
- Inscribirte en los clubs de lectura que desees.  
- Subir reseñas de libros (siempre que no haya una ya creada).  

## 💡 Consejos finales
- Sigue siempre los pasos explicados anteriormente. Puede parecer complicado al principio, pero después de realizar un par de commits y merges será mucho más sencillo.
- Si tienes dudas o encuentras algún problema, **contáctanos a través de nuestra cuenta de GitHub**. ¡Estaremos encantadas de ayudarte!
