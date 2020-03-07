# Quonauts 7 — Proposals

<a name='1'/>

## #1 — Passed

Append to rule 5.4 "Editing proposals":

> The author of a proposal, or the player passing the proposal may choose to add or remove whitespace and fix typos or grammar mistakes as needed so long as the meaning of the proposal remains unchanged. Clarifications or additional details should always be added a new proposal.

(stolen from Lukalot in Quonauts 6, I'd meant to put that in initial)

<a name='2'/>

## #2 — Failed

Add a new quantity, called "Ducks".
Ducks are earned every 5 proposals from the author of the proposals passing.
Each duck earned adds the number of ducks to the points earned from a proposal, effectively increasing your points. 
Along with this, append to rule 6. "Quantities" ( %quantities)
> **• Ducks:**  Each duck earned adds the number of ducks to the points earned from a proposal.
aswell as that, add rule 6.1 "Ducks" (%ducks)
> Ducks are earned every 5 proposals passing from the proposal author, and they increase the amount of points earned from a proposal by the amount of ducks the author has.

<a name='3'/>

## #3 — Failed

Append to 5.3.1 (%passing-and-failing-proposals):
> Improperly carrying out a proposal is a rule violation.

<a name='4'/>

## #4 — Failed

Add a new rule 9 after rule 8 called "Despotism" with the following content:
> All players who voted 👍  for the Proposal that created this rule, while that Proposal was Open, are Nobles. All other players are not Nobles. Not-Nobles are also known as Peasants. Nobles can react to an Open Proposal authored by a Peasant with a 🔥 to Fail and Close that Proposal. Peasants cannot vote 👎 on an Open Proposal authored by a Noble.

<a name='5'/>

## #5 — Passed

If this proposal passes, nothing happens.

<a name='6'/>

## #6 — Passed

Add a new rule (%land);
> The Land is an infinite square lattice. A 'land tile' is a point of this lattice, and has corresponding coordinates and a type (number associated with a string). Every pair of integer coordinates has a corresponding land tile.
> 'land-x' and 'land-y' are quantities. A player with (land-x, land-y) matching the coordinates of a certain land tile 'resides' in that land tile.
add a rule under %land (%land-movement);
> Subject to a 12-hour cooldown, a player may add or subtract 1 from one of their coordinates.
and add another rule under %land (%land-generation).
> By default, a land tile has type 'empty', or 0. A land tile with type 0 and a player residing in it changes its type to 'grass', or 1.

<a name='7'/>

## #7 — Passed

Amend Rule 6 (%quantities);
> Quantities may be traded and exchanged in ways specifically allowed by the rules.

<a name='8'/>

## #8 — Passed

Add a new rule, "Purchase" (%purchase) (%quantities);

This proposal depends on #7

> A Purchase is a voluntary transaction of any two quantities between any two Players.

> A Purchase must be agreed on by both Players performing the Purchase to be Complete.

> Once a purchase is Complete, the Quantities must be exchanged according to the agreement.

> A Complete Purchase cannot be revoked or undone in any way.

> An Invalid Purchase does not allow an exchange.

> Any Purchase in which the Quantities being exchanged is not explicitly stated before the Purchase is Complete is Invalid.

> Any Purchase in which the amount of Quantities being exchanged is not explicitly stated before the Purchase is Complete is Invalid.

<a name='9'/>

## #9 — Failed

This proposal depends on #2.

Append to rule 6 "Quantities":
> * **Point**

Append to rule 5.3.1 "Passing and failing proposals":
> If a proposal passes, the author and the player who passed it gain one point. The author also gains points equal to their number of ducks.

<a name='10'/>

## #10 — Failed

Add a new rule: %monarch
> One player carries the title of "Monarch" (or "King" or "Queen", if preferred), chosen by election (see %royal-election). The monarch's vote on a proposal counts twice. If the monarch becomes inactive or one of their proposals fails, they are forced to either pass on their title voluntarily or abdicate, which means they immediately loses this title of monarch and a new election happens to elect a new king. The monarch may pass on their title to another active player voluntarily any time.
Add a subrule %royal-election:
> A new king is chosen by poll, with all active players as candidates (unless they explicitly declare not to candidate). The conditions for ending the election are similar to proposals:
> * 48 hours have passed since start of the poll
> * all active players have cast a vote
> * one candidate has gained an absolute majority of votes
> If one of these occur, the election is immediately over and no more votes may be cast in the poll. If then one player has the most votes, they become the new monarch. Otherwise, a new election begins.
When this proposal passes, immediately start the first royal election.

<a name='11'/>

## #11 — Passed

Create a channel named #the-land, add the following rule under %channels (%land-channel):
> Players must announce their movement through The Land in #the-land, and their announcements must match their actual movements.
and append
> 'North' and 'South' respectively correspond to the positive and negative y-axis, and 'East' and 'West' respectively to the positive and negative x-axis.
to %land.

<a name='12'/>

## #12 — Passed

Add a new rule, "Equality" (%equality);
This proposal conflicts with #10

> All Players have exactly one vote for every proposal.

> There is no way for a Player to gain additional votes.

<a name='13'/>

## #13 — Passed

Replace %the-end with:
> The game ends if a player has won.
Replace %winning with:
> A player can win the game if a rule says so. A proposal cannot directly lead to a player winning. The game cannot be won by more than one player. If according to a rule two or more players win at the same time, that rule does not apply.

<a name='14'/>

## #14 — Passed

A duck-free alternative.

Create a new quantity called "point" and append to rule 6 (%quantities):
> * **Point**: The number of points a player has.

<a name='15'/>

## #15 — Passed

Remove from rule 1.2 (%precedence):
> 2. If one clause is negative while the other is positive, the negative clause takes precedence.

<a name='16'/>

## #16 — Passed

Append to section 1.8 (%glossary):
> * **Limited scope** (of two clauses): The clause that applies in the least situations, having the most constraints.

<a name='17'/>

## #17 — Failed

Change rule 8 to:
The End is a dimension consisting of a large chunk of end stone, twelve obsidian towers, one bedrock fountain, and one dragon.

<a name='18'/>

## #18 — Passed

This proposal conflicts with #10.
Alternative to #10 that is open for any development.

Add a new rule "Monarch" (%monarch) after %land:
> One player carries the title of "Monarch" (or "King" or "Queen", if preferred), chosen by election (see %royal-election).

Add a subrule of %monarch, "Royal election" (%royal-election):
> A new king is chosen by a poll, called a "Royal election", with all active players as candidates (unless they explicitly declare they are not a candidate). The election ends when
> * 48 hours have passed since start of the poll
> * all active players have cast a vote
> * one candidate has gained an absolute majority of votes
> If one of these occur, the election is immediately over and no more votes may be cast in the poll. If then one player has the most votes, they become the new monarch. Otherwise, a new election begins.

When this proposal passes, immediately start the first royal election.

<a name='19'/>

## #19 — Failed

Add a new rule section inside "Proposal Content" named "Ducks".
> Aside from this proposal, no proposals may mention ducks. Creation of a proposal that mentions ducks is a rule violation.
They will not win.

<a name='20'/>

## #20 — Passed

This proposal depends on #18. Delay the first election until a future proposal has implemented gameplay benefits for the position of monarch.

<a name='21'/>

## #21 — Failed

Add a new rule within "Proposal content" named "Power.
> No proposals may give any players power over any other player. "Power" is defined as one or more roles which one or more players have which allows or prevents them from taking certain game actions. The "Rule Offender" role is exempt from this.
> 
> Any benefit given by quantities that is not just another method of giving players "roles" does not count as "power".
> 
> All proposals which violate this rule or would have violated this rule are to be retroactively undone.

<a name='22'/>

## #22 — Passed

Add a new rule, "Land Ownership" (%land) (%purchase);
> A piece of Land may be Owned by any Player.
> Each piece of Land may only be Owned by one Player at a time.
> Land is allowed to be Purchased.

<a name='23'/>

## #23 — Passed

This proposal depends on #22
> Wait for rules determining the impact of Owning Land and for additional rules determining how land may be acquired to implement #22.

<a name='24'/>

## #24 — Failed

Append to the rule "Monarch" (% monarch):
> The monarch's vote for a proposal counts twice. The monarch is forced to abdicate (immediately triggering a new election) once a proposal they voted for fails.
This proposal fulfills #20, so upon passing the first royal election will start.

<a name='25'/>

## #25 — Failed

Add a new rule %player-interactions after %land
> Players may interact with other players on the same tile, ie. their land-x and land-y quantities are the same. Interaction replaces movement and may only be done when the player would be allowed to move. Only interactions listed in the rules are allowed.
Add a new subrule %attacking under %player-interactions:
> One possible interaction is attacking the other player. The result of an attack is decided by coin toss: Roll a 2-sided dice using the bot or another verifiable random number generator. If the result is the higher possible result, the other player gets wounded and is immediately moved back to (0,0). Otherwise nothing happens.

<a name='26'/>

## #26 — Passed

Do proposal 25 but without the attacking part.

<a name='27'/>

## #27 — Passed

Add a new quantity, called "Ducks".
Ducks are earned every 5 proposals from the author of the proposals passing.
Each duck earned adds the number of ducks to the points earned from a proposal, effectively increasing your points. 
Along with this, append to rule 6. "Quantities" ( %quantities)
> **• Ducks**: Each duck earned adds the number of ducks to the points earned from a proposal.
aswell as that, add rule 6.2 "Ducks" (%ducks)
> Ducks are earned every 5 proposals passing from the proposal author, and they increase the amount of points earned from a proposal by the amount of ducks the author has.

<a name='28'/>

## #28 — Passed

#25 but without the attacking part, cause #26 is probably invalid.

Add a new rule "Player interactions" %player-interactions after %land:

> Players may interact with other players on the same tile, ie. their land-x and land-y quantities are the same. Interaction replaces movement and may only be done when the player would be allowed to move.
> Only interactions listed in the rules are allowed.

<a name='29'/>

## #29 — Passed

Append to rule 5.3 "Closing proposals":
> When a proposal is closed, if it passed, its author receives one point.

<a name='30'/>

## #30 — Passed

This proposal depends on #22. Append to "Land Ownership":
> A player can claim the land tile they are currently standing on (thus making the tile Owned by them) if it is not yet claimed and there are no other players on this tile. This action replaces movement and can only be done when the player would be allowed to move.

<a name='31'/>

## #31 — Passed

This proposal depends on #22. Add a new currency "goods". Add a new subrule "Production" (%production) at the end of %land:
> Each land tile Owned by a player may be used to produce one unit of goods per day.

<a name='32'/>

## #32 — Failed

This proposal overrides all other rules.
Add a new rule "Sinthorion":
> Sinthorions votes are to count as 2 votes.

<a name='33'/>

## #33 — Failed

Add a new rule "Heavpoot, Adr and <@!427589146295664667>":
> This overrides all other rules.
> Heavpoot, Adr and <@!427589146295664667>s votes are all to count as 3 votes.

<a name='34'/>

## #34 — Failed

Give everyone who votes **against** this proposal 1000 units of goods.

<a name='35'/>

## #35 — Passed

Change rule 6.2 "Ducks" (%ducks) to this:
> Ducks are earned every 5 land a person claims, and they increase the amount of points earned from a proposal by the amount of ducks the author has.

<a name='36'/>

## #36 — Passed

As an extension to Proposal 35, add the following rule:
if the player has at least one duck, the amount of goods they get from each tile owned is 1+(number of ducks)^2.

<a name='37'/>

## #37 — Failed

Append to rule %ducks:
> Any player with at least 5 ducks gets an additional vote for proposals.
Remove rule 12 %equality.

<a name='38'/>

## #38 — Failed

My version of Proposal 37.
Change rule 12 to:
```
All Players have exactly one vote for every proposal.

There is no way for a Player to gain additional votes, except for having at least 5 ducks, which gives them an extra vote for proposals.```

<a name='39'/>

## #39 — Passed

Replace %land-generation with:
> By default, a land tile has type 'unknown', or 0. A land tile with type 0 and a player residing in it changes its type to a random value, determined by a 6-sided dice roll:
> 1-2 => type 1 "grass"
> 3 => type 2 "forest"
> 4 => type 3 "mountain"
> 5 => type 4 "water"
> 6 => roll a 4-sided dice and select the terrain type of the tile in that direction (1 = North, 2 = East, 3 = South, 4 = West). If that tile is "unknown", generate it first.

<a name='40'/>

## #40 — Passed

Replace the last paragraph of rule %dependency-resolution to:
> A proposal may also state incompatible proposals, in which case all changes made by the older incompatible proposal will be undone if both proposals pass.
> 
> A proposal may only be declared to depend on or conflict with another proposal that has not yet been closed at the time of making the new proposal.
This will align the rule with 5.1.1 and increase the incentive to actually declare incompatibilities.

<a name='41'/>

## #41 — Passed

Add a new channel #map
Add a new rule "#land-map" (%map-channel) as new subrule to %channels, after %land-channel:
> The #map channel can be used by players or bots to post maps depicting the current player positions, tile ownership, terrain or other interesting things about land. The channel has no direct gameplay relevance, but posting a false (not outdated) map is a rule violation and the map should be deleted as soon as the error is noticed.

<a name='42'/>

## #42 — Passed

Add rule 5.1.3, Proposal Linking:
If proposal A and B are linked, then they both pass if the total number of 👍 votes on A and B exceed the total number of 👎 votes on A and B. A and B are considered to have been passed or failed at the same time.
The authors of proposals A and B must both agree to linking their proposals for their proposals to be linked.
If both A and B share the same author, the author may link the two proposals as they see fit.
To actually link the proposals once the author/authors decide to do so, one of the following actions must be taken:
Edit both proposals to state linkage.
Submit a third "helper" proposal saying that A and B are linked. If the proposals have different authors, they must both upvote the "helper" proposal to make the linkage official.

<a name='43'/>

## #43 — Failed

The serious version of Proposal 17.

Change rule 8 to:
The End is a dimension consisting of a large chunk
of end stone, twelve obsidian towers, one bedrock
fountain, and one dragon.
As a land action, a player may either enter or leave The End.
End actions are independent from land actions cooldown from End actions does not count in The Land and vice versa.
The End action cooldown works the same way as the Land action cooldown.
List of End actions:
In the End, a player may mine an end stone for 1 unit of fragmented goods with a 1 minute cooldown, or mine an obsidian for 1 unit of reinforced glue with a 1 day cooldown.
A player may also craft 9 units of fragmented goods and 1 unit of reinforced glue into 2 units of goods without cooldown.

<a name='44'/>

## #44 — Failed

Extension to #43. Every day, a random player in The End gets sent back to The Land because of the dragon's attacking. Create the quantities "fragmented goods" and "reinforced glue".

<a name='45'/>

## #45 — Passed

Change 6.2 Ducks (%ducks) to this:
> Ducks are earned every 5 land a person claims, and they increase the amount of points earned from a proposal by the amount of ducks the author has.
> If the player has at least one duck, the amount of goods they get from each tile owned is 1+(number of ducks)^2.

<a name='46'/>

## #46 — Failed

Remove Rule 6.2.1 but only if #45 passes.

<a name='47'/>

## #47 — Passed

Replace the contents of %land with the following:
> The Land is an infinite square lattice. A 'land tile' is a point of this lattice, and has corresponding coordinates and a type (number associated with a string). **Future proposals can give land tiles additional properties.** Every pair of integer coordinates has a corresponding land tile.
> 
> 'land-x' and 'land-y' are quantities. A player with (land-x, land-y) matching the coordinates of a certain land tile 'resides' in that land tile.
> 
> 'North' and 'South' respectively correspond to the positive and negative y-axis, and 'East' and 'West' respectively to the positive and negative x-axis.
Formatting in the new text was added for clarity and should be ignored if the change is made.

<a name='48'/>

## #48 — Passed

Move rule %land-ownership into a subrule of %land and remove the sentence "Land is allowed to be Purchased."

Replace %purchase with:
> For the purposes of this rule, an item is either:
> * A quantity
> * The ownership of a land tile
> 
> A purchase is a voluntary transaction of any two items between any two players.
> 
> A purchase must be agreed on by both players performing the purchase to be complete.
> 
> Once a purchase is complete, the items must be exchanged according to the agreement.
> 
> An invalid purchase does not allow an exchange.
> 
> Any purchase in which the items being exchanged is not explicitly stated before the purchase is complete is invalid.
> 
> Any purchase in which the amount of item/s being exchanged is not explicitly stated before the purchase is complete is invalid.

<a name='49'/>

## #49 — Passed

This proposal aims to unify the system of movement and other actions that replace movement. It does not intend to change any gameplay mechanics, only improve terminology and clarity in the rules.

Remove rules %player-interactions and %land-movement. Remove the second paragraph of %land-ownership.

Add new rule "Actions" (%land-actions) before %land-movement (as first subrule to %land):
> Players may take various Actions in regard to the land or related things. After taking an action, the player has a 12 hour cooldown before being allowed to take another action. Each action has to be announced in <#680403819699765285>.
> A special case of an Action is an Interaction, aimed at another player. The other player must be on the same map tile to perform an Interaction.
(Re)add rule "Land movement" (%land-movement) as subrule of %land-actions:
> As an action, a player may move to a neighbouring tile, ie. add or subtract 1 from one of their coordinates.
Add rule "Land claiming" (%land-claiming) as new subrule of %land-actions:
> As an action, a player may claim the tile they are currently residing in, which makes the tile Owned by this player (see %land-ownership). This may not be done if the tile is already Owned by a player or another player is also residing in it.

If until passing this proposal other proposals have added new rules mentioning actions that replace movement, try to change their rules as well to match the pattern created by this proposal.

<a name='50'/>

## #50 — Passed

(trying to bring it in line with %production)

Append to %quantities:
> * **Goods**: The amount of goods produced by a players land

<a name='51'/>

## #51 — Passed

Append to %quantities:

> When a new quantity is created, this rule should be edited to add it, along with a short description, to the above list. The description has no relevance to the game.

<a name='52'/>

## #52 — Passed

This proposal depends on #49.

Add new rule "Building portal" (%building-portal) as subrule of %land-actions:
> As an action, a player may build a portal on the tile they currently reside in. The player must spend either 5 goods or 1 duck to do this, and announce the frequency of the portal. Portals may not be built in tiles that already have a portal. No more than two portals may have the same frequency.
Add new rule "Portal travel" (%portal-travel) as subrule of %land-actions:
> As an action, the player may travel through a portal on their current tile. This will immediately change the player's coordinates to those of another portal that has the same frequency as the portal moved through. This may not be done if there is no portal on the current tile or if the portal has no matching other portal with the same frequency.

<a name='53'/>

## #53 — Passed

Land tiles of type four (water) have a property named 'duck count', default value 0. A player can increase the duck count of a tile they own by some amount by decreasing their ducks by the same amount.

<a name='54'/>

## #54 — Failed

Heavpoot wins the game.

<a name='55'/>

## #55 — Failed

Blee wins the game.

<a name='56'/>

## #56 — Failed

Gollark wins the game.

<a name='57'/>

## #57 — Failed

Hactar wins the game.

<a name='58'/>

## #58 — Failed

Jerdie wins the game.

<a name='59'/>

## #59 — Failed

All players win the game.

<a name='60'/>

## #60 — Failed

Sarperen wins the game.

<a name='61'/>

## #61 — Failed

Sinthorion wins the game.

<a name='62'/>

## #62 — Failed

xp2_882030kgz010602 wins the game.

<a name='63'/>

## #63 — Failed

Adr wins the game.

<a name='64'/>

## #64 — Failed

Cognaso wins the game.

<a name='65'/>

## #65 — Failed

Elswyth wins the game.

<a name='66'/>

## #66 — Failed

Cuddlebeam wins the game.

<a name='67'/>

## #67 — Failed

FakePersona wins the game.

<a name='68'/>

## #68 — Failed

Jacob Arduino wins the game.

<a name='69'/>

## #69 — Failed

Lukalot just lost The Game.

<a name='70'/>

## #70 — Failed

PvPGecko wins the game.

<a name='71'/>

## #71 — Failed

All wweis that vote against this proposal are to be potatoed IMMEDIATELY, without hesitation.

<a name='72'/>

## #72 — Failed

Pyrotelekinetic wins the game.

<a name='73'/>

## #73 — Failed

Tinytitan wins the game.

<a name='74'/>

## #74 — Failed

has a 50% chance of winning the game when this proposal is passed.﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽﷽

<a name='75'/>

## #75 — Failed

Any player that votes for this proposal receives 2 points. Any player that votes against this proposal loses 15 points.

<a name='76'/>

## #76 — Passed

Create a new quantity called "land" equal to the number of land tiles that you own.

<a name='77'/>

## #77 — Passed

Any player that votes for this proposal receives 20 points. Any player that votes against this proposal or abstains loses 15 points.

<a name='78'/>

## #78 — Failed

Player Heavpoot#5118's proposals automatically fail upon proposal for the next 24 hours.

<a name='79'/>

## #79 — Failed

Everyone instantly gets 5 goods

<a name='80'/>

## #80 — Passed

Everyone is allowed to claim 5 goods within 24h of passing this proposal.

<a name='81'/>

## #81 — Passed

Move %production into a subrule of %land-actions and edit:
> As an action, a player may produce one "goods" for each land tile they ovn.

<a name='82'/>

## #82

Remove the points quantity. Remove every mention of it in the rules. Fail every open proposal that uses it.

<a name='83'/>

## #83 — Failed

Every timestamp by <@427589146295664667> is assumed to be in whatever time that New York State is currently using.

<a name='84'/>

## #84 — Failed

Append to %passing-and-failing-proposals:
> When a proposal passes, its author receives 1 duck.

<a name='85'/>

## #85 — Passed

Create a new quantity, "bread".

<a name='86'/>

## #86 — Passed

This proposal depends on #85.

Create a new rule "Feeding ducks", %feeding-ducks, within %land-actions:

> A player on a land tile with type water and duck count above 1 may spend 1 bread to take a duck from the tile.

<a name='87'/>

## #87 — Failed

Append this to %land-generation.
> All land generated before this message (https://discordapp.com/channels/547529950404542476/680403819699765285/686003310775500866) are land of type 1, grass.

<a name='88'/>

## #88 — Failed

Any player that votes for this proposal receives 35 land. Any player that votes against this proposal or abstains loses all of their land and gains two strikes.

<a name='89'/>

## #89

bread

<a name='90'/>

## #90

Make a new rule named "Hyper Speed Walking":
> Any player may move 32768*4 tiles in any direction, so long as they build up speed for 12 hours. They must be in shallow water, and also must hold A down the entire time.

<a name='91'/>

## #91

Ban Heavpoot from the game until he promises to take it seriously

<a name='92'/>

## #92

Ban Sinthorion from the game until he promises to not disallow players from playing the game due to their proposal content, as this game relies on people having different opinions of what should and shouldn't be allowed into the ruleset and this inherently goes against the spirit of the game.

<a name='93'/>

## #93

All users are required to nickname theirselves as 🍞, and keep it until 13/02/2020 (dd/mm/yyyy) UTC. Not doing this within 24 hours of this proposal passing will be considered a rule violation.

<a name='94'/>

## #94

Sinthorion is to be breaded, repeatedly

<a name='95'/>

## #95

This proposal depends on #94. Add butter to the bread.

<a name='96'/>

## #96

This is proposal #96.

<a name='97'/>

## #97

This is proposal #97.

<a name='98'/>

## #98

This is proposal #98.

<a name='99'/>

## #99

This proposal depends on proposal #100.
Invalidate proposal #100.

<a name='100'/>

## #100

This proposal depends on proposal #99.
Invalidate proposal #99.

<a name='101'/>

## #101

This proposal depends on the next 3 proposals made by Adr.
Invalidate the next 3 proposals made by Adr.

<a name='102'/>

## #102

This proposal depends on #101.
These messages will be split into multiple proposals.
Invalidate

<a name='103'/>

## #103

proposal

<a name='104'/>

## #104

#101

<a name='105'/>

## #105

Adr is to be considered a potato.

<a name='106'/>

## #106

Baba is you.

<a name='107'/>

## #107

This proposal is to be treated as all failed proposals, joined together by newlines.

<a name='108'/>

## #108 — Failed

This proposal depends on #105.
Create rule 6.2.1, "Potatoes" (%potatoes) with the following content:
> Potatoes get ducks every 2 land they travel.

<a name='109'/>

## #109 — Failed

This proposal depends on proposal #108.
Adr is not to be considered a potato.

<a name='110'/>

## #110

This proposal depends on the next 10 proposals.
Adr is to be considered the monarch and has 40 more votes than everyone else.

<a name='111'/>

## #111

This proposal depends on #105.
Create rule 6.2.1, "Potatoes" (%potatoes) with the following content:
> Potatoes get 1 duck every 2 land they travel.
> However, Potatoes can only have 3 ducks at a time.
> All other ducks either must be either put into water tiles, or discarded.

<a name='112'/>

## #112

This depends on any non-failed Adr proposal that contain any mention of "potatoes".
Everybody but adr is to be considered a potato.

<a name='113'/>

## #113

The next 10 proposals all depend on eachother.

<a name='114'/>

## #114

bread

<a name='115'/>

## #115

bread

<a name='116'/>

## #116

bread

<a name='117'/>

## #117

bread

<a name='118'/>

## #118

bread

