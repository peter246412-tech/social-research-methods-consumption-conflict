# When Distant Conflict Reaches the Shopping Basket

> A social-research design examining whether real-time digital connectivity has changed how South Korean households respond to overseas geopolitical conflict through essential-goods consumption.

This was a four-person team project for the **Social Research Methods** course in the Social Science & AI program at Hankuk University of Foreign Studies. The course assignment ended at the research-proposal stage; this repository therefore presents a research design, not completed empirical findings.

## Where the Question Came From

The project began while tensions involving the United States and Iran were intensifying and rising prices were placing visible pressure on the Korean economy. I had already been interested in geopolitics and economics, so the news led me to a historical question: when similar conflicts occurred decades ago, did Korean households change what they bought in the same way?

That question expanded into a second one. Conflict itself is not the only thing that has changed. In today's hyper-connected environment, news alerts, search platforms, social media, and mobile devices can make an overseas event feel immediate. If a historical pattern could be identified—and if today's response differed after controlling for major price effects—household consumption might offer one useful signal for studying how societies react to future geopolitical shocks.

I proposed this topic to the team at the beginning of the project, and the central idea remained intact through the final submission.

## Research Question and Hypotheses

**Research question:** Has the transition to a hyper-connected society changed the strength of South Korean households' essential-goods consumption response to U.S.–Iran conflict?

The proposal developed two primary hypotheses:

1. The share of household spending devoted to essential goods will increase more during recent U.S.–Iran conflict periods than during comparable historical periods.
2. The difference will remain after controlling for economic pressures such as oil prices, inflation, and exchange rates, which would be consistent with an additional pathway involving attention, perceived threat, and psychological uncertainty.

The second hypothesis is deliberately framed as something to test rather than a conclusion. The proposed observational design cannot, by itself, prove a “pure psychological effect.” It can estimate whether a difference remains after measured economic factors are considered, while acknowledging possible unobserved confounders.

## Proposed Research Design

| Element | Operationalization |
| --- | --- |
| Unit of analysis | Monthly observations of South Korean household consumption |
| Historical comparison | U.S.–Iran and Middle East tension periods from the late 1980s through the early 2000s |
| Recent comparison | The 2020 Soleimani crisis and subsequent periods of direct tension |
| Independent variable | The onset and intensity window of U.S.–Iran conflict or military tension |
| Dependent variable | Change in the share or growth rate of essential-goods expenditure, including food, daily necessities, and medicine where consistently measurable |
| Proposed mediating pathway | Conflict attention and psychological uncertainty, approximated through news volume, search interest, and consumer sentiment where available |
| Controls | Consumer Price Index, exchange rate, domestic gasoline price, crude-oil indicators, and major macroeconomic shocks |

The historical window was selected because intense Middle East conflict and oil-price pressure made it a meaningful comparison candidate. It is not treated as automatically equivalent to the present. Differences in consumption classification, data availability, media systems, household structure, and the broader economy must be evaluated before making a valid comparison.

## Analytical Strategy

The proposed study combines:

- event-window and interrupted time-series comparisons around conflict dates;
- a Difference-in-Differences logic, conditional on finding defensible treatment and comparison periods;
- regression models with economic controls;
- mediation or moderation analysis only after specifying a defensible relationship to digital connectivity; and
- validity checks addressing measurement changes, contemporaneous shocks, and historical comparability.

Potential data sources include KOSIS household expenditure data, Bank of Korea ECOS indicators, Korea National Oil Corporation price data, BIGKinds news volume, and Naver DataLab search trends for periods where comparable data are available.

## My Contribution

I originated the research idea and helped translate it into hypotheses, variables, and a comparative design. Within the four-person team, my assigned analytical focus included the Difference-in-Differences framework, time-series design, and the proposed mediation/moderation analysis using R, Python, or Stata.

At the start of the course, I did not yet have a strong command of regression or causal inference. This project was one of my first attempts to move from an intuitive social question to a design that could be criticized, measured, and potentially tested. That gap was part of the learning process rather than something I want to conceal. It forced me to distinguish an interesting narrative from evidence capable of supporting it.

## How Feedback Changed the Design

The instructor's feedback identified a weakness in our early framing: we invoked “hyper-connectivity” without clearly explaining how it entered the causal mechanism. We were also asked to justify why historical and contemporary periods should be separated, explain why older data might not be directly comparable, make the mediation and moderation structure visible, and recognize that such claims require explicit regression models.

We revised the final proposal accordingly. Hyper-connectivity was repositioned as a contextual mechanism to be supported at the end of the analysis rather than assumed at the outset. The variables and analytical paths were made more explicit, and the historical comparison was framed as a methodological challenge requiring justification—not simply as two convenient date ranges.

This was the most valuable part of the project for me. The feedback showed that a compelling idea is only a starting point. A research design must explain what each concept means, how it will be measured, what alternative explanations exist, and what the available evidence can and cannot establish.

## Scope and Limitations

The course assignment was a research plan, and the team did not proceed to full data collection and estimation. I wanted to extend the project, but continuing a substantial empirical study outside the course required coordination and time that the team could not sustain.

Accordingly, this repository does **not** claim that overseas conflict caused a measured increase in essential-goods purchases. Important unresolved issues include:

- inconsistent household expenditure categories across historical periods;
- limited availability of search and digital-media measures for older periods;
- concurrent shocks such as financial crises, pandemics, and domestic policy changes;
- the difficulty of separating psychological uncertainty from price expectations; and
- the parallel-trends and comparison-group requirements of a credible Difference-in-Differences design.

## What I Would Do Next

1. Conduct a data-availability audit before fixing the final historical windows.
2. Build a harmonized monthly expenditure series with a documented category crosswalk.
3. Predefine conflict event windows and alternative specifications.
4. Visualize pre-trends before applying any Difference-in-Differences model.
5. Estimate progressively richer models and report sensitivity checks.
6. Treat news volume, search interest, and sentiment as distinct proxies rather than interchangeable measures of anxiety.
7. Publish a reproducible notebook and clearly separate exploratory findings from confirmatory tests.

## What This Project Represents

This project captures an early but important stage in my development as a Social Science & AI student. I began with a question shaped by my interest in geopolitics and economics, learned to operationalize abstract ideas such as uncertainty and attention, and discovered how much discipline is required before an intuitive pattern can become a defensible empirical claim.

The project remains unfinished as an empirical study, but it is complete as an honest record of learning how to design social research.

## Repository Contents

- [`연구계획서_미이란분쟁_필수재소비.pdf`](연구계획서_미이란분쟁_필수재소비.pdf): final Korean-language team research proposal
- [`2조 연구주제 (1차).pdf`](2조%20연구주제%20(1차).pdf): early topic framing and development
- [`연구주제탐색_체크리스트.docx`](연구주제탐색_체크리스트.docx): research-topic exploration worksheet
- [`PORTFOLIO_CASE_STUDY.md`](PORTFOLIO_CASE_STUDY.md): extended methodological notes and future empirical plan

## Academic Integrity

Team-produced documents are identified as team outputs, and my individual contribution is described separately. No private participant data are included. If the project is extended, data licenses, preprocessing decisions, code, and model specifications should be documented for reproducibility.
