# frhd-tools
Tools that don't really fit any of my existing repositories, for the sake of hosting on gh pages

---

## tpsim
A tool to help automatically test input combinations for larger (stacking) teleport structures. The main textarea is used for the teleport structure, which consists of lines of space-separated teleport names (note that having more than 2 of a particular teleport name will have undesireable effects, but is not currently automatically detected), while the add button creates a new instance, which consists of a list of all of the remaining teleporters in the same format as the input after executing the provided sequence, as well as how the provided sequence executes, along with an input for entering a sequence as space-separated teleporter names. Everything updates automatically as soon as you click off of an interactable element, and you should be able to copy+paste the teleport sequence from the textarea into the tpgen program (which isn't yet finished or released unfortunately).
