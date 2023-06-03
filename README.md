# TikTakToe
The MinMax algorithm with alpha-beta pruning has been previously described and is commonly used for generating optimal moves in strategic games. Additionally, as part of this project, the SFML library was employed to create a graphical user interface for the game. SFML (Simple and Fast Multimedia Library) is a programming library that enables easy development of multimedia applications, such as games, using the C++ language.

To optimize the performance of the MinMax algorithm, the technique of alpha-beta pruning was applied. It involves eliminating unnecessary searches in the state tree by introducing two additional parameters: alpha and beta. The alpha parameter represents the best value that the maximizing player can achieve, while the beta parameter represents the worst value that the minimizing player can achieve. During the tree traversal, if the value for a particular node is worse than alpha or better than beta, the search can be terminated as it will not affect the final outcome.

![image](https://github.com/MateuszAmbrozy/TikTakToe/assets/127397482/da50a9bd-e739-496e-9eb2-0ac8aadf80a9)
![image](https://github.com/MateuszAmbrozy/TikTakToe/assets/127397482/53d9209d-8090-406d-ad55-065d2a8f50ec)
