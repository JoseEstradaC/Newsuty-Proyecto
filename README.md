# Newsuty

Es una aplicación que nos permite compartir noticias y que la comunidad las pueda puntuar.

---
# Video Explicativo

https://youtu.be/TMROfnFNyRQ

---
# Codigo

El código y el apk se encuentra en este repo https://github.com/JoseEstradaC/Newsuty-Kotlin

---

Mi aplicación estará basada en el proyecto del primer trimestre. [https://github.com/JoseEstradaC/Newsuty-Kotlin](https://github.com/JoseEstradaC/Newsuty-Kotlin), la cual va a ser modificada para cumplir los objetivos de el proyecto.

- Se añadirán **Material Design Alert Dialogs,** para confirmar acciones
- Se añadirá el idioma ingles
- Se añadirá almacenamiento usando **firebase**
- Se usara la cámara del dispositivo para permitir agregar noticias de periódicos físicos, esta contará con un video explicativo de como usar esta función
- Se añadirán observables a la aplicación
- Además se añadirá un pagina de configuración para poder configurar el idioma y otros aspectos de la aplicación
- Se creara una landing page que cumpla los criterios de DI usando angular y hosteado con Flask.

---

## Base de datos

### News

| Campo | Tipo de datos | Opcional |
| --- | --- | --- |
| url | String | ✅ |
| urlImagen | String | ✅ |
| base64Imagen | String | ✅ |
| titulo | String | ❌ |
| userCreatorUID | String | ❌ |
| fechaPublicacion | Long | ❌ |

### NewsVotes

| Campo | Tipo de datos | Opcional |
| --- | --- | --- |
| newsID | Long | ❌ |
| userUID | String | ❌ |
| esLike | Boolean | ❌ |

Los usuarios se almacenan en firebase auth por tanto no lo contemplo en este esquema

---

## Figma

[Figma](https://www.figma.com/file/yE7cgYgX0NNrUcmfl3qZta/Newsuty?node-id=0%3A1)
