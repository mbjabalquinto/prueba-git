Se ha realizado todo el laboratorio desde cmd de windows. Comandos emplemados en orden siguiendo las intrucciones del laboratorio:
git add nuevo_archivo.py
git commit -m "Creo nuevo archivo para subir los cambios a GitHub."
git push origin main
git branch development
git switch development
git add nuevo_archivo.py
git commit -m "Hago cambios en el nuevo archivo de la rama: rama_nueva."
git push --set-upstream origin development
git checkout main
git merge development
git push origin

