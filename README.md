
# 🅿️ AutoKalena

<p align="center">
  <img src="icon.png" width="120" alt="AutoKalena"/>
</p>

**Reserva tu plaza de parking automáticamente.**

En muchos parkings corporativos las plazas se liberan **7 días antes a las 08:00** y
vuelan en segundos. AutoKalena se encarga por ti: programa la reserva con antelación,
prepara la sesión unos segundos antes y **la dispara en el instante exacto**. Tú solo lo
configuras una vez.

Es una app de escritorio para **Windows, macOS y Linux**. Vive discretamente en la
bandeja / barra de menú y trabaja en segundo plano. **No necesitas instalar nada más** (ni
Docker, ni Python, ni cuentas): descargas, abres y listo.

---

## ⬇️ Descarga

Ve a **[Releases](../../releases/latest)** y baja el archivo de tu sistema:

| Sistema | Archivo | Cómo se abre |
|---|---|---|
| 🪟 **Windows** | `AutoKalena-windows.zip` | Descomprime y ejecuta `AutoKalena.exe` |
| 🍎 **macOS** | `AutoKalena-macos.dmg` | Ábrelo y arrastra AutoKalena a Aplicaciones |
| 🐧 **Linux** | `AutoKalena-x86_64.AppImage` | Dale permiso de ejecución y haz doble clic |

---

## 🚀 Primeros pasos

1. **Ábrelo.** La primera vez te pedirá tus datos de **Kalena** (usuario, contraseña y la
   dirección del portal) y tus preferencias (zona, plazas a excluir…).
2. **Déjalo activo.** AutoKalena se queda en la bandeja / barra de menú. Mientras el
   ordenador esté encendido a la hora de apertura, la reserva se dispara sola.
3. **Abrir al iniciar sesión** (recomendado): así siempre está listo para las 08:00 sin que
   tengas que acordarte de abrirlo.

Puedes cambiar cualquier ajuste cuando quieras desde el icono → **Ajustes**. La pantalla
**Cómo funciona** explica el resto.

> 💡 Para que la reserva salte a su hora, el ordenador debe estar **encendido** (no hace
> falta que la ventana esté abierta; basta con que la app viva en la bandeja).

---

## ⚠️ Avisos al abrir (app sin firma)

Los instaladores no están firmados con un certificado de pago, así que el sistema puede
avisar la primera vez. Es normal:

- **macOS**: si dice que "no se puede comprobar el desarrollador", ve a *Ajustes del
  Sistema → Privacidad y seguridad* y pulsa **Abrir de todas formas**. O clic derecho sobre
  la app → **Abrir**.
- **Windows**: si aparece *Windows protegió tu PC*, pulsa **Más información → Ejecutar de
  todas formas**.
- **Linux**: si al abrir el AppImage se queja de **WebKitGTK**, instálalo con tu gestor de
  paquetes (p. ej. Ubuntu/Debian: `sudo apt install libwebkit2gtk-4.1-0`; Fedora:
  `sudo dnf install webkit2gtk4.1`; Arch: `sudo pacman -S webkit2gtk-4.1`).

---

## 🔒 Privacidad

Tus credenciales de Kalena se guardan **solo en tu equipo** y se usan únicamente para
reservar en tu portal. La app funciona en local: no hay servidor intermedio ni cuenta que
crear.

---

## 🆘 ¿Problemas?

Abre un *issue* en este repositorio describiendo qué sistema usas y qué ocurre.
