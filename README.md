# NEO Rescue Tools for L2 BGN

## Requirements
- Text Editor (For example: Vim, Nano, Atom, Notepad++, Visual Studio Code, Sublime Text)
- Wget

## Installation
- Make sure to download and place the tool in the ``/usr/bin`` directory.
- Download the tool source code by running the command: ``sudo wget https://raw.githubusercontent.com/madfxr/neo-rescue-tools/main/neo-rescue-tools``.
- Grant access rights to the ``/usr/bin/neo-rescue-tools`` file by running the command: ``sudo chmod +x /usr/bin/neo-rescue-tools``.
- Before running this tool, make sure to modify the ``/usr/bin/neo-rescue-tools`` file and change the section:
  ```
  declare -a image_ids=("<image_id>:IMG-1" "<image_id>:IMG-2" "<image_id>:IMG-3")
  ```

## Notes
- Change on this line ``"<image_id>:IMG-1" "<image_id>:IMG-2" "<image_id>:IMG-3"`` with the Image ID being used (For example: ``12345678-abcd-a1b2-2024-neo123456789:IMG-1 12345678-efgh-c3d4-2024-neo123456789:IMG-2 12345678-ijkl-e5f6-2024-neo123456789:IMG-3``*
