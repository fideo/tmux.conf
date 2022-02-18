# tmux.conf
Comparto mi configuración de tmux por si alguien quiere utilizar la misma configuración.

La idea de esto es poder tener un repositorio compartido para que otras personas puedan utilizar y sobre todo proponer mas funcionalidades interesantes para tmux.

#### Imagen ilustrativa

![Imagen ilustrativa de tmux](/asset/TerminalMultiplexer.png)



## Componentes instalados

- [tpm](https://github.com/tmux-plugins/tpm)
- [tmux-resurrect](https://github.com/tmux-plugins/tmux-resurrect)
- [tmux-cpu](https://github.com/tmux-plugins/tmux-cpu)
- [tmux-net-speed](https://github.com/tmux-plugins/tmux-net-speed)
- [tmux-prefix-highlight](https://github.com/tmux-plugins/tmux-prefix-highlight)
- [o0th/tmux-nova](https://github.com/o0th/tmux-nova)

### POWERLINE

Dejo también dentro de este repositorio el directorio powerline para que se vea como la imagen de arriba. Este debe estar ubicado en ~/./config/porwerline

Para que esto funcione se tiene que instalar Powerline que se hace con los siguientes comandos:

``sudo apt update && sudo apt install powerline powerline-gitstatus fonts-powerline``

luego pueden reemplazar el archivo .bashrc también compartido en este repositorio ó pueden pegar esto en su propio archivo .bashrc

``if [ -f /usr/share/powerline/bindings/bash/powerline.sh ]; then
source /usr/share/powerline/bindings/bash/powerline.sh
fi]``
