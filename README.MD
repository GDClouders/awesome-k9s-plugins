# Awesome K9s Plugins

A simple collection of K9s plugins that I use in my personal setup.


## Plugins

A list of plugins included in this repository.  
- **anti-finalizer** - ***simply put finalizer to NULL***
- **full-wonderful-logs** - ***coloured log scrollable*** - requirements: ccze, bat

## Usage

Copy any plugin folder into your local K9s configuration:

```bash
cp $PLUGIN_FILE ~/.config/k9s/plugins/
```

## Tips
- file ~/.config/k9s/**plugins.yaml** and folder ~/.config/k9s/**plugins**/ does not exist at default k9s installation, you need to create them. 

- You need the **plugins.yaml** file with the "plugins:" on top only **~/.config/k9s/** to let k9s magically merge all the plugins that you put in the subfolder "plugins"

## Recommended Commit Types

| Type    | Content                                   | Example Commit                                  |
|---------|-----------------------------------------------|------------------------------------------------|
| `feat`  | Adding a new plugin or snippet                | `feat: add remove-finalizers plugin`          |
| `fix`   | Fixing an existing plugin or snippet          | `fix: correct args for restart-pods plugin`  |
| `docs`  | Updating documentation                         | `docs: add usage instructions for plugin X`  |
| `chore` | Repo cleanup, folder reorganization, config   | `chore: reorganize plugin folders`           |

