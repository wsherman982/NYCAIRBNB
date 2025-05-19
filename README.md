NYC Airbnb 2024 – Simple Final Report
1 | Missing Data
license column – 85 % empty → I ignored it.

price – 41 % empty → I kept only rows that have a price.

last review and review‑related numbers – about 30 % empty → I filled these using the reviews file.

host_name and name – almost no gaps.

id – no gaps; safe to use as the main key.

2 | Typical Nightly Price
Most listings cost about $150 per night.
(I found this from the tallest bar in the price chart.)

3 | Price by Room Type
Room type	Middle price
Entire home/apt	$350
Private room	$110
Shared room / hotel	lower but few samples

Entire homes cost roughly three times more than private rooms.

4 | Reviews vs. Price
Many listings have only 1–2 reviews but can cost anywhere from $20 to $2 500.

Listings with lots of reviews (100+) usually sit between $100 and $400 – guests trust them more, so hosts can charge extra.

Cheaper crowd: lots of places under $100 have few reviews.

5 | Where Prices Are Highest
My heat‑map shows:

Manhattan (SoHo, West Village, Tribeca) is the priciest.

Brooklyn waterfront (Williamsburg, DUMBO) comes next.

Outer areas in Queens, the Bronx, and far‑east Brooklyn are cheaper.

6 | What to Do with This
Hosts

New hosts could set a private‑room price around $90–$120 to match the busy part of the market.

If you already have 100+ reviews, you can safely price 20 % above your area average.

Data users

Drop the license column.

Keep only rows with a valid price.

Build price models with: room type, borough, latitude/longitude, review count, availability, etc.
