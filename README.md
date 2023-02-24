# MMLC Extractor
Extracts NES ROMs from the Mega Man Legacy Collection.

Based on anpage's script: https://gist.github.com/anpage/b895a34efb0bf1e4a9a4f52228067fa8

## How to use
* Make sure the latest version of Python 3 is installed at https://python.org.
* Place one of the scripts in the same directory as the MMLC executable.
  * **IMPORTANT:** Make sure that the game you extracting the ROMs from is fully updated.
  * For good measure, verify the integrity of the game via Steam.
* Run the script (in most cases, you should be able to double-click it to run it).

## FAQ
### What are the difference between the ROMs in the MMLC and the original ROMs?
They aren't identical to their original releases. All references to Nintendo have been removed in each game.

The Rockman ROMs are identical to the original games, however.

### Are the extracted ROMs compatible with ROM hacks?
No, the ROMs included with the MMLC are modified (except for the Rockman ROMs), and thus incompatible with ROM hacks. However, I included IPS patches that make the ROMs identical to the original releases, which in turn make them compatible with ROM hacks. I would recommend making backup copies of the extracted ROMs before patching them, as there may be other changes to the ROMs that I am unaware of. You can apply the IPS patches using [Lunar IPS](https://fusoya.eludevisibility.org/lips/).

**Beware that applying the patches directly without making backups will overwrite the original ROMs!**

### An update released for the MMLC and the script doesn't output valid ROMs anymore!
This is probably due to the offsets for the ROMs shifting. Create an issue and I'll try to fix it.
