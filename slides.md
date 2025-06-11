---
theme: penguin
title: Aplicación Frontend - Brightcooms
highlighter: shiki
class: text-center custom-bg
transition: fade-out
layout: intro
themeConfig:
  logoHeader: '/brightcooms-logo.svg'
---

# ¡Hola Brightcooms! 👋

Mi nombre es **Luis Isea**

Estoy aplicando al puesto de **Frontend Developer**

<div class="pt-12">
  <span @click="$nav.nextSlide" class="px-2 p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10">
    Empecemos <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: presenter
transition: fade
presenterImage: '/luis-isea.jpg'
---

# Luis Isea

Desarrollador Web con experiencia en tanto Frontend como Backend

- Estudiante de Ingeniería de la Computación en la USB
- Preparador y administrador del Laboratorio de Aulas Computarizadas de la USB (MAC)
- Me gusta aprender herramientas nuevas como [slidev](https://sli.dev/) que es justo la que estoy usando para esta presentación

<!-- Logos -->
<div style="position: fixed; right: 4.5rem; bottom: 1rem; z-index: 50;">
  <img src="/logo-usb.png" alt="USB Logo" style="height:48px; width:auto; opacity:0.9;">
</div>
<div style="position: fixed; left: 2rem; bottom: 1rem; z-index: 50;">
  <a href="https://github.com/lmisea" target="_blank" title="GitHub">
    <img src="https://cdn.simpleicons.org/github/fff" alt="GitHub Logo" style="height:30px; width:auto; opacity:0.9;">
  </a>
</div>
<div style="position: fixed; left: 48%; bottom: 1rem; transform: translateX(-50%); z-index: 50;">
  <a href="https://www.linkedin.com/in/luis-miguel-isea" target="_blank" title="LinkedIn">
    <img src="/in-white.png" alt="LinkedIn Logo" style="height:30px; width:auto; opacity:0.9;">
  </a>
</div>

---
layout: text-image
media: '/seconds.png'
caption: 'User Page después de iniciar sesión'
transition: slide-left
---

# Seconds.me

<div class="flex items-center justify-center gap-8 mt-8">
  <a href="https://seconds.me" target="_blank">
    <img src="https://seconds.me/favicon.ico" alt="Seconds.me" style="width:24px;height:24px;">
  </a>
  <span class="text-2xl font-bold">Desarrollador Fullstack</span>
</div>

## Frontend

<v-click>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://reactjs.org/" target="_blank" style="text-decoration: none;">React.js</a> (typescript components, tsx)
    <img src="https://cdn.simpleicons.org/react/61DAFB/white" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>
<v-click>
<br>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://chakra-ui.com/" target="_blank" style="text-decoration: none;">Chakra UI</a> (component library)
    <img src="https://cdn.simpleicons.org/chakraui/319795/white" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>

## Backend
<v-click>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://blitzjs.com/" target="_blank" style="text-decoration: none;">Blitz.js</a> (fullstack framework)
    <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAIAAAACACAYAAADDPmHLAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAQ9SURBVHgB7d3dVdtAEIbhcSpICUoH0IEogQqSVBBSAU4FSSpIOoAORAfQgSghHXzZ1U/YcMD4R9rZmf2ec3y448LyiNf27iLiGIAmPLrweC9Un3DhrzG6EarLNP09nlwJ1SOZ/lQr5N80/S/p2QMVCBf5N17XCfm1Y/rBHqjAG9PPHvBsz+mf9WAP+HLA9M/YA14cOP2payH7jpj+VCtk1wnTP+vj7xCy6cTpn7EHLMLp059iD1iD8eveJbVCNsSLheX1YA/YgOWnf8YeKB3Wmf7Ud6Fy4f/FHmtpxbl3YlC4MJ/Cj0bWdwPnPbARg+L0S54XQHS32WwuxClzd4CM0z9rPfeAuTtA5ulPXYQ7wZ04Y+oOoDD9KZc9YOoOoDj9s4dwFzgXR6w1wIPoOvPWA9buAHEJ173o3gWiy3AnuBUHLEbgmYwvAk1/wuM8vAgexThzbwPDkx7/DHwVXfFOxP2GmsKd4Ab6zPeAyU8CI7AHFmH2BRCBPXAyk18GzUrqAXCTiR4ssyj0VFw/oCU8+e+RZ33AWz6KMaYbIIWxB+JSLs1bsbkeMN0AqakHvoku9oA2sAfqBvbAQdw0QArsgb25aYBUQT3QgT2gB+yBuqGcHij2UCqXDZACe2Anlw2QYg/QAOyBuoE98CL3DZDCuK4/rh/Q7oGL6U+TOvcNkJoijN8X1C48+T+g75eQDrAH/qmqAVJgDwyqaoAUe4AGYA/UDZX3QLUNkEIZPRCd5+6BahsgVUgPROwBTSijB7jpVAvGHriHvmw9wAZ4BpX1ABvgmakHtPcbRuwBTWAPULgAV9D/jKDY9YRvwvgEaurD44uQHvAol7qBW7WKluVtIHiUS7GyvA0s6CiXDnxrpQfsgbqBS7GKk/2jYHCrVlGyfxTMrVo0ALdq1Q3sgSKofh0M9oA61a+D2QM0AHugbmAPqClmSRjK2apVVQ8UsySsoK1aHdgDesCtWnUDeyCrIpeFg1u3sylyWTi3btMA7IG6gT2wuuK3hoE9sKrit4YVslWLPaAN7IG6ocKt2zmY2h4O9sDiTG0PZw/QANy6XTewBxZj9ogYVHy025LMHhEz9cBn0We6B0yfERReBLfhx0/R1YQHPx/QBPbA0VwcEwf2wNFcHBPHHjiem3MC2QPHcXdSaJjA+KfgTPQ8hhfjBzHC40mhlzJ+Xq9lK4a4PCs43AVaGTed5mZq+iOXZwWHi3AnOj2wFWNcnxYe7gTxLtBKHuamP/J+Wnh8a5irB7ZC5Yk9gPX1QuXC+usHWqGyhYvUYR0a7zboUOFCNVhnk0krZAOW7wFOvzXhom2xnEbIHizTA1wEYhWW6YFGyC6c1gOcfg9wfA80Qj7g8B7g9HuCww+haIR8wf49wOn3Cvv9k8tGyC/s7gFOv3fY3QONkH+v9MBWqB7PeqDn9FcIT//kcitUn6kHOu/T/xfWzlQy3dEHhwAAAABJRU5ErkJggg==" alt="Blitz.js Logo" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>
<v-click>
<br>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://www.typescriptlang.org/" target="_blank" style="text-decoration: none;">TypeScript</a>
    <img src="https://cdn.simpleicons.org/typescript/3178C6/white" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>
<v-click>
<br>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://www.mysql.com/" target="_blank" style="text-decoration: none;">MySQL</a>
    <img src="https://cdn.simpleicons.org/mysql/4479A1/white" style="height:1.6em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>
<v-click>
<br>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://www.docker.com/" target="_blank" style="text-decoration: none;">Docker</a>
    <img src="https://cdn.simpleicons.org/docker/2496ED/white" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>

---
layout: text-image
reverse: true
media: '/rintronic.png'
caption: 'Modulo de conferencias doctor-paciente'
transition: slide-down
---

# Rintronic

<div class="flex items-center gap-6" style="display: inline-flex; align-items: center;">
  <img src="/rintronic-logo.png" alt="Rintronic" style="width:38px;height:32px;">
  <span class="text-2xl font-bold">Desarrollador Frontend</span>
</div>

## Frontend

<v-click>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://reactjs.org/" target="_blank" style="text-decoration: none;">React.js</a> (typescript components, tsx)
    <img src="https://cdn.simpleicons.org/react/61DAFB/white" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>
<v-click>
<br>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://getbootstrap.com/" target="_blank" style="text-decoration: none;">Bootstrap</a> (component library)
    <img src="https://cdn.simpleicons.org/bootstrap/7952B3/white" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>

## Backend

<v-click>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://loopback.io/doc/en/lb4/" target="_blank" style="text-decoration: none;">Loopback v4</a>
    <img src="https://cdn.simpleicons.org/loopback/3FA9F4/white" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>
<v-click>
<br>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://www.typescriptlang.org/" target="_blank" style="text-decoration: none;">TypeScript</a>
    <img src="https://cdn.simpleicons.org/typescript/3178C6/white" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>
<br>
<v-click>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://www.microsoft.com/en-us/sql-server/" target="_blank" style="text-decoration: none;">MSSQL</a>
    <img src="/sql-server.png" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>
<v-click>
<br>
- <div style="display: inline-flex; align-items: center;">
    <a href="https://www.docker.com/" target="_blank" style="text-decoration: none;">Docker</a>
    <img src="https://cdn.simpleicons.org/docker/2496ED/white" style="height:1.4em; margin-left: 0.4em; vertical-align: middle;">
  </div>
</v-click>

---
class: 'grid text-center align-self-center'
---

# ¡Gracias por la oportunidad!
Sumamente emocionado por la posibilidad de contribuir con ustedes
