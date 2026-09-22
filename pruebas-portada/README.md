# Pruebas de portada (v0.19)

Entrada principal (home): **metalGyro** — wordmark oro cromado 3D (extrusión, bevel, specular líquido + star glint) con luz guiada por giroscopio; en iPhone la inclinación mueve la luz (pedir permiso con “Activar inclinación”). Sin permiso / desktop: deriva suave de la luz. Al tocar el logo (~0.8s, sin zoom): brillo hacia blanco/hot → dissolve/blur → whiteGate → hub. Fondo de portada blanco/off-white (el oro es solo el logo).
Transiciones entre páginas: fade (cerrado, no tocar) — `tween(120)` / whiteGate `90`+`110`.

1. Gold chrome gyro — oro cromado 3D + giroscopio / idle drift (default)
2. ASCII morph
3. Zoom dither
4. Soft fade
5. Punch
6. Rise
7. Snap flash
8. Sink
9. Slices
10. Bloom
11. Hard cut
