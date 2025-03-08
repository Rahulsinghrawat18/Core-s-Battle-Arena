# Core's Battle Arena
Core's Battle Arena is a strategy-based board game where two players, each controlling a team of five unique adventurers, compete to conquer the enemy’s base. This game combines tactical decision-making and adventurous gameplay.

Check out the live deployment here: [Core Battle Arena!](https://core-battle-arena.vercel.app/) 🚀

## Demo-Video
https://www.youtube.com/

## Key Features
* ####  2-Player Gameplay
* ####  Unique Adventurer Roles and Abilities of Pieces
* ####  Core Blockchain integration
     ##### 1.Character Skins Purchase: Users can buy character skins using Core.
     ##### 2.Exclusive Collab Skins: Special Core collaboration skins are available for purchase.
     ##### 3.Reward System: Players earn WIN tokens upon victory.

## Objective
The goal is to strategically maneuver your pieces and place one on your opponent's base to win the game.

## Game Rule
1. Each player starts with five pieces, each having unique abilities.
2. Players take turns moving one piece at a time on the board.
3. A piece must reach the opponent's base to win the game.
4. All pieces are unique, having their own attack power, health, move range, and 
   special abilities.
   
![Screenshot (16)](https://github.com/user-attachments/assets/09692366-48d9-4107-ad5d-d81a08c1b381)

![Screenshot (17)](https://github.com/user-attachments/assets/9677bec9-2da2-418e-89fa-384fb98236a0)

## Technologies Used
* ####  Frontend: Vite ( React ), Tailwind CSS
* ####  Backend: Node.js, Express.js, Socket.io
* ####  Blockchain: Foundry ( Contract deployed on Core Testnet )
* ####  Smart contract Connection: Ethers.js

## The Game

![Screenshot (1)](https://github.com/user-attachments/assets/71997b4f-1d95-47f2-afe6-e62fda2f7cea)

![Screenshot (2)](https://github.com/user-attachments/assets/882575e4-fc0c-48d4-a82a-dc7efa68427a)

## Important Points
1. You do not need to connect a wallet to play but connecting wallet allows you to select the skins. If both players have their wallet connected, they can agree to register the winner.
2. Zoom in/out if unable to see all pieces and map according to your comfort.
3. Read the How-to-play on Home page to know about the instructions.
4. For the online site, it may happen that the server does not respond due to being inactive after a period of inactivity as it was hosted on a free tier.

## Creating and Joining Room
A player can create room and get the room code which can then be shared with the other player, and both can jump into a game.

![Screenshot (7)](https://github.com/user-attachments/assets/ec979c6b-c96e-4b95-a908-644ffd097799)

## Connect Wallet and Skins
A player can choose to connect their wallet. The code is set up to connect to shape sepolia since the contract was deployed on that. Although it is also set to ask permission to add the testnet if not present in user's metamask, iff facing issue, make sure to add and switch to shape sepolia testnet before connecting wallet. Else if connected wallet but not on shape sepolia, you will be able to see current skins and the ones for collab but will be unable to buy the skins through smart contract.

### Current Skins
Shows the current equipped skins of the player. Go to lobby, reload page, and come back if you want to change to default skins after changing the skins.

![Screenshot (3)](https://github.com/user-attachments/assets/2944dd53-d08a-4045-8963-7fdc0ca76eb7)

### Available Skins 
Shows the current available skins you can buy and apply.

![Screenshot (4)](https://github.com/user-attachments/assets/a2cef72b-01ec-4e77-bb73-f00475e670b9)

### Core Collab Skins
Shows the skins that are provided through some web3 collaboration. Right now there is a volcano map which you can buy and upon selecting that you can change your lobby and arena background.

![Screenshot (5)](https://github.com/user-attachments/assets/266f6918-6842-43b9-b018-3ea054ed05c3)

#### Background with Collab Skins

![Screenshot (8)](https://github.com/user-attachments/assets/72cae4f9-3dbd-4b6a-8eaa-737f018be2b6)

#### Background without Collab Skins

![Screenshot (9)](https://github.com/user-attachments/assets/26470c7f-3e2f-47ca-b840-b5831245e5c1)

## Registering the Winner
If both players have their wallet connected, then after one player wins, players can choose to agree and register the winning of the winner on blockchain. The option is provided on the same screen which shows who won after the game ends.

![Screenshot (10)](https://github.com/user-attachments/assets/b73a74f2-d17e-4043-8d3d-b67af86a83ad)

![Screenshot (11)](https://github.com/user-attachments/assets/94ba0c80-137f-4559-8cb1-75a3fd94349b)

![Screenshot (13)](https://github.com/user-attachments/assets/ba2eb1f0-5093-4f5b-9833-7a293b912c03)

## WIN Tokens as Reward
The person who wins gets 100 WIN tokens as reward which he can see in his wallet upon successfully importing the WIN token address.

![Screenshot (15)](https://github.com/user-attachments/assets/4d1bfd58-c0c1-48b5-807d-6cb20f126f9f)

# The Contract

Core's Battle Arena Contract Address - 0x1AA7a043487bf78C64B28b810dE8c63246B04edc

WIN Token Address - 0x6D9616C0040ee13284794960A2957B941007A728

Block Explorer Link - https://scan.test2.btcs.network/address/0x1AA7a043487bf78C64B28b810dE8c63246B04edc









