<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	System Icons (Catppuccin theme)
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/a3chron/system-icons/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/template?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/a3chron/system-icons/issues"><img src="https://img.shields.io/github/issues/catppuccin/template?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/a3chron/system-icons/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/template?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

# System Icons (Catppuccin themed)

This is a little collection of my catppuccin themed system icons for some of my apps.  
Little sidenote, I am no designer, so don't expect too much.

Also got one or two otehr icons in here, will style or remove them in the near future :)

## Usage

Edit your `.desktop` files:

```
Icon=/home/your-username/Downloads/system-icons/app.png
```

Include the path to the icons there.

Sometimes they update after a few seconds, sometime only after logging out / restarting.

**Snap**

For snap apps, you will have to copy your `.desktop` file to locally override the global `.desktop` entry, 
as it will be otherwise overwritten at every restart:

```bash
cp /var/lib/snapd/desktop/applications/code_code.desktop ~/.local/share/applications/
```

(Then edit the local version)

**Flathub**

For Flathub / Flatpak Apps, you will have to give them permissions 
to access to the directory with the icons, for example:
```
~/Downloads/system.icons:ro
```

> [!NOTE]
> You can use apps like [Flatseal](https://flathub.org/apps/com.github.tchx84.Flatseal) 
> to give flatpak-apps permissions

## Preview

TODO: Will add an preview here

## Contributing

Contributions are welcome, I tried adding the transparent version of the icons too where I had it, 
so it is easier to create custom icons.

## Thanks

- [ray.so](https://ray.so/icon), A tool to create the icons


<p align="center">
 <a href="https://github.com/a3chron/gith/LICENSE"><img src="https://img.shields.io/github/license/a3chron/gith?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
</p>
