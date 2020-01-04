# Onboarding
Welcome to the PhD program!
Here are a few resources that you will hopefully find useful.

## Computational Resources
### High Performance Computing
Cranfield's supercomputer for researchers is Delta.
Before accessing it you will need to fill and submit this
  [form](https://intranet.cranfield.ac.uk/it/Documents3/DeltaApplication.pdf)
  to IT.
The official documentation can be found
  [here](https://intranet.cranfield.ac.uk/it/Documents3/Getting%20Started%20With%20HPC.pdf).

Hint: stick this command, where s000000 is your student number, in a bash script
  to make accessing the system easier.
``` bash
ssh -t s000000@hpcgate.cranfield.ac.uk ssh s000000@delta.central.cranfield.ac.uk
```

Use `module load [package name]` or `ml [package name]` to load the software you want to use.
Type `ml` to list the loaded packages.
The module system is nice because it allows you to easily load and manage the software you want to use.


### Personal Computer
Linux is used on HPC systems and by many scientists, it is very useful to get comfortable with it.
Luckily Linux has been integrated into Windows, there is no more need to dual boot.

#### Accessing Linux from Windows
 1. [Install](https://docs.microsoft.com/en-us/windows/wsl/install-win10) Windows Subsystem Linux (WSL).
    This will give you access to the Command Line Interface (CLI) of a Linux Distro.
    Ubuntu is the most used and probably the best tested, it's the one I would recommend.
 2. [Install](https://code.visualstudio.com/download) Visual Studio Code
 3. Open WSL and enter `code .` or `code fileToEdit.cpp`.
    This will open VS Code that is integrated with WSL, allowing you to use the Linux CLI from inside VS Code.
 4. [Install](https://sourceforge.net/projects/xming/) Xming and add `export DISPLAY=:0` to your `.bashrc` file.
    Here is more info about [.bashrc](https://www.maketecheasier.com/what-is-bashrc/).
 5. It is helpful to [learn Emacs](http://ergoemacs.org/emacs/emacs_basics.html) or [learn Vim](https://danielmiessler.com/study/vim/).
    Both are text editors that can be used from the command line.
    It's a great thing when you figure out how to do everything using your keyboard, it takes so long to reach out and use the mouse ;)
    You can get extension is VS Code that will allow you to use key-bindings for either of these.
    I prefer Emacs, it is crazy powerful, but just an fyi there is a never ending battle between Emacs people and Vim people.
    You should learn a bit of both since each ones key binding show-up all over the place.




Helpful Links
 * [A Quick Guide to Get Started with the Linux Command Line](https://www.makeuseof.com/tag/using-linux-with-wayland/)
 * Understand how to use Git with this [Hello World](https://guides.github.com/activities/hello-world/)
 * [An In-depth tutorial on Linux development on Windows with WSL and VS Code](https://devblogs.microsoft.com/commandline/an-in-depth-tutorial-on-linux-development-on-windows-with-wsl-and-visual-studio-code/)
