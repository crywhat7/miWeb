###Git
  * Comando basicos de git
    (Inicializar un proyecto) -> git init
    (Agregar un archivo) -> git add
    (Ver el estado) -> git status
    (Hacer un cambio) -> git commit -m "Comentario"
    (Ver el historial) -> git log --oneline
    () -> git push
    () -> git pull
    (Ramas) -> git checkout
    (Ver los cambios) -> git diff "archivo.ext"
    (Subir los archivos a la nube) -> git remote add origin "url"

  * Clonacion de Repositorios
    (Clonar un repositorio) -> git clone

  * Cambiar entre ramas
    (Crear Rama) -> git checkout -b "Nombre Rama"
    (Cambiar Rama) -> git checkout "Nombre Rama"
    (Ver ramas) -> git branch

  * Crear Stashes y saber que son y para que sirven
    Sirven para guardar todo el trabajo que hemos estado realizando en una rama
    y poder cambiarnos a otra en el caso de que sea estrictamente necesario.
    (Comandos)
      git stash save "Comentario" -> (Guarda el progreso.)
      git stash apply -> (Aplicar los ultimos cambios en el stash en la rama que estamos.)
      git stash list -> (Ver la lista de stash)
      git stash drop -> (Eliminar el stash)
      git stash show *Nombre del Stash* -> (Muestra el estado de un stash)
      git stash branch "Rama nombre" "Nombre stash" -> (Crea una rama nueva a partir de un stash)

  * Crear Pull Requests

  * Recomendaciones para hacer Comit
    1- Usar verbos imperativos (agregar, cambiar, solucionar, remover).
    2- Utilizar como maximo 50 caracteres para el mensaje del commit.
    3- Darle uso al cuerpo del commit agregando todo lo necesario para comprender la razon por la cual
    se realizo el commit.
    https://medium.com/@jmz12/buenas-pr%C3%A1cticas-para-commits-5eb4c86b9a47    

  * Estructura de las ramas recomendadas para un proyecto
    Ramas principales y ramas auxiliares.
      Las ramas principales: Master y Develop
      Las ramas secundarias: Feature, Release y Hotfix    
      Siempre debemos integrar codigo en otras ramas (auxiliares) antes de integrar con las ramas Master y Develop (principales)

  * Saber para que sirve cada tipo de rama
    Feature: Sirve para nuevas caracteristicas, nuevos requisitos o nuevas historias de usuario.
    Release: Para estandarizar o cortar una serie de codigo que ha estado desarrollandose en la rama Develop.
    Hotfix: Sirve para depurar codigo que venga de produccion, cuando se detecta un defecto critico y deba resolverse de inmediato.

  * Uso de SourceTree

  * Hacer merge entre ramas
    (Hacer un merge) -> git merge "Nombre Rama"

  * Rebase entre ramas
    git rebase -> (Sirve para realizar un fast forward: Cuando estamos haciendo cambios en otra rama, en vez de hacer un merge
    podemos hacer un rebase, que trae los commits realizados en la primer rama y agrega los commits de la rama en la que estamos
    trabajando, luego hace un commit a la primer rama, generando una grafica lineal)

  * Revert
    git revert "Commit" -> (Mediante este comando podemos revertir el estado a un commit anterior pero no borra los commits que han pasado
    , hace un merge que contiene el revert que realizamos.)
    git reset --hard "Commit" -> (Este comando nos devuelve a un commit realizado, es un comando peligroso.)

  * Recuperacion de un Stash almacenado

###Angular
  * Typescript
  * Crear y usar interfaces o modelos
  * Linter (esLint u otros)
  * Redux o NgRx para manejar estados dentro de una aplicacion
  * Que son y como manejar los servicios en angular
  * Como conectarse a la base de datos desde un servicio
  * Pg Libreria para usar postgres con angular (Version mas reciente)
  * Nodejs
  * Nestjs
  * Herramientas para documentacion de codigo
  * Normas para la estructura del proyecto
  * CSS y SCSS para estilos adicionales
  * Primeng (Como usar paramtros entre componentes y vistas)
  * EventEmitter, BehaviorSubject, ViewChild, Input y Outputs en angular
  * Angular Router
  * Angular LifeCycles Hooks
  * SPA
  * API REST
  * Async y Await 
  * Responsive Design 
  * UX Flow

###Adobe XD
  * Como crear componentes y eventos en los mismos	
  * Como usar transiciones en los diseños
  * Material Theme para app moviles en XD	

###Servidores
  * PM2
  * Comando basicos para utilizar linux
  * comando git para usar en consola
  * SSH

###PostgreSql
  * Funciones
  * PgReference
  * Funciones de Arreglos en Postgres
  * Restauracion de base de datos

###AWS (Amazon Web Services)
  * S3
  * SDK de S3 para uso en aplicaciones en C#, JavaScript y PHP

###Generalidades
  * Funciones y metodos de los Arreglos
  * JSON
  * JWT (Json Web Token)
  * Patrones de diseño de Software
  * Iframes