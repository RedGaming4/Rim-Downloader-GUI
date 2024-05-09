installation and usage:
1. `git clone https://github.com/hadobedo/myrientgrabber-ps3/ && cd myrientgrabber-ps3/`
2. `pip install -r requirements.txt`
3. `python3 ./myrientDownloaderGUI.py`

if you're on a linux distro like arch whose python environment is externally managed you can install requirements like so:
`sudo pacman -S python-requests python-beautifulsoup4 python-pyqt5 python-tqdm`

todo:
- proper windows support (settings button w/ support for setting custom `PS3Dec`, `splitps3iso` binary paths)
- better output
