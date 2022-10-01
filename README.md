## Despliegue de apps Spring Boot en Heroku

Crear archivo 'system.properties' a nivel de proyecto con el contenido:

```
java.runtime.version = 17
```

1. Crear cuenta en heroku.com  y github.com
2. Tener configurado git en el ordenador
   1. git config --global user.name "Bryan Corrales"
   2. git config --global user.email bryan@example.com
3. Subir el proyecto a Github desde Intellij IDEA desde la opción: VCS > Share project on Github
4. Desde Heroku, crear app y elegir método Github y buscar el repositorio subido
5. Habilitar deploy automático y ejecutar el Deploy