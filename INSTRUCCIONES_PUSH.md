# Instrucciones para Subir Código a GitHub

## 🔐 Problema de Autenticación

El error `403 Permission denied` indica que necesitas autenticarte correctamente con GitHub.

## ✅ Opciones para Solucionarlo

### Opción 1: Autenticarse con Personal Access Token (Recomendado)

1. **Generar un Personal Access Token:**
   - Ve a: https://github.com/settings/tokens
   - Click en "Generate new token (classic)"
   - Dale un nombre (ej: "TestBotCypress")
   - Selecciona el scope `repo` (acceso completo a repositorios)
   - Click en "Generate token"
   - **Copia el token** (solo se muestra una vez)

2. **Usar el token para hacer push:**
   ```bash
   git push origin main
   ```
   
   Cuando te pida credenciales:
   - Username: `danigonzalez21201`
   - Password: **Pega el token que generaste**

### Opción 2: Actualizar Credenciales en macOS Keychain

Si tienes credenciales guardadas en la Keychain de macOS:

```bash
# Ver credenciales guardadas
git credential-osxkeychain erase
host=github.com
protocol=https

# Luego intenta de nuevo
git push origin main
```

### Opción 3: Configurar Git Credential Manager

```bash
# Configurar para que pida credenciales
git config --global credential.helper osxkeychain

# Hacer push (te pedirá tus credenciales)
git push origin main
```

## 📤 Comandos Listos para Ejecutar

Una vez que estés autenticado, ejecuta:

```bash
cd /Users/danielagonzalez/Desktop/Automation/Cypress/TestBotCypress
git push origin main
```

## ✅ Verificar

Después del push, verifica en: https://github.com/danigonzalez21201/Cypress

---

## 📋 Resumen de Commits Listos

Los siguientes commits están listos para subir:

1. ✅ `Mejoras en código: limpieza de imports, manejo de errores y documentación` (features)
2. ✅ `Agregar requirements.txt y .gitignore`
3. ✅ `Actualizar submódulo features con mejoras`
4. ✅ `Agregar README.md con documentación del proyecto`

Solo necesitas autenticarte para hacer el push.

