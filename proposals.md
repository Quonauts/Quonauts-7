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

## #15

Remove from rule 1.2 (%precedence):
> 2. If one clause is negative while the other is positive, the negative clause takes precedence.

<a name='16'/>

## #16

Append to section 1.8 (%glossary):
> * **Limited scope** (of two clauses): The clause that applies in the least situations, having the most constraints.

<a name='17'/>

## #17

Change rule 8 to:
The End is a dimension consisting of a large chunk of end stone, twelve obsidian towers, one bedrock fountain, and one dragon.

<a name='18'/>

## #18

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

## #19

Add a new rule section inside "Proposal Content" named "Ducks".
> Aside from this proposal, no proposals may mention ducks. Creation of a proposal that mentions ducks is a rule violation.
They will not win.

<a name='20'/>

## #20

This proposal depends on #18. Delay the first election until a future proposal has implemented gameplay benefits for the position of monarch.

<a name='21'/>

## #21

Add a new rule within "Proposal content" named "Power.
> No proposals may give any players power over any other player. "Power" is defined as one or more roles which one or more players have which allows or prevents them from taking certain game actions. The "Rule Offender" role is exempt from this.
> 
> Any benefit given by quantities that is not just another method of giving players "roles" does not count as "power".
> 
> All proposals which violate this rule or would have violated this rule are to be retroactively undone.

