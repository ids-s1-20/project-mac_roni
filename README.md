How do the amenities offered (cabin, seat, lounge and over time) impact
the flight’s overall rating?
================
by macaRoni

## Summary

We used a Skytrax Reviews dataset with individual data frames for
Airline, Seat and Lounge ratings. Each dataset has 20 variables, there
are approx. 40000 observations for Airline, approx. 2000 for Seat and
Lounge.

  - Columns consist of Airline Information, Author Information, Overall
    Rating, Contributors to the overall rating

  - Each observation is a passenger that filled out a survey based on
    their experience of the airline, lounge or seat.

Question 1: How does the overall rating for airlines change depending on
the time of the year?

Parameters:

  - Time ranges from 2014 - 2015 (lack of data points for other years)

  - Overall ratings averaged by date to avoid multiple data points for
    the same day

  - Top five airlines were chosen with highest overall ratings

Airlines: Air Astana, Asiana Airlines, Garuda Indonesia, Bangkok
Airways, Indigo Airlines

Main finding: no significant pattern in between years or at certain
times of the year as airlines offer the same service throughout each
year.

Decrease in overall ratings during the winter months (less survey
submissions and therefore negative surveys having more weight).

Limitations:

  - Variability of ratings – uncertainty in geom\_smooth function

  - Limited time period (2 years)

Question 2: To what extent do passengers in First Class(FC) give better
ratings than passengers in other cabin types?

We looked at different cabin classes in a flight, specifically the FC
cabin since we assume it offers the greatest number of services which
others may not offer. The passengers’ experience was measured in terms
of the overall rating.

Hypothesis: FC gives the highest overall (flight) rating since its
generally known for offering the plushest services.

Result: Business Class, followed by FC

Suggested claim: Fewer people were seeking first class amenities.

Further analysis affirms our claim. This limitation is important to note
because out of all the travelers, least number of them chose to fly in
the FC cabin.

Using text analysis, we only looked at facilities mentioned commonly in
the comments submitted assuming, if the passenger decided to mention it
in the feedback, then it may be a stronger factor contributing to the
overall rating submitted than the other facilities offered.

To conclude a connection between amenities and overall rating, we looked
at summary statistics and visualized variability using density plots
which confirmed the values obtained. The overall rating (1-10) and
amenities (1-5) have a similar rating proportionately (between 65-70%).
Few passengers rated food 1/5 which explains why the average food rating
is not in the similar range as others.

Question 3: Improvements in what amenities correlate to improvement in
the overal rating the most.

Airline’s improvement is defined as the sign of the slope of the overall
rating vs date fit.

The same definition of improvement was used to find the improvement of
cabin staff, food and beverage, seat comfort inflight entertainment and
value for money rating. We omitted wifi rating due to lack of data
points.

The improvement was calculated for every distinct airline reviewer pair.
This yields an answer to the question has the airline improved over time
in the eyes of a particular reviewer? (yes, no, it got worse)

Our findings

  - Cabin staff rating correlates the strongest with the improvement in
    overall rating

  - Inflight entertainment rating correlates the least

Question 4: Do positive reviews on an airline and positive reviews on
lounge and seat have a correlation?

Hypothesis: seat and lounge rating to have a positive correlation to the
airline rating because both are provided by the airline so this would
affect the authors rating of it.

First, we produced graphs to show the percentage difference between the
ratings of lounge and airline, and seat and airline. In general, the
percentage differences were quite low despite there being a few
exceptions as can be seen on the graphs.

We found the correlation coefficient to try and answer the question and
it showed that both values are closer to 1 than -1 so both the lounge
and seat ratings have a positive correlation to the airline rating which
proves our hypothesis to be correct. This suggests that the seat and
lounge will have an effect on the authors rating of the airline.

Conclusions:

1.  Time doesn’t affect the overall ratings as airlines give same
    service on all flights.

2.  There exists a connection between the cabin class assumed to have
    the most amenities (FC) and overall ratings.

3.  Cabin staff rating correlates the strongest and, in-flight
    entertainment the least, with the improvement in overall rating.

4.  The Seats and lounges will affect the airlines overall rating.

## Presentation

Our presentation can be found [here](presentation/presentation.html).

## Pre-Recorded Presentation

Our pre-recorded presentation can be found
[here](https://ed-ac-uk.zoom.us/rec/share/43NlcULVjNAhX_DVJWhQU5OdJjrJmxkdoguh3f152VFfF1Ib4T7jnPI4ceyzR7lu.QPNDBsuoWvOIlYtw?startTime=1607024273000).

Password: MacaR0n\!

## Data

Nguyen, Q 2015, Skytrax User Reviews Dataset (August 2nd, 2015),
electronic dataset, quankiquanki, viewed 01 December 2020, \<
<https://github.com/quankiquanki/skytrax-reviews-dataset/commits?author=quankiquanki>\>

## References

Nguyen, Q 2015, Skytrax User Reviews Dataset (August 2nd, 2015),
electronic dataset, quankiquanki, viewed 01 December 2020, \<
<https://github.com/quankiquanki/skytrax-reviews-dataset/commits?author=quankiquanki>\>
