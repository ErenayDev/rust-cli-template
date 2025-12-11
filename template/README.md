# {{ crate_name }}

{{ long_description }}

[![Rust CI](https://img.shields.io/github/actions/workflow/status/{{ gh-username }}/{{ crate_name }}/ci.yml?style=for-the-badge&label=Rust%20CI)](https://github.com/{{ gh-username }}/{{ crate_name }}/actions/workflows/ci.yml)

## Installation

### Note
If you are using Linux, you may need to install additional dependencies such as `example_lib`

### Prebuilt Binaries
You can download prebuilt binaries for **Linux**, **MacOS** and **Windows** from the [Releases page](https://github.com/{{ gh-username }}/{{ crate_name }}/releases).

| System / Distribution | File Extension | Description |
|:----------------------|:---------------|:------------|
| **Generic Linux** | `.tar.gz`      | The most universal build. Extract and run the binary. |
| **Debian / Ubuntu** | `.deb`         | Install using `dpkg`. |
| **Fedora / CentOS / openSUSE** | `.rpm`  | For all RPM-based systems. |
| **Windows** | `.exe` or `.zip` | The standalone **`.exe`** is ready to run. The **`.zip`** contains the executable. |
| **macOS** | `.tar.gz`      | Extract and run the binary. |

### From Source
Requires **Git**, **Rust**, **Cargo**:

```bash
git clone https://github.com/{{ gh-username }}/{{ crate_name }}.git
cd {{ crate_name }}
cargo install --path .
```

After installation, you can run `{{ crate_name }}` in your terminal.

## CLI Arguments
`-i`: Pass a file path to this. just for example
etc.

## Cross-platform
We tested in Linux and Windows. It works fine. But MacOS has the `x` problem. See [#1](/../../issues/1) <!-- issue number -->

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos={{ gh-username }}/{{ crate_name }}&type=date&legend=top-left)](https://www.star-history.com/#{{ gh-username }}/{{ crate_name }}&type=date&legend=top-left)

## Contributing
Contributions are welcome! Issues, PR's etc.

<a href="https://github.com/{{ gh-username }}/{{ crate_name }}/graphs/contributors">
    <img src="https://contrib.rocks/image?repo={{ gh-username }}/{{ crate_name }}" alt="{{ crate_name }} contributors" />
</a>

---

Created with 🩵 by [{{ gh-username }}](https://github.com/{{ gh-username }})
