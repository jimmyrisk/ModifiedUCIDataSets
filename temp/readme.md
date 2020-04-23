# Temperature in Seoul South Korea

Link: https://archive.ics.uci.edu/ml/datasets/Bias+correction+of+numerical+prediction+model+temperature+forecast

## Modifications

* Removed date (otherwise, this is a time series and we cannot deal with that)
* Removed station (is categorical, R doesn't handle as such)

## Variables

Response: **EITHER OF**: Next_Tmax or Next_Tmin (but do **not** include the other as a predictor)

Predictors: **all** other variables (aside from Next_Tmax and Next_Tmin)

* Example: we want to predict tomorrow's max temperature, Next_Tmax.  We cannot use Next_Tmin as a predictor since that would not be available to us for prediction purposes.
