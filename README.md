# Android Pattern Generator

A free, private, browser-based tool to explore every Android lock pattern — from the simplest to the most complex — and choose a secure one.

🔗 **Live demo:** `https://YOUR-USERNAME.github.io/pattern-lock-generator`

---

## 🇬🇧 English

**Android Pattern Generator** lets you walk through all **389,112** valid Android unlock patterns (3×3 grid, 4 to 9 dots, following Android's real connection rules) in order from the simplest to the most complex. Each pattern is drawn with a step-by-step animation, numbered dots, and a start→end color code, so it's easy to see exactly how it's traced.

It's built as a learning and decision tool: by seeing which patterns are short and obvious (and therefore easy to guess), you can pick a longer, less predictable one for your own device.

### Features
- Step-by-step animation with adjustable speed, order numbers, and start (green) → end (yellow) colors.
- Ordered walkthrough from simplest (4 dots) to most complex (9 dots), generated mathematically — nothing is pre-stored.
- Mark patterns as "done" so they don't show up again; everything is saved locally in your browser (IndexedDB).
- Re-show your saved patterns, newest first.
- Export and import your progress as a JSON file to move it between devices.
- Reset the database with a confirmation step.
- Available in English, Spanish, and Portuguese.
- Fully responsive (works on phones and desktops) and 100% client-side — your data never leaves your device.

### Note
This is an educational tool for understanding the pattern space and **choosing a strong lock pattern**. It is **not** a tool for unlocking phones: Android limits failed attempts, so trying patterns one by one will not bypass a real lock screen. If you've forgotten your own device's pattern, use the official recovery options (your Google account, Find My Device, or your manufacturer's tools).

### Privacy
No backend, no tracking, no accounts. All data is stored only in your own browser.

---

## 🇪🇸 Español

**Generador de Patrones Android** te permite recorrer los **389.112** patrones de desbloqueo válidos de Android (cuadrícula 3×3, de 4 a 9 puntos, siguiendo las reglas reales de conexión) en orden, del más simple al más complejo. Cada patrón se dibuja con una animación paso a paso, puntos numerados y un código de color inicio→fin, para que se vea con claridad cómo se traza.

Está pensado como herramienta educativa y de decisión: al ver qué patrones son cortos y evidentes (y por tanto fáciles de adivinar), puedes elegir uno más largo y menos predecible para tu propio dispositivo.

### Características
- Animación paso a paso con velocidad ajustable, números de orden y colores de inicio (verde) → fin (amarillo).
- Recorrido ordenado del más simple (4 puntos) al más complejo (9 puntos), generado matemáticamente: nada se almacena de antemano.
- Marca patrones como "hechos" para que no vuelvan a salir; todo se guarda localmente en tu navegador (IndexedDB).
- Vuelve a ver tus patrones guardados, del más reciente al más antiguo.
- Exporta e importa tu progreso como archivo JSON para llevarlo a otro equipo.
- Reinicia la base de datos con un paso de confirmación.
- Disponible en inglés, español y portugués.
- Totalmente responsivo (funciona en móviles y ordenadores) y 100% en el navegador: tus datos nunca salen de tu dispositivo.

### Nota
Es una herramienta educativa para entender el espacio de patrones y **elegir un patrón de bloqueo seguro**. **No** es una herramienta para desbloquear teléfonos: Android limita los intentos fallidos, así que probar patrones uno por uno no salta una pantalla de bloqueo real. Si olvidaste el patrón de tu propio dispositivo, usa las opciones oficiales de recuperación (tu cuenta de Google, Encontrar mi dispositivo, o las herramientas de tu fabricante).

### Privacidad
Sin backend, sin rastreo, sin cuentas. Todos los datos se guardan solo en tu propio navegador.

---

## 🇧🇷 Português

O **Gerador de Padrões Android** permite percorrer todos os **389.112** padrões de desbloqueio válidos do Android (grade 3×3, de 4 a 9 pontos, seguindo as regras reais de conexão) em ordem, do mais simples ao mais complexo. Cada padrão é desenhado com uma animação passo a passo, pontos numerados e um código de cor início→fim, para que fique claro como ele é traçado.

Foi criado como ferramenta educativa e de decisão: ao ver quais padrões são curtos e óbvios (e, portanto, fáceis de adivinhar), você pode escolher um mais longo e menos previsível para o seu próprio dispositivo.

### Recursos
- Animação passo a passo com velocidade ajustável, números de ordem e cores de início (verde) → fim (amarelo).
- Percurso ordenado do mais simples (4 pontos) ao mais complexo (9 pontos), gerado matematicamente — nada é armazenado previamente.
- Marque padrões como "feitos" para que não apareçam de novo; tudo é salvo localmente no seu navegador (IndexedDB).
- Reveja os padrões salvos, do mais recente ao mais antigo.
- Exporte e importe seu progresso como arquivo JSON para levá-lo a outro dispositivo.
- Redefina a base de dados com uma etapa de confirmação.
- Disponível em inglês, espanhol e português.
- Totalmente responsivo (funciona em celulares e computadores) e 100% no navegador — seus dados nunca saem do seu dispositivo.

### Observação
Esta é uma ferramenta educativa para entender o espaço de padrões e **escolher um padrão de bloqueio seguro**. **Não** é uma ferramenta para desbloquear celulares: o Android limita as tentativas com erro, então testar padrões um a um não burla uma tela de bloqueio real. Se você esqueceu o padrão do seu próprio dispositivo, use as opções oficiais de recuperação (sua conta Google, Encontre Meu Dispositivo, ou as ferramentas do fabricante).

### Privacidade
Sem backend, sem rastreamento, sem contas. Todos os dados são armazenados apenas no seu próprio navegador.

---

## 🚀 Deploy (GitHub Pages)

1. Rename the main file to `index.html`.
2. Push it to your repository.
3. Go to **Settings → Pages**, set the source to your branch (e.g. `main`) and root folder, and save.
4. Your site will be live at `https://YOUR-USERNAME.github.io/pattern-lock-generator/`.

## 🛠️ Tech

Single HTML file. No build step, no dependencies, no server. Vanilla JavaScript + SVG + IndexedDB.

## 📄 License

MIT — feel free to use, modify, and share.
