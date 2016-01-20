# [boundaries.seattle.io](http://boundaries.seattle.io)

Wondering if a point is inside a city park? Know your latitude and longitude but not sure which city council district you're in?
Want to know all the Seattle-related boundaries that a point is inside?

Send a request like this:

```
http://boundaries.seattle.io/boundaries?long=-122.345002&lat=47.667044
```

Get a `FeatureCollection` of the matching features from each dataset in response.

Additionally, you can append the extension `.topojson` to receive the response back in [TopoJSON](https://github.com/mbostock/topojson), e.g., the previous request would become `http://boundaries.seattle.io/boundaries.topojson?long=-122.345002&lat=47.667044`.

## See also
- [seattle-boundaries](https://github.com/openseattle/seattle-boundaries) – the collection of geojson boundaries this server uses
