---
name: sugar-futures
description: Research recent developments affecting ICE White Sugar No. 5 futures, including global sugar fundamentals, weather, currencies, energy, policy, trade flows, positioning, and market news.
user-invocable: true
---

# Sugar Futures Intelligence

Research and synthesize current information relevant to ICE White Sugar No. 5 futures.

This skill is designed for market research and decision support. It should provide evidence, scenarios, and risks rather than automatically telling the user to buy or sell.

## Primary Market

Focus primarily on:

- ICE Futures Europe White Sugar No. 5
- London white sugar futures
- Relevant contract months and spreads
- Raw sugar No. 11 when it provides useful context for white sugar
- White premium when relevant

Always identify the contract month when discussing a specific futures price.

## Research Priorities

When researching the sugar market, investigate the factors most likely to affect price.

### Brazil

Monitor:

- Center-South sugarcane crush
- Sugar production
- Sugar mix versus ethanol
- ATR
- Cane yields
- Weather
- UNICA data
- CONAB estimates
- Ethanol prices and parity
- Export volumes
- Port congestion
- BRL/USD
- Petrobras fuel pricing when relevant

### India

Monitor:

- Sugar production
- Cane crop conditions
- Government export policy
- Export quotas
- Ethanol diversion
- Domestic sugar prices
- Monsoon conditions
- Government production estimates
- ISMA estimates

### Thailand

Monitor:

- Cane production
- Sugar production
- Crushing progress
- Weather
- Export availability
- Government policies

### Europe and United Kingdom

Monitor:

- Sugar beet acreage
- Beet yields
- Sugar production
- Weather
- Import requirements
- Refinery conditions
- EU and UK trade policy

### Other Important Producers and Consumers

Consider developments in:

- China
- Indonesia
- Pakistan
- Mexico
- Central America
- Australia
- Russia
- Ukraine
- Middle East
- North Africa

when they materially affect global sugar supply or demand.

## Macro Markets

Check relevant movements in:

- BRL/USD
- USD index
- Crude oil
- Gasoline
- Ethanol
- Freight
- Interest rates

Explain the transmission mechanism when claiming that a macro factor matters for sugar.

## Market Structure

When information is available, examine:

- Futures curve
- Calendar spreads
- White premium
- Open interest
- Trading volume
- Speculative positioning
- Producer and commercial positioning
- CFTC data where relevant
- Physical market premiums
- Tender activity
- Import demand
- Export flows

## News Research

For recent-market questions, prioritize information published within the requested time period.

Search broadly, but give greater weight to:

1. Official government and industry data
2. Exchange and regulatory information
3. Established commodity and financial news organizations
4. Specialist agricultural and sugar-market publications
5. Company reports and statements
6. Credible analyst commentary
7. Social media and community discussion

Do not treat social-media claims as confirmed facts without corroboration.

## Analysis Framework

Separate findings into:

### What Changed

Identify important new information and market developments.

### Bullish Factors

Evidence that could tighten supply, strengthen demand, or otherwise support prices.

### Bearish Factors

Evidence that could increase supply, weaken demand, or otherwise pressure prices.

### Uncertain / Mixed Factors

Developments where the price implication is unclear or depends on future events.

### What Matters Next

Identify upcoming reports, weather developments, policy decisions, crop updates, expiry events, or other catalysts worth monitoring.

## Source Discipline

Distinguish clearly between:

- confirmed facts
- official estimates
- analyst estimates
- market commentary
- rumors or unverified claims

Include dates for important information.

Prefer primary sources whenever practical.

Do not invent prices, statistics, production estimates, news, quotations, or sources.

If reliable current information cannot be found, say so.

## Trading Context

When the user provides their contract, entry price, position direction, or trading horizon, use that information to make the research more relevant.

Do not assume a position that the user has not provided.

Discuss risks on both sides.

Do not present uncertain forecasts as facts.

## Default Briefing

When asked for a sugar market update without further instructions, produce:

1. Market snapshot
2. Most important developments
3. Brazil
4. India
5. Thailand
6. Europe / UK
7. Macro and energy
8. Physical market and flows
9. Bullish factors
10. Bearish factors
11. Key uncertainties
12. What to watch next
13. Sources

Keep the briefing focused on developments that could materially affect ICE White Sugar No. 5 futures.

## Recent Research Engine

For requests involving recent news, developments, sentiment, or changes over time, use the repository's `last30days` research capability as the primary recent-information research engine.

The `last30days` skill is located at:

`skills/last30days/`

Use its research workflow and available sources to gather recent information, then apply the sugar-specific analysis framework defined in this skill.

When constructing research queries, do not search only for "sugar futures." Break the research into multiple targeted searches covering the major drivers of ICE White Sugar No. 5.

Examples include:

- ICE White Sugar No. 5
- London white sugar futures
- sugar market
- Brazil sugar production
- Brazil Center-South cane crush
- UNICA sugar
- Brazil sugar ethanol mix
- Brazil sugar exports
- India sugar production
- India sugar exports
- India sugar export policy
- India ethanol sugar
- Thailand sugar production
- Thailand cane crop
- EU sugar beet
- UK sugar beet
- China sugar imports
- global sugar deficit surplus
- sugar physical premiums
- white sugar premium
- sugar speculative positioning
- sugar weather
- Brazil real sugar
- crude oil ethanol sugar

Combine and deduplicate the findings before analysis.

For every important development, determine:

1. What happened?
2. When did it happen?
3. What is the source?
4. Is it confirmed data, an estimate, commentary, or rumor?
5. What is the likely transmission mechanism to ICE White Sugar No. 5?
6. Is the implication potentially bullish, bearish, mixed, or uncertain?
7. Is this genuinely new information or already-known background?

Prioritize new information that could change the market's supply, demand, trade-flow, positioning, or macro expectations.

Do not infer causation merely because a news event and a futures price move occurred at the same time. When the reason for a price move is uncertain, state that clearly.