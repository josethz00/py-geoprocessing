# Python GeoProcessing

## Data Types in GeoProcessing

- vector data
- raster data
- alphanumeric

### Vector Data

- points
- lines
- polygons

Vector data is stored as a series of x,y coordinates.  Each point is a pair of x,y coordinates.  A line is a series of points.  A polygon is a series of points that are connected to form a closed shape.

### Raster Data

Raster data is stored as a grid of cells.  It is like a matrix.  Each cell has a value.  The value could be a number, a category, or a color.  Raster data is used to represent continuous phenomena such as elevation, temperature, or precipitation.

### Alphanumeric (Tabular)

Alphanumeric data is stored in a table.  Each row is a record.  Each column is a field.  A field is a single piece of information.  A record is a collection of fields.  A table is a collection of records.

## CRS (Coordinate Reference System)

A coordinate reference system (CRS) is a coordinate-based local, regional or global system used to locate geographical entities.  A CRS is defined by a datum and a projection.  A datum is a model of the earth.  A projection is a method for transforming the earth's curved surface into a flat surface.

### Datum examples

- WGS84: World Geodetic System 1984 is a global datum that is used by GPS.
- NAD83: North American Datum 1983 is a regional datum that is used by the US, Canada, and Mexico.
- NAD27: North American Datum 1927 is a regional datum that is used by the US, Canada, and Mexico.
- NAD83 (CSRS): North American Datum 1983 (Canadian Spatial Reference System) is a regional datum that is used by Canada.

### Projection examples

- UTM: Universal Transverse Mercator is a global projection that is used by the USGS.
- State Plane: State Plane is a regional projection that is used by the USGS.
- Albers Equal Area: Albers Equal Area is a regional projection that is used by the USGS.

_Note: USGS = United States Geological Survey_