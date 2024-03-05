# Automation

Choosing the appropriate module can simplify your tasks, enhance code readability, and ensure cross-platform compatibility, ultimately contributing to better code quality and maintainability.

[Python Regular Expressions Tutorial](https://www.datacamp.com/community/tutorials/python-regular-expression-tutorial)

[shutil](https://pymotw.com/3/shutil/)

[os](https://pymotw.com/3/os/)

[Automation Ideas](https://www.youtube.com/watch?v=qbW6FRbaSl0&t=69s)

[Automating Your Browser and Desktop Apps](https://www.youtube.com/watch?v=dZLyfbSQPXI)

[Watchdog](https://pythonhosted.org/watchdog/)

1. How can you use regular expressions in Python to search for specific patterns in a string, and what is the primary module to work with them?

* Import the re module

* Define a regex pattern

* Use re functions to search for patterns

2. What is the purpose of the shutil module in Python, and provide an example of a common use case for file or directory management with this module?

The shutil module in Python is used for file and directory management. Common use cases include copying, moving, renaming, deleting files or directories, and archiving.

* Copying:

import shutil
shutil.copy('source.txt', 'destination.txt')

* Moving/Renaming:

import shutil
shutil.move('old_location.txt', 'new_location.txt')

* Deleting:

import shutil
shutil.rmtree('directory_to_delete')

* Archiving/Extracting:

import shutil
shutil.make_archive('archive_name', 'zip', 'source_directory')
shutil.unpack_archive('archive_name.zip', 'extracted_directory')

3. Compare and contrast the os and shutil modules. When would you choose to use one over the other?

`os` is suitable for basic file and directory operations and platform-specific tasks, while `shutil` is preferred for high-level, cross-platform operations like copying, moving, and archiving files and directories. Use os for simplicity and platform-specific needs; use shutil for convenience and portability.