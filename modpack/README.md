# Archivos del cliente de Aeldoria RPG

Esta carpeta define cómo se organiza el cliente que instalará Aeldoria Launcher.

## Dónde colocar cada archivo

- `mods/`: mods necesarios en el cliente.
- `config/`: configuraciones comunes del modpack.
- `defaultconfigs/`: configuraciones predeterminadas de Forge.
- `resourcepacks/`: paquetes de recursos obligatorios.
- `shaderpacks/`: shaders opcionales.
- `customnpcs/`: recursos de CustomNPCs que necesite el cliente.
- `kubejs/`: scripts y recursos KubeJS que necesite el cliente.
- `overrides/`: otros archivos respetando su ruta dentro de la instancia.

## Importante

Los archivos `.jar` y otros binarios del modpack se publicarán como assets de GitHub Releases. No deben añadirse directamente al historial del repositorio. Esta estructura sirve como zona de preparación y referencia para generar `distribution.json`.

No incluyas mundos, datos de jugadores, logs, copias de seguridad, claves, tokens, configuraciones privadas del servidor ni mods exclusivamente de servidor.
