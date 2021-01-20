# Awesome-flights-apis
List of all current info for flight apis
Overview - https://www.altexsoft.com/blog/engineering/airline-flight-booking-apis-gdss-specialized-data-providers-otas-and-metasearch-engines/

### Inspiration
Information about flight APIs seems to be scattered. I wanted to do a project using flight data - and it took a significant amount of research time to figure out what I wanted to do wasn't realistic. 

The biggest issue is that each of the flight API's only use a subset of the total airlines. This obviously makes it harder to find the cheapest & most convient route. On some of the flight API's (like skyscanner) there is a very small rate limit, making it infeasable for doing clever searchs. 

There are really three options you can take moving forward.
1. GDSs
2. Flight API Aggregators
3. Direct Integrations

## Worldwide flight aggregators [GDSs] 
These are going to be more complex to integrate with - but have more supported airlines
* [Amadeus](https://developers.amadeus.com/self-serviced)\
Flights from low-cost carriers are currently unavailable.\
Flights from American Airlines are currently unavailable.
* [Sabre](https://developer.sabre.com/homed)
* [Travelport](https://support.travelport.com/webhelp/uapi/uAPI.htm#Introduction.htm%3FTocPath%3D_____1d)

## Avaliable flight API Aggregators:
* [Google Flights API](https://news.ycombinator.com/item?id[15594975d) - Depriciated
* [Skyscanner](https://www.partners.skyscanner.net/affiliates/travel-apisd) - You need to be accepted as a partner to use their API. I personally got declined, but you may have better luck. 
* [FlightAPI](https://www.flightapi.io/docs/d)

## Direct Integrations
* [British Airways] (https://developer.iairgroup.com/british_airwaysd)
