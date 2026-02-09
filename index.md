# Thermoluminescence Dating: A Guide to Good Practice

2017, Archaeology Data Service.

*This case study was undertaken in 2017 with funds from the [ARIADNE](https://ariadne-infrastructure.eu/) project*

All material in this guide is available [open access](https://archaeologydataservice.ac.uk/about/policies/use-access-to-data/) under a CC-BY 4.0 licence.

```{image} ads_logo.png
:height: 50px
:align: left
:alt: ADS Logo
```

```{image} hsds_blue_black.png
:height: 50px
:align: left
:alt: HSDS Logo
```

```{image} /images/ariadne_logo.jpg
:height: 50px
:align: left
:alt: ariadne Logo
```

## 1 Introduction

### 1.1 Scope of the Guide

The present document serves as a guide to good practice for the collection and archiving of data produced by Thermoluminescence (*TL*) measurements (analyses) of archaeological materials, such as ceramics, in the context of the archaeological research. This guide does not elaborate on the methods involved in thermoluminescence analysis in general, but aims at informing researchers involved in archaeological studies about the key elements and important metadata that should be documented from thermoluminescence analyses during the determination of the age of archaeological materials.

It should be noted that specific metadata can be very important since they are descriptive of the procedure followed for the treatment of physical samples and the protocols or techniques used during the analysis which are solidly interconnected to the produced data. Special attention should be given to documenting such metadata, which allow not only the easy archiving but also the reuse of the datasets produced. This ensures the re-evaluation of samples and the comparison of results between laboratories.

### 1.2 What is Thermoluminescence?

In summary, thermoluminescence is the emission of light during the heating of a solid sample, usually an insulating one, which has been previously excited. The source of the emitted light is the initial excitation, which is typically created by irradiation, while heating acts as a trigger which contributes to the releasing of this accumulated energy.

To elaborate on the above, a solid sample such as ceramic can be excited by ionizing radiation at a certain relatively low temperature. This irradiation can either take place in the laboratory or in a radiative environment. However, another version, more related to the archaeological use of thermoluminescence, is when a material is irradiated by the radiation field in its natural surrounding. At the end of this stage, the sample is placed in an appropriate instrument where its temperature is gradually raised at a constant heating rate. Then the emitted light (photons) is recorded as a function of the temperature using a light sensitive detector, such as a photomultiplier [@chen1997theory] and a glow-curve is acquired (Fig. 1).

```{figure} /images/TL_fig1.jpg
:alt: Figure 1


__Figure 1:__ Typical glow curve of a pottery sample recorded after artificial radiation administered in the laboratory
```

### 1.3 Applications of Thermoluminescence in Archaeology

__a) Dating__

The most common and important application of thermoluminescence in Archaeology is dating of archaeological objects, mainly ceramics, such as pottery, bricks or terracotta. The rapid heating of such objects up to 500&#xB0;C results in the weak, but measurable emission of light, which stems from some of the constituents minerals. The TL from the specimen is mostly due to TL sensitive mineral inclusions (mostly quartz) in the host clay matrix of the pottery. The basis of TL dating in archaeology is a definite event, the kiln firing. This event is regarded as the starting of the "TL clock" for archaeological dating, since any TL previously stored in the object is completely erased during the firing process. After the onset of the TL clock, the pottery starts to build up TL due to its exposure to the weak flux of nuclear radiation emitted by radio-active impurities in the pottery and the surrounding burial soil, the most active of which are the potassium-40 (K-40), thorium (Th) and uranium (U). The above radioisotopes have half-lives of more than 10%%sup 9 %% years, which results in a constant radiation flux.

Based on the above, the amount of the material's thermoluminescence can provide an estimation of the elapsed time since the pottery was fired. This is better described by *Eq. 1* [@aitken1985thermoluminescence], while the whole process is illustrated in Fig. 2.

```{figure} /images/TL_equation.jpg
:alt: Flow chart


```

The "paleodose" is calculated by the thermoluminescence of the pottery (archaeologically acquired thermoluminescence). Estimation of the "annual dose" is based on the appropriate calculation of the contribution of the alpha and beta particles of the radioisotopes mentioned above (K-40, Th and U) using other methods.

It is obvious that the thermoluminescence constitutes only a part of a complex process used to achieve an accurate and reliable dating of ceramics. Various measurements with several techniques should be conducted to get the correct age, rather than an estimation of it, for an archaeological object. This is better illustrated by Fig. 2.

```{figure} /images/TL_fig2.jpg
:alt: Figure 2


__Figure 2:__ Flow chart of the process for pottery dating
```


__b) Authenticity testing of ceramic objects__

Thermoluminescence can also be used in the battle against art forgery and has been widely employed in the field of authenticity testing. Porcelain or ceramic objects can be the subject of thermoluminescence testing in order to determine their archaeological value. A modern object which has only been fired recently will carry only a trivial level of stored TL energy, compared to its ancient prototype [@fleming1979thermoluminescence]. Consequently, it is relatively easy to distinguish between a fake object whose age is less than a hundred years and those aged more than five hundred.

__c) Pottery provenance and transactions among ancient communities__

Thermoluminescence can also provide information on the provenance of pottery and further shed light on local production and socio-economical relationships amongst ancient communities. Such information can complement archaeological observations of typology and the recognition of special fabric textures of excavated pottery and lead to a more concrete decisions regarding provenance. Several such studies have been undertaken [e.g. @vaz1997determination; @rasmussen2001focus] and are based on differences of TL sensitivity and/or characteristics of pottery of different provenance. These variances are the outcome of different tempering materials and concentrations of trace elements found in the clay used for the manufacture of pottery from different sources (geographical regions).

### 1.4 Current Issues or Concerns

__a) Efficiency and diffusion of the thermoluminescence data__

In many cases, thermoluminescence data from various archaeological objects (mainly pottery) are produced to support the work of archaeologists, without being stored with additional information about the object itself (e.g. type), mainly because archaeologists most often neglect to provide such information. This limits the reusability of TL data for the benefit of the wider archaeological community, since they are only produced for a specific purpose (e.g. the age of an object). This situation is further worsened by the fact that such data are not published, since only the result of the process (e.g. the age) is of interest for the archaeologists. However, TL data could provide further information about the temporal or spatial distribution of pottery when compared with similar data of other objects.

__b) The need for additional metadata__

To ensure the use of TL data in other archaeological studies and to allow the comparison between data acquired in different laboratories or the repetition of the same measurement, several metadata elements should also be stored. This metadata includes both details of the under-study object (e.g. sampling procedure, excavation site, picture, etc) and the measuring conditions (method, number of sub-samples, doses, temperatures, etc).

### 1.5 Data and Metadata

Definition of *Data* and *Metadata* is a controversial issue with multifold approaches, since it extensively depends on usage. In the case of thermoluminescence, raw data, i.e., the results of every measurement (directly produced by the scientific instrument without any intermediate calculations), are considered as data. In fact they are temperature-photon counts pairs, whose population depends on the heating rate and final temperature selected for the measurement. However, metadata also comprise all subsequent information resulting from the post-processing of raw data along with other sample-related and pre-measurement (sample treatment, operational conditions etc) information which allows the interpretation of results or comparison with previous measurements. Examples include the location of the archaeological material, the method/technique, the measurement parameters etc.

## 2 Acquiring and Processing Thermoluminescence Data

### 2.1 Project Planning and Requirements

The requirements for project planning are not standard and can vary depending on various factors such as the size and/or available mass of the sample, desired precision, the sampling procedure, and the archaelogist's estimation of the object's age. All such information is significant and will determine the protocol and technique that will be used for the TL measurement (e.g. fine grain, coarse grain, etc.), the number of sub-samples (aliquots) that will be prepared, and the doses that will be applied for the calibration.

### 2.2 Sources of Data and File Types

Production of TL data is accomplished worldwide either by commercially available or custom-made instruments. As a result, both the source (platform or software) and the type of data are instrument dependent and proprietary. In all cases the TL-data can easily be converted to an ASCII text format, which allows easy processing within spreadsheet programs such as MS Excel. A difference, however, can be the ability of the various types of software used to store alongside the data the measurement-associated metadata, which could hamper or even block their comparison with other TL-data.

## 3 Archiving Thermoluminescence Data

### 3.1 Deciding What to Archive

The size of the acquired files containing TL-data can be very small (in most cases only few kilobytes) and thus, practically, there is not a dilemma about choosing the appropriate files to archive. In any case, the resulting TL-data file(s) should always be archived along with the file(s) which describe the detailed sequence of steps followed (i.e. complete experimental conditions and procedure) during the TL measurement of the various samples or sub-samples. This allows the prompt matching of results with the appropriate measurement and sample.

Furthermore, it is good practice to store and archive additional information describing the objects, such as photos, archaeological observations and information, and related research reports in order to enhance the usability of the TL data by other researchers or future studies.

### 3.2 Deciding How to Archive

To the Authors' best knowledge there are not any established standards which would dictate the content and related fields that a database of TL data should be composed of. As a result, TL data are mainly stored in custom-made repositories of arbitrary structure. In any case such a database should always be structured on the premise that TL data should be publicly available and freely shared to other researchers in order to enhance archaeological research and contribute to cultural heritage management.

The minimum requirements regarding the structure of such a database should at least fulfil the need to allow future re-evaluation or verification of certain TL measurements. However, one should always have in mind that it is good practice to build such a generic repository covering a wide range of metadata, which would allow the comparison of results among different TL-data-producing instruments and their use in follow-up research.

### 3.3 File Types for Archiving

As previously stated, the format of the TL data is native or proprietary. Consequently, besides their original format, raw data should also be converted and stored in ASCII format in order to enhance their readability by other researchers and in other studies. Furthermore, most metadata are descriptive in nature and thus should be stored preferably in accessible text format, while images/photographs of the objects should be stored in a commonly used image file format (jpg or tiff being the most appropriate).

### 3.4 Archiving TL-related Metadata

Required metadata can be divided into three levels: Project level, Object level, and Measurement level, with each one providing different information. Project level metadata mainly refers to information related to the archaeological site at which the object(s) was found. Object level metadata provides information (mainly archaeological) and descriptions of every object to be measured. Finally, measurement level metadata relates to all available information about the experimental/measuring procedure including any post-measurement data treatment. Based on the above, a project may include multiple measurements of several objects found in the same excavation site.

Although the more metadata recorded the better, in most cases a certain minimum set of metadata is enough to establish their usability for future purposes. Table 1 presents all metadata that should be stored when archiving TL data.

```{list-table} Metadata fields (*M: Mandatory, D: Desirable, O: Optional*) that should be filled when archiving TL data.
:header-rows: 1
:name: Metadata fields (*M: Mandatory, D: Desirable, O: Optional*) that should be filled when archiving TL data.

* - Element
  - Description
  - Field Importance
* - __Project level__
  - 
  -  
* - Project name
  - Name of the project
  - M
* - Project date
  - Date the project started
  - M
* - Name of stakeholder
  - Name of excavation, museum, collection, archaeological project, etc., where the objects come from
  - M
* - Object location
  - Geographical area, where the object(s) was found or stored or excavation site or name of Museum
  - M
* - Site geographical longitude
  - Longitude of the excavation site
  - D
* - Site geographical latitude
  - Latitude of the excavation site
  - D
* - __Object level__
  - 
  -  
* - Object ID code
  - The ID of the object as registered in the excavation or museum
  - M
* - Object lab ID
  - The ID of the object registered by the laboratory performing the measurement
  - M
* - Object lab date
  - Date the object was delivered to the laboratory
  - M
* - Batch protocol number
  - The protocol number of the batch in which the object belongs
  - D
* - Group object ID
  - The ID of the group to which the object belongs (archaeological excavation)
  - O
* - Excavation section
  - The section of the excavation site in which the object was found
  - O
* - Area description
  - Description of the area where the object was found (e.g. in a kiln)
  - M
* - Object depth
  - The depth from the surface where the object was found
  - M
* - Object type
  - The type of object (e.g. soil, clay, sherd, brick, other)
  - M
* - Object category
  - The category where the object belongs (mainly applicable for ceramics) according to the archaeological classification
  - O
* - Object dimensions
  - The dimensions of the object in cm (length, width, height). Not applicable for powder objects (e.g. soil)
  - O
* - Object description
  - Free text describing the object (colors, texture, etc)
  - O
* - Object picture
  - Picture or filename of the object in tiff or jpg format
  - D
* - Related documents
  - Other related documents (e.g. other object pictures, pictures from the area where the object was found, bibliography etc.)
  - O
* - __Measurement level__
  - 
  -  
* - Sample preparation
  - Free text describing the preparation/pretreatment of the sample (cleaning, sieving, etc.)
  - M
* - Measuring technique
  - Technique used for the TL measurement (e.g. fine grain, coarse grain, etc.)
  - M
* - Grain size
  - Size of the grains used for measurement
  - M
* - Number of aliquots
  - The number of sub-samples used for measurement for statistical purposes
  - M
* - Measurement protocol
  - File describing the steps and the operational conditions of the measurement protocol
  - M
* - Filters
  - Details of the optical filters used for TL measurement
  - M
* - Instrument(s)
  - Instrument(s) used for TL measurement (brand name, model and serial number)
  - M
* - Instrument(s) details
  - Other instrument details (especially those that are unique for the specific instrument (s) used)
  - O
* - Laboratory
  - Name of Laboratory performing the measurement
  - M
* - Researcher(s)
  - Name of the Researcher(s) who conducted the measurements
  - D
* - Start measurement date
  - The date the measurement of the sample started
  - M
* - End measurement date
  - The date the measurement of the sample ended
  - M
* - Date of results
  - The date the results (age) were produced
  - D
* - Technical Report file
  - Technical report of the measurement (text file)
  - M
* - Annual dose estimation
  - Methods and/or assumptions used for the determination of the annual dose
  - D
* - Method for potassium (if applicable)
  - Method used for the determination of the sample's potassium (K) concentration (ICP, XRF etc)
  - D
* - Method for uranium/thorium (if applicable)
  - Method used for the determination of the sample's uranium (U) and thorium (Th) concentration
  - D
```

## 4 Case Study: Dating pottery from Ancient Abdera (Greece)

### 4.1 Project Background/Scope

The site of Abdera, city of Democritos, was settled in the middle of the 7th century B.C. by colonists from Clazomenae and in 545 B.C. by the inhabitants of Teos. The site has undergone various changes during its history, from a prosperous city during the Roman period to a cemetery during the Byzantine period. According to the archaeologists, ceramics found in the site are both local and imported products, while their age may vary.

The scope of the project was the dating of several ceramic objects (mainly pottery) found in the archaeological site of ancient Abdera in Greece using Thermoluminescence.

### 4.2 Project Deliverables

For each object the age and the corresponding error were calculated following the established TL protocol along with all necessary complementary measurements as previously mentioned. The datasets selected for archiving include:

* Raw TL-data file
* Converted TL-data file in ASCII format
* Raw data from every other measurement conducted for the estimation of the "annual dose"

### 4.3 Archival Metadata Example

In order to present an example of a complete metadata set, one of the analyzed objects was selected. Project level metadata have been completed once, since they refer to the archaeological site and apply to all project objects. The remaining metadata (object and measurement level) are different for each object (in most cases the majority of the measurement level metadata may also be common for all objects). All archived metadata are in given *Table 2*.

```{list-table} Metadata fields filled for the ancient Abdera project
:header-rows: 1
:name: Metadata fields filled for the ancient Abdera project

* - Element
  - Field entry
* - __Project level__
  - 
* - Project name
  - Ancient Abdera
* - Project date
  - 10 May 2005
* - Name of stakeholder
  - Abdera museum
* - Object location
  - Site of Ancient Abdera, Greece
* - Site geographical longitude
  - 40.934249
* - Site geographical latitude
  - 24.975368
* - __Object level__
  - 
* - Object ID code
  - AB.ST.s(1)10
* - Object lab ID
  - AA10
* - Object lab date
  - 15 May 2005
* - Batch protocol number
  - -
* - Group object ID
  - Group A
* - Excavation section
  - -
* - Area description
  - -
* - Object depth
  - 20 cm
* - Object type
  - sherd
* - Object category
  - amphora
* - Object dimensions
  - 25 x 28 x 4 mm
* - Object description
  - -
* - Object picture
  - AB.ST.s(1)10.tiff
* - Related documents
  - -
* - __Measurement level__
  - 
* - Sample preparation
  - A piece of the sherd is removed. Then after removing few &#xB5;m of the external layer, it is gently pulverized and then sieved
* - Measuring technique
  - Fine grain
* - Grain size
  - 2-10 &#xB5;m
* - Number of aliquots
  - 16
* - Measurement protocol
  - AA10.SEQ
* - Filters
  - Corning 7-59 & Pilkington HA-3
* - Instrument(s)
  - Riso TL/OSL reader (model TL/OSL-DA-15), S/N: RISO 105/00/06/b/OSL-B42-IR/830
* - Instrument(s) details
  - -
* - Laboratory
  - Laboratory of Archaeometry and Physicochemical Measurements, R.C. Athena
* - Researcher
  - Dr Nikolaos Kazakis
* - Start measurement date
  - 1 June 2005
* - End measurement date
  - 2 June 2005
* - Date of results
  - 20 June 2005
* - Technical Report file
  - Ancient_Abdera_May_2005.doc
* - Annual dose estimation
  - Measured K, U, Th activities, cosmic ray dose equal to 0.015 rads/yr
* - Method for potassium
  - Micro-XRF
* - Method for uranium/thorium
  - ELSEC 7286 Low Level Alpha Counter
```

## Bibliography

Aitken, M.J. (1985) *Thermoluminescence Dating.* Academic Press, Orlando, Florida.

Chen, R., McKeever, S.W.S. (1997) *Theory of Thermoluminescence and Related Phenomena.* World Scientific Publishing Co. Pte. Ltd, Singapore.

Fleming S. (1979) *Thermoluminescence Techniques in Archaeology.* Clarendon Press, Oxford.

Rasmussen, K.L. (2001) 'FOCUS: Provenance of Ceramics Revealed by Magnetic Susceptibility and Thermoluminescence'. *Journal of Archaeological Science* __28__(5), 451-456. DOI: 10.1006/jasc.2001.0610

Vaz, J.E., LaBrecque, J.J., Cruxent, J.M. (1997) 'Determination of the provenance of majolica ceramics from Europe by thermoluminescence employing principal components.' *Fresenius' Journal of Analytical Chemistry* __358__(4), 529-532. DOI: 10.1007/s002160050460