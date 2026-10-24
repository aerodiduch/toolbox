# toolbox

[![License: MIT](https://img.shields.io/github/license/aerodiduch/toolbox)](LICENSE) ![macOS](https://img.shields.io/badge/macOS-555555?logo=apple&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude%20Code-mods-D97757)

[English](README.md)

Paso el día en la MacBook, casi siempre adentro de Claude Code en iTerm2. Las herramientas de esta lista salieron de cosas que me molestaban en ese día a día, y las uso todas, todos los días. Cada una tiene su repo con el código y la instalación; la lista crece cada vez que sumo una.

## LidMute

Cerraba la MacBook, me iba a dormir y me acordaba de que había quedado con sonido. Me tenía que levantar, abrirla y mutearla. LidMute la mutea sola cuando cerrás la tapa y no la desmutea cuando la abrís. Escucha la tapa y no el reposo, así que anda aunque Amphetamine no deje dormir a la Mac.

- Mutea la salida que esté en uso: los parlantes, unos AirPods, una placa USB.
- Se prende y se apaga desde un ícono en la barra de menú.
- Si enchufás un monitor con la tapa cerrada, no te vuelve a mutear.

```sh
git clone https://github.com/aerodiduch/lid-mute.git && bash lid-mute/install.sh
```

macOS, Swift sin dependencias. [Repo y detalles](https://github.com/aerodiduch/lid-mute).

## Image Links

![Claude Code con tres imágenes como chips arriba del prompt y una abierta al lado del puntero](https://github.com/aerodiduch/claude-image-links/raw/main/docs/cover.jpg)

Claude me manda capturas todo el tiempo, de una pantalla que acaba de armar o de una prueba, y me quedaban como rutas que tenía que abrir a mano. Este mod las pone como chips arriba del prompt: pasás el mouse y ves la imagen al lado del puntero, y con un clic se abre en Vista Previa.

- Toma las imágenes que Claude te manda y las rutas que escribe en la respuesta.
- La ventanita nunca te saca el foco: seguís escribiendo en la terminal.
- Se limpian cuando mandás el próximo mensaje.

```sh
claude plugin install image-links --marketplace aerodiduch/claude-image-links
```

Mod de Claude Code; la vista previa anda en macOS. Necesita la interfaz de pantalla completa (`"tui": "fullscreen"`). [Repo y detalles](https://github.com/aerodiduch/claude-image-links).

## Licencia

MIT. Cada herramienta tiene su licencia en su repo.
