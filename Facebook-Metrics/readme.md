# Facebook Metrics (Cosmetic Page)

Link: https://archive.ics.uci.edu/ml/datasets/Facebook+metrics

## Description

This data is for a **specific cosmetic brand facebook page**.  It displays various facebook metrics for the entire page (and post) for various posts.  See data description below.

## Modifications

* Renamed several variables for ease of use in R, see below (short variable name)

## Variables

Response: Any of the following:

| Variable Name | Short Variable Name | Description | 
| --- | --- | --- |
| Lifetime post total reach | reach | The number of people who saw a page post (unique users).|
| Lifetime post total impressions | impressions | Impressions are the number of times a post from a page is displayed, whether the post is clicked or not. People may see multiple impressions of the same post. For example, someone might see a Page update in News Feed once, and then a second time if a friend shares it. |
| Lifetime engaged users | users | The number of people who clicked anywhere in a post (unique users).|
| Lifetime post consumers | consumers | The number of people who clicked anywhere in a post.|
| Lifetime post consumptions | consumptions | The number of clicks anywhere in a post.|
| Lifetime post impressions by people who have liked a page | impressions-liked | Total number of impressions just from people who have liked a page.|
| Lifetime post reach by people who like a page | reach-liked | The number of people who saw a page post because they have liked that page (unique users). |
| Lifetime people who have liked a page and engaged with a post | likedengaged | The number of people who have liked a Page and clicked anywhere in a post (Unique users).
| Comments | comments | Number of comments on the publication.|
| Likes | likes | Number of “Likes” on the publication.|
| Shares | shares | Number of times the publication was shared.|
| Total interactions | interactions | The sum of “likes,” “comments,” and “shares” of the post. |

Predictors: **all** other variables

| Variable Name | Short Variable Name | Description | 
| --- | --- | --- |
| Category | category | Manual content characterization: action (special offers and contests), product (direct advertisement, explicit brand content), and inspiration (non-explicit brand related content).|
| Page total likes | totallikes | Number of people who have liked the company's page. |
| Type  | type | Type of content (Link, Photo, Status, Video).|
| Post month | month | Month the post was published (January, February, March, ... ,December).|
| Post hour | hour | Hour the post was published (0, 1, 2, 3, 4, ..., 23).|
| Post weekday | weekday | Weekday the post was published (Sunday, Monday, ..., Saturday).|
| Paid | paid | If the company paid to Facebook for advertising (yes, no).|
