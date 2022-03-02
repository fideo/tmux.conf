# tmux.conf
Comparto mi configuración de tmux por si alguien quiere utilizar la misma configuración.

La idea de esto es poder tener un repositorio compartido para que otras personas puedan utilizar y sobre todo proponer mas funcionalidades interesantes para tmux.

#### Imagen ilustrativa

![Imagen ilustrativa de tmux](/asset/TerminalMultiplexer.png)


# Instalación

Para poder tener todo instalado primero debemos tener instalado tpm que nos permitirá cargar los demás plugins.
Clonamos el repositorio de tpm dentro del directorio plugins dentro de .tmux

``$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm``

una vez que tenemos esto clonado en ~/.tmux/plugins/tpm levantamos en nuestra terminal tmux; luego ejecutamos el prefix (Ctrl+b) y luego Shift+I para que procese los cambios guardados en .tmux.conf que se encuentra en nuestra directorio de usuario (en mi caso por ejemplo: /home/fideo/.tmux.conf)

_Enjoy!!!_


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

``
if [ -f /usr/share/powerline/bindings/bash/powerline.sh ]; then
  source /usr/share/powerline/bindings/bash/powerline.sh 
fi
``
