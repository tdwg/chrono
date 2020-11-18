# Feature Report
**Authors**: Members of the Chronometric Age Extension Task Group [1]

From section 4.2.1 of the Vocabulary Maintenance Specification [2]:

"*The purpose of the Feature Report is to identify the features that should be included in the enhancement in order to achieve goals identified by the community...the report should include a numbered list of features and indicate how the need for each feature was determined from community input*."

# Features
In the course of the development, various required features were identified, namely, the vocabulary must be able to express
1. a chronometric age without confounding that age with the Darwin Core eventDate (https://dwc.tdwg.org/terms/#dwc:eventDate), which, according to common usage, should represent when the material was recovered from its context.
1. inputs to, the results of, and the process used to determine a chronometric age.
1. the chronometric age in terms of distinct minimum and maximum values.
1. the type of material used as the basis of the chronometric age determination.
1. a (single) temporal uncertainty associated with minimum and maximum ages.
1. published references associated with the chronometric age determination.
1. the output of a dating assay before it is calibrated into an age using a specific conversion protocol.
1. the method used to convert the uncalibrated chronometric age (feature 7) into a chronometric age in years.
1. who was responsible for the chronometric age determination, and when it was done.

Features numbered 1-6 were the original features required for the publication of a set of exemplar zooarchaeological data sets with varied chronometric assays to determine age. These examples were elected by researchers from ZooArchNet [3] and originally implemented both in the extension definition and in data publication in collaboration with VertNet [4]. Features 7-8 were identified after the first implementations had been tested for zooarchaeology and then circulated to the archaeological and paleontology communities [5]. Features identified in 9 were recommended by the Darwin Core Maintenance Interest Group [6] in order to be consistent with other classes of information in Darwin Core.

# References
[1] https://www.tdwg.org/community/esp/chrono/ \
[2] https://github.com/tdwg/vocab/blob/master/vms/maintenance-specification.md \
[3] https://zooarchnet.org/ \
[4] http://vertnet.org/ \
[5] LeFebvre MJ, Brenskelle L, Wieczorek J, Kansa SW, Kansa EC, Wallis NJ, et al. (2019) ZooArchNet: Connecting zooarchaeological specimens to the biodiversity and archaeology data networks. PLoS ONE 14(4): e0215369. https://doi.org/10.1371/journal.pone.0215369 \
[6] https://www.tdwg.org/community/dwc/
