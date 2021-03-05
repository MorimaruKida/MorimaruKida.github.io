---
layout: page
title: Study site
subtitle: Map of past and present study sites 
---
<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2" xmlns:gx="http://www.google.com/kml/ext/2.2" xmlns:kml="http://www.opengis.net/kml/2.2" xmlns:atom="http://www.w3.org/2005/Atom">
<Document>
	<name>KmlFile</name>
	<Schema name="AntarcticGPS for Google Earth" id="S_AntarcticGPS_for_Google_Earth_SDD0">
		<SimpleField type="string" name="Lake_name"><displayName>&lt;b&gt;Lake name&lt;/b&gt;</displayName>
</SimpleField>
		<SimpleField type="double" name="Lat_"><displayName>&lt;b&gt;Lat.&lt;/b&gt;</displayName>
</SimpleField>
		<SimpleField type="double" name="Long_"><displayName>&lt;b&gt;Long.&lt;/b&gt;</displayName>
</SimpleField>
	</Schema>
	<Style id="hlightPointStyle2">
		<IconStyle>
			<Icon>
				<href>http://maps.google.com/mapfiles/kml/shapes/placemark_circle_highlight.png</href>
			</Icon>
		</IconStyle>
		<BalloonStyle>
			<text><![CDATA[<table border="0">
  <tr><td><b>Lake name</b></td><td>$[AntarcticGPS for Google Earth/Lake_name]</td></tr>
  <tr><td><b>Lat.</b></td><td>$[AntarcticGPS for Google Earth/Lat_]</td></tr>
  <tr><td><b>Long.</b></td><td>$[AntarcticGPS for Google Earth/Long_]</td></tr>
</table>]]></text>
		</BalloonStyle>
	</Style>
	<Style id="normPointStyle2">
		<IconStyle>
			<Icon>
				<href>http://maps.google.com/mapfiles/kml/shapes/placemark_circle.png</href>
			</Icon>
		</IconStyle>
		<BalloonStyle>
			<text><![CDATA[<table border="0">
  <tr><td><b>Lake name</b></td><td>$[AntarcticGPS for Google Earth/Lake_name]</td></tr>
  <tr><td><b>Lat.</b></td><td>$[AntarcticGPS for Google Earth/Lat_]</td></tr>
  <tr><td><b>Long.</b></td><td>$[AntarcticGPS for Google Earth/Long_]</td></tr>
</table>]]></text>
		</BalloonStyle>
	</Style>
	<StyleMap id="pointStyleMap2">
		<Pair>
			<key>normal</key>
			<styleUrl>#normPointStyle2</styleUrl>
		</Pair>
		<Pair>
			<key>highlight</key>
			<styleUrl>#hlightPointStyle2</styleUrl>
		</Pair>
	</StyleMap>
	<Folder id="layer 0">
		<name>AntarcticGPS for Google Earth</name>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">A-5</SimpleData>
					<SimpleData name="Lat_">-69.493</SimpleData>
					<SimpleData name="Long_">39.6031</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.60315,-69.49299999999998,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">HAMAGIKU</SimpleData>
					<SimpleData name="Lat_">-69.4906</SimpleData>
					<SimpleData name="Long_">39.6012</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.60124,-69.49059999999999,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Amundsen Lake1</SimpleData>
					<SimpleData name="Lat_">-66.7771</SimpleData>
					<SimpleData name="Long_">50.5692</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>50.56920999999997,-66.77713,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Amundsen Lake2</SimpleData>
					<SimpleData name="Lat_">-66.7889</SimpleData>
					<SimpleData name="Long_">50.5638</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>50.56383,-66.78888000000001,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Amundsen Lake3</SimpleData>
					<SimpleData name="Lat_">-66.7897</SimpleData>
					<SimpleData name="Long_">50.5526</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>50.55261999999998,-66.78975,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">BOSATSU</SimpleData>
					<SimpleData name="Lat_">-69.4781</SimpleData>
					<SimpleData name="Long_">39.572</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.57204,-69.47806,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">BRVAGNIPA LAKE1</SimpleData>
					<SimpleData name="Lat_">-69.3605</SimpleData>
					<SimpleData name="Long_">39.8334</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.83343000000001,-69.36045,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">EBI</SimpleData>
					<SimpleData name="Lat_">-69.4943</SimpleData>
					<SimpleData name="Long_">39.6096</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.60961,-69.49435,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">FUNAZOKO</SimpleData>
					<SimpleData name="Lat_">-69.4454</SimpleData>
					<SimpleData name="Long_">39.5588</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.55880999999999,-69.44541000000001,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Glacial Lake</SimpleData>
					<SimpleData name="Lat_">-69.6834</SimpleData>
					<SimpleData name="Long_">39.4848</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.48477,-69.68343,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Glacial Water</SimpleData>
					<SimpleData name="Lat_">-69.6848</SimpleData>
					<SimpleData name="Long_">39.481</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.48103000000002,-69.68481,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">HASHIOKI</SimpleData>
					<SimpleData name="Lat_">-69.4789</SimpleData>
					<SimpleData name="Long_">39.6513</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.65127999999999,-69.47893000000001,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">HECHIMA</SimpleData>
					<SimpleData name="Lat_">-69.487</SimpleData>
					<SimpleData name="Long_">39.6279</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.62794000000001,-69.48701,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">HIMAGO</SimpleData>
					<SimpleData name="Lat_">-69.4738</SimpleData>
					<SimpleData name="Long_">39.62</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.61999000000002,-69.47382,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">HIROE</SimpleData>
					<SimpleData name="Lat_">-69.351</SimpleData>
					<SimpleData name="Long_">39.8009</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.80092999999999,-69.351,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">HOTOKE</SimpleData>
					<SimpleData name="Lat_">-69.4765</SimpleData>
					<SimpleData name="Long_">39.561</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.56097000000001,-69.4765,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">HYOTAN</SimpleData>
					<SimpleData name="Lat_">-69.4856</SimpleData>
					<SimpleData name="Long_">39.6135</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.61346000000001,-69.48559000000002,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">JIZOU</SimpleData>
					<SimpleData name="Lat_">-69.4793</SimpleData>
					<SimpleData name="Long_">39.5733</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.57327000000002,-69.47933999999999,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">KIKUNO</SimpleData>
					<SimpleData name="Lat_">-69.4865</SimpleData>
					<SimpleData name="Long_">39.5901</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.59007,-69.48645,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">KOBACHI</SimpleData>
					<SimpleData name="Lat_">-69.4837</SimpleData>
					<SimpleData name="Long_">39.6415</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.64149,-69.48372000000001,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">KUMOGATA</SimpleData>
					<SimpleData name="Lat_">-69.4535</SimpleData>
					<SimpleData name="Long_">39.5768</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.57679000000002,-69.45354,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">KUWAI</SimpleData>
					<SimpleData name="Lat_">-69.4744</SimpleData>
					<SimpleData name="Long_">39.5713</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.57127999999999,-69.47437999999998,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">MAGO</SimpleData>
					<SimpleData name="Lat_">-69.4729</SimpleData>
					<SimpleData name="Long_">39.6259</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.62594,-69.47292000000002,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">MAGOBACHI</SimpleData>
					<SimpleData name="Lat_">-69.4879</SimpleData>
					<SimpleData name="Long_">39.6414</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.64135999999999,-69.4879,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">MARUWAN KITA</SimpleData>
					<SimpleData name="Lat_">-69.9053</SimpleData>
					<SimpleData name="Long_">39.0453</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.04525000000002,-69.90532,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">MARUWAN MINAMI</SimpleData>
					<SimpleData name="Lat_">-69.9095</SimpleData>
					<SimpleData name="Long_">39.0402</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.04023000000001,-69.90952,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">MARUWAN OIKE</SimpleData>
					<SimpleData name="Lat_">-69.9086</SimpleData>
					<SimpleData name="Long_">39.0431</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.04311000000001,-69.90864000000001,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">MISUMI</SimpleData>
					<SimpleData name="Lat_">-69.4925</SimpleData>
					<SimpleData name="Long_">39.642</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.64202999999999,-69.49248,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">MITSUIKE NAKA</SimpleData>
					<SimpleData name="Lat_">-69.2517</SimpleData>
					<SimpleData name="Long_">39.7303</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.73027999999999,-69.25169,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">MITSUIKE SHITA</SimpleData>
					<SimpleData name="Lat_">-69.2504</SimpleData>
					<SimpleData name="Long_">39.728</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.72799000000001,-69.2504,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">MITSUIKE UE</SimpleData>
					<SimpleData name="Lat_">-69.2532</SimpleData>
					<SimpleData name="Long_">39.7321</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.73205,-69.25319,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">NAGA</SimpleData>
					<SimpleData name="Lat_">-69.4873</SimpleData>
					<SimpleData name="Long_">39.5974</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.59736000000002,-69.4873,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">NURUME</SimpleData>
					<SimpleData name="Lat_">-69.2232</SimpleData>
					<SimpleData name="Long_">39.6591</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.65906000000003,-69.22317,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">NYORAI</SimpleData>
					<SimpleData name="Lat_">-69.4776</SimpleData>
					<SimpleData name="Long_">39.5678</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.56783000000003,-69.47765000000001,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">OYAKO</SimpleData>
					<SimpleData name="Lat_">-69.4755</SimpleData>
					<SimpleData name="Long_">39.6018</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.60176000000001,-69.47552,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Richardson</SimpleData>
					<SimpleData name="Lat_">-66.7746</SimpleData>
					<SimpleData name="Long_">50.6015</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>50.60150999999999,-66.77463999999999,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">SARA</SimpleData>
					<SimpleData name="Lat_">-69.4813</SimpleData>
					<SimpleData name="Long_">39.6558</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.65575999999997,-69.48125000000002,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Skallen Lake1</SimpleData>
					<SimpleData name="Lat_">-69.6847</SimpleData>
					<SimpleData name="Long_">39.4716</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.47165000000001,-69.68468999999999,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Skallen Lake2</SimpleData>
					<SimpleData name="Lat_">-69.6845</SimpleData>
					<SimpleData name="Long_">39.4644</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.46443999999998,-69.68451000000002,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Skallen Lake3</SimpleData>
					<SimpleData name="Lat_">-69.6577</SimpleData>
					<SimpleData name="Long_">39.4035</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.40352999999999,-69.65772,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Skallen Lake4</SimpleData>
					<SimpleData name="Lat_">-69.6469</SimpleData>
					<SimpleData name="Long_">39.4331</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.43309999999998,-69.6469,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Skallen Lake5</SimpleData>
					<SimpleData name="Lat_">-69.6647</SimpleData>
					<SimpleData name="Long_">39.4195</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.41953000000002,-69.66471,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">Skallen Oike</SimpleData>
					<SimpleData name="Lat_">-69.6717</SimpleData>
					<SimpleData name="Long_">39.414</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.41402999999998,-69.67168000000001,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">SKARVSNES LAKE2</SimpleData>
					<SimpleData name="Lat_">-69.4951</SimpleData>
					<SimpleData name="Long_">39.6051</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.60507000000003,-69.49513,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">SURIBACHI</SimpleData>
					<SimpleData name="Lat_">-69.485</SimpleData>
					<SimpleData name="Long_">39.6717</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.67169999999999,-69.48502999999999,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">TOKKURI</SimpleData>
					<SimpleData name="Lat_">-69.4563</SimpleData>
					<SimpleData name="Long_">39.5811</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.58106,-69.45630999999999,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YATSUDE 1</SimpleData>
					<SimpleData name="Lat_">-69.262</SimpleData>
					<SimpleData name="Long_">39.7873</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.78727000000002,-69.26201,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YATSUDE 2 HEITOU</SimpleData>
					<SimpleData name="Lat_">-69.2577</SimpleData>
					<SimpleData name="Long_">39.7755</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.77546999999998,-69.25769,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YATSUDE 3</SimpleData>
					<SimpleData name="Lat_">-69.2533</SimpleData>
					<SimpleData name="Long_">39.7662</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.76625000000003,-69.25331,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YATSUDE 4</SimpleData>
					<SimpleData name="Lat_">-69.2527</SimpleData>
					<SimpleData name="Long_">39.7646</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.76462000000001,-69.25268,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YATSUDE 5</SimpleData>
					<SimpleData name="Lat_">-69.2517</SimpleData>
					<SimpleData name="Long_">39.7606</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.76064,-69.25172999999999,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YATSUDE 6</SimpleData>
					<SimpleData name="Lat_">-69.2494</SimpleData>
					<SimpleData name="Long_">39.7505</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.75051000000001,-69.24942,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YATSUDE 7</SimpleData>
					<SimpleData name="Lat_">-69.2475</SimpleData>
					<SimpleData name="Long_">39.7438</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.74376000000002,-69.24751999999999,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YATSUDE 8</SimpleData>
					<SimpleData name="Lat_">-69.2453</SimpleData>
					<SimpleData name="Long_">39.7338</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.73379000000001,-69.24531000000002,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YATSUDE 9</SimpleData>
					<SimpleData name="Lat_">-69.2442</SimpleData>
					<SimpleData name="Long_">39.72</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.71998000000001,-69.24416000000001,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YUKIDORI 1</SimpleData>
					<SimpleData name="Lat_">-69.2411</SimpleData>
					<SimpleData name="Long_">39.7799</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.77994999999999,-69.24105,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YUKIDORI 2</SimpleData>
					<SimpleData name="Lat_">-69.2407</SimpleData>
					<SimpleData name="Long_">39.7779</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.77784999999998,-69.24071999999998,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YUKIDORI 3</SimpleData>
					<SimpleData name="Lat_">-69.2405</SimpleData>
					<SimpleData name="Long_">39.7717</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.77172000000002,-69.24052,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YUKIDORI 4</SimpleData>
					<SimpleData name="Lat_">-69.2406</SimpleData>
					<SimpleData name="Long_">39.7635</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.76346999999998,-69.24057000000001,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YUKIDORI 5 Yukidori</SimpleData>
					<SimpleData name="Lat_">-69.2396</SimpleData>
					<SimpleData name="Long_">39.7598</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.75976000000001,-69.23961,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YUKIDORI 6</SimpleData>
					<SimpleData name="Lat_">-69.2408</SimpleData>
					<SimpleData name="Long_">39.753</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.753,-69.24075000000002,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YUKIDORI 7</SimpleData>
					<SimpleData name="Lat_">-69.2409</SimpleData>
					<SimpleData name="Long_">39.7445</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.74454000000002,-69.2409,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YUKIDORI 8</SimpleData>
					<SimpleData name="Lat_">-69.2417</SimpleData>
					<SimpleData name="Long_">39.7313</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.73134000000001,-69.24173999999999,0</coordinates>
			</Point>
		</Placemark>
		<Placemark>
			<styleUrl>#pointStyleMap2</styleUrl>
			<ExtendedData>
				<SchemaData schemaUrl="#S_AntarcticGPS_for_Google_Earth_SDD0">
					<SimpleData name="Lake_name">YUKIDORI 9</SimpleData>
					<SimpleData name="Lat_">-69.2423</SimpleData>
					<SimpleData name="Long_">39.7184</SimpleData>
				</SchemaData>
			</ExtendedData>
			<Point>
				<coordinates>39.71842000000003,-69.24226000000002,0</coordinates>
			</Point>
		</Placemark>
	</Folder>
</Document>
</kml>
