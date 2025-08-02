# Documentación de appsettings.Production.json

Este archivo contiene comentarios y documentación para el archivo `appsettings.Production.json`.

---
**Nota:** El formato JSON estándar no admite comentarios. Este archivo Markdown sirve como complemento para proporcionar explicaciones y contexto para la configuración en `appsettings.Production.json`.

## mailKit

```json
"mailKit": {
    "Name": "Roomee",
    "Email": "vinhphucit02@gmail.com",
    // "Password": "qfvjrvwjozrxyrwp", // Consider using environment variables for sensitive information
    "Password": "" // Placeholder for environment variable
    "Host": "smtp.gmail.com",
    "Port": 587
}
```
**Comentarios:**
- `Password`: Se recomienda usar variables de entorno para información sensible. El valor actual es un marcador de posición.

## sql

```json
"sql": {
    "Server": "sql",
    "Database": "rest_hotel",
    "TrustServerCerti ficate": false,
    "Encrypt": true, // Changed to true for security. Consider using environment variables for sensitive information.
    "Username": "sa", // Consider using environment variables for sensitive information.
    "Password": "" //pa55w0rd!  Placeholder for environment variable. Consider using environment variables for sensitive information.
}
```
**Comentarios:**
- `Encrypt`: Cambiado a `true` por seguridad. Se recomienda usar variables de entorno para información sensible.
- `Username`: Se recomienda usar variables de entorno para información sensible.
- `Password`: Marcador de posición para variable de entorno. Se recomienda usar variables de entorno para información sensible.
