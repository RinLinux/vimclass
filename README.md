# Vim class
Record the summary of vim usage


## Navigation

+ **h** -Move **Right**
+ **j** -Move **Down**
+ **k** -Move **Up**
+ **l** -Move **Left**

**word**
+ **w** -Move **Forward** word
+ **W** -Move **Forward** word ignore puntuation
+ **b** -Move **Backward** word
+ **B** -Move **Backward** word ignore puntuation
+ **e** -Move to the **end** of the current word
+ **ea** -Move to the **end** of the current word and **add**

**line**
+ **0** -Move to **Beginning** of a line
+ **^** -Move to **Beginning** of a line
+ **$** -Move to **End** of a line

+ **[count]+gg** -Move to [count] line
+ **:[count]** -Move to [count] line
+ **gg** -Move to the **First** line
+ **G** -Move to the **Last** line
+ **:$** -Move to the **Last** line
+ **Ctrl-g** -Information of current line
+ **Ctrl-f** -Page Down
+ **Ctrl-b** -Page Up


## Deleting

**operatin{motion}**
+ **dw** -Delete a forward word
+ **db** -Delete a backward word
+ **[count]dd** -Delete [count] lines
+ **d[count]w** -Delete [count] words


## Getting Help
+ **:h {subjetct}** -Get help on a given subject
+ **Ctrl-w Ctrl-w** -switch between the help window and the editing window


## Cut Copy and Paste
+ **[count]dd** -Cut [count] lines
+ **[count]yy** -Copy [count] lines
+ **x** -Cut a letter 
+ **[count]p** -Paste [count] times


## Registers
+ **""** -Holds the text from **d**, **c**, **x**, and **y** operations
+ **"0** -Holds the last text from yanked(**y**)
+ **"1** -Holds the last text from deleted(**d**) or changed(**c**)
+ **Numbered** rigesters shift each **d** and **c**
+ **"[register]p** -Paste [rigester] content
+ **"[register][operation]** -Put the text to the [rigester], e.g **"ayy**, put the current line to the **a** register
+ **"[REGISTER][operation]** -Append the text to the [REGISTER]
+ **[count][register]** -Repeating the register [count] times
+ **:reg** -Show [registers]


## Undo
+ **u** -Undo
+ **Ctrl-r** -Redo


## Searching

### Same Line Searching

+ **f{char}** -Forward search
+ **F{char}** -Reverse search
+ **t{char}** -Forward till search
+ **T{char}** -Reverse till search
+ **;** -Repeat in the same direction
+ **,** -Repeat in the opposite direction

### Searching

+ **/{pattern}** -Forward search
+ **?{pattern}** -Reverse search
+ **n** -Repeat search in the same direction
+ **N** -Repeat search in the opposite direction
+ ***** -Forward search for a word
+ **#** -Reverse search for a word

## Substitude Command

**Format**
+ **:[range]s/{pattern}/{string}/[flags]**

**Global Substitution**
+ **:%s/{pattern}/{string}/g**
