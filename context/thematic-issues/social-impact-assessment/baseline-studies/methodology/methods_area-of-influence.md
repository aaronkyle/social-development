Step 1: Mapping geographical locations of villages [territorial area and ‘pinpoint’ locations]

An early task is to map the locations of every officially-recorded village (called '*desa*' in Indonesian) in the two regions nearest to the project concession area:

* REGION 1: *kabupaten* (regency) Maluku Tenggara Barat (MTB)
* REGION 2: *kabupaten* (regency) Maluku Barat Daya (MBD)

The Government of Indonesia makes village territorial boundaries publicly available as shapefiles.

Based on these, I create "point files" to show the actual location of each village community. That is, the government-provided shapefiles defined village areas, which are large territorial units that extend from the coast into the island’s interior. Our
"point files", by contrast, seeks to identify the actual village settlement area (inhabited village area), which is only a tiny part of the village territory (usually along the coastline).

The immediate task is to get this information into the PostgreSQL database in a meaningful way and to render it in the web application.

NOTE: After our village ‘point’ files have been loaded into the GIS database, we will eventually want to review and improve the accuracy of each marker.

Step 2: Mapping sub-district (*kecamatan*) and regency (*kabupaten*) boundaries and territorial
areas

Below the national government, Indonesia is divided as follows

administrative level 1: province (*provinsi*)

administrative level 2: regency (*kabupaten*) and city (*kota*)

administrative level 3: (sub-)district (*kecamatan*)

administrative level 3: village (*desa* or *kelurahan*)

As noted above, our work will focus on two regencies (*kabupaten*) within Maluku Province:

1. Maluku Tenggara Barat (MTB)

2. Maluku Barat Daya (MBD)

We will need to ensure that the distinction between *kabupaten* is retained in some manner as we
load data into our application. There are many options for doing this, such as using different colour
pallets as we map out villages (more on this in a minute), or simply by mapping in some times to
show where the administrative borders are defined. For the moment, please just keep this need in
mind.

More immediately, we will want to identify sub-district (*kecamatan*) boundaries. As with the village shapefiles, the immediate task is to get this information into the PostgreSQL database in a meaningful way and to render it in the web
application.

Step 3: Creating Useful Visual Effects for Looking at Villages and Higher-Level Administrative Areas

As suggested above, once we have loaded in the village and kecamatan for both MTB and MBD, our
next task is to find an aesthetic way present this information.

One way we have attempted to do this for MTB was to colorize the shapefile polygons (please refer
to the Google Earth package for an example). We like this approach, but we also encourage your
creative thinking about how to best visualize villages, sub-districts, and regencies in the context of
our map application. For example, it might help to include a slider option to increase and decrease
transparency of fill layers, and also to allow the villages and overlay the sub-districts, and for both
villages and sub-districts to overlay the regency divisions, so that the sum of all overlays has the two
regions in slightly different base colors, and all sub-districts (i.e. mainting the visual distinction).
NOTE: With the Google Earth files, we duplicated some of the village information so that we could
see just the boundaries of the villages and sub-districts without any "color fill". This choice was
made simply to enable multiple "views" of the village boundaries; it is not necessary to duplicate
data in this way for our web application.

Step 4: Loading and Visualizing Population Data

PLEASE NOTE: Village population data for MTB and MDB should already be included within the
shapefile data tables. Some of this information, however, is inaccurate. We may call on you to help
explain how to update, correct, and maintain data embedded in shapefiles, including instructions on
how to access and change this information in the database.

Current (and corrected) village population data Data for MTB and MDB is available as a speadsheet
file on Google Drive.

Once all the shapefiles are loaded in, we will want to develop a few different ways to visualize the
relative sizes of village and to allow users to toggle between these views. Some approaches we’ve
considered include:

1. scaling village name size; for example, to make the names of larger villages (i.e. Olit, Saumlaki, and Adaut) appear proportionately larger than other villages. 


2. scaling circles of various sizes that correspond to the ‘pinpoint’ village locations described in
Step 1; that is, to scale the village "dot" / "pinpoint" indicators to be larger or smaller
relative to population size (i.e. making relatively larger or smaller circles that are
proportionate to the population size of each village. [In the below example / mockup, I
distinguished only 3 tiers, but ideally we'd want a graduated scale that reflects more
precisely the differences].

3. creating a graduated choloropleth scale

Some concepts to consider in terms of the actual mechanics of the web
application:

CONCEPT 1: It would be terrific if we could enable relative village sizes (as corresponding
scale keys) to change dynamically based on the relative viewing window, so that if a person
is zoomed in on MTB she or he would see village point files scaled in relation to MTB villages,
but if zooming out to show both MTB and MDB, those scales would refresh and change.

CONCEPT 2: In the case that we can’t get the dynamic scale to work appropriately, it would
still be helpful if we could set specific scales depending on whether a person is looking at
viewing space that shows only MTB, only MDB or both (e.g. ‘regional view’), and then to
define set, custom scales depending on the view. For example, in this mockup we have a
view of all of Maluku province. If it were cleaner and easier to read, this map would reflect
that within MDB three is only 1 village of any size comparable to Olit, Saumlaki, and Adaut.

 CONCEPT 3: If neither of the above are feasible (or if they simply don’t make sense), you’re
welcome to propose your own design concept. In so doing, please keep in mind that we are
interested to look at sizes within a single province (e.g. MTB) as well as to compare
population size across multiple provinces (e.g., MTB and MDB).

NOTE: In the Google Earth files, we attempted to create an easy mechanism to allow users to
identify small and large villages by grouping them in folders (which can be toggled on and off) by
"arithmetic quartile". While this is a somewhat arbitrary size division, it still possesses some value
for the purposes of project planning. The Google Earth files were a bit "rough" in terms of how the
village labels are shown (i.e. some of the renderings of the labels create a lot of visual clutter, and
also we appear to still have some duplication of information like the village names, as evinced in
your current model). We’re looking for a more elegant solution for the web app.

Step 5: Plotting in the project area

Step 6: Adding in additional information
With our basic work done of mapping in villages and higher-level administrative areas, and also
having linked in the population data, we can turn our attention to adding in other information and
markers about geographic features of the region. For example, we can note the locations, name (and
maybe even sizes) of ports, airports, roads, etc. We can also flag certain areas as potential sites of
construction activity. We should also be sure to add in the names of islands, etc.

Ideally, we’d want to be able to toggle on and off these additional markers individually.
