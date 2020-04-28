## Requirements
 - Install ms-vscode.cpptools extension for IntelliSense
 - Install code-debug fork extension for kgdb support (https://github.com/atseanpaul/code-debug/releases)
 - Create compile_commands.json using scripts/gen_compile_commands.py in kernel tree

## Configuration
Edit values in settings.json to reflect your development environment. Note some paths are outside chroot and some are inside chroot, they're commented in there.