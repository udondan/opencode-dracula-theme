### [OpenCode](https://opencode.ai)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/opencode.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/opencode/archive/main.zip) option and unzip them.

#### Activating theme

1. Create the OpenCode themes directory if it doesn't exist:

   ```bash
   mkdir -p ~/.config/opencode/themes
   ```

2. Symlink the theme file to the OpenCode themes directory:

   ```bash
   ln -s /path/to/opencode-dracula-theme/dracula.json ~/.config/opencode/themes/dracula.json
   ```

   Replace `/path/to/opencode-dracula-theme` with the actual path where you cloned/downloaded the theme.

3. Edit your OpenCode configuration file (`~/.config/opencode/config.json`) and set the theme:

   ```json
   {
     "theme": "dracula"
   }
   ```

4. Restart OpenCode
