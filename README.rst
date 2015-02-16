Quick method: clone this repository and run ``make``.

Customizing the keybinding for ``less(1)`` is straightforward:
make a keybindings file and run ``lesskey`` on it.
It will generate a binary file called ``.less`` in your home directory,
and ``less`` will apply those customizations each time it runs.

The keybindings file does not need to be ``~/.lesskey``,
but it might be easier to find that way.
I've symlinked ``~/.lesskey`` to the `lesskey file <./lesskey>`_ in my local repository.
