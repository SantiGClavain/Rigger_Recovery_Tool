# Rigger_Recovery_Tool

Proyecto con utilidades MEL para Maya (herramientas simples para crear objetos y detectar objetos "bakeados").

Cómo probar localmente

1. Abrir Maya y el Script Editor (lenguaje MEL).
2. Sourcear el script MEL principal (ajusta la ruta si no corresponde):

```mel
source "C:/Users/sgonzalez/OneDrive - Virtualware 2007 S.A/Programacion/MEL/Rigger_Recovery_Tool/Rigger_Recovery_Tool/Rigger_Recovery_Tool.mel";
```

3. Ejecutar la función (tras source):

```mel
GetBakedObjects("Bake_set");
```

Comandos Git (PowerShell)

- Inicializar repo local (si aún no lo has hecho):

```powershell
git init
git add .
git commit -m "Initial commit"
```

- Conectar con el repo remoto en GitHub (reemplaza la URL):

```powershell
git remote add origin https://github.com/tuUsuario/Rigger_Recovery_Tool.git
git branch -M main
git push -u origin main
```

Si prefieres que cree el `.gitignore` y otros ficheros iniciales aquí, puedo generarlos ahora.
