# SummerProject
Summer project between friends

This is the main description file where shit gets described.
Open it in notepad++


**Rules:**
4-6 players (preferably 5, var players)

5-10 rounds (var rounds) - each round is an equal period of time (we can describe it as 1 year)

After each round several events happen: one macroeconomic (var macro), one event related to the company's individual external/internal operations (var ind_event). Both events influence the state of the company, potential growth rate, risks and other conditions which influence the expected value/payoff/cash flow of the company

Each player runs a company (var company) owning 100% of stock at the beginning

Players can trade with the stocks they own. Combination of different stocks creates synergies which can improve the operations of the companies (var synergies). The synergies might work in both ways, e.g. if there is an exchange between steel producer and car producer, theoretically the car producer reduces the costs of the raw materials which decreases the overall costs and makes the business more efficient and profitable, but the steel producer obtains a stable customer that reduces some company risks. The shares traded are transferred to their new owners who now receive profits from them.

Of course, other players might not accept the trade if the deal is not attractive

The company has several base indicators, which determine their risk (var risk), growth rate (var growth) and probably other conditions (e.g. debt-to-equity ratio, capital-to-labor ratio, beta), these conditions should be developed further. As to the risk and the growth rate, the risk reflects some downside probability which might occur due to the macro events or individual company events, the growth rates show the coefficients by which the current cash flow/profits into the company are multiplied after each round. The growth rate can also change after some macro or individual effect occurs

The goal of the game is to earn more than other player after the last round

In case it appears that the players are still too dependent on the events and are too limited in their actions, I offer to add some opportunities to invest money in the companies. The mechanism would be just adding 2-3 available projects during each round indicating the implementation time, cost of the project, risks and expected gains with +/-20% value. The gain can be indicated on the cash flow basis or profit basis. If some project is implemented but the stock is traded afterwards, all the negative and positive sides of the project are shifted together with a stock. If there occurs a situation when a company has several owners, to implement a project, all the owners should vote. The project should get >50% weighted votes "for" to accept the project. If the project is accepted, the company finances it from available money in the company (meaning that ALL players pay for it). Each player can choose only 1 project per round

The slots of the projects are split in the following way:
If the player owns more than 50% of his initial company, he receives 2 available projects for this company and one project of another random company that the player also owns.
If the player owns more than 30% of his initial company, it is guaranteed that the player receives at least one project for his initial company and 2 other projects for random companies that the player also owns (1/2 remaining slots can be filled with the initial company as well). In case the player owns 50% of some company, he will also receive at least one project for this company by guarantee.
If the player owns less than 30% of his initial company, he receives a project for the company where he owns a major stock (if there are 2 or more companies with equal %, the company is chosen on the value base). Other 2 slots are filled with random companies that the player owns (again, 1/2 remaining slots can be filled with the project for the company where the player owns his biggest share)

The general rule: the player cannot receive all 3 projects for one company - this is done to motivate players to trade, so when a player owns only 1 company, there are 2 available project slots (both filled with one company)

**How the rounds take place:**
Since the game should not last several days, I propose giving about 2-3 minutes on each round.

Firstly, the players have about 90 seconds to think and prepare trade offers to other players or consider different projects.

I also propose setting a limit on the number of actions the player can make per move (as "faster" players would have an advantage in this case), as well as the limit on the maximum amount of offers from one player to another (to prevent spamming). When the trade offers are prepared and 90 seconds pass, the offers are sent to other players at a time who have 20-30 seconds to consider them and decide whether they accept any of them or not.

All the offers appear in a way that the player can see them all and compare, there is no limit on the accepted amount of offers unless the player has resources to trade.

When the exchange is finished, the previously chosen projects appear on the screen and the players choose whether to accept them or not (20-30 seconds)

The weights of the votes are counted based on the new structure of owners (e.g. I own 60% of a company in round t and choose some project for it from 3 that were available. Then I receive an offer from another player to exchange 20% of my company on something else and accept it. When it comes to accepting the project, my voting power is only 40%, meaning that I need a support from the guy I traded with or from someone else who owns some amount of this stock. The project will be accepted if it receives 50% of the votes)

When the project gets accepted or rejected, the players have 20 seconds to make one more offer, and 10-15 seconds to accept or reject the incoming offer. Then the round finishes  

When the round is finished, the events appear on the screen for each player - macro events with consequences and the individual events for each company the player owns with the consequences.


**What the players see**

Every player's earned money
Every player's shares
Every player's portfolio (combined indicators of the owned companies)
The status of every company with indicators
Possible synergies between companies with formulae


**Possible problems to solve:**
Nobody trades with each other at all
2 players start cooperating and block others
kamikaze tactics with excessive risk
time constraints
