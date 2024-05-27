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


## Atajos de Teclado
<kbd>Windows</kbd> + <kbd>Enter</kbd>: Abre una ventana de emulador de terminal (kitty). 🖥️
<kbd>Windows</kbd> + <kbd>W</kbd>: Cierra la ventana actual. 🪟
<kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>R</kbd>: Reinicia la configuración de bspwm. 🔄
<kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>Q</kbd>: Cierra la sesión. 🚪
<kbd>Windows</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Navega entre ventanas en el espacio de trabajo actual. 🧭
<kbd>Windows</kbd> + <kbd>D</kbd>: Abre Rofi. Presiona <kbd>Esc</kbd> para salir. 🕵️
<kbd>Windows</kbd> + <kbd>(1,2,3,4,5,6,7,8,9,0)</kbd>: Cambia al espacio de trabajo respectivo. 🏢
<kbd>Windows</kbd> + <kbd>T</kbd>: Cambia la ventana actual al modo mosaico. 🖼️
<kbd>Windows</kbd> + <kbd>M</kbd>: Alternar la ventana actual al modo "completo" (no ocupa la polybar). Presiona las mismas teclas para volver al modo mosaico. 🔄
<kbd>Windows</kbd> + <kbd>F</kbd>: Cambia la ventana actual al modo de pantalla completa (ocupa toda la pantalla, incluida la polybar). 🖥️
<kbd>Windows</kbd> + <kbd>S</kbd>: Cambia la ventana actual al modo flotante. 🌊
<kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>(1,2,3,4,5,6,7,8,9,0)</kbd>: Mueve la ventana actual a otro espacio de trabajo. 🚚
    <kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Cambia el tamaño de la ventana actual (solo funciona si está en modo flotante). 📏
    <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>(⬆⬅⬆➡)</kbd>: Cambia la posición de la ventana actual (solo funciona si está en modo flotante). 📐
    <kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>F</kbd>: Abre Firefox. 🦊
    <kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd>: Abre Burpsuite. 🛠️
    <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>L</kbd>: Bloquea la pantalla. 🔒
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>⬆⬇</kbd>: Aumenta/disminuye el volumen. 🔊🔉
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>M</kbd>: Silenciar/desilenciar el volumen. 🔇
    <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Muestra una preselección y luego abre una ventana (kitty, Firefox, administrador de archivos, etc.).
        <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Space</kbd>: Deshacer la preselección. 🔄
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Enter</kbd>: Abre una subventana en la ventana actual. 🪟
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Z</kbd>: Amplía la subventana actual. 🔍
    <kbd>Ctrl</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Navega entre subventanas en la ventana actual. 🧭
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>R</kbd>: Cambia el tamaño de la subventana actual. Después, usa:
<kbd>W</kbd> para 'Más ancho'
        <kbd>N</kbd> para 'Más estrecho'
        <kbd>T</kbd> para 'Más alto'
        <kbd>S</kbd> para 'Más corto'
        <kbd>R</kbd> para 'Restablecer'
        <kbd>Esc</kbd> para salir del modo de cambio de tamaño. 📏
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>L</kbd>: Alterna el arreglo de subventanas. 🔄
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>W</kbd>: Cierra la subventana o pestaña actual. 🚪
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>T</kbd>: Abre una pestaña en la ventana actual. 📑
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd>: Renombra el título de la pestaña actual. 🏷️
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>(⬅➡)</kbd>: Navega entre las pestañas actuales. 🔄
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd>: Copiar al portapapeles. 📋
    <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>V</kbd>: Pegar desde el portapapeles. 📋
<kbd>F1</kbd>: Copiar en el buffer A. 📋
<kbd>F2</kbd>: Pegar desde el buffer A. 📋
<kbd>F3</kbd>: Copiar en el buffer B. 📋
<kbd>F4</kbd>: Pegar desde el buffer B. 📋
    
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
