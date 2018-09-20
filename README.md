# fitnesse-formatter
Utilize the FitNesse WikiFormattter to mass format files from the command line

Requirements
============
- nodejs
- FitNesse supporting wiki format pages

Running
=======
Execute the `fitnesse-format` script and provide the path to the FitNesse
directory. By default, the formatter will scan for all `.wiki` files and
format them using the FitNesse formatter found in the GUI version of
FitNesse.

If you wish to format only a subset of files, an additional argument can
be passed to specify the specific scan directoroy.

- `./fitnesse-format /path/to/FitNesse` - will format all FitNesse .wiki files
- `./fitnesse-format /path/to/FitNesse /path/to/FitNesse/Suite/subdir` - will
  format only .wiki files in the Suite/subdir directory
