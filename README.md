# Custom-Tkinter-ScrolledListbox
Custom Tkinter ScrolledListbox with List/Tuples of variables, Un/Selected Item delete with a few configure options

Based off the ScrolledText, ScrolledListbox is used to create a scrollable listbox.

Configure options:

listvariable: List or Tuple of values.

bg: Change color of the listbox background

fg: Change color of the listbox text color

exportselection:  if multiple listboxes are used 1 clears listbox1 selected item when listbox2 is click:  0 will allow the listbox to act  independently.

selectbackground:  Change color of listbox select/highlight background


Actions:

delete_selected: The ability to delete all items that selected.

delete_unselected: The ability to delete all items that are not selected.

delete: The ability to delete a single item.

insert: The ability to insert a single item.

curselection: The ability to return a list of items that are selected.