# Simon Game with MemeCoin Integration

A fun and interactive Simon game built on Flow, with players staking MemeCoins to advance levels and withdraw winnings. Players can interact with the contract via their Flow address, and their progress is tracked on-chain.

## Features

- Players stake FunFi Coins to start and advance in the game.
- The game supports multiple players simultaneously.
- Players can withdraw their winnings after completing levels.
- The smart contract ensures secure transactions and game logic.

## Contract Details

- **Contract Address**: `0x7302f8d26173165D475A20e7185aBd99459568e9`
- **Network**: Flow Testnet

## Deployment

- **Contract Address**: [View on Explorer](http://evm-testnet.flowscan.io/address/0x7302f8d26173165D475A20e7185aBd99459568e9)
- **Coin Used**: FLOW

## How It Works

- **Starting the Game**: Players start by staking MemeCoins. Each correct level advance doubles the stake.
- **Advancing Levels**: Players can advance to the next level by matching the sequence of colors. If they choose to stake more, their stakes are doubled.
- **Withdrawing**: Players can withdraw their winnings after completing any level by choosing to end the game. The MemeCoins are sent directly to their wallet.

## Smart Contract Functions

- `startGame()`: Starts a new game and initializes the player's state.
- `advanceLevel(bool stakeMore)`: Advances the level by either staking more MemeCoins or withdrawing the player's winnings.
- `withdrawUnstaked()`: Allows players to withdraw their initial stake if they choose to end the game early.

## How to Play

1. **Start the Game**: Click on the "Start Game" button to begin. A random color sequence will be shown to you.
2. **Advance Levels**: After successfully matching the sequence, click on "Advance Level" to move to the next level. Your stake doubles with each level.
3. **Withdraw**: If you want to end the game, click on "Withdraw" to receive your winnings.

## Interacting with the Contract

This project interacts with the Flow blockchain through MetaMask or another Flow-compatible wallet. Ensure your wallet is connected to the Flow Testnet before playing.

## Screenshots
<img width="1440" alt="Screenshot 2024-12-25 at 12 40 02 AM" src="https://github.com/user-attachments/assets/aa163ba8-c5d4-40fe-94e9-328dfecb718d" />

<img width="1280" height="713" alt="Screenshot 2025-08-30 at 2 32 30 AM" src="https://github.com/user-attachments/assets/06e8417e-893a-4084-b55c-14d4468d8de6" />

<img width="1209" height="621" alt="Screenshot 2025-08-30 at 2 33 12 AM" src="https://github.com/user-attachments/assets/bc887009-5c88-4f57-b389-92eb7fbc92b4" />




