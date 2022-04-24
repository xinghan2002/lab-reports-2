# Debugging Lab and three modification on the code

1. **Infinite Loop**: When we tried [this file](https://github.com/kcyy127/markdown-parser/blob/main/test-file.md) on the programm, there was an infinite loop being generated. This is due to the fact that after the last close parenthesis' index is return, the value of currentIndex would stay -1 (unfound), and thus this always satisfies the prerequisite for entering the for loop.
