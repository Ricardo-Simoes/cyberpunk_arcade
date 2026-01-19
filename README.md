<p align="center">
  <img width=90% src="https://raw.githubusercontent.com/Ricardo-Simoes/cyberpunk_arcade/refs/heads/main/media/banner.png" alt="banner" />
</p>

<div align="center">
  <a href="https://raw.githubusercontent.com/Ricardo-Simoes/cyberpunk_arcade/refs/heads/main/LICENSE">
    <img src="https://img.shields.io/badge/license-009dff?style=for-the-badge" alt="license" />
  </a>
  <a href="https://www.pling.com/p/2342719/">
    <img src="https://img.shields.io/badge/Download-32cd32?style=for-the-badge" alt="download" />
  </a>
</div>
<br>
<div align="center">
  Cyberpunk + Arcade + TRON = This GRUB Theme!
</div>

### ⚙️ Installation ( Manual )

#### 1️⃣ Unpack theme

```fish
unzip cyberpunk_arcade.zip
```

#### 2️⃣ Copy the theme directory.

```fish
sudo cp -r cyberpunk_arcade /boot/grub/themes/
```

#### 3️⃣ Make changes to the GRUB config file.

```fish
sudo nano /etc/default/grub
```

  Find the line `GRUB_THEME=` then change it to `GRUB_THEME="/boot/grub/themes/cyberpunk_arcade/theme.txt"`

  Then save the file.

#### 4️⃣ Finally, update the grub.

```fish
sudo update-grub
```

  Now the theme should be installed successfully, enjoy !!

</details>

## 🖼️ Preview

![preview](https://raw.githubusercontent.com/Ricardo-Simoes/cyberpunk_arcade/refs/heads/main/media/previews/preview_cyberpunk_arcade_grub_theme.jpg)
