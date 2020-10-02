# Paletin: Convert Your Own Image Into Color Palette

Paletin is a converter tool to create a GIMP color palette file (\*.gpl) from your own image. This tool is initiated by Gimpscape Community. 



## Dependecy

This tool needs the following package/tool to run as well.

- [extcolors](https://github.com/CairX/extract-colors-py/) (Please refer to its Readme to install this dependency)



## Installation

Here is some steps to install paletin

```bash
# download script
sudo wget https://raw.githubusercontent.com/raniaamina/paletin/main/paletin -P /usr/local/bin/

# make it executeable
sudo chmod +x /usr/local/bin/paletin


```



## Usage

Here is the command to use paletin

`paletin your-image.jpg palette-name`

If you have inkscape installed in your system, paletin will automatically copy the generated palette into your Inkscape palette directory. Make sure your palette name does not contain any space.



## Disclaimer

We don't guarantee anything about this tool, so please use it at your own risk. We can't give 24/7 support if you have a problem when using paletin. Of course we'll help as much as we can. The [Gimpscape Telegram group](https://t.me/gimpscape) is the best place to ask your questions about this tool.

If you feel that this tool has helped you to create, feel free to donate a cup of coffee on the [**Dev-Lovers Page**](https://devlovers.netlify.com/) :")
