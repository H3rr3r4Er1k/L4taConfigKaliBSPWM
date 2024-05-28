# auto-bspwm
> Automatización para configurar un entorno de hacking profesional en Kali Linux utilizando el gestor de ventanas en mosaico [bspwm](https://github.com/baskerville/bspwm). 🔒

## Instalación
1. **Actualizar el sistema.** 🔄
    ```shell
    sudo apt update
    sudo apt upgrade -y
    ```

2. **Clonar el repositorio y acceder a él.** 📂
    ```shell
    git clone https://github.com/r1vs3c/auto-bspwm.git
    cd auto-bspwm
    ```

3. **Conceder permisos de ejecución al script.** 🔑
    ```shell
    chmod +x setup.sh
    ```

4. **Ejecutar el script.** ▶️
    ```shell
    ./setup.sh
    ```

5. **Reiniciar y seleccionar `bspwm` como gestor de ventanas.** 🚀

## Visión general del entorno
![overview1](/assets/overview1.png "overview1")

![overview2](/assets/overview2.png "overview2")

![overview3](/assets/overview3.png "overview3")

# Atajos de teclado
## Aplicaciones
- <kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>F</kbd>: Firefox. 🦊
- <kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd>: Burpsuite. 🌐
- <kbd>Windows</kbd> + <kbd>Enter</kbd>: Kitty. 🐱
- <kbd>Windows</kbd> + <kbd>D</kbd>: Abrir Rofi. Presiona <kbd>Esc</kbd> para salir. 🚪

## Ventanas - WM(windows manager)
- <kbd>Windows</kbd> + <kbd>T</kbd>: Cambiar a mosaico. 🖼️
- <kbd>Windows</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Navegar entre ventanas. 🚗
- <kbd>Windows</kbd> + <kbd>W</kbd>: Cerrar ventana actual. ❌
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Enter</kbd>: Abrir subventana. 📂
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>L</kbd>: Alternar subventanas. 🔄
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>W</kbd>: Cerrar subventana actual. ❎
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>T</kbd>: Abrir pestaña en ventana actual. 📑

### Modos
- <kbd>Windows</kbd> + <kbd>M</kbd>: Modo "completo". 🖥️
- <kbd>Windows</kbd> + <kbd>F</kbd>: Pantalla completa. 🌐
- <kbd>Windows</kbd> + <kbd>S</kbd>: Modo flotante. 🌊
- <kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Cambiar tamaño (flotante). 📏
- <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>(⬆⬅⬆➡)</kbd>: Cambiar posición (flotante). 🔄
- <kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>(1,2,3,4,5,6,7,8,9,0)</kbd>: Mover ventana a otro espacio. 🚀

## Sistema
- <kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>R</kbd>: Reiniciar configuración. 🔄
- <kbd>Windows</kbd> + <kbd>Alt</kbd> + <kbd>Q</kbd>: Cerrar sesión. 🚪
- <kbd>Windows</kbd> + <kbd>(1,2,3,4,5,6,7,8,9,0)</kbd>: Cambiar espacio. 🌌
- <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>L</kbd>: Bloquear pantalla. 🔒
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>⬆⬇</kbd>: Ajustar volumen. 🔊🔉
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>M</kbd>: Silenciar sonido. 🔇
- <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Mostrar preselección y abrir ventana. 🖼️🚪
   - <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Space</kbd>: Deshacer preselección. 🔙
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Z</kbd>: Ampliar subventana actual. 🔍
- <kbd>Ctrl</kbd> + <kbd>(⬆⬅⬇➡)</kbd>: Navegar entre subventanas. 🚗
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>R</kbd>: Cambiar tamaño de subventana. 📏
   - Luego, usa:
     - <kbd>W</kbd> para 'Más ancho'
     - <kbd>N</kbd> para 'Más estrecho'
     - <kbd>T</kbd> para 'Más alto'
     - <kbd>S</kbd> para 'Más corto'
     - <kbd>R</kbd> para 'Restablecer'
     - <kbd>Esc</kbd> para salir del modo de cambio de tamaño. 🔄
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd>: Renombrar título de pestaña. 📑


- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>(⬅➡)</kbd>: Navegar entre pestañas. 📑
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd>: Copiar al portapapeles. 📋
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>V</kbd>: Pegar desde el portapapeles. 📋
- <kbd>F1</kbd>: Copiar al búfer A. 📋
- <kbd>F2</kbd>: Pegar desde el búfer A. 📋
- <kbd>F3</kbd>: Copiar al búfer B. 📋
- <kbd>F4</kbd>: Pegar desde el búfer B. 📋

## Software 🛠️
Esta configuración utiliza el siguiente software:
- **WM**: [bspwm](https://github.com/baskerville/bspwm) 🖥️
- **Hotkey**: [sxhkd](https://github.com/baskerville/sxhkd) 🔥
- **Locker**: [i3lock-fancy](https://github.com/meskarune/i3lock-fancy) 🔒
- **Shell**: [zsh](https://www.zsh.org/) 🐚
- **Shell Theme**: [powerlevel10k](https://github.com/romkatv/powerlevel10k) 🌈
- **Shell configuration manager**: [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) ⚙️
- **Bars**: [polybar](https://github.com/polybar/polybar) 🍹
- **Bars Theme**: [polybar-themes](https://github.com/adi1090x/polybar-themes) 🎨
- **Compositor**: [picom](https://github.com/yshui/picom) 🖌️
- **File Manager**: [thunar](https://docs.xfce.org/xfce/thunar/start) 📁
- **Fonts**: [iosevka](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Iosevka) and [hack](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Hack) ✍️
- **Application Launcher**: [rofi](https://github.com/davatorium/rofi) 🚀
- **Browsers**: [firefox](https://www.mozilla.org/en-US/firefox/new/) 🌐
- **Terminals**: [kitty](https://sw.kovidgoyal.net/kitty/) and [qterminal](https://github.com/lxqt/qterminal) 💻
- **Static Wallpaper**: [feh](https://github.com/derf/feh) 🖼️
- **Color Scheme**: [pywal](https://github.com/dylanaraps/pywal) 🎨
- **Screenshot**: [flameshot](https://flameshot.org/) 📸


## Créditos
- Este entorno está inspirado en las funcionalidades de [S4vitar](https://github.com/s4vitar). 🌟

