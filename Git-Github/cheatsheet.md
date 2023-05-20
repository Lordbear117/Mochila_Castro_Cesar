# Comandos de git

## Primeros pasos
<br> 

### Configuración inicial
Para inciar el repositorio local

```
git init
git config user.name nombre
git config user.email correo
```

### Conocer estado actual de los cambios
```
git status
```

### Guardar cambios
git add . agrega todos los cambios y commit los agrega al repo.
```
git add .
git commit -m "mensaje"
```

### Eliminar cambios
Eliminar los cambios que se agregaron con git add
```
git reset
```

### Vincular con repositorio remoto
```
git remote add origin "nombre repositorio remoto"
```

### Subir cambios
Se suben los cambios que estan dentro del commit.
```
git push
&
git push origin main
```

### Bajar cambios
Se bajan los cambios mas actualizados del repositorio.
```
git pull
&
git pull origin main
```
<br>

## Pasos para repositorio existente

<br>

### Descargar repositorio a computadora
Como el nombre lo indica, crea una copia de un repositorio que ya existe.
```
git clone "enlace del repositorio"
```

### Pasos para subir o bajar cambios
Los pasos de siempre para subir nuevos cambios.
```
git add . 
git commit -m "mensaje"
git push
git pull
```