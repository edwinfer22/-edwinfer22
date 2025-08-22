# 📌 Notas de Git

## 🚀 Alias útiles de Git

Para hacer más rápido tu flujo de trabajo con Git, puedes usar estos alias:

```bash
# Muestra todos los alias configurados
git config --get-regexp alias
```

### 📌 Alias configurados

- **Guardar y subir cambios de una vez**

  ```bash
  git save "mensaje"
  ```

  👉 Hace `git add -A`, `git commit -m "mensaje"` y `git push origin main`

- **Agregar + commit (sin push)**
  ```bash
  git acp "mensaje"
  ```
  👉 Hace `git add -A` y `git commit -m "mensaje"`

---

### 🔧 Comandos útiles adicionales

- **Ver cambios en el repositorio**
  ```bash
  git status
  ```
- **Ver historial de commits**
  ```bash
  git log --oneline --graph --decorate
  ```
- **Deshacer cambios en un archivo**
  ```bash
  git restore nombre_archivo
  ```

---

✅ Con esto tienes a la mano un mini **chuletario de Git** que te sirve en cualquier proyecto.
