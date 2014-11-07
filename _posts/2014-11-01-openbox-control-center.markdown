---
layout: post
title:  "OpenBox Control Center Story"
date:   2014-11-01 22:18:30
categories: Bento
---

# Table to be done for the Bento-dev project

List of features, description of the problem and description of the required solution

## A GUI for Openbox?

In an Openbox “desktop”, the setup of the desktop is spread in different places, making them difficult to locate. It would be better to group everything in a consistant way, eventuelly in new programs overwriting the exising ones if needed.

We need new **graphical user interfaces** coded in the same langage and having an harmonized appearance, which could provide these features and be each ran from within a unique GUI  (think about the setup GUI in Xfce)

These graphical programs need to be coming along with their non graphical underlying part, therefore will need to be entirely rewritten, taking inspiration or imitating existing programs, or when needed being created if they don't already exist (there are quite a few in fact).

/!\ **The system programs aren't concerned by this projet**.

The system tools are the ones which request an administration password to allow performing the requested task. So, only the programs dedicated to the user customizations are involved by this project.

Ideally, the new tools should be destkop agnostic, have as less depends as possible, be light on resource.

## List of setups:

- Fonts
- Screen background setup
- Margins
- Main Openbox menu
- Additional entries to the main Openbox menu (think about obmenu)
- Keyboard shortcuts
- Keyboard layout
- Screen resolution
- Applications default started with the session
- Tint2 panel setup (the dedicated application does not work: "saving is not supported" and tint2 itself isn't developped anymore since 2011)
- method for localization

## The programs which allow managing all this so far:

- obconf (from the Openbox project)
- lxappearance (from the LXDE project)
- obmenu (third party program to configure the Openbox main menu)
- obkey (an exissting program, to manage the keyboard shortcuts)
- tint2conf 0.11+svn20111022 (the tint2 panel configuration tool which write the configuration file)
- lxqt-config (just born, allows management of the Qt programs appearance).
- « Keyboard layout » : a home made script calling “dpkg-reconfigure keyboard-layout” in a maximized default console. (x-terminal-emulator), because the lxkeyboard program was not writing the configuration, when I was trying it in the first Ubuntu Openbox Remixes produced. (While “Keyboard Layout” prompts the user for the administration password, so a non root program could also be nice to have… perhaps even with a root/non root option, so to have the choice of applying the change system wide or to the user configuration only.
- To be continued…
