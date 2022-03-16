# Get_next_line
My work on the 42 get_next_line project (here without the bonus part).

The aim of this project is to make you code a function that returns a line,
read from a file descriptor.

This project will not only allow you to add a very convenient function to your collection,
but it will also allow you to learn a highly interesting new concept in C programming:
static variables.

### Function Prototype

```c
char	*get_next_line(int fd);
```

### Return value

| Value | Description         |
 |-----------|----------------------|
|  Read line| correct behavior |
|  NULL| nothing else to read or an error has occured |

### Functions Used

**External Functions**

| Function | Description         |
 |-----------|----------------------|
|  read() | A line has been read |
|  malloc() | EOF has been reached |
|  free() | An error happened |

# Notes

I wrote this code to be as easy to understand as possible because it was coded for a video tutorial, which explains why I left some comments inside the main function.

# Bonus

I made two videos about this project!

## understanding get_next_line
<p align="center">
<br>
<a href="https://youtu.be/-Mt2FdJjVno" target="_blank">
<img src="img/yt-tbn.png" alt="coder get_next_line" width="300px"><br>
(understanding get_next_line)
</a><br><i>english subtitles</i><br>
</p>

## coding get_next_line
<p align="center">
<br>
<a href="https://youtu.be/xgDSXNOHTIA" target="_blank">
<img src="img/yt-tbn2.png" alt="coder get_next_line" width="300px"><br>
(coding get_next_line)
</a><br><i>subtitles to come</i>
</p>