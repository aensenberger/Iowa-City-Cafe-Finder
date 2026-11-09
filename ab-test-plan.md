# Iowa City Cafe Finder A/B Test Plan

**Course:** MKTG:4400 Digital Marketing  
**Project:** Deliverable 3  
**Date of revision:** November 9, 2026

## 1. Page and element being tested

The experiment will test the homepage of the Iowa City Cafe Finder website.

The single element being changed is the homepage hero image.

- **Version A (original):** https://aensenberger.github.io/Iowa-City-Cafe-Finder/
  - Features an illustration of a steaming coffee cup on books.
- **Version B (variant):** https://aensenberger.github.io/Iowa-City-Cafe-Finder/index-b.html
  - Features a photograph of a cozy coffee shop study environment with a coffee cup, notebook, and study materials on a table, with no people.

The hero image is the only intended difference between the two versions. The headline, navigation, call-to-action, page content, and other homepage elements will remain the same.

Version B includes a noindex tag and will be excluded from the sitemap to prevent it from competing with Version A in search results.

## 2. Hypothesis and reasoning

**Hypothesis:** AI visitors who see Version B will be more likely to say they would click "Explore Study Cafes" than visitors who see Version A.

The reasoning is that a realistic photograph of a coffee shop study environment may help visitors imagine themselves studying in a cafe. It may make the website's purpose and recommendations feel more relevant to a student looking for a place to study between classes.

The original illustration communicates coffee and studying, but the photograph may create a stronger connection to the actual experience the website is recommending.

## 3. AI visitor, persona, prompt, and assignment

**Model:** ChatGPT GPT-6. The same model and settings will be used for every trial. The displayed model label/version and date will be recorded for each trial.

**Persona:**

You are a University of Iowa undergraduate student who lives or studies in Iowa City. You need a coffee shop to study between classes. You value a comfortable atmosphere, reliable Wi-Fi, and access to outlets.

**Exact prompt:**

You are acting as the student described in the persona. Visit the Iowa City Cafe Finder homepage at the live URL provided below as if you have just arrived. Based only on what you can see on the live page, would you click "Explore Study Cafes" to look through the cafe recommendations? Answer YES or NO, followed by one sentence explaining your decision. Do not guess about information not shown.

Persona: You are a University of Iowa undergraduate student who lives or studies in Iowa City. You need a coffee shop to study between classes. You value a comfortable atmosphere, reliable Wi-Fi, and access to outlets.

Live homepage URL: [Insert the assigned Version A or Version B URL here.]

Each trial will take place in a fresh conversation with no memory of earlier trials. Only the assigned version's live URL will be provided in each trial. The prompt and persona will remain exactly the same, with only the assigned URL changing.

**Assignment method:**

A total of 100 trials will be conducted: 50 for Version A and 50 for Version B. Before collecting the new results, a list containing 50 A assignments and 50 B assignments will be shuffled using a random number generator. The randomized order will be saved and followed throughout the experiment. The version will not be chosen based on previous responses.

## 4. Primary outcome and measurement

The primary outcome is click intention.

Each response will be recorded as:

- YES = 1
- NO = 0

The exact response from each AI visitor will be saved. Responses that cannot clearly be classified as YES or NO will be recorded as missing, with an explanation in the notes rather than being silently removed or replaced.

The raw data will include:
- Trial number
- Assigned version
- Date
- Model label/version
- Exact AI response
- Outcome (YES = 1, NO = 0)
- Notes, if needed

## 5. Sample size and expected completion date

The experiment will include 100 total trials, with 50 assigned to Version A and 50 assigned to Version B.

The expected collection period is November 9–24, 2026, with all 100 trials completed by November 24, 2026.

The experiment will not stop early based on interim results. All assigned trials will be completed even if the results appear similar or one version initially performs better.

## 6. Comparison and definition of support

The percentage of YES responses will be calculated separately for Version A and Version B.

The difference will be calculated as:

**Version B YES percentage − Version A YES percentage**

A two-proportion z-test will be used to evaluate whether the difference is statistically significant at an alpha level of 0.05.

The hypothesis will be considered supported only if Version B has a higher YES percentage than Version A and the two-sided statistical test produces a p-value below 0.05.

If the difference is not statistically significant, the result will be reported as no clear evidence of a difference between the two versions.

## 7. Limitations

This experiment uses AI visitors rather than actual customers. The results measure stated click intention from an AI model playing a student persona, not real website clicks or actual behavior from University of Iowa students.

The AI model cannot fully reproduce the preferences, experiences, or decisions of real visitors. Results may also depend on the model, its settings, and how it interprets the website.

The findings should therefore be treated as a limited comparison of two homepage designs rather than proof of how real customers would behave.

## 8. Change log

- **November 9, 2026:** Revised the experiment method from providing homepage screenshots to providing the live Version A or Version B website URL. Updated the exact prompt to reflect live-page evaluation. The first 10 screenshot-based trials will be retained separately and excluded from the revised experiment results. The revised experiment will use a new randomized assignment order and collect 100 live-URL trials, with 50 trials per version. The hypothesis, persona, primary outcome, and statistical comparison remain unchanged.
