
# 🧠 Hyprland Keybinds Documentation

Atajos de teclado de Hyprland



## 🌐 Submap Inicial

```hypr
exec = hyprctl dispatch submap global
submap = global
```
Define el submap por defecto llamado `global`, desde donde se ejecutan la mayoría de los atajos.

---

## 🚀 Launcher

| Tecla | Acción |
|------|--------|
| Super (sólo) | Lanza `caelestia:launcher` |
| Super + cualquier otra (incluyendo clicks y scrolls) | Interrumpe con `caelestia:launcherInterrupt` |

---

## 🛠️ Misc

| Tecla | Acción |
|------|--------|
| Ctrl + Alt + Delete | `caelestia:session` |
| Ctrl + Alt + C | Limpia notificaciones |
| Super + K | Mostrar todo (`showall`) |
| Super + L | Bloquea sesión |
| Super + Alt + L | Desbloquea (`shell -d`) o bloquea sesión |

---


## 🎵 Media

| Tecla | Acción |
|------|--------|
| Ctrl + Super + Space, XF86AudioPlay/Pause | Toggle de reproducción |
| Ctrl + Super + = / XF86AudioNext | Siguiente canción |
| Ctrl + Super + - / XF86AudioPrev | Canción anterior |

---

## 🔁 Kill / Restart

| Tecla | Acción |
|------|--------|
| Ctrl + Super + Shift + R | `caelestia kill` | restarrt |
| Ctrl + Super + Alt + R | `caelestia kill` + `caelestia shell -d` |

---

## 🖥️ Cambio de Workspaces

| Tecla | Acción |
|------|--------|
| Super + [1–0] | Ir a workspace 1–10 |
| Ctrl + Super + [1–9] | Ir a grupo de workspaces |
| Super + Scroll / Page_Up/Down / Ctrl + Super + arrows | Navegar workspaces y grupos |
| Super + S | Toggle special workspace |

---

## 🪟 Mover ventanas

| Tecla | Acción |
|------|--------|
| Super + Alt + [1–8] | Mover ventana a workspace |
| Ctrl + Super + Alt + [1–0] | Mover ventana a grupo de workspaces |
| Super + Alt + Page_Up/Down, Scroll, Arrows | Mover a workspace anterior/siguiente |
| Ctrl + Super + Shift + Up/Down | Mover a special workspace o sacarla |

---

## 🧩 Grupos de Ventanas

| Tecla | Acción |
|------|--------|
| Alt + Tab | Ciclar ventana activa |
| Ctrl + Alt + Tab | Cambiar foco dentro del grupo |
| Super + , | Toggle group |
| Super + Shift + , | Lock active group |

---

## 🔲 Acciones de Ventana

Incluye navegación, movimiento, cambio de tamaño, centrado, pin, fullscreen, etc.

| Tecla | Acción |
|------|--------|
| Super + Arrow | Mover foco |
| Super + Shift + Arrow | Mover ventana |
| Super + = / - | Ajustar split ratio |
| Super + Mouse Left / Z | Mover ventana |
| Super + Mouse Right / X | Redimensionar |
| Ctrl + Super + \ | Centrar ventana |
| Super + Alt + \ | PIP (Picture in Picture) |
| Super + Q | Cerrar ventana |

---

## 📦 Workspaces Especiales

| Tecla | Acción |
|------|--------|
| Ctrl + Shift + Escape | Toggle monitor de sistema |
| Super + M / D / R | Toggle música, comunicación, tareas |

---

## 🧭 Aplicaciones

| Tecla | App |
|------|-----|
| Super + T | Terminal (foot) |
| Super + B | Brave |
| Super + C | VSCode |
| Super + G | GitHub Desktop |
| Super + S | Spotify |
| Super + Alt + E | Nemo |
| Ctrl + Alt + Escape | QPS |
| Ctrl + Alt + V | Pavucontrol |

---

## 🛠️ Utilidades

| Tecla | Acción |
|------|--------|
| Print | Captura completa (clipboard) |
| Super + Shift + S | Captura región (freeze) |
| Super + Shift + Alt + S | Captura región |
| Super + Alt + R | Grabar pantalla con sonido |
| Ctrl + Alt + R | Grabar pantalla |
| Super + Shift + Alt + R | Grabar región |
| Super + Shift + C | Selector de color |

---

## 🔊 Volumen

| Tecla | Acción |
|------|--------|
| XF86AudioMute, Super + Shift + M | Toggle mute |
| XF86AudioRaise/LowerVolume | Subir/bajar volumen (con unfix del mute) |

---

## 😴 Suspensión

| Tecla | Acción |
|------|--------|
| Super + Shift + L | `systemctl suspend-then-hibernate` |

---

## 📋 Portapapeles y Emojis

| Tecla | Acción |
|------|--------|
| Super + V | Portapapeles |
| Super + Alt + V | Portapapeles (detached) |
| Super + . | Selector de emoji |
| Ctrl + Shift + Alt + V | Pegar último item del clipboard |

---

## 🧪 Test

| Tecla | Acción |
|------|--------|
| Super + Alt + F12 | Notificación de prueba |

---

Fin de la documentación. 🎉
