# Casual classic game "Arkanoid" - VillageHolidays

## The project was developed in Blueprints using Unreal Engine 4 (v. 4.27).
<br>

### The playing field is a village garden on which pumpkins grow (at the start of the game, the level is auto-generated according to the given algorithms), which our main character breaks with a bat and a baseball.
<br>

### Game conditions:
1. Break all the pumpkins. Pumpkins are destroyed when the ball hits again.
2. After destroying the pumpkin, there is a 20% chance of dropping a parameter buff/debuff. Debuff - slows down the movement of the bat. Buff - with a 50% chance, it provides an additional ball to the playing field, or a superball that destroys pumpkins immediately upon hit, but then disappears.
3. When the main ball is lost, lives are taken away, but if there were additional balls on the playing field, the main ball simply respawns. Additional balls when lost do not respawn and do not take away the total number of lives.
4. The game time is not limited.
5. After all pumpkins are destroyed or all lives are lost, the game over widget appears with the total score (of broken pumpkins).
