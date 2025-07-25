<img
    align="right" alt="title" width="200px"
    src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/7/7f/Fishing_Rod_JE2_BE2.png/revision/latest?cb=20200201063839"
/>

# Rod Scroll, Macro Mod

When you right-click, the mod quickly scrolls to a random hotbar slot  waits 3 ticks, and then automatically switches back to your fishing rod 

## Supported Clients / Versions

<table>
<tr><th>Supported Clients</th><th>Supported Versions</th></tr>
<tr><td>
        
| Client  |     Supported      |
|---------|:------------------:|
| Vanilla | :white_check_mark: |
| Forge   | :white_check_mark: |
| Lunar   | :white_check_mark: |
| Badlion |        :x:         |
| Feather |        :x:         |
| Labymod | :white_check_mark: |

</td><td>
    
| Version |     Supported      |
|---------|:------------------:|
| 1.8     | :white_check_mark: |

</td></tr>
</table>


## Installation

To install Weave-Loader, you can either download a pre-built release from
the [releases page](https://github.com/Weave-MC/Weave-Loader/releases), or build it yourself from source.

### Building with Gradle

- First clone the project with [Git][git] then `cd` into the project directory: 

```bash
git clone --recursive https://github.com/Weave-MC/Weave-Loader
cd Weave-Loader
```

You then need to give permission to the Gradle wrapper and run the `agent` task. This can be done a bit differently
depending on your operating system:

<details open>
<summary><b>UN*X</b> (Linux, BSDs, macOS, etc.)</summary>

```bash
chmod +x ./gradlew
./gradlew agent
```
</details>

<details>
<summary><b>Windows</b></summary>

```powershell
.\gradlew.bat agent
```
</details>

## Usage

To use Weave-Loader, you have two options:
- Use [Weave-Manager](https://github.com/Weave-MC/Weave-Manager) to handle the process of attaching Weave to your preferred Minecraft client automatically.
- Manually add the Weave-Loader agent mentioned in the previous step to the JVM arguments when launching Minecraft.
  - You will need to include the following argument: `-javaagent:$PATH_TO_AGENT`

Weave will automatically load mods from `~/.weave/mods/`.

## Contributing

We welcome contributions from anyone interested in improving Weave-Loader. If you find a bug or have an idea for a new
feature, feel free to submit a pull request.

---

<div align="right">

Weave-Loader is licensed under the [GNU General Public License v3.0][license].

</div>

[git]:     https://git-scm.com/

[license]: https://github.com/Weave-MC/Weave-Loader/blob/master/LICENSE
