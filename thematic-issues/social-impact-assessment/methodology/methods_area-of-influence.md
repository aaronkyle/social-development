# area of influence

**Defining the Project Area of Influence for a Social Development Initiative**

### **Step 1: Mapping Geographical Locations of Villages**

###

An essential initial task in defining the project's area of influence is the accurate mapping of all officially recorded villages (*desa*) within the two regencies closest to the project concession area:

* **Region 1**: *Kabupaten* Maluku Tenggara Barat (MTB)
* **Region 2**: *Kabupaten* Maluku Barat Daya (MBD)

The Government of Indonesia provides village territorial boundaries in the form of publicly available shapefiles. These shapefiles delineate extensive village territories that often stretch from coastal regions into the interior. However, our objective is to generate "point files" to mark the actual inhabited areas of these villages, which are typically concentrated along the coastline.

The immediate technical task involves integrating this data into a PostgreSQL database to facilitate its visualization within a web-based application. It is important to note that once village point files have been uploaded into the GIS database, further review and refinement will be necessary to enhance the accuracy of the markers.

### **Step 2: Mapping Sub-District (** ***Kecamatan*** **) and Regency (** ***Kabupaten*** **) Boundaries**

###

Indonesia's administrative structure consists of the following levels:

1. **Province (** ***Provinsi*** **)**
2. **Regency (** ***Kabupaten*** **) and City (** ***Kota*** **)**
3. **Sub-District (** ***Kecamatan*** **)**
4. **Village (** ***Desa*** **or** ***Kelurahan*** **)**

As noted earlier, this project is concentrated on two regencies within Maluku Province: MTB and MBD. It is crucial to maintain clear distinctions between these regencies when integrating the data into the application. This can be achieved through various mapping techniques, such as differentiated color palettes or the inclusion of administrative border overlays.

In addition to regency-level delineations, sub-district (*kecamatan*) boundaries will also need to be mapped. Similar to the village shapefiles, this information will be loaded into the PostgreSQL database and rendered in the web application for enhanced accessibility and analysis.

### **Step 3: Enhancing Visual Representation of Villages and Administrative Divisions**

###

Once the village and sub-district data for MTB and MBD have been integrated, the next step is to design an effective visualization strategy.

One approach, previously employed for MTB, involves colorizing shapefile polygons to distinguish various administrative levels. Additional visualization techniques could include:

* Implementing a transparency slider to allow users to toggle between different administrative layers.
* Enabling overlays to distinguish village, sub-district, and regency boundaries while maintaining their relative visibility.
* Providing multiple viewing modes, such as boundary-only views versus filled color maps.

Google Earth files previously used for visualization included duplicated village data to facilitate multiple viewing modes. However, such redundancy is unnecessary for the web application and should be streamlined to improve user experience.

### **Step 4: Incorporating and Displaying Population Data**

###

The available village shapefiles for MTB and MBD contain population data, though some of this information may require verification and correction. The most up-to-date population figures are stored in a Google Drive spreadsheet, and integration of this dataset into the database will be required.

Once the population data is loaded, different visualization techniques can be explored, such as:

1. **Scaling village name sizes** to reflect relative population sizes.
2. **Using proportional circle indicators** at pinpointed village locations to visually represent population density.
3. **Applying a graduated choropleth scale** to depict population distribution across the region.

**Concepts for Consideration:**

* **Dynamic scaling**: Adjusting village markers dynamically based on the zoom level of the map to ensure legibility and proportional representation.
* **Context-dependent scaling**: Allowing different visualization modes based on whether the user is viewing a single regency or both regencies simultaneously.
* **Alternative design solutions**: Implementing an approach that allows for easy comparison of village sizes within and across regencies, while ensuring readability and usability.

In previous Google Earth models, an arithmetic quartile-based classification system was used to group villages by size. While this approach was functional, it created visual clutter and redundancy. The web application should seek a more refined and interactive method to convey population data.

### **Step 5: Defining the Project Area**

###

Once the foundational geographical and demographic data have been mapped, the next step is to delineate the specific project area. This involves identifying and marking relevant locations within the project’s sphere of influence. The project area may be determined based on proximity to key village settlements, transportation access, and other socio-economic factors.

### **Step 6: Integrating Additional Geographic and Infrastructure Data**

###

With the primary mapping completed, the project can extend to incorporating other relevant geographic features, such as:

* Ports
* Airports
* Roads
* Construction activity sites
* Island names and locations

A user-friendly feature for toggling these additional layers on and off should be implemented to allow for flexible data exploration.

### **Conclusion**

###

The process of defining the project’s area of influence involves a structured approach to mapping villages, administrative boundaries, and population data, followed by the integration of key infrastructure elements. The ultimate goal is to develop a functional and visually effective web-based GIS tool that facilitates informed decision-making for social development planning. Future refinements will focus on enhancing data accuracy, improving visual representation, and ensuring the accessibility of critical information for project stakeholders.