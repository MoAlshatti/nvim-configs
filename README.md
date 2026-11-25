## Usage
First install the tools needed <br>
For ubuntu and debian: `sudo apt install -y unzip curl wget git build-essential nodejs npm python3-venv golang-go` <br>
For Fedora: `sudo dnf install -y unzip curl wget git gcc make nodejs npm python3 golang` <br>
For Arch: `sudo pacman -S --needed unzip curl wget git base-devel nodejs npm python go` <br>
<br>
To install treesitter run the following: <br>
```
curl -LO https://github.com/tree-sitter/tree-sitter/releases/latest/download/tree-sitter-linux-x64.gz
gunzip tree-sitter-linux-x64.gz
chmod +x tree-sitter-linux-x64
sudo mv tree-sitter-linux-x64 /usr/local/bin/tree-sitter
tree-sitter --version
```
<br>

Copy the configs: `git clone https://github.com/MoAlshatti/nvim-configs ~/.config/nvim`


