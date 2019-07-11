# Anaconda Main Packages

This is a repository with a list of the packages to install after performing
a clean install of [Anaconda](https://www.anaconda.com/).

## Directions

In order to install these dependencies, one has to do the following:

1. Do a clean install of Anaconda [here](https://www.anaconda.com/distribution/#download-section).
2. After installing the base Anaconda installation, go to this directory on the terminal, and type the following

	```bash
	make all
	```
	
This will install all of the desired packages to the `core` or `base` Anaconda environment.
And you're all set!

You can check if any of the packages were correctly installed by:

```python
import <name of package>
```

after opening an _iPython_ session in the terminal.
	
