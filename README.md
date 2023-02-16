# My First Unreal Application

I developed a 3D platform game using components from the Side Scroller Template and the Starter Content Assets Kit.

Taking advantage of the existing scenario, I created floating blocks that rotate around their own axis and serve as collectible items. The gray block is associated with a variable that counts the number of points. Collecting one of these blocks, the value of points goes up by 1. When collecting all 5 blocks, the game is won. The brown block deals damage equal to 50% of the character's total life value. There are 3 in the scenario. When the character's life reaches zero, the player loses the game.

<p align="center">
<img width="800" src="/Figures/01.png" alt="Figure 01">
</p>

An initial UI was created where the player can decide to start the game, go to the options menu or close the application. The options menu has no functionality applied.

<p align="center">
<img width="800" src="/Figures/02.png" alt="Figure 02">
</p>

Starting the game, the life bar was positioned in the upper left corner, while the point counter was positioned in the upper right corner.

<p align="center">
<img width="800" src="/Figures/03.png" alt="Figure 03">
</p>

When collecting one of the gray blocks, the point counter is updated and the block is replaced with a particle effect.

<p align="center">
<img width="800" src="/Figures/04.png" alt="Figure 04">
</p>

When picking up one of the brown blocks, the player takes damage equal to 50% of their total life and the block is replaced by a particle effect.

<p align="center">
<img width="800" src="/Figures/05.png" alt="Figure 05">
</p>

Reaching zero life, the game over message is displayed, having a button to restart the game.

<p align="center">
<img width="800" src="/Figures/06.png" alt="Figure 06">
</p>

When collecting the 5 score blocks, a victory message is displayed, as well as a button to start over.

<p align="center">
<img width="800" src="/Figures/07.png" alt="Figure 07">
</p>

Last but not least, a Save and Load system was developed that can be activated by keys 1 and 2. When pressing key 1, the Save system will be activated, so that the player's HP and Point values in that moment will be saved. When pressing the 2 key, the Load system is activated and the current values of HP and Points are replaced by those previously saved.
