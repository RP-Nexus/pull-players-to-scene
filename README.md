# Pull Players to Scene

A Foundry VTT add-on that makes pulling multiple players to a scene easier. It adds a context menu option on scenes that opens a dialog where you choose which players to pull.

Compatible with Foundry VTT v13 (verified on v14).

## Installation

### Option 1: Install from manifest URL (recommended)

1. In Foundry VTT, open the **Setup** screen and go to **Add-on Modules**.
2. Click **Install Module**.
3. Paste this URL into the **Manifest URL** field at the bottom of the dialog:

   ```
   https://github.com/RP-Nexus/pull-players-to-scene/releases/latest/download/module.json
   ```

4. Click **Install** and wait for it to finish.

### Option 2: Manual install

1. Download `module.zip` from the [latest release](https://github.com/RP-Nexus/pull-players-to-scene/releases/latest).
2. Extract it into a folder named `pull-players-to-scene` inside your Foundry user data `Data/modules/` directory, so that `module.json` sits at `Data/modules/pull-players-to-scene/module.json`.
3. Restart Foundry VTT.

### Enable the module

1. Launch your world as a Game Master.
2. Go to **Game Settings** → **Manage Modules**.
3. Check **Pull Players to Scene** and click **Save Module Settings**.

## Usage

1. Open the **Scenes** sidebar tab.
2. Right-click a scene and choose the pull players option.
3. Select the players to pull and confirm.

## Building from source

Requires Node.js 24 or newer.

```
npm ci
npm run build
```

The built module is written to `dist/`. Copy or symlink that folder to `Data/modules/pull-players-to-scene` to test it.

## License

MIT
