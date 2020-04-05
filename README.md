Yahtzee - The game
------------------

Yahtzee is a chance-and-strategy dice rolling game. A game is played over 13 rounds.

Each round, the player rolls five 6-sided dice. They may click on any number of dice to “freeze” or “unfreeze” them (frozen dice are displayed in a different color). They may re-roll the unfrozen dice up to 2 times.

Each round, they must assign their dice to any unclaimed scoring category. Each category scores differently.

After 13 rounds, the game is over, and the player’s score is the total of each scoring category.

### Scoring Categories

<table>
<col width="25%" />
<col width="51%" />
<col width="24%" />
<thead>
<tr class="header">
<th align="left">Category</th>
<th align="left">Description</th>
<th align="left">Example Score</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><strong>Ones</strong></td>
<td align="left">Score 1 for every 1</td>
<td align="left"><code class="docutils literal notranslate">1 1 2 3 4</code> = 2</td>
</tr>
<tr class="even">
<td align="left"><strong>Twos</strong></td>
<td align="left">Score 2 for every 2</td>
<td align="left"><code class="docutils literal notranslate">1 2 2 3 4</code> = 4</td>
</tr>
<tr class="odd">
<td align="left"><strong>Threes</strong></td>
<td align="left">Score 3 for every 3</td>
<td align="left"><code class="docutils literal notranslate">1 2 3 3 3</code> = 9</td>
</tr>
<tr class="even">
<td align="left"><strong>Fours</strong></td>
<td align="left">Score 4 for every 4</td>
<td align="left"><code class="docutils literal notranslate">1 2 4 4 5</code> = 8</td>
</tr>
<tr class="odd">
<td align="left"><strong>Fives</strong></td>
<td align="left">Score 5 for every 5</td>
<td align="left"><code class="docutils literal notranslate">1 2 5 5 5</code> = 15</td>
</tr>
<tr class="even">
<td align="left"><strong>Sixes</strong></td>
<td align="left">Score 6 for every 6</td>
<td align="left"><code class="docutils literal notranslate">1 2 3 6 6</code> = 12</td>
</tr>
<tr class="odd">
<td align="left"><strong>3 of Kind</strong></td>
<td align="left">If 3+ of one value, score sum of all dice (otherwise, score 0)</td>
<td align="left"><code class="docutils literal notranslate">1 2 3 3 3</code> = 12</td>
</tr>
<tr class="even">
<td align="left"><strong>4 of Kind</strong></td>
<td align="left">If 4+ of one value, score sum of all dice (else 0)</td>
<td align="left"><code class="docutils literal notranslate">1 2 2 2 2</code> = 8</td>
</tr>
<tr class="odd">
<td align="left"><strong>Full House</strong></td>
<td align="left">If 3 of one value and 2 of another, score 25 (else 0)</td>
<td align="left"><code class="docutils literal notranslate">2 2 3 3 3</code> = 25</td>
</tr>
<tr class="even">
<td align="left"><strong>Small Straight</strong></td>
<td align="left">If 4+ values in a row, score 30 (else 0)</td>
<td align="left"><code class="docutils literal notranslate">1 2 3 4 6</code> = 30</td>
</tr>
<tr class="odd">
<td align="left"><strong>Large Straight</strong></td>
<td align="left">If 5 values in a row, score 40 (else 0)</td>
<td align="left"><code class="docutils literal notranslate">1 2 3 4 5</code> = 40</td>
</tr>
<tr class="even">
<td align="left"><strong>Yahtzee</strong></td>
<td align="left">If all values match, score 50 (else 0)</td>
<td align="left"><code class="docutils literal notranslate">2 2 2 2 2</code> = 50</td>
</tr>
<tr class="odd">
<td align="left"><strong>Chance</strong></td>
<td align="left">Score sum of all dice</td>
<td align="left"><code class="docutils literal notranslate">1 2 3 4 6</code> = 16</td>
</tr>
</tbody>
</table>

### Example Round

The initial roll is: `2 4 3 2 5`.

The player decides to try to get as many twos as possible, and clicks to freeze both twos, then re-rolls, getting a new `2 3 5`. They now have: `2 2 3 2 5`.

The player decides to try for a full house, and freezes all of their twos and their three (hoping to roll another 3 to get a full house). They re-roll the die showing five, getting a `6` and now have `2 2 3 2 6`.

Sadly, they didn’t get their full house. They could score this as:

-   *Twos*: for 6 points
-   *Threes* for 3 points
-   *Sixes*: for 6 points
-   *Three of Kind:* (twos) for 15 points
-   *Chance*: for 15 points

Any other category they claimed on this round would score 0.
