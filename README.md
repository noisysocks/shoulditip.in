# shoulditip.in

This is the complete code for <http://shoulditip.in/>---a simple website to
help people work out whether or not they're meant to tip in the country they
find theirselves in.

## Why?

I travel quite a lot, and, as an Australian, tipping is a total [foreign
concept][australia] to me. As a result, 'should i tip in [country]' is a common
item in my search history.

[australia]: http://shoulditip.in/australia/

## Who is this for?

My intention is that someone in a bind can very quickly Google 'should i tip in
mexico', find <http://shoulditip.in/mexico/> and have a straightforward
(albeit, not totally nuanced) answer in seconds.

Obviously, tipping is an incredibly elaborate social custom and cannot possibly
be *neatly* summarised into six numbers. I aim only to give a quick, 'good
enough', guide.

## How are you doing this?

My aim is to populate the site by going through this [World Bank list][list] of
countries by number of international tourists one by one, starting with the top
50.

For each country, I try to answer:

* Is tipping customary? (yes/no)
* How much (in local currency, USD or a %) should one tip:
  * Waiters, i.e. someone serving you food
  * Bartenders, i.e. someone serving you a beer
  * Taxi drivers
  * Luggage handlers, i.e. a porter at a hotel
  * Housekeepers, i.e. cleaning staff at a hotel
  * Tour guides, i.e. someone who guides you around, typically for a day

[list]: http://data.worldbank.org/indicator/ST.INT.ARVL?order=wbapi_data_value_2013+wbapi_data_value+wbapi_data_value-last&sort=desc

## How can I help?

The website is just a Jekyll static site hosted with GitHub Pages. All country
data is located in the `_countries` directory---one markdown file per country.
If you can code, submit a Pull Request with corrected country data or data for
a country that we don't have added yet. Otherwise, simply create a new issue
describing what needs to be changed. In either case, try to provide links to
some other sites that back up the numbers that you've described.
