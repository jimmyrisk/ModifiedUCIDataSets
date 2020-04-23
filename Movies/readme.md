# Movies

Link: https://archive.ics.uci.edu/ml/datasets/CSM+%28Conventional+and+Social+Media+Movies%29+Dataset+2014+and+2015#

## Modifications

* Several variables were removed, whose names were unclear as to what they meant.  The site did not provide full data descriptions.

## Variables

**Movie**: do not use this as a predictor or response - it is included just so you can see the movie if you're curious.

**Gross**: I believe this is the gross income for a movie on its first week in the box office.  **Be careful with this variable:** I looked deeper into the data and found that some movies had exceptionally low gross.  Further investigation shoed that the gross variable is only the domestic gross, not accounting for international gross.  (For example, the movie 13 Sins has gross = $9,314, but has an international gross of $813,104.)  You **may** want to omit this variable from your analysis.

Response: Any aside from "movie," "year," and "budget"

Predictors: Hypothetically all others, but it might not make sense for example to *predict* budget with gross.
