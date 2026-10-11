# Política de privacidad · Privacy policy

**AI Wide View** — extensión para Chrome / Chrome extension

[Español](#español) · [English](#english)

---

## Español

*Última actualización: 11 de octubre de 2026*

### Resumen

**AI Wide View no recopila, no almacena en servidores externos, no vende y no comparte ningún dato personal.** La extensión funciona íntegramente en tu navegador.

### Qué hace la extensión

AI Wide View amplía el ancho de las interfaces web de chats de inteligencia artificial (por ejemplo ChatGPT, Claude o Gemini) y, opcionalmente, oculta su barra lateral. Para ello analiza localmente la *estructura visual* de la página (tamaños y posiciones de los elementos) y aplica estilos CSS.

### Datos que trata

- **Contenido de las páginas:** la extensión inspecciona la estructura de la página únicamente para calcular el diseño. No lee, guarda ni transmite el texto de tus conversaciones ni ningún otro contenido.
- **Preferencias:** el ancho elegido, los modos activados, el idioma y la lista de sitios que hayas activado manualmente se guardan con `chrome.storage`. Si tienes activada la sincronización de Chrome, Google sincroniza estas preferencias entre tus dispositivos según su propia política de privacidad. El desarrollador no tiene acceso a ellas.
- **Posición del botón flotante y tema del sistema:** se guardan localmente en tu navegador.

### Qué no hace

- No envía datos a ningún servidor ni realiza peticiones de red a terceros.
- No usa analítica, cookies, publicidad ni rastreadores.
- No ejecuta código remoto: todo el código está incluido en el paquete de la extensión.
- No vende ni transfiere datos a terceros, ni los usa para fines ajenos a su única función.
- El enlace opcional «Invítame a un café» abre la web externa [Buy Me a Coffee](https://buymeacoffee.com/veslava.ia) solo si haces clic. La extensión no le envía ningún dato.

### Permisos

| Permiso | Para qué se usa |
|---|---|
| Acceso a los chats de IA compatibles | Aplicar el diseño ancho en esas páginas. |
| Acceso opcional a otros sitios | Solo se solicita si pulsas «Activar en este sitio», y solo para ese dominio. Puedes revocarlo en cualquier momento desde la propia extensión o desde `chrome://extensions`. |
| `storage` | Guardar tus preferencias. |
| `scripting` | Aplicar el diseño en las pestañas que ya estaban abiertas y en los sitios que actives. |
| `activeTab` | Saber en qué sitio estás al abrir la ventana de la extensión. |

### Cambios y contacto

Si esta política cambia, se actualizará este documento y la fecha indicada arriba. Para cualquier consulta escribe a **CONTACT_EMAIL** o abre una incidencia en [GitHub Issues](https://github.com/eslava-ai/aiwideview/issues).

---

## English

*Last updated: October 11, 2026*

### Summary

**AI Wide View does not collect, store on external servers, sell or share any personal data.** The extension runs entirely inside your browser.

### What the extension does

AI Wide View widens the web interfaces of AI chat services (such as ChatGPT, Claude or Gemini) and can optionally hide their sidebar. To do so it locally analyzes the page's *visual structure* (element sizes and positions) and applies CSS styles.

### Data it handles

- **Page content:** the extension inspects the page structure only to compute the layout. It does not read, store or transmit the text of your conversations or any other content.
- **Preferences:** your chosen width, enabled modes, language and the list of sites you enabled manually are saved with `chrome.storage`. If Chrome Sync is on, Google syncs these preferences across your devices under its own privacy policy. The developer has no access to them.
- **Floating button position and system theme:** stored locally in your browser.

### What it does not do

- It sends no data to any server and makes no network requests to third parties.
- No analytics, cookies, ads or trackers.
- No remote code: all code ships inside the extension package.
- It does not sell or transfer data to third parties, nor use it for anything beyond its single purpose.
- The optional “Buy me a coffee” link opens the external [Buy Me a Coffee](https://buymeacoffee.com/veslava.ia) website only when you click it. The extension sends it no data.

### Permissions

| Permission | What it is used for |
|---|---|
| Access to supported AI chat sites | Apply the wide layout on those pages. |
| Optional access to other sites | Only requested when you click “Enable on this site”, and only for that domain. You can revoke it at any time from the extension or from `chrome://extensions`. |
| `storage` | Save your preferences. |
| `scripting` | Apply the layout to tabs that were already open and to sites you enable. |
| `activeTab` | Detect the current site when you open the extension popup. |

### Changes and contact

If this policy changes, this document and the date above will be updated. Questions: write to **CONTACT_EMAIL** or open an issue on [GitHub Issues](https://github.com/eslava-ai/aiwideview/issues).
