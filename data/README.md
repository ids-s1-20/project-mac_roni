# data

The dataset is a Skytrax User Reviews Dataset (published August 2nd, 2015)
at https://github.com/quankiquanki/skytrax-reviews-dataset

## datasets

The reviews are separated into 4 files

- `airline.csv`: airline reviews
- `airport.csv`: airport reviews
- `lounge.csv`: lounge reviews
- `seat.csv`: eat reviews


### Airline Dataset 

Rows: 41394
Columns: 20

Number of Values per Column
- (object) airline_name: 41396 -the name of the airline
- (object) link: 41396 - link to the airline
- (object) title: 41396 - title of the review
- (object) author: 41396 - name of the autor of the review
- (object) author_country: 39805 - home country of the author
- (object) date: 41396 - date of review
- (object) content: 41396 - authors comment
- (object) aircraft: 1278 - aircraft model
- (object) type_traveller: 2378 - type of traveller
- (object) cabin_flown: 38520 - class fo the cabin
- (object) route: 2341 - route of flight
- (float64) overall_rating: 36861 - flight rating from 0-10
- (float64) seat_comfort_rating: 33706 - seat comfort rating from 0-5
- (float64) cabin_staff_rating: 33708 - cabin staff rating from 0-5
- (float64) food_beverages_rating: 33264 food and beverages rating from 0-5
- (float64) inflight_entertainment_rating: 31114 inflight entertainement rating from 0-5
- (float64) ground_service_rating: 2203 - ground service rating 0-5
- (float64) wifi_connectivity_rating: 565 - wifi connectivity rating 0-5
- (float64) value_money_rating: 39723 - value for money rating 0-5
- (int64) recommended: 41396 - would the passenger reccomend the flight 1-yes 0-no



### Airport Dataset

Rows: 17721
Columns: 20

Number of Values per Column:
- (object) airport_name: 17721 - airport name
- (object) link: 17721 - link to the airport
- (object) title: 17721 - title of the review
- (object) author: 17721 - review author name
- (object) author_country: 12777 - home country of the author
- (object) date: 17721 - date of review
- (object) content: 17721 - authors comment
- (object) experience_airport: 647 - how did the author use said airport
- (object) date_visit: 593 - date the airport was visited by the review author
- (object) type_traveller: 646 - type of traveller 
- (float64) overall_rating: 13796 - overal airport rating 0-10
- (float64) queuing_rating: 12813 - airport queue rating 0-5
- (float64) terminal_cleanliness_rating: 12815 - terminal cleanliness rating 0-5
- (float64) terminal_seating_rating: 587 - terminal seating rating 0-5
- (float64) terminal_signs_rating: 27 - terminal seating rating 0-5
- (float64) food_beverages_rating: 630 - airport food and beverages rating 0-5
- (float64) airport_shopping_rating: 12676 - airport shopping rating 0-5
- (float64) wifi_connectivity_rating: 412 - wifi connectivity rating 0-5
- (float64) airport_staff_rating: 26 - airport staff rating 0-5
- (int64) recommended: 17721 - would the reviewer recommend the airport 1-yes 0-no



### Lounge Dataset

Rows: 2264
Columns: 21

Number of Values per Column:
- (object) airline_name: 2264 - name of the airlne flown
- (object) link: 2264 - link to the airline
- (object) title: 2264 - title of the reviw
- (object) author: 2264 - review authors name
- (object) author_country: 1783 - home country of reviewer
- (object) date: 2264 - date of review
- (object) content: 2264 - comment
- (object) lounge_name: 2261 - lounge name
- (object) airport: 2170 - airport name
- (object) lounge_type: 1964 - type of the lounge
- (object) date_visit: 99 - date the reviewer visited
- (object) type_traveller: 119 - type of the traveller
- (float64) overall_rating: 2259 - overal lounge rating 0-10
- (int64) comfort_rating: 2264 - lounge comfort rating 0-5
- (int64) cleanliness_rating: 2264 - lounge cleanliness rating 0-5
- (float64) bar_beverages_rating: 2259 - lounge bar beverages rating 0-5
- (float64) catering_rating: 2261 - lounge catering rating 0-5 
- (float64) washrooms_rating: 2238 - lounge washroom rating 0-5
- (float64) wifi_connectivity_rating: 2253 - lounge wifi connectivity rating 0-5
- (float64) staff_service_rating: 2255 - lounge staff service rating 0-5
- (int64) recommended: 2264 - would the reviewer reccomend the lounge 1-yes 0-no



### Seat Dataset

Rows: 1258
Columns: 21

Number of Values per Column:
- (object) airline_name: 1258 - airline name
- (object) link: 1258 - link to the airline
- (object) title: 1258 - title of the review
- (object) author: 1258 - author name
- (object) author_country: 1250 - author hoe country
- (object) date: 1258 - date of the review
- (object) content: 1258 - authors comment
- (object) aircraft: 1258 - aircraft type
- (object) seat_layout: 1252 - seat layout
- (object) date_flown: 113 - date flown
- (object) cabin_flown: 1252 - cabin class flown
- (object) type_traveller: 118 - traveller type
- (float64) overall_rating: 1257 - overall rating 0-10
- (int64) seat_legroom_rating: 1258 - seat legroom rating 0-5
- (int64) seat_recline_rating: 1258 - seat recline rating 0-5
- (int64) seat_width_rating: 1258 - seat width rating 0-5
- (int64) aisle_space_rating: 1258 - aisle space rating 0-5
- (float64) viewing_tv_rating: 1229 - tv rating 0-5
- (float64) power_supply_rating: 62 - power supply rating 0-5
- (float64) seat_storage_rating: 113 - seat storage rating 0-5
- (int64) recommended: 1258 - would the reviewer recommend 1-yes 0-no