# ai-hiring

## Project Scope

This project begins with one major question:

### To what extent is AI a smokescreen for the tech industry RIFs?

This project was inspired after Salesforce announced layoffs of 4,000 people in September 2025, with CEO Marc Benioff justifying that *"I need less heads [with AI]"*. However, an online commentator pointed out that between 2023 - Q3 2025, Salesforce has had over 3,600 H-1B worker visas approved by the U.S. Citizen & Immigration Services (USCIS). 

At the start of this project, it's not clear if this is all net new workers being 'insourced', continuations, what continuation requirements are, or other situations. However, it felt worth examining tech companies laying off thousands, whilst maintaining (or growing?) thousands of workers on a capped visa that runs on a [lottery system](https://www.uscis.gov/working-in-the-united-states/temporary-workers/h-1b-specialty-occupations/h-1b-electronic-registration-process) while the domestic talent pool, available with less legal strings attached, grows larger with every layoff.

To examine this further, I have pulled from two data sources:
- [Layoffs.fyi](https://layoffs.fyi), where the author Roger Lee (credit) has kept a database of news sources reporting on layoffs since COVID began
- The [H-1B Employer Data Hub](https://www.uscis.gov/tools/reports-and-studies/h-1b-employer-data-hub), showing employer petitions for H1B visas from 2017 to October 2025. The H-1B data shows several circumstances including new applicants, decisions on existing worker continuation and changes of employer.

My core argument is that **any downward pressure on headcount from AI should apply equally to both domestic and foreign labor at a given company**, since this is not a technology strategy, not a labor or immigration one. The H-1B dataset happens to be a readily available, high quality, company-specific labor report where to my knowledge a domestic equivalent doesn't exist. 

This project will examine:
- The companies most vocal about AI's impact, including the Magnificent 7 and mega cap tech companies
- Companies making the biggest layoffs
- Those with the largest H-1B petitions overall and petitions relative to its total headcount. 

Key conclusions should relate to:
- Layoffs correlating with decreasing numbers of net new H-1Bs;
- Continuations not increasing;
- Increased numbers of rejected applications, as a domestic talent pool is now ubiquitous and competitive for similar jobs.

This project is **not** about:
- Whether AI in its current state (mostly LLMs such as ChatGPT) is of genuine value. 
    - I have read the [MIT study](https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf) showing 95% of companies saw no meaningful P&L impact from post-pilot adoption. I have also read criticisms of it, but I don't feel there are any unbiased sources in a debate with so much money and market hype invested here.
- Identifying flaws in the H-1B and immigration process. The project goal is to examine the AI-first, labour-second narrative. To do that though, I will outline the process to show where the domestic and foreign worker journeys differ that might have an impact on job security for either the employer or the worker. 
    - I will need to establish the definitions of each visa category to explore if H-1B is acting as a labor substitute after layoffs at a given company.
    - I will also try to find information on how or where labor market testing is done, which should unearth the large pool of domestic talent. This mostly applies to tech companies, not other sectors that often use H-1B such as healthcare and academia.

## Background

### AI and work

AI is being touted as a universal threat to jobs in tech companies and has been quoted as the motive in nearly all layoff notices since late 2022, when ChatGPT was released. This is apparent across functions from customer success, now threatened by voice agentic AI, and for engineering there are many tools pitched as equivalent to junior developers, such as [Devin, the AI Software Engineer](https://devin.ai).

Unless a group is directly involved in the cutting edge of AI research or other technology (a very small subset), the H-1B visa data can examine if headcount is actually dropping. It could instead be an exercise in 'insourcing', in spite of an increasingly large domestic technology workforce available after years of layoffs. This also ignores any growth in Global Capacity Centres (GCCs), which already generate about $64bn in revenue and is expected to hit $110bn by 2030.

### A foreign tech worker's journey to US settlement

1. Three-year H-1B visa. Employers don't have to do labor market testing at this stage, but the job must be a specialised, degree-level occupation.
2. After six years maximum on an H-1B visa, the job must be labor market tested and advertised to US citizens (PERM). This takes around 12-18 months.
3. If PERM approved, the foreign worker can apply for a Green Card through employer sponsorship. **Employment-based Green Cards have a per-country cap** (7% of 140,000 annual issuances). This creates huge backlogs for Chinese and particularly Indian applicants and [Some sources](https://www.boundless.com/immigration-resources/average-green-card-wait-times) show Indian Green Card applicants being processed now were initially applied for in early 2013, nearly 13 years ago. This has feasibly created a situation where tens of thousands of people spend north of 15 years with their status in the US tied to a specific employer and job that could now be highly threatened by AI.
