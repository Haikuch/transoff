# transoff
very simple offline translator for linux

Sloppy coded but very useful simple offline translator for Ubuntu.
Based on dict, so its just a GUI for dict to be fair.

You need installed: dict, zenity, xclip 

`$ sudo apt-get install dict zenity xclip`

Put all files in your /bin folder (for example ~/bin). Then point shortcuts to trans-entry and trans-marked.

**To use trans-entry**: just press your shortcut and you will get a prompt that asks you to insert the word for translation. Press enter and you get a zenity notification with the possible translations. Very stupid and simple.

**To use trans.marked**: thats much nicer. Just mark a word anywhere in any application you use. Then press the shortcut for trans-marked and you will get the zenity notification with the translation. How does it work? It just gets the marked word from xclip (your clipboard) and translates it. Very simple, but very effective because it works in any application you might use.
