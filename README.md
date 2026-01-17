# Rebuilding Society

Welcome to the Rebuilding Society vault! This vault contains information on how to rebuild civilization in the event society ever collapses.

> [!warning]
> If you are in a rush, please see [EMERGENCY](../EMERGENCY.md).

The only pre-requisite is that you can read English at the B2 level as defined by Common European Framework of Reference for Languages (CEFR).

This document goes over how to install this project. If you would like to start reading about the project's contents, please see [START HERE](GitHub/00%20-%20Introduction/START%20HERE.md).

If you would like to read more about the project vision, please see [VISION](./VISION.md).

Note: due to GitHub restrictions on file sizes, books are stored here: https://drive.google.com/drive/folders/1YsfrqwQUMK0xpzpKCEjX6iRCRldhBG2V?dmr=1&ec=wgc-drive-globalnav-goto.

## Installation

> [!warning]
> This section requires knowledge of the command line and git.

To install this project on your machine:

1. Clone (download) this repository onto your machine:

	```shell
	git clone https://github.com/kevin8999/Rebuild-Society/
	```

2. Go into the project folder.

	```shell
	cd Rebuild-Society/
	```

### Server

To run the documentation server:

1. Create a virtual enviroment in Python.

	```shell
	python3 -m venv .venv
	```

2. Activate the virtual environment.
	- On Windows, run:
	
		```shell
		source ./.venv/Scripts/activate
		```
	
	- On MacOS and Linux, run:

		```shell
		source ./.venv/bin/activate
		```

3. Install the software to run the server.

	```shell
	pip install mkdocs-material
	```

4. Run the server.

	```shell
	mkdocs serve
	```

5. The website should now be viewable at http://localhost:8000
