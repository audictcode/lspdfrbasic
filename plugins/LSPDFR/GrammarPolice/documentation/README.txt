========================
Grammar Police Ultimate
========================
Welcome to Grammar Police!  This was written as a replacement for VocalDispatch.
The goal was to provide a more reliable speech recognition experience and a more
flexible interface.  Some key features:

    - Accept callouts, request backup, and change your status vocally
    - HoldToTalk setting will prevent dispatch from interrupting you
    - Define your own actions and customize your dialogue
    - Automatically manage callout availabilty based on status 
    - Defaults to StopThePed and UltimateBackup when available


Prerequisites
=============
- Rage Plugin Hook v1.90
- LSPDFR 0.4.9
- StopThePed or TrafficPolicer for Registration/Insurance status (optional)
- StopThePed or ArrestManager for Coroner and Tow Truck (optional)


Installation
============
1. Copy contents of "Grand Theft Auto V" into your "Grand Theft Auto V" folder.
2. Edit the settings if desired.  See CONFIG.txt for details.


Grammar
=======
To modify actions and the phrases that trigger them, you will need to modify
XML files in plugins/LSPDFR/GrammarPolice/custom/.  A detailed guide is
available in GRAMMAR.txt.

A video tutorial is available here: https://youtu.be/H1_wwvzK9hc


Language Support
================
GrammarPolice supports custom languages.  Please see LANGUAGES.txt.


Plugin Interaction
==================
Grammar Police contains native functions to support most of its actions.
However, when available, an external plugin might be utilized instead.
