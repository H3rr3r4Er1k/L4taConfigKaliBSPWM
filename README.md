# auto-bspwm
> This is a Bash script that automates the setup of a professional hacking environment for Kali Linux using the tiled window manager [bspwm](https://github.com/baskerville/bspwm).

## Installation
1. Install available updates.

```shell
sudo apt update
sudo apt upgrade -y
```

2. Clone the repository and navigate to it.

```shell
git clone https://github.com/r1vs3c/auto-bspwm.git
cd auto-bspwm
```

3. Grant execution permissions to the script.

```shell
chmod +x setup.sh
```

4. Execute the script.

```shell
./setup.sh
```

5. After the script has finished, you will be prompted to restart the system. Once you have rebooted, select `bspwm` as the window manager and then log in.

## Overview of the environment
![overview1](/assets/overview1.png "overview1")

![overview2](/assets/overview2.png "overview2")

![overview3](/assets/overview3.png "overview3")


## Atajos de teclado
- <kbd>Windows</kbd> + <kbd>Enter</kbd>: Abrir una ventana de emulador de terminal (kitty).
- <kbd>Windows</kbd> + <kbd>W</kbd>: Cerrar la ventana actual.
- <kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>R</kbd>: Reiniciar la configuración de bspwm.
- <kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>Q</kbd>: Cerrar sesión.
- <kbd>Windows</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Navegar entre ventanas en el espacio de trabajo actual.
- <kbd>Windows</kbd> + <kbd>D</kbd>: Abrir Rofi. Presiona <kbd>Esc</kbd> para salir.
- <kbd>Windows</kbd> + <kbd>(1,2,3,4,5,6,7,8,9,0)</kbd>: Cambiar al espacio de trabajo respectivo.
- <kbd>Windows</kbd> + <kbd>T</kbd>: Cambiar la ventana actual al modo mosaico.
- <kbd>Windows</kbd> + <kbd>M</kbd>: Alternar la ventana actual al modo "completo" (no ocupa la barra de herramientas). Presiona las mismas teclas para volver al modo mosaico.
- <kbd>Windows</kbd> + <kbd>F</kbd>: Cambiar la ventana actual al modo de pantalla completa (ocupa toda la pantalla, incluida la barra de herramientas).
- <kbd>Windows</kbd> + <kbd>S</kbd>: Cambiar la ventana actual al modo flotante.
- <kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>(1,2,3,4,5,6,7,8,9,0)</kbd>: Mover la ventana actual a otro espacio de trabajo.
- <kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Cambiar el tamaño de la ventana actual (solo funciona si está en modo flotante).
- <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>(⬆⬅⬆➡)</kbd>: Cambiar la posición de la ventana actual (solo funciona si está en modo flotante).
- <kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>F</kbd>: Abrir Firefox.
- <kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd>: Abrir Burpsuite.
- <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>L</kbd>: Bloquear la pantalla.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>⬆⬇</kbd>: Aumentar/disminuir el volumen.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>M</kbd>: Silenciar/activar el sonido.
- <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Mostrar una preselección y luego abrir una ventana (kitty, Firefox, administrador de archivos, etc.).
   - <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Space</kbd>: Deshacer la preselección.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Enter</kbd>: Abrir una subventana en la ventana actual.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Z</kbd>: Ampliar la subventana actual.
- <kbd>Ctrl</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Navegar entre subventanas en la ventana actual.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>R</kbd>: Cambiar el tamaño de la subventana actual. Después, usa:
   - <kbd>W</kbd> para 'Más ancho'
   - <kbd>N</kbd> para 'Más estrecho'
   - <kbd>T</kbd> para 'Más alto'
   - <kbd>S</kbd> para 'Más corto'
   - <kbd>R</kbd> para 'Restablecer'
   - <kbd>Esc</kbd> para salir del modo de cambio de tamaño.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>L</kbd>: Alternar el arreglo de subventanas.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>W</kbd>: Cerrar la subventana o pestaña actual.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>T</kbd>: Abrir una pestaña en la ventana actual.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd>: Renombrar el título de la pestaña actual.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>(⬅➡)</kbd>: Navegar entre las pestañas actuales.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd>: Copiar al portapapeles.
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>V</kbd>: Pegar desde el portapapeles.
- <kbd>F1</kbd>: Copiar al búfer A.
- <kbd>F2</kbd>: Pegar desde el búfer A.
- <kbd>F3</kbd>: Copiar al búfer B.
- <kbd>F4</kbd>: Pegar desde el búfer B.

    
## Software
This configuration uses the following software:
- **WM**: [bspwm](https://github.com/baskerville/bspwm)
- **Hotkey**: [sxhkd](https://github.com/baskerville/sxhkd)
- **Locker**: [i3lock-fancy](https://github.com/meskarune/i3lock-fancy)
- **Shell**: [zsh](https://www.zsh.org/)
- **Shell Theme**: [powerlevel10k](https://github.com/romkatv/powerlevel10k)
- **Shell configuration manager**: [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh)
- **Bars**: [polybar](https://github.com/polybar/polybar)
- **Bars Theme**: [polybar-themes](https://github.com/adi1090x/polybar-themes)
- **Compositor**: [picom](https://github.com/yshui/picom)
- **File Manager**: [thunar](https://docs.xfce.org/xfce/thunar/start)
- **Fonts**: [iosevka](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Iosevka) and [hack](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Hack)
- **Application Launcher**: [rofi](https://github.com/davatorium/rofi)
- **Browsers**: [firefox](https://www.mozilla.org/en-US/firefox/new/)
- **Terminals**: [kitty](https://sw.kovidgoyal.net/kitty/) and [qterminal](https://github.com/lxqt/qterminal)
- **Static Wallpaper**: [feh](https://github.com/derf/feh)
- **Color Scheme**: [pywal](https://github.com/dylanaraps/pywal)
- **Screenshot**: [flameshot](https://flameshot.org/)

## Credits
- This environment has been inspired by the functionalities of [S4vitar's](https://github.com/s4vitar) environment.
- Thanks to [Cube](https://github.com/ZLCube) for their contribution to the creation of the `archkali.png` wallpaper.
