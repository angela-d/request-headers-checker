## Debian-based Linux Install (Ubuntu, Mint, etc) ##
- Obtain the latest .deb from [Github Releases](https://github.com/angela-d/request-headers-checker/releases)
- Navigate to where the .deb was downloaded to (ie. ~/Downloads) `cd ~/Downloads && ls *.deb`
- If you see reqhead.deb, install via apt: `apt install ./reqhead.deb`
- Note that apt will not auto-install new versions!  To see when new versions are released, click **Watch** at the top of this page and Github/Not a Bug will show it in your dashboard feed

**To update a previous .deb installed version**
- Repeat the download instructions above, apt will automatically install over the previous version.

## Non-Debian Install ##

**Dependencies**

- Python 3+
- Pip3

From the Python standard library:
* argparse
* json
* pprint
* socket
* ssl
* sys

Pip3:
* Requests

Clone the repository:
```bash
git clone https://github.com/angela-d/request-headers-checker && cd request-headers-checker
```


Install the pip dependency:
```bash
pip3 install -r requirements.txt
```

To run it:
```bash
./reqhead
```

You will be prompted to enter the URL you wish to validate.

Done.
