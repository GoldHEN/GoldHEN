# GoldHEN Cheat Menu
_Cheat Menu allows you bring up a Menu while in-game for you to select cheats._

## Features
- `.json` support
- `.shn` support
- `.mc4` support

### :warning: Warnings
The Cheat Menu is experimental, use with caution.  
Please report cheat related issues to the cheat author(s).

### Disclaimer:
While we make every effort to deliver high quality products, we do not guarantee that our products are free from defects. Our software is provided 'as is' and you use the software at your own risk.

### Usage:
- Long press `Share` button in-game to bring up Cheat menu.
- `↑` / `↓` to highlight cheat.
- `X` to Toggle cheat `On`/`Off`.
- `L1` / `R1` to switch between cheat files.
- **Note:** `L1` / `R1` is disabled when cheats are active.

### Storage:
- Use `FTP` to upload cheat files to:
  - `/user/data/GoldHEN/cheats/json/`
  - `/user/data/GoldHEN/cheats/shn/`
  - `/user/data/GoldHEN/cheats/mc4/`
- Naming convension: `{titleid}_{version}*.{format}`
  - e.g. `CUSA001234_01.01_anything_really_before.json`
  - e.g. `CUSA001234_01.01_abc_def_ghi.shn`
  - e.g. `CUSA001234_01.01.mc4`
 - **Note:** Maximum of 8 cheat files.

### Format Changes:
- Cheat descriptions:
  - json: Add a 'description' field to the cheat.
    - e.g. "description": "test",
  - shn/mc4: Add a 'Description' attribute to the cheat.
    - e.g. &lt;Cheat Text="HP" Description="sample text"&gt;
- **Note:** Only visible when in focus.

### To Do:
- Add more formats.

### Credits
- [ctn123](https://github.com/ctn123)
- [Shinigami](https://github.com/ScriptSK)
- [SiSTRo](https://github.com/SiSTR0)