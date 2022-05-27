# MARKDOWN CHEATSHEET

### **you can read markdown from terminal btw with some tools like <tt>glow</tt>

# HEADERS
md:
```
# header1
## header2
### header3
#### header4
##### header5
```
output:

> # header1
> ## header2
> ### header3
> #### header4
> ##### header5

# TODO & CHECKBOX
md:
```
[ ] todo 
[x] done 
```
output:

> - [ ] todo 
> - [x] done

# MOVING TO HEADERS
md:
```
[TEXT](#HEADERS)
[Goto first header](#HEADERS)
``` 
output:
> [Goto first header](#HEADERS)

# LINKS
md:
```
[TEXT](link)
```
output:
> [GOOGLE](https://google.com)

# TABLE
md:
```
| firstBlock | 2ndBlk |
| ---------- | ------ |
| 3rdBlk     | 4thBlk |
```
output:
> | firstBlock | 2ndBlk |
> | ---------- | ------ |
> | 3rdBlk     | 4thBlk |

# IMAGE 
md:
```
![TEXT](PATH_TO_IMAGE)
```
output:
> ![markDownLogo](./markdown.png)

# QUOTE
md:
```
Amirmohammad:
> hello
```
output:
> Amirmohammad:
> > hello

# SOME OTHERS
### IMAGE WITH LINK 
md: 
```
[![TEXT](PATH_TO_IMAGE)](LINK)
```
output:
> [![MDLOGO](./markdown.png)](https://github.com/am-shm/toolBox/tree/main/MarkDown_Cheatsheet)

### BLOCK
md:
```
hello
	this is a block with some text
```
output:
> hello
>	this is a block with some text
