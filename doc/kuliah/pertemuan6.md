
In my post yesterday we've talked about creating geospatial data using python programming language, while do as follows

first use the method to create a shapefile with the method Writer ()
Import shapefiles
Sf = shapefile.writer (shapeType = 1)
Sf = field ( 'NAME', 'C', '40')
Sf = field ( 'OWNER', 'C', '40')
Sf = record ( 'Spanish', 'Burasa')
Sf = point (10:10)
Sf.save ( 'restoran.shp')
Exit ().

then for the method edit using Editor ()
Import shapefiles
Sf = sahefile.Editor ( 'res.shp')
Sf = point (16,10,0,0)
Sf = record ( 'Restaurants Padang')
Sf = save ()
Sf = save ( 'res.shp')
A = shapefile.Reader ( 'res, shp')
A = records ()
A.shapes (). Points
A.shapes () [0]
A.shapes () [0] Points
[[10.0,10,0]]

while to delete the message
Sf.Delete (0)
A.shapes () [0] .Points
[[10,0,10,0]]
Sf = Point (16,10,0,0)
Sf = record ( 'Restaurants Padang')
