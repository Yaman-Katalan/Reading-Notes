# Reading Notes

## Command Line Basics

The command line, often abbreviated as CL, is a text-based interface used for executing commands to perform various tasks within an operating system. It interacts directly with the system's shell program, such as BASH in Unix-like systems, to execute commands and display results as text output.

## Basic Navigation

- **PWD**: Displays the current working directory.
- **Paths**: Can be either absolute (starting from the root directory, '/') or relative (relative to the current directory).

## File System Basics

- **Everything is a file**: Devices and resources like keyboards and monitors are represented as files.
- **Extensionless System**: Linux ignores file extensions to determine file types.
- **Case Sensitivity**: The Linux file system is case-sensitive.
- **Handling Spaces in Names**: Enclose names with spaces in double quotes or use escape characters.
- **Hidden Files**: Files starting with a dot ('.') are considered hidden.

## Manual Pages

Manual pages provide comprehensive guidance on command usage and available arguments. They typically categorize arguments into two types: short (single dash + letter) and long (double dash + word).

## File Manipulation

- **mkdir**: Creates directories. Options include -p (create parent directories) and -v (verbose).
- **rmdir**: Removes directories. Requires empty directories. Options include -v (verbose) and -p (create parent directories).
- **touch**: Creates or updates file timestamps. Can also create a blank file.
- **cp**: Copies files or directories. Supports options like -r (recursive copying).
- **mv**: Moves or renames files/directories. Can effectively rename within the same directory.
- **rm**: Removes files or directories. Supports options like -r (recursive removal).

### Cheat Sheet

- **Navigation**: Use PWD to check the current directory. Paths can be absolute or relative.
- **File System**: Everything is a file, Linux is extensionless and case-sensitive.
- **Manual Pages**: Provide detailed command usage information. Arguments can be short or long.
- **File Manipulation**: Use mkdir for creating directories, rmdir for removing directories, touch for timestamps and creating files, cp for copying, mv for moving/renaming, and rm for removing files/directories.
