# discord.eth

Discord.eth allows you to distribute the logic of a Discord bot across the Ethereum network. This is completely different to how traditional bots work, primarily by the fact that bots aren't tied to accounts; _anyone_ can create a bot account that runs on the distributed logic.

For example, you could write a bot using a classic API library — an interface. With this, you could proxy events to the Ethereum contract on which the event/command will be processed. The result will then be returned to the interface, where you can send a message back to the user.

## Advantages

- It is literally impossible for a bot running on Ethereum to go down.
- Payments are perfectly integrated.
- There isn't a central authority; even the original author can't change the code.
- All you need to manage

## Disadvantages

- It's relatively pricey if you want to actually use the live network.
- There are many things that aren't possible without extra effort.