### Humanware Brailliant B 80

Braille Commands for Linux assistive-technology stack:

* Orca screen reader program in graphical-mode
* Speakup a kernel-based screen reader for the Linux console in text-mode
* BRLTTY daemon to power the Brailliant BI 40X

### Orientation of Brailliant B 80

The Brailliant B 80 is an 80-cell refreshable braille display, with six commands keys (three either side of the display), and eight thumb keys.

#### The Top Face

The top face of the braille display consists of 80-cells with a cursor routing key above each cell. There are six commands keys, three to the left of the refreshable braille display, and three to the right. On the left, starting from the back, are C1, C2 and C3, which is the one to the front of the display. On the right side, are C4, C5 and C6.

#### Front Edge

On the front edge of the display are two sets of four rectangular thumb keys. From left to right, the buttons are as follows:

**Left Set of Thumb Keys:**

* Outer Right Thumb Key (Previous Thumb) Key
* Inner Left Thumb (Left Thumb) Key 
* Inner Right Thumb (Right Thumb) Key
* Outer Right Thumb (Next Thumb) Key

**Right Set of Thumb Keys:**

* Outer Right Thumb Key (Previous Thumb) Key
* Inner Left Thumb (Left Thumb) Key 
* Inner Right Thumb (Right Thumb) Key
* Outer Right Thumb (Next Thumb) Key

The thumb keys and command keys can be used to perform navigation commands:

#### Default Bindings

**Special Modes**

| Press this key  | To do this |
| ------------- | ------------- |
| C1 + C2 + C5  | enter/leave help display  |
| C1 + C4 + C5 + D6  | enter/leave command learn mode  |
| C1 + C3 + C4  | enter/leave preferences menu  |
| C2 + C5  | enter/leave status display  |
| C1 + C4 + C5  | set display mode attributes/text  |
| C1 + C2 + C4  | set screen image frozen/unfrozen  |
| C3 + routing Key  | describe character  |
| C1 + C5  | show current date and time  |

**Cursor Functions**

| Press this key  | To do this |
| ------------- | ------------- |
| C2 + C4 + C6  | go to screen cursor  |
| left thumb key + right thumb key  | go to screen cursor  |
| C1 + C6  | go back after cursor tracking  |
| routing key  | bring screen cursor to character  |
| C1 + C3 + C4 + C6  | bring screen cursor to current line  |

**Vertical Navigation**

| Press this key  | To do this |
| ------------- | ------------- |
| C4  | go up one line  |
| previous thumb key  | go up one line  |
| C6  | go down one line  |
| next thumb key  | go down one line  |
| C1 + C4  | go to top line  |
| C3 + C6  | go to bottom line  |
| C2 + C4  | go to beginning of top line  |
| left thumb key + previous thumb key  | go to beginning of top line  |
| C2 + C6  | go to beginning of bottom line  |
| left thumb key + netx thumb key  | go to beginning of bottom line  |
| C4 + C5  | go up to nearest line with different content  |
| right thumb key + previous thumb key  | go up to nearest line with different content  |
| C5 + C6  | go down to nearest line with different content  |
| right thumb key + next thumb key  | go down to nearest line with different content  |
| C1 + C2  | go up to nearest line with different highlighting  |
| C2 + C3  | go down to nearest line with different highlighting  |
| C2 + C4 + C5  | go up to first line of paragraph  |
| C2 + C5 + C6  | go down to first line of next paragraph  |
| C1 + C2 + C4 + C5  | go up to previous command prompt  |
| C2 + C3 + C5 + C6  | go down to next command prompt  |
| C1 + C2 + routing key  | go up to nearest line with less indent than character  |
| C2 + C3 + routing key  | go down to nearest line with less indent than character  |
| C4 + C5 + routing key  | go up to nearest line with different character  |
| C5 + C6 + routing key  | go down to nearest line with different character  |

**Horizontal Navigation**

| Press this key  | To do this |
| ------------- | ------------- |
| C2  | go backward one braille window  |
| left thumb key  | go backward one braille window  |
| C5  | go forward one braille window  |
| right thumb key  | go forward one braille window  |
| C1 + C2 + C3  | go to beginning of line  |
| C4 + C5 + C6  | go to end of line  |
| C1 + C3  | go left one character  |
| C4 + C6  | go right one character  |
| C6 + routing key  | place left end of braille window at character  |

**Clipboard Functions**

| Press this key  | To do this |
| ------------- | ------------- |
| C1 + routing key  | start new clipboard at character  |
| previous thumb key + routing key  | start new clipboard at character  |
| C2 + routing key  | append to clipboard from character  |
| left thumb key + routing key  | append to clipboard from character  |
| C4 + routing key  | linear copy to character  |
| right thumb key + routing key| linear copy to character  |
| C5 + routing key  | rectangular copy to character  |
| next thumb key + routing key  | rectangular copy to character  |
| routing key + routing key  | copy characters to clipboard  |
| C2 + routing key + routing key  | append characters to clipboard  |
| previous thumb key + next thumb key  | insert clipboard text after screen cursor  |
| C1 + C2 + C3 + C4  | insert clipboard text after screen cursor  |
| C1 + C2 + C4 + C6  | search backward for clipboard text  |
| C2 + C3 + C4 + C6  | search forward for clipboard text  |

**Configuration Functions**

| Press this key  | To do this |
| ------------- | ------------- |
| C2 + C3 + C5  | set text style 6-dot  |
| C2 + C3 + C6  | set text style 8-dot  |
| C1  | set track screen cursor on  |
| C3  | set track screen cursor off  |
| C2 + C3 + C4 + C5  | set attribute underlining on/off  |

**Menu Operations**

| Press this key  | To do this |
| ------------- | ------------- |
| C2 + C4 + C5 + C6  | save preferences to disk  |
| C1 + C2 + C3 + C5  | restore preferences from disk  |

**Speech Functions**

| Press this key  | To do this |
| ------------- | ------------- |
| C3 + C4  | stop speaking  |
| C3 + C5  | speak current line  |
| C3 + C4 + C5  | speak from top of screen through current line  |
| C3 + C5 + C6  | speak from current line through bottom of screen  |
| C1 + C3 + C5  | go to current speaking position  |
| C3 + C4 + C6  | set autospeak on/off  |

**Keyboard Input**

| Press this key  | To do this |
| ------------- | ------------- |
| C4 + C5 + C6 + routing key  | switch to specific virtual terminal  |
| C3 + C4 + C5 + C6  | switch to the previous virtual terminal  |
| C1 + C2 + C3 + C6  | switch to the next virtual terminal  |

**Special Functions**

| Press this key  | To do this |
| ------------- | ------------- |
| C1 + C3 + routing key  | remember current braille window position  |
| C4 + C6 + routing key  | go to remembered braille window position  |
| C2 + C3 + C4  | restart speech driver  |

#### Menu Bindings

**Special Modes**

| Press this key  | To do this |
| ------------- | ------------- |
| left thumb key + right thumb key  | enter/leave preferences menu  |

**Horizontal Navigation**

| Press this key  | To do this |
| ------------- | ------------- |
|left thumb key  | go backward one braille window  |
| right thumb key  | go forward one braille window  |

**Menu Operations**

| Press this key  | To do this |
| ------------- | ------------- |
| previous thumb key  | go up to previous item  |
| next thumb key  | go down to next item  |
| left thumb key + previous thumb key  | go up to first item  |
| left thumb key + next thumb key  | go down to last item   |
| right thumb key + previous thumb key  | select previous choice  |
| right thumb key + next thumb key  | select next choice  |
| left thumb key + right thumb key + next thumb key  | save preferences to disk  |
| left thumb key + right thumb key + previous thumb key  | restore preferences from disk  |
