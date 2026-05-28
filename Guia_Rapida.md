# PawMatch - Guia Rapida

## Instalacion

1. Copia la carpeta `PawMatchV2` a `C:\xampp\htdocs\`
2. Abre XAMPP y da Start a **Apache** y **MySQL**
3. Ve a `http://localhost/phpmyadmin`, crea una BD llamada `pawmatch` e importa `database/pawmatch_complete.sql`
4. Abre `http://localhost/PawMatchV2/public/`

Si ves errores 404 al usar la app, habilita `mod_rewrite` en `C:\xampp\apache\conf\httpd.conf`: descomenta la linea `LoadModule rewrite_module` y cambia `AllowOverride None` a `AllowOverride All` dentro del bloque de `htdocs`. Reinicia Apache.

---

## Credenciales de prueba

| Correo | Contrasena | Rol |
|---|---|---|
| admin@pawmatch.com | Admin@123 | Administrador |
| juan@pawmatch.com | Admin@123 | Usuario |

---

## Que puedes hacer

- **Buscar Mascotas** - filtra por especie, tamaño y energia, haz clic en una tarjeta para ver el detalle y solicitar la adopcion
- **Test** - responde 5 preguntas sobre tu estilo de vida y recibe recomendaciones de mascotas
- **Reportes** - haz clic en el mapa para marcar donde viste un animal callejero y reportarlo
- **Donar** - ingresa un monto en MXN y un mensaje opcional
- **Solicitudes** - consulta el estado de tus solicitudes de adopcion (pending / approved / rejected)
- **Perfil** - edita tu nombre, ubicacion, telefono y bio

El administrador ademas puede agregar, editar y eliminar mascotas, aprobar o rechazar solicitudes y eliminar reportes.
