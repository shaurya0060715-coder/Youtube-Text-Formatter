# Minecraft Blocks YouTube Comment Formatter
A client-side utility built for content creators, developers, and Minecraft enthusiasts. This lightweight, single-page application allows you to type, format, and preview text exactly as it appears when posted in a YouTube comment thread—all wrapped up in a pixel-perfect, custom-designed Minecraft block interface.
------------------------------
## 🎨 System Architecture & Interface Design

* Custom Block Matrix: Features a fully reactive UI container mimicking authentic in-game blocks. Users can hot-swap the interface wrapping between Bedrock, Crafting Table, and Netherite structural themes.
* Vector Hotbar Icons: Displays pure-CSS pixel graphics directly inline next to headers, with an interactive drop-down picker to switch between a Diamond Sword, Diamond Pickaxe, and Golden Apple.
* Optimized Canvas Tab Metadata: Employs an inline URL-safe data URI stream in the web page <head> to cleanly render a 3D isometric Minecraft Grass Block favicon without external asset dependency.
* Fully Autonomous Layout Rendering: Built using strict functional scripting models to guarantee the code logic processes entirely client-side without layout leaks, third-party trackers, or network requirements.

------------------------------
## 🛠️ Code Engine Core Components 
### 1. Granular Markdown Parser Matrix
The formatting engine translates YouTube's unique inline syntax wrappers on the fly. It utilizes text boundary matrices to safely interpret isolated or nested text weights without breaking your general structure:

* *text* → Bold (<strong>)
* _text_ → Italics (<em>)
* -text- → Strikethrough (<del>)
* Supports full string combinations such as *_-nested text-_* for multi-style layouts.

### 2. Temporal Chronological Tracking
An inline regular expression tracker automatically looks for dynamic time indicators (matching patterns like MM:SS or HH:MM:SS). It strips out the values and wraps them in interactive time anchors (.yt-timestamp), allowing you to accurately stage clickable timestamp highlights for video references (e.g., 12:34).
### 3. Boundary Character Safeguard Engine
Monitors the text string sizing boundaries in real time. Because YouTube imposes a strict 10,000-character ceiling on user threads, the tool tracks your usage count against the storage constraint and applies conditional formatting states to flag a bright red layout alert if you overflow the cap.
### 4. Zero-Friction Target Clipboard Pipeline
Features a green, retro-button trigger linked to the modern browser navigator.clipboard framework. It packages the raw text exactly as typed (preserving formatting tokens) for safe execution to your clipboard space.
------------------------------
## 📄 License & Asset Attributions

* Interface Typography: Built using Google Web Fonts' open-source VT323 monospaced pixel typeface under the SIL Open Font License.
* Vector Models: Custom inline data-encoded SVG assets are mapped explicitly within document structures to avoid external fetching latency.
------------------------------
## 🌐 Website Link

* The website is available at `https://youtube-text-formatter.vercel.app`
