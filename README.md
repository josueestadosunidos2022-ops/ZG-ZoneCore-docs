# ZoneCore — Zone API

## English

**Summary:** Server-side integration API for the ZONE family of Minecraft Forge 1.20.1 mods.

ZoneCore lets ZONE server mods register configuration reload handlers, permission names, and a rank provider through one shared API. It contains no player-facing items or client interface.

### Install

1. Install Minecraft 1.20.1 with Forge 47.x on the server.
2. Place the official `zonecore` release JAR in the server's `mods` folder.
3. Install each ZONE mod together with the dependencies and versions listed on its own project page.
4. Start the server. Players do not need to install ZoneCore on their clients.

### Command and permissions

`/zonecore reload` reloads the TOML configuration of ZONE modules that registered a reload handler. It requires Minecraft operator permission level 2. A JAR update still requires a server restart.

### TOML configuration

Forge creates `config/zonecore-common.toml`. It has one option:

| Key | Default | Effect |
|---|---:|---|
| `debug` | `false` | Writes successful ZONE module reload diagnostics to the server log. |

### Compatibility

- Minecraft: 1.20.1
- Mod loader: Forge 47.x
- Side: dedicated server; no client installation required
- Other ZONE mods may depend on ZoneCore. Check each mod's project page for its exact minimum ZoneCore version.

## Español

**Resumen:** API de integración del servidor para los mods de la familia ZONE en Minecraft Forge 1.20.1.

ZoneCore permite que los mods ZONE del servidor registren manejadores de recarga de configuración, nombres de permisos y un proveedor de rangos mediante una API compartida. No añade objetos visibles ni interfaz para el jugador.

### Instalación

1. Instala Minecraft 1.20.1 con Forge 47.x en el servidor.
2. Coloca el JAR oficial de `zonecore` en la carpeta `mods` del servidor.
3. Instala cada mod ZONE con las dependencias y versiones indicadas en su propia página.
4. Inicia el servidor. Los jugadores no necesitan instalar ZoneCore en sus clientes.

### Comando y permisos

`/zonecore reload` recarga los archivos TOML de los módulos ZONE que registraron un manejador de recarga. Requiere permiso de operador nivel 2 de Minecraft. Una actualización del JAR todavía requiere reiniciar el servidor.

### Configuración TOML

Forge crea `config/zonecore-common.toml`. Contiene una opción:

| Clave | Valor inicial | Efecto |
|---|---:|---|
| `debug` | `false` | Escribe en el registro del servidor los módulos ZONE recargados correctamente. |

### Compatibilidad

- Minecraft: 1.20.1
- Cargador: Forge 47.x
- Lado: servidor dedicado; no requiere instalación en el cliente
- Otros mods ZONE pueden depender de ZoneCore. Consulta la versión mínima exacta en la página de cada mod.

## Ownership / Titularidad

Documentation and original ZONE visual assets © Elgochogms. This public repository contains documentation and the avatar only; it does not distribute source code, private mappings, secrets, or production configuration.

