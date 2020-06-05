# vimclass
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

## Same Line Searching

+ **f{char}** -Forward search
+ **F{char}** -Reverse search
+ **t{char}** -Forward till search
+ **T{char}** -Reverse till search
+ **;** -Repeat in the same direction
+ **,** -Repeat in the opposite direction

## Searching

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
