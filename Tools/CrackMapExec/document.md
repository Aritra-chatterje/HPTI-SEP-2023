Certainly! Here are the installation instructions for CrackMapExec (CME) on a Unix-based system in Markdown format:

```markdown
# CrackMapExec Installation on Unix Systems

CrackMapExec (CME) is a post-exploitation framework used by penetration testers and red teamers for automating network vulnerability assessment and exploitation. You can install it on Unix systems using different methods. Here are some options:

## Installation from Source with Poetry

Before starting, ensure you have Git, Python 3, Poetry, and the required development libraries installed on your system.

```bash
# Install necessary dependencies
sudo apt-get install -y libssl-dev libffi-dev python3-dev build-essential

# Clone the CME repository
git clone https://github.com/mpgn/CrackMapExec

# Change to the CME directory
cd CrackMapExec

# Install dependencies with Poetry
poetry install

# Run CrackMapExec
poetry run crackmapexec
```

## Python Package Installation (using pipx)

It's recommended to use pipx for installing CME as it helps manage Python packages.

```bash
# Install pipx
python3 -m pip install pipx

# Clone the CME repository
git clone https://github.com/mpgn/CrackMapExec

# Change to the CME directory
cd CrackMapExec

# Install CME with pipx
pipx install .
```

## APT Package (Kali Linux)

Note that this method may not have the most up-to-date version of CME.

```bash
# Install CME using APT (Kali Linux)
sudo apt install crackmapexec
```

## Binaries

In most cases, using pre-compiled binaries is the easiest way to install CME as it requires no additional installation steps.

1. Go to the "Actions" tab at the top of the CME repository on GitHub.
2. Click on the latest build.
3. Download the appropriate binary for your OS.
4. Binaries are available for Python 3.8, 3.9, 3.10, and 3.11.
5. Note that you need to be logged into GitHub to download the binaries from the Actions feature.
```

You can save this text to a `.md` file, and it should render as a nicely formatted Markdown document.
