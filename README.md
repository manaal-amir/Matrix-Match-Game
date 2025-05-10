# Matrix-Match-Game  

A single-player game in C++ that involves manipulating a two-dimensional matrix, implemented as a vector of vector of char. The initial state of the matrix is loaded from a text file.  

During the game, the player swaps two adjacent elements in the matrix based on user input. If this results in a group of three or more consecutive elements of the same shape, those elements are automatically removed. After each removal, the remaining elements fall down according to gravity. This process of removal and gravity continues until no more matching groups remain.  

Players can keep making swaps as long as they wish to continue. The implementation also includes input validation during both the matrix loading phase and gameplay.
