**Vampires on Avalanche doing cage fights**

Reflections, Royalties and Marketplace fee redistribution is canceled - only useful for superearly minters

Reflection rewards can be approximated by: 
reward = rr * c * (ln N - ln x)
rr: Reflection rate
c: cost to mint
N: total number of available NFTs
x: the number of the NFT we are calculating the rewards for
With 7000 NFTs and a reflection rate of 0.2, we can calculate when the last NFT is minted that can cover it's own cost with reflections:
x_breakeven = exp(ln 7000 - 1/rr) = 47 <-- super early minters benefit

5 Generations (rarities):
Gen0
Gen1
Gen2
Gen3
Gen4

Tokenomics:
Clan Vampires can:
 - HUNT Human (NFT)
 - BITE Human to turn them into Slave Vampire being one generation below them
 - Both will put the Clan Vampire into stasis, it needs $BLUT token to unlock
 - The amount of $BLUT needed is dependent on the generation

Human:
 - Can be staked for $BLUT
 - Is created by the HUNT
 - Is destroyed by the BITE

Slave Vampire:
 - Can store $BLUT
 - Can fight other Slave Vampires in a CAGE FIGHT
 - Winner takes all $BLUT
 - Winner has 1% chance to join the clan --> ascend from Slave Vampire to Clan vampire
 - Loser has a 1% change to be destroyed

Cage fight is inherited concept from ChainedVampires:
 - By comparing the generation of the two participants each participants receives a part of the number space between 1 and 100
 - Draw a random number from the 1 to 100 space, the slave vampire having this number is its part is the winner