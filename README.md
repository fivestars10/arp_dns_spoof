# DNS & ARP Spoofing

This script will demonstrate the concept of DNS and ARP spoofing.

## Installation

Use the package manager [apt-get](https://linux.die.net/man/8/apt-get) and [pip](https://pip.pypa.io/en/stable/) to install dependencies.

```bash
Update Repositories Type
   sudo apt-get update

Download Required Packages By Using this Command
   sudo apt-get -y install gcc make

Download Python Package By Using This Command
   wget https://www.python.org/ftp/python/3.6.5/Python-3.6.5.tgz

Extract Package File
   tar -xvf Python3.6.5.tgz

Navigate to Python Folder
   cd Python-3.6.5

Install By Using These Commands
   sudo ./configure
   sudo make
   sudo make install

Install Required Packages for NetFilterQueue
   sudo apt-get install build-essential python-dev libnetfilter-queue-dev

Install from requirement file
   python3.6 -m pip install -r requirements.txt
```

## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
