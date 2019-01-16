# c-terminal-text-editor
A terminal text editor. Hand-written in C. Learning from online book "Build Your Own Text Editor".

## Usage
```shell
# Compile using Make
make

# Run text editor (without a filename)
./kilo

# Run text editor (with a filename)
# - If a file with this filename exists in the working directory, editor opens the file for edit.
# - Else, editor creates a new file with this name for edit.
./kilo path/to/file.ext
```
