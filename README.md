# Pokemon Go Raid/Legendary Catch Rate Analysis

![](https://i.redd.it/pi99022jqb2e1.gif)

I messed up a palkia catch today and decided to determine once and for all, is it me or RNG?

I admit I'm not the most patient gamer. Sometimes the legendary just keeps moving (looking at you kyogre) and I throw a hail mary only to miss by a mile. "Whatever, that was just to gauge distance. I didn't even want to hit him anyways."

Well, here is a visual showing exactly why it's not the game, it's me.

# Figure

I won't break down the exact math here as there's a few resources that mention it already, but some things to note:

* For raid balls, I used a 1.05\^n multiplier where n is the number of balls thrown, but I don't have any sources so this is hearsay on my part.
* I defaulted to an "average" trainer which is almost certainly better than me. So my default values outside of the one changing parameter is: always golden razz, always great throw, silver medal, and always curved throw. Better players have plat medals and are mixing in excellents. I'm running with some bronze medals and some straight missed throws ¯\\\_(ツ)\_/¯ 
* The highlighted yellow area is the number of balls I think \*most\* players get (I actually have no idea tbh).

# Now, the Insights

There's some assumptions I had that really put things into perspective.

1. I thought missing a ball wouldn't be too bad. Erm actually, that one ball you missed pretty much cancelled out all your previous great throws. A missed ball puts your cumulative catch rate equal to *one tier* below e.g 11 great \~= 12 nice. Basically **Don't miss**. This also goes to show how important getting more balls in the raid actually is.
2. By far, the biggest improvement you can make to cumulative catch rate is curved throws. Huh?? Why the f does curved throw have a 1.7x multiplier (not complaining though but damn what a difference).
3. Medals are pretty minimal; makes me feel better about not putting the #timein.
4. Berry good. No berry not good. But seriously, no berry vs razz makes more of a difference than razz vs golden razz. Interestingly, silver pinap is not terribly worse than GRB - eyeballing, its about 7% worse than GRB at 12 great throws, and 2.8% worse with 16 balls in the chamber.
5. Because of the constant base multiplier and weather boost multiplier for raids, weather boost barely affects the cumulative catch rate (correct me if I'm wrong though, logically makes no sense to me that at 16 balls, it's a mere 0.7% difference).
6. And finally, how good are the raid balls actually? Well you kind of need more than 14 balls to feel the difference between that and ultra balls and at that point, you're at 97% chance to have caught that dawg already.

Anyways, TL;DR I did the math and I'm trash lmao. My mind went blank catching that palkia just so I can channel it here. Real TL;DR is don't miss, don't worry about weather boosted catches, if you're feeling mildly lucky go for the silver pinap, and don't blame the game blame the player (jk everyone get's unlucky sometimes).
