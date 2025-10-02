<h1 align="center">✨ My LazyVim Config ✨</h1>

<p align="center">
  Custom <code>colorscheme.lua</code> and <code>dashboard.lua</code> for <a href="https://www.lazyvim.org/">LazyVim</a>.
</p>

<hr />

<h2>📂 What’s inside</h2>

<ul>
  <li><b>colorscheme.lua</b> — Configures and applies your chosen colorscheme.</li>
  <li><b>dashboard.lua</b> — Custom startup dashboard layout & settings.</li>
</ul>

<!-- 👉 Place your colorscheme screenshot here -->
<p align="center">
  <img src="images/colorscheme.png" alt="LazyVim Custom Colorscheme Preview" width="700"/>
  <br />
  <i>Preview of my custom colorscheme</i>
</p>

<!-- 👉 Place your dashboard screenshot here -->
<p align="center">
  <img src="images/dashboard.png" alt="LazyVim Custom Dashboard Preview" width="700"/>
  <br />
  <i>Preview of my custom dashboard</i>
</p>

<hr />

<h2>⚡ Installation</h2>

<p>Clone or download the files into your LazyVim config directory (<code>~/.config/nvim/</code>).</p>

<h3>1) Backup existing files (optional)</h3>

```bash
mkdir -p ~/.config/nvim/backup
cp -n ~/.config/nvim/lua/plugins/colorscheme.lua ~/.config/nvim/backup/ 2>/dev/null || true
cp -n ~/.config/nvim/lua/plugins/dashboard.lua ~/.config/nvim/backup/ 2>/dev/null || true
