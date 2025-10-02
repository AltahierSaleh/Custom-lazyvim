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
<p align="center">  <img src="images/dashboard.png" alt="LazyVim Custom Dashboard Preview" width="700"/>

  <img width="2520" height="1680" alt="Screenshot From 2025-10-02 17-28-34" src="https://github.com/user-attachments/assets/55f05352-2720-46ab-b422-397fe901542e" />
  <br />
  <i>Preview of my custom colorscheme</i>
</p>

<!-- 👉 Place your dashboard screenshot here -->
<p align="center">
<img width="2520" height="1680" alt="Screenshot From 2025-10-02 17-29-22" src="https://github.com/user-attachments/assets/fc05eeca-1bee-4825-a319-59cc60c812be" />
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
