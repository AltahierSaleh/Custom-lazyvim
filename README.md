<h1 align="center">✨ My LazyVim Config ✨</h1>

<p align="center">
  Custom <code>colorscheme.lua</code> and <code>dash.lua</code> for <a href="https://www.lazyvim.org/">LazyVim</a>.
</p>

<hr />

<h2>📂 What’s inside</h2>

<ul>
  <li><b>colorscheme.lua</b> — Configures and applies your chosen colorscheme.</li>
  <li><b>dashboard.lua</b> — Custom startup dashboard layout & settings.</li>
</ul>

<!-- 👉 Place your colorscheme screenshot here -->
<p align="center">
  <img width="2511" height="1613" alt="Screenshot From 2025-10-02 17-36-49" src="https://github.com/user-attachments/assets/3cbde9a0-ac4f-4c0b-b716-c281f811ccaf" />
  <br />
  <i>Preview of my custom colorscheme</i>
</p>

<!-- 👉 Place your dashboard screenshot here -->
<p align="center">
<img width="2511" height="1613" alt="Screenshot From 2025-10-02 17-37-38" src="https://github.com/user-attachments/assets/7c5d4f32-f435-4b33-99c7-302f2dc0da02" />
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
```

<h3>2) Option A — Clone repo & copy</h3>

```bash
git clone https://github.com/AltahierSaleh/Custom-lazy.git /tmp/my-lazyvim-config

cp /tmp/my-lazyvim-config/colorscheme.lua ~/.config/nvim/lua/plugins/colorscheme.lua
cp /tmp/my-lazyvim-config/dash.lua ~/.config/nvim/lua/plugins/dashboard.lua
```

<h3>2) Option B — Download files directly</h3>

```bash
curl -fsSL https://raw.githubusercontent.com/AltahierSaleh/Custom-lazy/main/colorscheme.lua \
  -o ~/.config/nvim/lua/plugins/colorscheme.lua

curl -fsSL https://raw.githubusercontent.com/AltahierSaleh/Custom-lazy/main/dash.lua \
  -o ~/.config/nvim/lua/plugins/dashboard.lua
```

<h3>3) Sync plugins</h3>
<p>use the lazyvim sync command to sync added plugins Then restart Neovim. </p>

<hr /> <h2>📝 Notes</h2> <ul> <li>Place plugin specs like <code>colorscheme.lua</code> in <code>lua/plugins/</code> — LazyVim loads them automatically.</li> <li>You can move <code>dashboard.lua</code> into <code>lua/plugins/</code> or into your own namespace (e.g., <code>lua/yourname/dashboard.lua</code>).</li> <li>If colorscheme doesn’t apply, make sure it’s set correctly inside <code>colorscheme.lua</code>.</li> </ul> 












