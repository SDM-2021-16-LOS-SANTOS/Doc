1. Current situation
-----------

    We plan to write a coin game. It is an easy and interesting game. It belongs to take-away game. 
    This game can exercise your thinking and make you be thoughtful.
    

2. Dream system
 -------------
  
    The game is a  two-player coin flipping game with a simple and clear game interface, and the game also provides brief instructions on how to perform operations.
   Players can customize the number of coins to win in the game (for example, it is stipulated that whoever turns over 10 coins will win), and the player can also
   Exit, pause, and view rule operations.
    
3. Current processes
 ---------------
   * 1.Planning the game logic structure
   * 2.Write a game prototype
   * 3.Test the prototype
   * 4.Add the handling and feedback of each error in the game
   * 5.Optimize game algorithm
   * 6.Add UI to the game
   * 7.Test the full game



4. Required processes
--------------
      * 1.Need to have 2 players to play this game 
      * 2.each player throw 1-3 coins per round.
      * 3.Need to record the number of coins left and the number of rounds.
      * 4.The player who threw in the 10th coins firstly win.


5. Law, rules, standards
----------------
     * 1.Should use C++  to create games and game interfaces.
     * 2. UI should be created based on C++ console.


6. Requirement list
----------------
   * 1.Need a simple and clear game interface
   * 2.Players can choose to exit, pause, and view the rules of the game at any time during the game
   * 3.When encountering an input error, be able to remind the player and be able to continue the game
   

7. Dictionary
--------------

8. Use case
---------------- 
   * 1.You choose to be player A or player B.
   * 2.Start the game, first show how many coins are still face up.
   * 3.Choose 1-3 coins and then choose to flip the numbered coins.
   * 4.Once you forget the rules, or don't want to continue playing, you can choose to view the rules and exit the game according to the prompts.
   * 5.If your input does not meet the specifications, the game will prompt, and then enter the number that meets the specifications and the game will continue.
   * 6.If you stipulate that the person who flips all 10 coins wins, and you flip all 10 coins, you will win
10. ERD
 -------------
![2806d7f061572d233e073c3cdfbc57a](https://user-images.githubusercontent.com/78998273/134819649-22638f78-4cc4-406c-a9f4-c4676a5c0fa6.png)
