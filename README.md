# MappingSpecification
Spec for interpreting data available on USGS website... www.usgs.org

Interprete freely available data from www.usgs.org

The programming language will be Java and I will specifically use the javafx libraries.

Draw a map with visible cues to slope with grades being marked and decernable in
1 degree implements from 0-10 or 20.

Bonus would be to identify and fill in bodies of water.

sample files in 
03/23/2015  04:57 PM        45,258,553 n43w072.zip

floatn43w072_1.flt
	Looks all binary,  Heights
	          look at hdr file, 3612*3612 * sizeof(float) = size of this file exactly.

floatn43w072_1.hdr
	Text file explaining coordinstes for lower left corner, size of each cell/Pixel?  No Data Value, endian 
		and number of rows and columns.
                   Little Endian.  41.998333333 degrees North, 72.0016666667 degrees West  3612 cols, 3612 rows

floatn43w072_1.prj
        ASCII  basic info, projection, zunits in meters, 

floatn43w072_1_thumb.jpg
	Thumbnail image of the data rendered...


n43w072.zip
	Downloaded from usgs website

n43w072_1_meta.dbf
	A large spreadsheet with town names, and lots of data

n43w072_1_meta.html
	page with some info and links....

n43w072_1_meta.prj
	ASCII file with some information about this data

n43w072_1_meta.sbn size=1,148
	Binary File, not sure....

n43w072_1_meta.sbx
	Binary File  size=228

n43w072_1_meta.shp
	Binary file size=119,460
		Shape file for overlaying metadata, towns, and other info?

n43w072_1_meta.shp.xml
	Looks info about when files were created, etc...

n43w072_1_meta.shx
	Binary file size=900

n43w072_1_meta.txt
	Text file, same as n43w072_1_meta.xml

n43w072_1_meta.xml
	Looks like licensing info and request to acknowledge usgs for the data 

ned_1arcsec_g.dbf
	Looks like a spread sheet listing all the available 1x1 degree maps available and their file names

ned_1arcsec_g.prj
	ASCII looks like info about this stuff, Copyright

ned_1arcsec_g.sbn
	Binary file of size=16,724

ned_1arcsec_g.sbx
	Binary file of size=484

ned_1arcsec_g.shp
	Binary file of size=242,860

ned_1arcsec_g.shx
	Binary file of size=14,380

NED_DataDictionary.url
	URL to file NED_DataDictionary.pdf
readme.pdf
