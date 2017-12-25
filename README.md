gnome-shell-extension-suspend-button
====================================

GNOME Shell Extension Suspend-Button for GNOME 3.10 / 3.12 / 3.14 / 3.16 / 3.18 / 3.20 / 3.22 / 3.24 / 3.26


Install
=======

Run

```
make
make install
```

This will build and install the extension to ``~/.local/share/gnome-shell/extensions/``.   

Alternatively run
```
make
DESTDIR=/ make install
```

This will build and install the extension to ``$(DESTDIR)/usr/share/gnome-shell/extensions/``.


Use
===
The `Two buttons` toggle option when ON display both a suspend button and a shutdown button. When OFF it display only a Suspend button. 

The `Suspend default` toggle option when ON change alt-switch-buttons behaviour to default to suspend. Press alt to shutdown. This setting has no effect if `Two buttons` toggle is set to ON.
