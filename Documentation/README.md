# North London Line

This is a representation of the North London Line around the year 2023,
at this time the route is operated by Transport for London as part of the London Overground network.
Included within the simulation is the full route from Stratford to Richmond via Gospel Oak. Also included is the Gospel Oak to Barking Line as far as Barking, and the West London Line between Willesden Junction and Imperial Wharf.
The included timetable provides a challenge with a few services already present on the map right from the the 05:30am start time.

The North London Line has evolved over the years, up until the late 1980s services also commenced at the now long since demolished London terminus of Broad Street. After the closure of the Broad Street to Dalston Junction
services continued to operate from Richmond to the SouthWest of the capital, and North Woolwich in the east. Operations on the line were taken over in 1986 by Silverlink trains under their Metro franchise, which also included West London Line services
from Willesden Junction to Clapham Junction, Gospel Oak to Barking Line services (the route at this time being unelectrified), and Watford DC Line services from London Euston to Watford Junction.
From 2007 Transport for London took over all four routes which became part of its London Overground services. From 2010 the section of line between Shoreditch just north of Broad Street and
Dalston Junction was re-opened to form part of the East London Line section with trains running onward to West Croydon and Crystal Palace. In 2018 the Gospel Oak to Barking Line was electrified with electric trains commencing operation
in 2019, the line was extended beyond Barking to the new terminus of Barking Riverside in 2022.

As well as passengers services the network pays host to a range of interregional freight movements, providing an important corridor for routing freight across the city and connecting the north of the country with industry in the south.

## Simulation

Included within this simulation is a detailed timetable set on a weekday in 2023, this includes both passenger and freight services, as well as empty stock movements. It is highly recommended that the session file be used, and the simulation
run at a speed of at the most 1x considering the service density.


### Tips

Control of the North London Line is a challenge:

* Close attention must be paid to not only the destination of services but also the time at which they are due. It is common for services to not be due at their next location for some time, meaning despite RailOS indicating they are awaiting a clear route, these services should instead be held at their current location in order to allow a higher priority service to pass.
* Pay close attention to services entering from the directory of Tilbury/Barking Riverside via Barking station. Only one service can pass along this line at a time, in general services alternate in direction. Services from Woodgrange Park are usually held at this location to await those coming from Barking.
* Note the level crossing near Mitre Bridge Jn, you should aim to open this crossing in time for services coming from Wembley. As a rule, try to keep an eye on all entry points.
* Make sure to route services correctly at Willesden Junction, Gunnersbury Junction, Mitre Bridge Junction and Gospel Oak.
* Caledonian Road & Barnsbury is an island platform station, make sure to route stopping services correctly. Also make sure services which are timetabled to pause at Westbourne Road Junction do not block passenger trains.
* Acton Wells Junction has quite a few freight services entering then leaving the map (a couple even re-enter to/from Mitre Bridge Junction).
* At Kensington (Olympia) passenger services heading towards Shepherd's Bush are routed into the platform (see timetable). Freight services are sent along the central bypass.
* At any one time, no fewer than 5 services may state they require attention, however they may all not yet be due. Just because there is lots of flashing does not mean you are doing badly! Focus on keeping services on time as opposed to all "happy".


## Development

This simulation features an event rich timetable. I have not had enough time to test the whole four and a half hours of simulated timetable. If you come across any issues please do either open an issue or contact me via Discord.
