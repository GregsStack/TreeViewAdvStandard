treeviewadv
===========

Forked from http://sourceforge.net/projects/treeviewadv/

# Local Changes

* Added an IsEnabled property to the Node class
* Added an IsEnabled property to the TreeNodeAdv class

When an individual node is disabled by setting IsEnabled to false, the text is shown as grayed out and the checkbox, if any, is displayed as disabled and its state cannot be changed. This lets you construct a tree with both nodes that you can tick/untick and nodes that are preset and cannot be changed.
