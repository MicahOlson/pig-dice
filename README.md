Describe: Player(name)
Test: "This function constructs a player object with a name, and two score counters initialized to 0"
Code: let player1 = new Player("Player 1");
Expect(player1).toEqual(Player {name: "Player 1", turnScore: 0, overallScore: 0})