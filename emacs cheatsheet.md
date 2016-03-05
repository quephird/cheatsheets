## Editor commands

| Key strokes | Command |  
|---------|------------|  
| C-x C-c | Exit emacs |  
| C-g | Quits last action |
| C-_ | Undoes last action |
| C-h | Activates help |  
| M-x <<command>> | Executes command |

## File commands

| Key strokes | Command |  
|---------|------------|  
| C-x C-f | Activates file find window |  
| C-x C-s | Save current buffer |  
| C-x C-w | "Save as..." current buffer |  

## Pane commands

| Key strokes | Command |  
|---------|------------|  
| C-x o | Switch focus to next pane |  
| C-x 3 | Open new horizontal pane |  
| C-x 2 | Open new vertical pane |  
| C-x 1 | Close all panes except active one |  
| C-x 0 | Close active pane |  

## Buffer commands

| Key strokes | Command |  
|---------|------------|  
| C-x b | Activates switch buffer window |  
| C-x k | Kills current buffer |  
| C-x right | Cycles through buffers to the right |  
| C-x left | Cycles through buffers to the left |  

## Text selection commands

| Key strokes | Command |  
|---------|------------|  
| C-space | Marks beginning of text selection |
| left, right, up, down | moves the cursor, selects text between current position and mark set by C-space |
| M-@ | Selects text between current position in word to its end |



## Text manipulation commands

| Key strokes | Command |  
|---------|------------|  
| C-w | Deletes selected text and puts on clipboard |
| C-y | Yanks selected text into clipboard |
| C-k | Deletes text from current position to the end of the current line and puts on clipboard |
| M-delete | Deletes from current position to the beginning of the current word |
| M-d | Deletes from current position to the end of the current word |
| M-t | Transposes current word with the one following it |  


## Cursor commands

| Key strokes | Command |  
|---------|------------|  
| up, down, left, right | Self-explanatory |
| M-b | Move back one word |
| M-f | Move forward one word |
| C-a | Move to beginning of line |
| C-e | Move to end of line |
| M-v | Page up |
| C-v | Page down |
| M-< | Move to top of document |
| M-> | Move to bottom of document |

## Search commands

| Key strokes | Command |  
|---------|------------|  
| C-s <<string>> | "Regular" search for <<string>>, with the following subcommands
* repeatedly hitting C-s continues to search for <<string>>, return stops the search |
| M-s <<string>> | |  



M-x xterm-mouse-mode activate mouse
