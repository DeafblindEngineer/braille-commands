### Humanware Brailliant BI 40X 

Braille Commands for Linux assistive-technology stack:

* Orca screen reader program in graphical-mode
* speakup a kernel-based screen reader for the Linux console in text-mode
* BRLTTY daemon to power the Brailliant BI 40X

### Orientation of Brailliant BI 40X

The Brailliant BI 40X is a 40-cell refreshable braille display, with a perkins-style keyboard, six commands keys (three either side of the display), four thumb keys and a home button.

#### The Top Face

The top section of the braille display is divided into two sections: front and rear. The rear section of the display has a perkins-style braille keyboard that represents the dots of an 8-dot braille cell. The keys under the left hand represent dots 1, 2, 3, and 7, where dot 1 is located under the index finger and dot 7 under the little finger. The keys under the right hand represent dots 4, 5, 6, and 8, where dot 4 is located under the index finger and dot 8 under the little finger.

The front section of the braille display consists of 40-cells with a cursor routing key above each cell. There are two space bars below the display. There are six commands keys, three to the left of the refreshable braille display, and three to the right. On the left, starting from the back, are C1, C2 and C3, which is the one to the front of the display. On the right side, are C4, C5 and C6.

#### Front Edge

On the front edge of the display are five buttons: four rectangular thumb keys and one round button. From left to right, the buttons are as follows:

* Outer Right Thumb Key (Previous Thumb) Key
* Inner Left Thumb (Left Thumb) Key 
*  Home Button
* Inner Right Thumb (Right Thumb) Key
* Outer Right Thumb (Next Thumb) Key

The Braille keyboard, command keys, and thumb keys can be used to perform navigation commands:

#### Default Bindings

**Special Modes**

| Press this key  | To do this |
| ------------- | ------------- |
| C1 + C2 + C5  | enter/leave help display  |
| space + dots 1-2-5  | enter/leave help display  |
| space + dots 1-2-3  | enter/leave command learn mode  |
| C1 + C4 + C5 + C6  | enter/leave command learn mode  |
| C1 + C3 + C4  | enter/leave preferences menu  |
| space + dots 1-2-3-4  | enter/leave preferences menu  |
| C2 + C5  | enter/leave status display  |
| space + dots 2-3-4  | enter/leave status display  |
| C1 + C4 + C5  | set display mode attributes/text  |
| space + dots 1-4-5  | set display mode attributes/text  |
| space + dots1-4-5-8  | set display mode attributes  |
| space + dots 1-4-5-7  | set display mode text  |
| C1 + C2+ C4  | set screen image frozen/unfrozen  |
| space + dots 1-2-4  | set screen image frozen/unfrozen  |
| space + dots 1-2-4-8  | set screen image frozen  |
| space + cots 1-2-4-7  | set screen image unfrozen  |
| C3 + Routing Key  | describe character  |
| C1 + C5  | show current date and time  |

**Cursor Functions**

| Press this key  | To do this |
| ------------- | ------------- |
| left thumb key + right thumb key  | go to screen cursor  |
| C2 + C4 + C6  | go to screen cursor  |
| C1 + C6  | go back after cursor tracking  |
| routing key  | bring screen cursor to character  |
| C1 + C3 + C4 + C6  | bring screen cursor to current line  |
| space + dots 1-2-3-6  | bring screen cursor to current line  |

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
| left thumb key + next thumb key  | go to beginning of bottom line  |
| C5 + C4  | go up to nearest line with different content  |
| right thumb key + previous thumb key  | go up to nearest line with different content  |
| C5 + C6 | go down to nearest line with different content  |
| right thumb key + next thumb key  | go down to nearest line with different content  |
| C1 + C2  | go up to nearest line with different highlighting  |
| C2 + C3  | go down to nearest line with different highlighting  |
| C2 + C4 + C5  | go up to first line of paragraph  |
| C2 + C5 + C6  | go down to first line of next paragraph  |
| C1 + C2 + C4 + C5  | go up to previous command prompt  |
| C2 + C3 + C5 + C6  | go down to next command prompt  |
| C1 + C2 + Routing Key  | go up to nearest line with less indent than character  |
| C2 + C3 + Routing Key  | go down to nearest line with less indent than character  |
| C4 + C5 + Routing Key  | go up to nearest line with different character  |
| C5 + C6 + Routing Key  | go down to nearest line with different character  |

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
| right thumb key + routing key  | linear copy to character  |
| C5 + routing key  | rectangular copy to character  |
| next thumb key + routing key  | rectangular copy to character  |
| routing key + routing key  | copy characters to clipboard  |
| C2 + routing key + routing key  | append characters to clipboard  |
| previous thumb key + next thumb key  | insert clipboard text after screen cursor  |
| C1 + C2 + C3 + C4 | insert clipboard text after screen cursor  |
| space + dots 1-3-4-6  | insert clipboard text after screen cursor |
| C1 + C2 + C4 + C6  | search backward for clipboard text  |
| C2 + C3 + C4 + C6  | search forward for clipboard text  |
| space + dots 1-3-4-6-8  | save clipboard to disk  |
| space + dots 1-3-4-6-7  | restore clipboard from disk  |

**Configuration Functions**

| Press this key  | To do this |
| ------------- | ------------- |
| space + dots 1-2-3-5  | set autorepeat on/off  |
| space + dots 1-2-3-5-8  | set autorepeat on  |
| space + dots 1-2-3-5-7  | set autorepeat off  |
| C2 + C3 + C5  | set text style 6-dot  |
| C2 + C3 + C6  | set text style 8-dot  |
| space + dots 1-2-4-5  | set contracted/computer braille  |
| space + dots 1-2-4-5-8  | set contracted braille  |
| space + dots 1-2-4-5-7  | set computer braille  |
| space + dots 2-3-5  | set six dot computer braille  |
| space + dots 2-3-6  | set eight dot computer braille  |
| space + dots 2-4  | set skipping of lines with identical content on/off  |
| space + dots 2-4-8  | set skipping of lines with identical content on  |
| space + dots 2-4-7  | set skipping of lines with identical content off  |
| space + dots 1-2  | set skipping of blank braille windows on/off  |
| space + dots 1-2-8  | set skipping of blank braille windows on  |
| space + dots 1-2-7  | set skipping of blank braille windows off  |
| space + dots 2-4-5-6  | set sliding braille window on/off  |
| space + dots 2-4-5-6-8  | set sliding braille window on  |
| space + dots 2-4-5-6-7  | set sliding braille window off  |
| space + dots 2-3-4-5  | set track screen cursor on/off  |
| C1  | set track screen cursor on  |
| space + dots 2-3-4-5-8  | set track screen cursor on  |
| C3  | set track screen cursor off  |
| space + dots 2-3-4-5-7  | set track screen cursor off  |
| space + dots 1-4  | set screen cursor visibility on/off  |
| space + dots 1-4-8  | set screen cursor visibility on  |
| space + dots 1-4-7  | set screen cursor visibility off  |
| C2 + C3 + C4 + C5 | set attribute underlining on/off  |
| space + dots 1-3-6  | set attribute underlining on/off  |
| space + dots 1-3-6-8  | set attribute underlining on  |
| space + dots 1-3-6-7  | set attribute underlining off  |

** Menu Operations**

| Press this key  | To do this |
| ------------- | ------------- |
| C2 + C4 + C5 + C6  | save preferences to disk  |
| space + dots 1-2-3-4-8  | save preferences to disk  |
| C1 + C2 + C3 + C5  | restore preferences from disk  |
| space + dots 1-2-3-4-7  | restore preferences from disk  |
| space + dots 1-2-3-4-7-8  | reset preferences to defaults  |

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
| dot 1  | braille keyboard dot 1  |
| dot 2  | braille keyboard dot 2 |
| dot 3  | braille keyboard dot 3  |
| dot 4  | braille keyboard dot 4  |
| dot 5  | braille keyboard dot 5  |
| dot 6  | braille keyboard dot 6  |
| dot 7  | braille keyboard dot 7  |
| dot 8  | braille keyboard dot 8  |
| space  | braille keyboard space  |
| left thumb key  | braille keyboard meta  |
| right thumb key  | braille keyboard control  |
| space + dot 7  | type braille dots [7]  |
| space + dot 8  | type braille dots [8]  |
| dot 7  | backspace key  |
| space + dots 2-6  | escape key  |
| space + dot 3  | cursor-left key  |
| space + dot 6  | cursor-right key  |
| space + dot 1  | cursor-up key  |
| space + dot 4  | cursor-down key  |
| space + dots 2-3  | page-up key  |
| space + dots 5-6  | page-down key  |
| space + dot 2  | home key  |
| space + dot 5  | end key  |
| space + dots 3-5  | insert key   |
| space + dots 2-5-6  | delete key  |
| space + routing key  | function key  |
| right thumb key + space + routing key  | function key  |
| left thumb key + space + routing key  | function key  |
| left thumb key + right thumb Key + space + routing key  | function key  |
| dot 8  | enter key  |
| space + dots 4-5  | tab key  |
| space + dots 7-8  | clear all sticky input modifiers  |
| space + dots 6-8  | cycle the Upper sticky input modifier (next, on, off)  |
| space + dots 4-8  | cycle the Shift sticky input modifier (next, on, off)  |
| space + dots 3-8  | cycle the Control sticky input modifier (next, on, off)  |
| space + dots 2-8  | cycle the Meta (Left Alt) sticky input modifier (next, on, off)  |
| space + dots 5-8  | cycle the AltGr (Right Alt) sticky input modifier (next, on, off)  |
| space + dots 1-8  | cycle the GUI (Windows) sticky input modifier (next, on, off)  |
| C4 + C5 + C6 + routing key  | switch to specific virtual terminal  |
| C3 + C4 + C5 + C6  | switch to the previous virtual terminal  |
| space + dots 1-2-3-6-7  | switch to the previous virtual terminal  |
| C1 + C2 + C3 + C6  | switch to the next virtual terminal  |
| Space + dots 1-2-3-6-8  | switch to the next virtual terminal  |
| Space + dots 1-3-8  | set braille keyboard enabled  |
| space + dots 1-3-7  | set braille keyboard disabled  |
| space + dots 4-6-8  | set braille typing mode dots  |
| space + dots 4-6-7| set braille typing mode text  |

**Special Functions**

| Press this key  | To do this |
| ------------- | ------------- |
| C1 + C3 + routing key  | remember current braille window position  |
| C4 + C6 + routing key  | go to remembered braille window position  |
| C2 + C3 + C4  | restart speech driver  |

### Menu Bindings

**Special Modes**

| Press this key  | To do this |
| ------------- | ------------- |
| dot 8  | enter/leave preferences menu  |
| left thumb key + right thumb key  | enter/leave preferences menu  |

**Horizontal Navigation**

| Press this key  | To do this |
| ------------- | ------------- |
| left thumb key  | go backward one braille window  |
| right thumb key  | go forward one braille window  |

**Menu Operations**

| Press this key  | To do this |
| ------------- | ------------- |
| dot 1  | go up to previous item  |
| previous thumb key  | go up to previous item  |
| dot 4  | go down to next item  |
| next thumb key  | go down to next item  |
| dot 2  | go up to first item  |
| left thumb key + prevoius thumb key  | go up to first item  |
| dot 5  | go down to last item  |
| left thumb key + next thumb key  | go down to last item  |
| dot 3  | select previous choice  |
| right thumb key + previous thumb key  | select previous choice  |
| dot 6  | select next choice  |
| right thumb key + next thumb key  | select next choice  |
| dot 7  | go to previous menu level  |
| left thumb key + right thumb key + next thumb key  | save preferences to disk  |
| left thumb key + right thumb key + previous thumb key  | restore preferences from disk  |
