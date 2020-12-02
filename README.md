How do the amenities impact the flight’s overall rating?
================
by macaRoni

## Summary

We will be investigating the question: How do the amenities impact the
flight’s overall rating? In our case, the amenities we will be looking
at are cabin, seat, lounge and time.

A brief introduction to the dataset: In short, the website Skytrax
allows passengers to fill out a survey on certain aspects of their
flight. The answers to these surveys were scraped and compiled in three
dataframes (Airline ratings, Seat ratings and Lounge Ratings) using a
Github Repository by quankiquanki.

Each dataset has 20 variables, and the number of observations vary
depending on the dataset (approx. 40000 for Airline Ratings, approx.
2000 for Seat and Lounge).

  - Columns: Airline Information, Author Information, Overall Rating,
    Contributors to the overall rating.

  - Observations: each observation is a passenger that filled out a
    survey based on their experience of the airline, lounge or seat.

Question 1: How does the overall ratings for airlines change depending
on the time of the year?

Assumptions:

  - Time only ranges from 2014 - 2015 due to lack of data points for
    other years

  - Overall ratings averaged by date and airline name to avoid multiple
    data points for the same day

  - Focus was put on the top five airlines that had the highest overall
    ratings as we are trying to understand why some airlines get higher
    overall ratings than others.

These are Asiana Airlines, Garuda Indonesia, Air Astana, Bangkok
Airways, and Indigo Airlines.

Main finding from the visualization: no significant pattern in between
years or at certain times of the year as airlines to offer the same
service throughout each year. Slight dip in overall ratings during the
winter months due to less survey submissions and therefore negative
surveys having more weight.

Finally, some limitations:

  - Uncertainty in geom\_smooth function (high). Highlights the
    variability of ratings.

  - Limited time period (2 years) – 10 years would allow any patterns to
    be observed more reliably.

Question 2: To what extent do passengers in first class give better
ratings than passengers in other cabin types?

Question 3: Improvements in what amenities correlate to improvement in
the overal rating the most We defined improvement of a airline as the
sign of the slope of the overall rating vs date fit. The same definition
of improvement was used to find the improvement of cabin staff, food and
beverage, seat comfort inflight entertainment and value for money
rating. We omitted wifi rating because of a lack of data points. The
improvement was calculated separately for every distinct airline
reviewer pair. This yields an answer to the question has the airline
improved over time in the eyes of a particular reviewer? (yes, no, it
got worse)

Our findings

  - cabin staff rating correlates the strongest with the improvement in
    overall rating
  - inflight entertainment rating correlates the least

Question 4: Do positive reviews on an airline and positive reviews on
lounge and seat have a correlation?

Conclusions: 1. Time does not affect the overall ratings as airlines
give same service on all flights. 2. 3. 4.

Write-up of your project and findings go here. Think of this as the text
of your presentation. The length should be roughly 5 minutes when read
out loud. Although pacing varies, a 5-minute speech is roughly 750
words. To use the word count addin, select the text you want to count
the words of (probably this is the Summary section of this document, go
to Addins, and select the `Word count` addin). This addin counts words
using two different algorithms, but the results should be similar and as
long as you’re in the ballpark of 750 words, you’re good\! The addin
will ignore code chunks and only count the words in prose.

You can also load your data here and present any analysis results /
plots, but I strongly urge you to keep that to a minimum (maybe only the
most important graphic, if you have one you can choose). And make sure
to hide your code with `echo = FALSE` unless the point you are trying to
make is about the code itself. Your results with proper output and
graphics go in your presentation, this space is for a brief summary of
your project.

## Presentation

Our presentation can be found [here](presentation/presentation.html).

## Data

Nguyen, Q 2015, Skytrax User Reviews Dataset (August 2nd, 2015),
electronic dataset, quankiquanki, viewed 01 December 2020, \<
<https://github.com/quankiquanki/skytrax-reviews-dataset/commits?author=quankiquanki>\>

## References

Nguyen, Q 2015, Skytrax User Reviews Dataset (August 2nd, 2015),
electronic dataset, quankiquanki, viewed 01 December 2020, \<
<https://github.com/quankiquanki/skytrax-reviews-dataset/commits?author=quankiquanki>\>
