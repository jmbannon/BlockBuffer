# BlockBuffer
Simple API to read/write Minecraft blocks to memory and disk.

## Description
Stores blocks and light blocks separately. On restore command it will teleport the user to the location of the light blocks, 
then spawn the block back in its former place. This is because when you spawn a light block in a chunk that's not loaded, 
light will not emit properly.

## TODO
- Optimize file output
- Load chunks automatically when restoring light blocks
- Configurable timer to automate block restoration

## Our Message
We are strong advocates for fair, fun, and balanced Minecraft gameplay. We do not condone the current tactics employed by commercial servers for the sole purpose of profit revenue such as selling over-powered items, pay to be unbanned, ridiculously high pricing of cosmetic items, etc. The list goes on.

We strive to build a suite of plugins that can be modified by anyone with hopes that it contributes to small, community-ran servers willing to open-source. These plugins will be used by the Project Zombie server which will eventually be available to everyone to deploy their own custom instance.

## Interested in Contributing?
Please fork our repository and send a pull request with a meaningful feature/patch/bug-fix. We are always looking for other developers and are willing to help junior developers with the development process.
