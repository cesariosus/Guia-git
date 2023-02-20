# Guia-git

guit init- funciona para crear un nuevo repositorio de git, o para crear un proyecto existente en un repositorio de git. o uno vacio 
![image](https://user-images.githubusercontent.com/125385304/220131865-e43ab91b-6243-485f-b430-959d1a39695c.png)


git remote add origin "url repo"- este comando te permite enlazar tu repositorio con la pagina de github ubicarla y guardar los cambios hechos
![image](https://user-images.githubusercontent.com/125385304/220132853-84d0b81d-d5d5-4dae-b653-4721a710a0e2.png)


git status- este nos permite ver el estado de nuestro directorio, el entorno del ensayos y ver los archivos qie estan por subirse
![image](https://user-images.githubusercontent.com/125385304/220133970-887b4390-7dfb-4228-b407-416a63141573.png)


git fetch origin main- un comando principal que se usa para descargar contenidos desde un repositorio remoto 
![image](https://user-images.githubusercontent.com/125385304/220134634-362377f1-eeb3-4045-85d8-a6c79ecf50d3.png)


git pull origin main- se emplea para extraer y descargar contenido desde un repositorio remoto y actualizar al instante el repositorio local para reflejar ese contenido
![image](https://user-images.githubusercontent.com/125385304/220135151-986fb4a6-3c5b-4585-ab61-604d21e31d56.png)


git add . - añade un cambio del directorio de trabajo en el entorno de ensayo. De este modo, indica a Git que quieres incluir actualizaciones en un archivo concreto en la próxima confirmación.
![image](https://user-images.githubusercontent.com/125385304/220135887-6a001241-d06d-4799-8c71-adb92b1ebfaf.png)


git commit -m "name commit" - permite hacer instantáneas del estado actual del trabajo y guardar los cambios
![image](https://user-images.githubusercontent.com/125385304/220137479-a04d650e-4e84-43d1-a03f-e1cda9f42fbf.png)


git push -u origin main - Usa git push para insertar confirmaciones realizadas en la rama local en un repositorio remoto.
![image](https://user-images.githubusercontent.com/125385304/220137374-5d29fda2-3cba-47d3-8c9b-2344fb70c860.png)


estos pasos se utilizan cuando estamos creando el repositorio por primera vez, pero si queremos solo subir algun cambio de un repositorio ya existente solo sera utilizar git fetch origin main - git pull origin main - git add . - git commit -m y git push -u. 
