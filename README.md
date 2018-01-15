# MobiVoc: Open Mobility Vocabulary

MobiVoc is an open vocabulary for future-oriented mobility solutions.

New mobility concepts and better data networking are both crucial factors for
global economic development. To invent innovative and sustainable mobility
concepts, new data-based value-added services are required.

Our goal is to significantly improve the data mobility between all stakeholders by providing a standardized vocabulary using Semantic Web technologies and ontologies. 
For the open vocabulary covering various mobility aspects we use RDF (Resource Description Framework) - a recommended specification of the World Wide Web Consortium (W3C) and the so-called lingua franca for the integration of data and web. 
We invite everyone who is interested to join our MobiVoc initiative and to participate in the development of the Open Mobility Vocabulary.

## Class diagram

![Class diagram](diagrams/mobivoc.png "Mobivoc class diagram")

Further diagrams can be found in the [diagrams folder](diagrams).

## Example data

An example dataset on how to represent charging points is given in [OpenChargeMap.ttl](examples/OpenChargeMap.ttl). Data is taken from OpenChargeMap for the cities of Brussels, Lyon and Helsinki. The dataset is licensed CC BY-SA 4.0.

The API call used to retrieve the individual datasets is:

`https://api.openchargemap.io/v2/poi/?output=json&maxresults=1000&opendata=true&latitude=50.8504500&longitude=4.3487800&distance=20&distanceunit=km`

## Files

### Schema

* [schema/Metadata.ttl](schema/Metadata.ttl) - ontology metadata
* [schema/Core.ttl](schema/Core.ttl) - core classes and properties
* [schema/Parking.ttl](schema/Parking.ttl) - parking facilities and parking places
* [schema/ChargingPoints.ttl](schema/ChargingPoints.ttl) - charging stations

### Examples

* [examples/OpenChargeMap.ttl](examples/OpenChargeMap.ttl) - Example instances for charging stations

## Further links:

* homepage: [http://mobivoc.org](http://mobivoc.org)
* schema page and namespace: [http://schema.mobivoc.org/](http://schema.mobivoc.org/)
* suggested prefix: `mv`

