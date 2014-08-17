# Blackjack, the challenge

## Specification

Using the provided files (attached) as a starting point, build a single player blackjack game in a browser. Feel free to use any frameworks, libraries, etc. We've included some markup to allow you to easily create cards. Please see the html and css files for an example of how to use that. We've also included a blackjack table background image. There should be a way for a player to receive two initial cards and the dealer's initial card, hit as we please until we finally stand, and learn the outcome. The dealer should play the typical dealer strategy of standing at 17 or greater.  

## Solution [demo here](http://creativeroots.io/challenges/blackjack.html)

Estimated time: 10 hours
Actual time: between 10 and 11 hours

Notes: The original css file was using the background-position-(x|y) property. This property has been deprecated by per W3C recommendation and does not work in some modern browsers. These background-position modifications were moved to javascript via object properties and bound to the appropriate element's style attribute.

### Enhancement Recommendations

#### Computerized Players

I was originally expecting to have enough to to implement computerized players but as time progressed I struck this feature off the backlog, realizing the time wasn't there. Would have been fun to compute probabilities over 100's of thousands of automated rounds. This would enable recommendations for the player's actions.
