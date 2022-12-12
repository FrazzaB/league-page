<script context="module">
	export const prerender = true;
</script>

<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">LEGENDS LEAGUE CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: Roster</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>1.1 Positional Breakdown</h4>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneOneOne)}>1.1.1 Position Maximums</h5>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneTwo)}>1.2 Trading</h4>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoOne)}>1.2.1 Trade Collusion</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoTwo)}>1.2.2 Lending Players Prohibition</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoThree)}>1.2.3 Trade Deadline</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoFour)}>1.2.4 Trade Restrictions</h5>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneThree)}>1.3 Waiver Wire</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: Drafting</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoOne)}>2.1 Draft Order</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoThree)}>2.3 Draft Day Trades</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Scoring System</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>3.1 Scoring System</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Postseason</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>4.1 Playoffs</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourTwo)}>4.2 Seeding Tiebreakers</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Tanking Policy</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.1 League Tanking Policy</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Managers</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>6.1 Removing Managers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>6.2 Replacing Managers</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: League Finances</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>7.1 League Dues</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>7.2 Payout</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>7.3 Raising Dues</h4>
	
    <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>Section 8: Other Information</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightOne)}>8.1 Google Doc</h4>
    
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 Roster Breakdown</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Positional Breakdown</h3>
    
    <p>15 Total Players</p>
    
    <p class="underscore">Starters</p>
    <ul>
        <li>QB</li>
        <li>RB</li>
        <li>RB</li>
        <li>WR</li>
        <li>WR</li>
        <li>TE</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>SUPERFLEX (QB/RB/WR/TE)</li>
        <li>D/ST</li>
        <li>K</li>
    </ul>
    
    <p>5 Bench</p>

    <p>3 IR Spots (Player must be labeled as IR, Out, Doubtful or Covid in the Sleeper App)</p>
    
        <h4 bind:this={oneOneOne}>1.1.1 Position Maximums</h4>
        
        <div class="subBlock">
            <table class="positionMaximums">
                <tr><td>QB</td><td class="right">N/A</td></tr>
                <tr><td>RB</td><td class="right">N/A</td></tr>
                <tr><td>WR</td><td class="right">N/A</td></tr>
                <tr><td>TE</td><td class="right">N/A</td></tr>
                <tr><td>D/ST</td><td class="right">N/A</td></tr>
                <tr><td>K</td><td class="right">N/A</td></tr>
            </table>
        </div>


    <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Trading</h3>
    
    <p>Trading of players and draft picks are allowed. Trades will process immediately with no veto option unless collusion can be proven. Tradable assets include players, draft picks, keeper slots and FAAB$.</p>
    
    <h4 bind:this={oneTwoOne}>1.2.1 Trade Collusion</h4>
    <div class="subBlock">
        <p>If any form of trade collusion is suspected, this will be subject to an Ad-hoc vote to determine guilt and punishment. This includes the inclusion of non-tradeable assets in any official trade. If guilt is admitted, intentional or otherwise, Ad-Hoc vote will only determine the punishment until a precedent is established.</p>
       
        <p>All trades that are found guilty of collusion, will be reversed/denied. If the trade had affected the outcome of previous games, the results of those games will be revised.  </p>

        <p>The commissioner will err on the side of letting owners manage their teams the way they see fit. Any collusion will need to be clear. The commissioner reserves the right to step in and at the very least assess the thinking of any team involved in a heavily lop-sided trade. </p>
    </div>

    <h4 bind:this={oneTwoTwo}>1.2.2 Lending Players Prohibition</h4>
    <div class="subBlock">
        <p>Any player traded from a team may not be re-acquired via trade during that same season/following offseason. Any teams involved in this behavior will be subject to the aforementioned collusion procedure.</p>
    </div>
    
    <h4 bind:this={oneTwoThree}>1.2.3 Trade Deadline</h4>
    <div class="subBlock">
        <p>The in-season trade deadline will be set for the Wednesday of the week 12 games of the NFL season. Beyond this, trades are permissible between the AGM and the Keeper submission date.</p>
    </div>
    
    <h4 bind:this={oneTwoFour}>1.2.4 Trade Restrictions</h4>
    <div class="subBlock">
        <p>You will not be able to trade draft picks that are not available on the Sleeper app. You may only trade FAAB$ from the current season.</p>
    </div>
    
    <h3 bind:this={oneThree}>1.3 Waiver Wire</h3>
    
    <p>FAAB Waiver wire system. Each team will begin the season with $100. $0 bids are allowed. Bids will process Wednesdays at 8:05AM.</p>

    <p>FAAB budgets will reset each season post draft.</p>
    
    
    <h2 class="sectionHeading" bind:this={two}>Section 2 Drafting</h2>
    
    <h3 bind:this={twoOne}>2.1 Draft Order</h3>
    <p>The draft order each year will be a snake draft in reverse order of the previous year’s regular season standings after being subject to the Sacket winner's determination.</p>
	
    <p>Any spots not filled during the draft, can be filled immediately afterwards from the waiver wire.</p>
    
    <h3 bind:this={twoThree}>2.3 Draft Day Trades</h3>
    <p>Not permitted.</p>
    
    <h2 class="sectionHeading" bind:this={three}>Section 3 Scoring System</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>The league scoring system breakdown is listed on the Sleeper fantasy app (for the most part, it follows typical .5PPR Scoring). Any scoring changes made during an AGM/Ad-hoc vote will be effective immediately.</p>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 Postseason</h2>
    
    <h3 bind:this={fourOne}>4.1 Playoffs</h3>
    <p>At the end of the season 6 teams will make the playoffs. The first round of playoffs will commence in week 15. The top 6 teams that finish with the best records, will receive a playoff berth. The teams finishing 1st and 2nd will receive a bye week in the first round of the playoffs. Each playoff matchup will only last one week and the winner will advance. Week 18 will not be used.</p>
    
    <h3 bind:this={fourTwo}>4.2 Seeding Tiebreakers</h3>
    <p>If two teams finish with the same record the tiebreakers will go as followed:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head Record</li>
        <li>Total Points Against</li>
        <li>Coin Flip</li>
        <li>Duel to the death</li>
    </ol>

    <h2 class="sectionHeading" bind:this={five}>Section 5 Tanking Policy</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>Do what you want.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Managers</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>IF you take a picture of Martin crying and don't apologise, you will be removed.</p>
    
    <h3 bind:this={sixTwo}>6.2 Replacing Managers</h3>
    <p>Recommend a friend, unless you are Div. You've had your chance.</p>
	

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at £20. Dues are collected through Paypal "theleaguefund@gmail.com and collection will be sent out no later than the first week of the season.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: £150</li>
        <li>2nd place: £70</li>
        <li>3rd place: £20</li>
    </ul>
    <p>General practice is to leave the following seasons dues in the pot for ease. The total pot is subject to the league funds being approved for other uses, such as a New Trophy or other incidentals.</p>
    
    <h3 bind:this={sevenThree}>7.3 Raising Dues</h3>
    <p>Dues may be increased by the Commissioner due to additional incidental fees incurred.</p>
	
	<h2 class="sectionHeading" bind:this={eight}>Section 8 Other Information</h2>
    
    <h3 bind:this={eightOne}>8.1 Google Doc</h3>
    <p>All other league info and rules can be found in the Google Doc, this will change each season and can be obtained via the Commisioner. Current Doc is available <a href="https://docs.google.com/spreadsheets/d/1EkvNfM8z3XsEr6f6IbefKBglepLxxfU9OL99zGsSMKo">Here</a>
</p>
    
	


</div>
