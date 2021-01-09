# A/B Testing: Cookie CATS

## Cookie CATS Introduction:
**Cookie CATS** is a hugely popular mobile puzzle game developed by <a href="http://tactile.dk">Tactile Entertainment</a>. It's a classic "connect three"-style puzzle game where the player must connect tiles of the same color to clear the board and win the level. It also features singing cats. We're not kidding! Check out this short demo:</p>


[![cookie_CATS_youtube](https://user-images.githubusercontent.com/67468718/104091124-37064e00-5230-11eb-91aa-03fb69297f1e.JPG "cookie_CATS_youtube")](https://www.youtube.com/watch?v=GaP5f0jVTWE&feature=youtu.be)


<p>As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged.</p>


![Gates](https://user-images.githubusercontent.com/67468718/104091125-379ee480-5230-11eb-881d-7d37c2811f36.JPG)


<p>But where should the gates be placed? Initially the first gate was placed at level 30, but in this notebook we're going to analyze an AB-test where we moved the first gate in Cookie Cats from level 30 to level 40. In particular, we will look at the impact on player retention. But before we get to that, a key step before undertaking any analysis is understanding the data. So let's load it in and take a look!</p>
