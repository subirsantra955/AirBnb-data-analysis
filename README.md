# AirBnb-data-analysis
The following data analysis was made through python and suggests data driven strategy to maximize revenue.
The given dataset is of AirBnb and we have to analyse and explore this dataset to discover important facrtors which affects the customer booking. The above dataset has 48895 rows and 16 coulumns.The duplicate value count is Zero rows and Zero columns. There are 4 columns in dataset which have missing values and those columns are last_review, reviews_per_month, host_name and name.
id--->Airbnb's unique identifier for the listing,

name--->Name of the listing,

host_id--->Airbnb's unique identifier for the host/user,

host_name---->Name of the host. Usually just the first name(s),

neighbourhood_group------>The neighbourhood group as geocoded using the latitude and longitude against neighborhoods as defined by open or public digital shapefiles.

neighbourhood----> Neighbourhood

latitude----> Uses the World Geodetic System (WGS84) projection for latitude and longitude.

longitude-----> Uses the World Geodetic System (WGS84) projection for latitude and longitude.

room_type----> [Entire home/apt|Private room|Shared room|Hotel]

All homes are grouped into the following three room types:

 Entire place: Entire places are best if you're seeking a home away from home. With an entire place, you'll have the whole space to yourself. This usually includes a bedroom, a bathroom, a kitchen, and a separate, dedicated entrance. Hosts should note in the description if they'll be on the property or not (ex: "Host occupies first floor of the home"), and provide further details on the listing.

Private rooms: Private rooms are great for when you prefer a little privacy, and still value a local connection. When you book a private room, you'll have your own private room for sleeping and may share some spaces with others. You might need to walk through indoor spaces that another host or guest may occupy to get to your room.

Shared rooms: Shared rooms are for when you don't mind sharing a space with others. When you book a shared room, you'll be sleeping in a space that is shared with others and share the entire space with other people. Shared rooms are popular among flexible travelers looking for new friends and budget-friendly stays.

price----->daily price in local currency
minimum_nights---->minimum number of night stay for the listing (calendar rules may be different)
number_of_reviews--->The number of reviews the listing has
last_review---->The date of the last/newest review
reviews_per_month----->The number of reviews the listing has per month

calculated_host_listings_count----->The number of listings the host has in the current scrape, in the city/region geography.
We found that highest number of propertys are entire home/apt type which is 51.97 % of the total.Second highest number 45.66 % of the total is private room category.Least available type is shared room that makes only 2.37 % of the total.
From the above data insights we found that Bronx and staten island are underlisted,and entire home /apt rental price is 2.4 times more than that of private rooms.Airbnb can launch host aquisition campaign targetting entire home/apt in those areas.
Manhattan group's average listing price is the highest and Bronx's average listing price is the lowest.
These charts helps Airbnb identify popular neighborhoods to focus marketing, manage supply, and engage with hosts in key markets for optimized business growth.

availability_365----> avaliability_x. The availability of the listing x days in the future as determined by the calendar. Note a listing may not be available because it has been booked by a guest or blocked by the host.
