---
title: Alternative arbitrary code execution setup tutorial for Japanese LeafGreen
---

!!! important
    This method is LeafGreen only as it uses a version-exclusive trade Pokémon that is if you want a method that works for FireRed, check out [the main tutorial](ace-set-up.md).

This tutorial uses the method mentioned for FireRed as its basis but streamlines the steps and removes the manipulation/luck required to obtain the donor Pokémon through using a trade Pokémon, which comes with the advantage of having known and set data.

## Preparation

You will need:
- Mail corruption already activated on your save (you can watch [this video guide](https://www.youtube.com/watch?v=yVhK4pLC9ac) to learn how to activate it)
- Have the ニドくん (Nidoran♂) trade available
- Have at least 36 Retro Mail in the bag
- Have at least 1 Rare Candy in the bag
- Box 3, Slot 1 is empty

!!! note
    If you already have the ニドくん (Nidoran♂) trade Pokémon, make sure it has not been evolved into a Nidoking and its experience must an even value less than or equal to 61536.
    If it is still a Nidoran♂, make sure its level is less than level 41 so that it has been evolved to be a Nidorino by level 41.
    The trade Pokémon has a lonely nature and the OT’s trainer ID should be 63184.

!!! note
    If you have 36 or more Rare Candy, you can skip the Rare Candy cloning step but you could also use the opportunity to top up on your Rare Candy.

## Instructions

1.  Go to the Underground Pass entrance on Route 5, and trade a Nidoran♀ with the girl.

![The trading location](../../assets/images/alt-leafgreen-set-up/TradeLocation.png)
![Nidoran standing in the limelight with dialogue underneath it](../../assets/images/alt-leafgreen-set-up/GettingNidoranM.png)

2.  Give each member of your party (except for first member) Retro Mail, the message can be anything.
3.  Give the first member of the party Rare Candy
4.  Then attempt to give the first member of the party Retro Mail, when you see the mail message screen it should look like this

![A mail message full of ???](../../assets/images/alt-leafgreen-set-up/GlitchedMail.png)

5.  Press `START` and confirm the mail, when you do this you notice that the party member is still holding Rare Candy but the Rare Candy amount in the bag goes up by one while the Retro Mail in the bag goes down by one
6.  Repeat steps 4 and 5 until you have at least 36 Rare Candy in the bag
7.  Once you are done with the Rare Candy cloning, remove the Rare Candy from the first member of the party
8.  Give ニドくん Rare Candy until he is at level 41, make sure to evolve him to a Nidorino!
9.  Once ニドくん is at level 41, go to the daycare in Route 5 (or the one in the Sevii Islands if your save is extra completed)
    - At this point, ニドくん’s experience should be 61450.
10. Deposit ニドくん in the daycare and walk 86 steps, ending your last step in front of the daycare man
11. Withdraw ニドくん from the daycare, his experience should be 61536

![The Pokémon stats screen with a Nidorino, his experience is at 61536](../../assets/images/alt-leafgreen-set-up/FinalExperience.png)

12. Place ニドくん into Box 3, Slot 1, and withdraw another box Pokémon to be the sixth party member.

![The Pokémon box menu with Nidorino in Box 3, Slot 1](../../assets/images/alt-leafgreen-set-up/NidoranLocation.png)

13. Give Retro Mail to the sixth party member, and write the following message to the mail
    - ポケモンゲット as the 3rd word
    - うう as the 5th word
    - All other words left untouched

![A glitched mail with ポケモンゲット as the 3rd word, うう as the 5th word and the rest are ???](../../assets/images/alt-leafgreen-set-up/MailCorruptionMessage.png)

14. Confirm the mail, then check the Box 3 again, a glitch Pokémon should take the place of ニドくん.

![A question mark in Box 3, Slot 1](../../assets/images/alt-leafgreen-set-up/InitialACEMon.png)

15. Move four party members into the boxes with the last party member to move still held by the orange hand (can be activated by pressing SELECT)
16. Rename Boxes 1-5 to the following

    ```
    Box  1: リ び ‥ o く _ ゼ n	[リび‥oく ゼn]
    Box  2: _ ‥ t ま _ 1 t ほ	[ ‥tま 1tほ]
    Box  3: ぁ m _ _ あ い	[ぁm  あい]
    Box  4: ア B ぢ い い N	[アBぢいいN]
    Box  5: O	[O]
    ```

17. With a Pokémon still in the orange hand, go back to Box 3, and swap the glitch Pokémon with the Pokémon then back again

![The process of swapping two Pokémon](../../assets/images/alt-leafgreen-set-up/swapping.gif)

18. Exit out of Move Pokémon mode then enter deposit mode, in the third party slot there should be another glitch Pokémon in party slot 3
    - You should probably place it somewhere in the boxes

![A glitch Pokémon in party slot 3](../../assets/images/alt-leafgreen-set-up/FinalResult.png)

That is it, you have setup ACE in Japanese LeafGreen!
Further information on the ACE environment in Japanese FireRed/LeafGreen can 

You probably don’t want to keep the initial glitch Pokémon (created from mail corruption) in the boxes, to remove it please do the following:

1. Place the glitch Pokémon in the party (using the orange hand)
2. Exit the PC, then go to the party menu
3. Move the glitch Pokémon to the first party slot
4. Go back to the PC and enter deposit mode
5. Release the Pokémon by selecting the Pokémon then select release and confirm
