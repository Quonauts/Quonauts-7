# Quonauts 7 — Rules

## Table of contents

* [**1. Meta rules**](#meta-rules)
    * [**1.1. Accuracy**](#accuracy)
    * [**1.2. Precedence**](#precedence)
    * [**1.3. Disallowed by default**](#disallowed-by-default)
    * [**1.4. Rule violations**](#rule-violations)
        * [**1.4.1. Errors**](#errors)
        * [**1.4.2. Rule violation polls**](#rule-violation-polls)
        * [**1.4.3. Punitive action**](#punitive-action)
    * [**1.5. Timezones**](#timezones)
    * [**1.6. Bots**](#bots)
    * [**1.7. Style conventions**](#style-conventions)
        * [**1.7.1. Content**](#content)
        * [**1.7.2. Headers and tags**](#headers-and-tags)
        * [**1.7.3. Lists**](#lists)
        * [**1.7.4. Formatting**](#formatting)
    * [**1.8. Glossary**](#glossary)
* [**2. Channels**](#channels)
    * [**2.1. #general**](#general-channel)
    * [**2.2. #rules**](#rules-channel)
    * [**2.3. #proposals**](#proposals-channel)
    * [**2.4. #polls**](#polls-channel)
    * [**2.5. #transactions**](#transactions-channel)
    * [**2.6. #the-land**](#land-channel)
    * [**2.7. #map**](#map-channel)
* [**3. Roles**](#roles)
    * [**3.1. Rule offender**](#rule-offender)
* [**4. Activity**](#activity)
* [**5. Proposals**](#proposals)
    * [**5.1. Proposal content**](#proposal-content)
        * [**5.1.1. Conflict resolution**](#conflict-resolution)
        * [**5.1.2. Dependency resolution**](#dependency-resolution)
        * [**5.1.3. Proposal linking**](#proposal-linking)
    * [**5.2. Voting on proposals**](#voting-on-proposals)
    * [**5.3. Closing proposals**](#closing-proposals)
        * [**5.3.1. Passing and failing proposals**](#passing-and-failing-proposals)
    * [**5.4. Editing proposals**](#editing-proposals)
* [**6. Quantities**](#quantities)
    * [**6.1. Purchase**](#purchase)
    * [**6.2. Ducks**](#ducks)
* [**7. Winning**](#winning)
* [**8. The end**](#the-end)
* [**9. Land**](#land)
    * [**9.1. Land generation**](#land-generation)
    * [**9.2. Production**](#production)
    * [**9.3. Land ownership**](#land-ownership)
* [**10. Monarch**](#monarch)
    * [**10.1. Royal election**](#royal-election)
* [**11. Equality**](#equality)

## <a name='meta-rules'/> Meta rules

This section details how the rules are to be applied to the game.

### <a name='accuracy'/> Accuracy

This document is not guaranteed to always be up-to-date as the game rules are modified, however it is the duty of all players to keep this document accurate as game rules are modified. Where this document disagrees with the game rules, players must follow the game rules as they legally are, rather than their description in this document.

### <a name='precedence'/> Precedence

1. If one clause has a more limited scope than another, then the clause with the more limited scope takes precedence.
2. The clause which appears last in the rules takes precedence.

### <a name='disallowed-by-default'/> Disallowed by default

Unless explicitly stated in the rules, all game actions are forbidden.

### <a name='rule-violations'/> Rule violations

A rule violation is a game action that is not permitted by the rules. Resolving a rule violation is the process of reversing the immediate effects of that rule violation (not including any indirect effects permitted in reaction to the rule violation) to the extent that it is possible.

#### <a name='errors'/> Errors

An error is a rule violation made by a player either mistakenly or through ignorance. If a player causes a rule violation and is able to resolve the error, they may do so.

If a player resolves an error within 24 hours of making that error, and the resolution of the error leaves the game state in such fashion that it is as if the error had never occurred, no punitive action can be taken against the player.

#### <a name='rule-violation-polls'/> Rule violation polls

If any player (hereby "the accusing player") believes that another player (hereby "the accused player") has violated the rules, then the accusing player may conduct a poll (called a "rule violation poll") to determine whether the accused player has violated the rules.

In conducting a rule violation poll, the accusing player must describe which sections or clauses of the rules were violated and what illegal game action was taken by the accused player. Players should vote in favor of this poll only if they agree that the accused player violated the rules as described.

Any vote in such a poll cast by the accused player is not counted.

A rule violation poll must be available for voting for at least 24 hours before any action may be taken as a result.

A rule violation poll may not be started more than 7 days after the potential rule violation.

For any potential rule violation, only one rule violation poll may be conducted.

If a rule violation poll passes, then the accused player is now convicted of violating the rules as described in the poll and the rule violation must be resolved, if it has not already.

#### <a name='punitive-action'/> Punitive action

If a player (hereby "the convicted player") is convicted of violating the rules, another player may conduct a poll (called a "punitive action poll") to determine whether punitive action should be taken.

Players should vote in favour of this poll only if they believe the convicted player violated the rules knowingly and with malicious intent.

Any vote in such a poll cast by the convicted player is not counted.

A punitive action poll must be available for voting for at least 24 hours before any action may be taken as a result.

If a punitive action poll passes, then the convicted player gains one strike.

### <a name='timezones'/> Timezones

Unless otherwise specified, all times and dates are specified with respect to UTC.

### <a name='bots'/> Bots

Certain game functions may be performed automatically by automated "bots"; the behavior of such bots is not governed by the rules, and any function that bots may perform should be feasible, even if inconvenient, to do manually.

### <a name='style-conventions'/> Style conventions

This section and its subsections describe grammatical and stylistic conventions used throughout this ruleset.

Any player may edit the rules to conform to these style conventions. Edits made this way must otherwise be minimal; i.e. they may not change wording or meaning.

#### <a name='content'/> Content

* All rules should be written in English using proper English grammar and spelling. American and British English spelling are both acceptable.
* Where applicable, rules should be written using gender-neutral language, with "they/them/their" as a third-person pronoun, both singular and plural.
* Sentences should be separated by a single space.
* Paragraphs should be separated by a blank line.
* Each paragraph or list element must be shorter than 1000 characters.
* Rules may not contain invisible characters besides newlines, normal spaces, and (in special cases) tabs. Non-ASCII characters should be used sparingly.
* Double quotes should be preferred instead of single quotes. ASCII-compatible straight quotes should be used instead of "smart" quotes.

#### <a name='headers-and-tags'/> Headers and tags

* Each section must have a header and a tag.
* Headers must use [sentence case](https://en.wiktionary.org/wiki/sentence_case), and must be a short, succinct word or phrase (not a complete sentence) describing the section.
* A section tag must be a string of text begin with a lowercase letter, end with either a lowercase letter or a number, and may contain only lowercase letters `a`-`z`, digits `0`-`9`, and hyphens `-`.
* A rule's tag should resemble its header.
* Tags must be unique; no two rule sections may have the same tag.

#### <a name='lists'/> Lists

* Unordered lists should use a single asterisk followed by a space (`* `) before each list element.
* Ordered lists should use a single number followed by a period and a space (`1. `) before each list element.
* The numbers of a ordered list should start at `1` and increase by `1` for each element.
* Lists should not be nested.
* Lists should be separated by the paragraphs above and below by a blank line.
* Two lists of the same type can not be adjacent. (This is treated as one list when converted to Markdown.)

Within a given list, all elements should have the same style, chosen from the following:

* Elements are words or phrases, and do not end with a period.
* Elements are clauses ending in a period (or other punctuation), and optionally followed by complete sentences.
* Elements are complete sentences ending in a period, and optionally followed by more complete sentences.

#### <a name='formatting'/> Formatting

From [GitHub's "Mastering Markdown" document](https://guides.github.com/features/mastering-markdown/), the following may be used:

* Emphasis (italics and bold, not including double underscore `__`)
* Unordered and ordered lists (not nested)
* Links
* Inline code
* Automatic linking for URLs
* Strikethrough

Additionally, square brackets `[]` containing a tag will be converted into links to another rule section; e.g. `[%rule-tag]`. Discord mentions (@username, @role, and #channel) may be used, however they are not readable in GitHub-flavored markdown.

### <a name='glossary'/> Glossary

The definitions for terms listed here take precedence over their normal English meanings, however any terms defined in a specific section of the rules override these in the section in which they are defined and any subsections of that section. A section may also define terms for use in the whole document.

* **The Game**: The instance of Nomic which is governed by this rules document.
* **Game Action**: A game action is any message or reaction in a game channel or any other manipulation of game channels or quantities which are part of the game.
* **Game State**: A specific arrangement of all game rules, proposals, polls, votes and quantities.
* **Game Channel**: A game channel is any text or voice channel listed in the "Quonauts 7" channel category of the Discord server.
* **Player**: Any participant of the game.
* **The Rules**: The rules of the game, which are described by this document.
* **Section**: A part of the rules which is contained under one header, not including any subsections.
* **Subsection**: A section of the rules which is contained under another section.
* **Clause**: A single statement in the rules
* **Limited scope** (of two clauses): The clause that applies in the least situations, having the most constraints.

## <a name='channels'/> Channels

The game rules govern only messages and reactions in the "Quonauts 7" category of the Discord server. Each subsection of this rule section corresponds to a game channel; as these subsections are created, renamed, or reordered, game channels must be created/renamed/reordered accordingly.

### <a name='general-channel'/> #general

Players may freely converse in the <#679771779589341218> channel.

### <a name='rules-channel'/> #rules

The <#679771790506983509> channel contains this rules document.

### <a name='proposals-channel'/> #proposals

The <#679771801773277357> channel is governed by [**5. Proposals**](#proposals).

### <a name='polls-channel'/> #polls

A poll is a means of gathering the opinions of players on an issue. Players may conduct a poll by providing any necessary detail and posting a question in the <#679771811004809282> game channel.

Players may vote in favor of a poll by reacting to the poll with 👍. Players may vote against a poll by reacting to the poll with 👎.

The player that posted a poll may edit it freely, as long as such edits do not change the meaning/intent of any existing reactions to the poll.

### <a name='transactions-channel'/> #transactions

The <#679774549273084061> channel may be used to modify quantities, but only as the game rules allow quantities to be changed.

### <a name='land-channel'/> #the-land

Players must announce their movement through The Land in <#680403819699765285>, and their announcements must match their actual movements.

### <a name='map-channel'/> #map

The #map channel can be used by players or bots to post maps depicting the current player positions, tile ownership, terrain or other interesting things about land. The channel has no direct gameplay relevance, but posting a false (not outdated) map is a rule violation and the map should be deleted as soon as the error is noticed.

## <a name='roles'/> Roles

The game rules govern roles that have effect within the game.

### <a name='rule-offender'/> Rule offender

Any player which has 1 or more strikes gains the "Rule offender" role. Rule offenders may not perform any game actions; i.e. they may not participate in the game. After 24 hours, a players strike count will decrease by 1 if above 0. If a players strike count is 0, the role will be removed.

## <a name='activity'/> Activity

All players that have taken some game action in the preceding 72 hours are active players. All other players are inactive players.

## <a name='proposals'/> Proposals

Proposals can be made by posting them to the <#679771801773277357> game channel.

The first proposal is numbered #1 and each subsequent proposal's number is increased by 1. Deleted proposals retain their number.

A proposal is either open or closed. When it is first submitted a proposal is open. A closed proposal is either passed or failed. When a player closes a proposal, they must either pass it or fail it.

### <a name='proposal-content'/> Proposal content

A proposal can describe any number of actions that make changes to the game rules or otherwise alter the game state.

If a proposal describes a modification to the rules, it must unambiguously specify the rule section(s) to be modified and how they will be modified.

If a proposal describes the creation of a new rule section, it must specify its title, its location in relation to an existing one, and its content.

#### <a name='conflict-resolution'/> Conflict resolution

If multiple proposals describe the modification or addition of sections, paragraphs, or sentences to the same part of the rules, conflicts should be resolved based on the age of the proposal, such that the newer proposal's effect overrides the older one's. For example, if proposal #10 adds a new section "A" to the bottom of the rules, and proposal #11 adds a new section "B" to the bottom of the rules, and both proposals pass, then regardless of which proposal passed first, section "B" will appear below section "A" in the rules.

#### <a name='dependency-resolution'/> Dependency resolution

A proposal may also state incompatible proposals, in which case all changes made by the older incompatible proposal will be undone if both proposals pass. A proposal may only be declared to depend on or conflict with another proposal that has not yet been closed at the time of making the new proposal.

#### <a name='proposal-linking'/> Proposal linking

If proposal A and B are linked, then they both pass if the total number of thumbsup votes on A and B exceed the total number of thumbsdown votes on A and B. A and B are considered to have been passed or failed at the same time.
The authors of proposals A and B must both agree to linking their proposals for their proposals to be linked.
If both A and B share the same author, the author may link the two proposals as they see fit.
To actually link the proposals once the author/authors decide to do so, one of the following actions must be taken:
Edit both proposals to state linkage.
Submit a third "helper" proposal saying that A and B are linked. If the proposals have different authors, they must both upvote the "helper" proposal to make the linkage official.

### <a name='voting-on-proposals'/> Voting on proposals

Each player may cast one vote on each open proposal.

Players may vote for or against a proposal. Players may also explicitly abstain from voting.

A player may change their vote on an open proposal at any time.

### <a name='closing-proposals'/> Closing proposals

Any player may close an open proposal if one or more of the following conditions is met:
• The proposal is at least 48 hours (2 days) old.
• All active players have cast a vote on the proposal.
• A majority of active players have voted in favour of the proposal.
• A majority of active players have voted against the proposal.

When a proposal is closed, if it passed, its author receives one point.

#### <a name='passing-and-failing-proposals'/> Passing and failing proposals

When a proposal is closed, it passes if it has more votes in favour than against; otherwise, it fails.

The player that authored a proposal may fail or delete it at any time.

When a player passes a proposal, that player must carry out the effects of that proposal and its passing to the best of their ability.

### <a name='editing-proposals'/> Editing proposals

A player may edit a proposal they have submitted if that proposal is open for voting and has no votes cast by players other than its author.

The author of a proposal or the player passing a proposal may choose to add or remove whitespace and fix typos or grammer mistakes, as long as the meaning of the proposal remains unchanged. Clarifications or additional details should always be added by a new proposal.

## <a name='quantities'/> Quantities

A quantity is a named property with a numerical value for each player.

By default any unique quantity added to the game:
* applies to all players.
* is instantiated at zero.
* must always be an integer.
* must never have a negative value.

Quantities may be traded or exchanged in ways specifically allowed by the rules.

The following quantities exist:

* **strike**: The number of rule violations a player has committed.
* **point**: The number of points a player has scored.
* **ducks**: Each duck earned adds the number of ducks to the points earned from a proposal.
* **land-x**: A player's horizontal position in the land.
* **land-y**: A player's vertical position in the land.
* **goods**: The amount of goods produced by a player's land.
* **land**: The amount of land a player owns.

When a new quantity is created, this rule should be edited to add it, along with a short description, to the above list. The description has no relevance to the game.

### <a name='purchase'/> Purchase

A Purchase is a voluntary transaction of any two quantities between any two Players.

A Purchase must be agreed on by both Players performing the Purchase to be Complete.

Once a purchase is Complete, the Quantities must be exchanged according to the agreement.

A Complete Purchase cannot be revoked or undone in any way.

An Invalid Purchase does not allow an exchange.

Any Purchase in which the Quantities being exchanged is not explicitly stated before the Purchase is Complete is Invalid.

Any Purchase in which the amount of Quantities being exchanged is not explicitly stated before the Purchase is Complete is Invalid.

### <a name='ducks'/> Ducks

Ducks are earned every 5 land a person claims, and they increase the amount of points earned from a proposal by the amount of ducks the author has.

If the player has at least one duck, the amount of goods they get from each tile owned is 1+(number of ducks)^2.

## <a name='winning'/> Winning

A player can win the game if a rule says so. A proposal cannot directly lead to a player winning. The game cannot be won by more than one player. If according to a rule two or more players win at the same time, that rule does not apply.

## <a name='the-end'/> The end

The game ends if a player has won.

## <a name='land'/> Land

The Land is an infinite square lattice. A 'land tile' is a point of this lattice, and has corresponding coordinates and a type (number associated with a string). Every pair of integer coordinates has a corresponding land tile.

'land-x' and 'land-y' are quantities. A player with (land-x, land-y) matching the coordinates of a certain land tile 'resides' in that land tile.

'North' and 'South' respectively correspond to the positive and negative y-axis, and 'East' and 'West' respectively to the positive and negative x-axis.

### <a name='land-generation'/> Land generation

By default, a land tile has type 'unknown', or 0. A land tile with type 0 and a player residing in it changes its type to a random value, determined by a 6-sided dice roll:
1-2 => type 1 "grass"
3 => type 2 "forest"
4 => type 3 "mountain"
5 => type 4 "water"
6 => roll a 4-sided dice and select the terrain type of the tile in that direction (1 = North, 2 = East, 3 = South, 4 = West). If that tile is "unknown", generate it first.

### <a name='production'/> Production

Each land tile Owned by a player may be used to produce one unit of goods per day.

### <a name='land-ownership'/> Land ownership

A piece of land may be owned by any player.
Each piece of land may only be owned by one player at a time.

A player can claim the land tile they are currently standing on (thus making the tile owned by them) if it is not yet claimed and there are no other players on this tile. This action replaces movement and can only be done when the player would be allowed to move.

## <a name='monarch'/> Monarch

One player carries the title of "Monarch" (or "King" or "Queen", if preferred), chosen by election (see %royal-election).

### <a name='royal-election'/> Royal election

A new monarch is chosen by a poll, called a "Royal election", with all active players as candidates (unless they explicitly declare they are not a candidate). The election ends when
* 48 hours have passed since start of the poll
* all active players have cast a vote
* one candidate has gained an absolute majority of votes
When one of these occurs, the election is immediately over and no more votes may be cast in the poll. If then one player has the most votes, they become the new monarch. Otherwise, a new election begins.

## <a name='equality'/> Equality

All Players have exactly one vote for every proposal.

There is no way for a Player to gain additional votes.

