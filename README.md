# Functionality

<div class="flex-icon">
    <div style="max-width:30%;" onclick="location.href='#pre-game-matchmaking'">
        <img src="./assets/pics/icon-matchmaking.png" alt="icon-matchmaking" style="height:120pt;"/>
        <p>Pre-Game Matchmaking</p>
    </div>
    <div style="max-width:30%;" onclick="location.href='#in-game-win-prediction--comments-generation'">
        <img src="./assets/pics/icon-prediction.png" alt="icon-in-game" style="height:120pt;"/>
        <p>In-Game Win-Prediction & Comments-Generation</p>
    </div>
    <div style="max-width:30%;" onclick="location.href='#post-game-analysis'">
        <img src="./assets/pics/icon-group-analysis.png" alt="icon-post-game" style="height:120pt;padding-top: 40pt;"/>
        <img src="./assets/pics/icon-performance-analysis.png" alt="icon-post-game" style="height:120pt;padding-bottom: 40pt;"/>
        <p>Post-Game Analysis</p>
    </div>
</div>

## Pre-Game Matchmaking
> Matchmaking is the process of arranging queueing players into competitions.
>
> (i.e. decide who are going to be teammates and who are going to be adversaries)

**Fuxi Match** provides the AI-enhanced matchmaking services to maximize the gross players' satisfaction for upcoming matches.

AI algorithms are applied to 3 processes in a matchmaking system:
- User Modeling
- Arrival Modeling
- Online Planning


## In-Game Win-Prediction & Comments-Generation
- Realtime win prediction with the match going on
- Realtime comments generation to summarize the match and highlight the key actions/moments

## Post-Game Analysis
- Performance Rating
- Performance Radar Chart
- Piggybacking Detection
- Potential Cheating Diagnosis
- Power Leveling Detection
- Smurfing Detection

# Matchmaking SaaS
![matchmaking_server](./assets/pics/matchmaking_server.png)

# Research & Blogs
### Papers
- <mark><em>Fuxi AI Lab</em></mark> 【KDD'20】 OptMatch: Optimized Matchmaking via Modeling the High-Order Interactions on the Arena &nbsp;&nbsp;&nbsp;[>>Blog & Code & Data](../OptMatch/)
- <mark><em>Fuxi AI Lab</em></mark> 【CIKM'20】Match Tracing: A Unified Framework for Real-time Win Prediction and Quantifiable Performance Evaluation &nbsp;&nbsp;&nbsp;>>Blog & Code & Data
- <mark><em>Reproduction</em></mark> 【WWW'17】EOMM: An Engagement Optimized Matchmaking &nbsp;[>>Blog & Code & Data](../EOMM/)

### Practical Tricks
- How to measure a win-prediction model in the matchmaking context?

### Basics and Prerequisites
- ELO
- TrueSkill

