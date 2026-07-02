
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

Descarga directa de la **última versión** para tu sistema:

<p align="center">
  <a href="https://github.com/emilio-carrasco/autokalena/releases/latest/download/AutoKalena-macos.dmg">
    <img src="https://img.shields.io/badge/Descargar-macOS-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Descargar para macOS"></a>
  &nbsp;
  <a href="https://github.com/emilio-carrasco/autokalena/releases/latest/download/AutoKalena-windows.zip">
    <img src="https://img.shields.io/badge/Descargar-Windows-0078D6?style=for-the-badge&logo=windows11&logoColor=white" alt="Descargar para Windows"></a>
  &nbsp;
  <a href="https://github.com/emilio-carrasco/autokalena/releases/latest/download/AutoKalena-x86_64.AppImage">
    <img src="https://img.shields.io/badge/Descargar-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Descargar para Linux"></a>
</p>

<p align="center"><sub>Los botones apuntan siempre a la última release · <a href="../../releases/latest">ver todas las descargas y notas</a></sub></p>

| Sistema | Cómo se abre |
|---|---|
| 🍎 **macOS** | Abre el `.dmg` y arrastra AutoKalena a Aplicaciones |
| 🪟 **Windows** | Descomprime el `.zip` y ejecuta `AutoKalena.exe` |
| 🐧 **Linux** | Da permiso de ejecución al `.AppImage` y haz doble clic |

### 🍺 macOS con Homebrew

Si usas [Homebrew](https://brew.sh), instálalo con un solo comando (se auto-añade el tap):

```bash
brew install --cask emilio-carrasco/autokalena/autokalena
```

<details>
<summary>o en dos pasos</summary>

```bash
brew tap emilio-carrasco/autokalena
brew install --cask autokalena
```
</details>

La app no está firmada (sin cuenta de Apple Developer); el cask **retira la cuarentena de
Gatekeeper** tras instalar, así que abre sin bloqueos.

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
