Instalación del entorno de Arch de S4vitar

Utilizaremos como guía el video de S4vitar. ASÍ es el ENTORNO de un HACKER

(Este método me ha funcionado a la perfección, cabe aclarar que estoy en una máquina virtual y no se si funcionará para nativo).



—------------------------------------------------------------------------------------------------------------------------

Para comenzar seguiremos a pie de la letra los pasos del video hasta llegar al punto donde S4vitar empieza a descargar las dependencias del repositorio de rxyhn.  (Minuto: 37:45).

Las dependencias las instalaremos en esta versión del repositorio: https://github.com/rxyhn/dotfiles/tree/3f1ebe2fc4fc19fea1c1ff2c867d78ae3e344a11

Notaréis que no os funciona el audio, para arreglar ese problema usaremos este comando:

paru -Sy picom-git wezterm rofi acpi acpid acpi_call upower lxappearance-gtk3 \
jq inotify-tools polkit-gnome xdotool xclip gpick ffmpeg blueman redshift \
pipewire pipewire-alsa pipewire-pulse pamixer brightnessctl feh scrot \
mpv mpd mpc mpdris2 python-mutagen ncmpcpp playerctl --needed

habilitamos los servicios mencionados en el video de S4vitar o en el repos

(awesome lo instalaremos una vez hecho el paso de los dotfiles)

Instalaremos las fuentes mencionadas en el video de S4vitar.

Una vez acabado el anterior paso, cuando empieza a instalar los dotfiles (Siguiente paso después de instalar las fuentes) descargamos estos mismos pero desde esta versión del repositorio: https://github.com/rxyhn/dotfiles/tree/c1e2eef2baa91aebd37324891cb282666beae04f

Muy importante que no clonemos este repositorio, sinó que descarguemos los archivos en ZIP mediante el botón “code”.



Movemos este comprimido a la carpeta donde tengáis vuestros repositorios y lo descomprimimos. (Según el video de S4vitar debería ser (    Desktop/TuUsuario/repos   ) )

( Para descomprimir utilizamos el comando: unzip )

(Opcional) La carpeta que nos ha dejado el ZIP la renombramos a “dotfiles” y borramos el ZIP.

Una vez hecho esto podremos seguir con el video. (Minuto 44:18).

Si cuando S4vitar se cambia a Awesome no os aparece esa opción; entráis a gnome y ponéis el siguiente comando:

paru -S awesome-git.

Seguido de esto nos podemos saltar el paso de migrar al commit antiguo. (Del Minuto 45:27 al 48:00)

Listo! En principio podremos seguir con el video del 48:00 en adelante.

Aún así, no dudéis en preguntarme cualquier cosa a mi discord (Erxz#4477) o si me veis conectado a un directo, me podeis susurrar, ya que no estaré atento al discord. Mi nombre de Twitch: fe4r_cronic

Espero que os haya podido ayudar y un abrazo gente ^^

(Agradecer a Dracken por informarme de errores ^^)
