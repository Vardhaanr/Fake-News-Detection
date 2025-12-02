Enter any news claim or headline into the textbox provided (e.g., “A new virus was discovered in Europe yesterday”).

Click the “Fact Check” button to submit your claim.

The app sends your input to the Google Gemini 2.5 Flash API along with instructions to act as a professional fact-checker.

Gemini performs a live Google Search grounding to fetch fresh, verified information from the web.

The model checks whether the claim is true, false, misleading, or unverifiable based on the evidence found.

It returns a result containing:
1)A Yes/No accuracy verdict.
2)A fact-checked explanation in markdown.
3)Citations with links to the sources it used.
4)A corrected version of the news (if your claim is false).

The result appears instantly in the output section of the interface.

Each fact-check is automatically logged into a CSV file, which you can download directly through the “Download History” button.
