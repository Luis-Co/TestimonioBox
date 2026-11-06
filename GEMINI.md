# Reglas del Proyecto TestimonioBox

## Despliegue Continuo (Git & Dokploy)
- **Commit y Push inmediato**: Después de realizar cualquier modificación en los archivos del proyecto, haz `git add`, `git commit` y `git push` inmediatamente sin esperar a que el usuario lo pida, para que Dokploy despliegue los cambios automáticamente.
- **Identidad de Git**: Al hacer commit, utiliza siempre la identidad configurada del autor (`git -c user.name="Luis Manuel Corea Cabrera" -c user.email="corea3000@gmail.com" commit -m "..."`) si el entorno local no tiene `user.name` y `user.email` definidos globalmente.

