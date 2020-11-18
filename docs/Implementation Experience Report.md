
# Implementation Experience Report
**Authors**: Members of the Chronometric Age Extension Task Group [1]

From section 4.2.2 of the Vocabulary Maintenance Specification [2]:

"*The purpose of the Implementation Experience Report is to document the experience of independent implementations with the features listed in the Feature Report…
The report should provide information about the extent to which each implementer successfully included each of the features detailed in the Feature Report*."

# Summary
Implementation in this case consisted of the creation of a vocabulary associated with the concept of chronometric age, the creation and publication of an extension for the vocabulary in XML following the GBIF Darwin Core extension schema [3], and the publication of varied data sets using that extension to GBIF via an instance of the Integrated Publishing Toolkit [4] with the extension enabled. During the development process, this cycle was realized three times, one for the initial concept of ChronometricDate and twice in refinement following community input with the renamed concept ChronometricAge.

# Implementation History
The concepts of the chronometric age vocabulary were first defined as a test case for the publication of a variety of zooarchaeological datasets that used different chronometric assays to determine age. That first implementation included a set of terms, their definitions, usage notes and examples following the model of the Darwin Core after assessing their suitability to describe the exemplar datasets (see Feature Report). These terms were included in a Darwin Core Chronometric Date Extension XML document [5] following the GBIF Darwin Core extension schema [3,6] and put into production [7]. The extension was used to successfully publish four zooarchaeological data sets [8,9,10,11] to GBIF through the VertNet-hosted Integrated Publishing Toolkit (IPT) [4] and demonstrate the viability of the Chronometric age concept, though in this early stage it was called ChronometricDate. 

Presentations at the annual meetings of TDWG in 2017 [12] showed the broader need for terms to capture chronometric age information for non-neontological information spanning recent archaeological to paleontological biodiversity data. 

The ChronometricDate extension was evaluated by the custodians of the published datasets and again assessed in the larger community with discussions in the Earth Sciences and Paleontology Interest Group [13] and a presentation at the TDWG annual meeting in 2018 [14].
The set of terms and definitions were presented in a webinar [15] in the Darwin Core Hour series, a community standards event, and further feedback was solicited via issue tracking in the Chronometric Age GitHub repository [16]. The feedback helped identify terms that were too specific to the initial use cases or whose definitions that were unclear and was used to further refine the term names, definitions, usage notes, and examples under a renamed concept ChronometricAge.

The earlier ChronometricDate extension was deprecated, and a new ChronometricAge extension [17] was put into production to replace it. All previously published datasets using ChronometricDate as well as a representative paleontology data set [18] were published successfully using the new ChronometricAge extension.

A further round of solicited conversations with targeted representatives of the stakeholder communities revealed the need for properties to capture the output of a dating assay before it is calibrated into an age using a specific conversion protocol and the method used to convert the uncalibrated chronometric age into an age in years. A comprehensive review by the Darwin Core Maintenance Interest Group [19] resulted in recommendations for the addition of terms to capture who did the chronometric age determination and when. All of these new terms have been incorporated into the final version of the extension [20] to go to review for inclusion in the corpus of terms maintained by the Darwin Core Maintenance Interest Group. 

Upon ratification, the following actions will complete the implementation of the vocabulary:
The final version of the extension will be put into production [21] so that any data set with chronometric age data can be published in Darwin Core Archives using the extension and map to this extension using the Integrated Publishing Toolkit. 
The namespaces chrono: (http://rs.tdwg.org/chrono/terms/) and chronoiri: (http://rs.tdwg.org/chrono/iri/) will be enabled so that the term IRIs resolve. 
The Darwin Core RDF Guide [22] will be updated to accommodate the new terms defined in the extension.
The ChronometricAge Quick Reference Guide [23] will be updated to a final standard version.
The ChronometricAge term list [24] will be updated to a final standard version.
The ChronometricAge Task Group [25] will be closed.
Maintenance of the terms will pass to the Darwin Core Maintenance Interest Group [19]
A non-normative guide to the use of the ChronometricAge Extension, with examples, will be produced by ZooArchNet [26].

# Community Participation
All prototypes and testing were done in a collaboration between ZooArchNet [26] and VertNet [27]. All standards documents were produced in collaboration with the Darwin Core Maintenance Interest Group [19]. In addition to participants in attendance at the TDWG Earth Sciences and Paleobiology Interest Group [13] meetings in 2017 and 2018, researchers representing the following groups participated in the review of the implementations of the vocabulary as GBIF extensions: 
* Florida Museum of Natural History, Biodiversity Informatics (https://sites.google.com/site/robgur/)
* Florida Museum of Natural History, Environmental Archaeology (https://www.floridamuseum.ufl.edu/envarch/)
* Florida Museum of Natural History, Florida Archaeology and Bioarchaeology (https://www.floridamuseum.ufl.edu/flarch/home/)
* Functional Trait Resource for Environmental Studies (https://futreswebsite.netlify.com/)
* Neotoma Paleoecology Database (https://www.neotomadb.org/)
* Open Context (https://opencontext.org/)
* Paleo Core (https://paleocore.org/)
* Paleobiology Database (https://paleobiodb.org/)
* Simon Fraser University Department of Archaeology (https://www.sfu.ca/archaeology.html)
* Smithsonian Institution Department of Paleobiology (https://naturalhistory.si.edu/research/paleobiology)
* Smithsonian Tropical Research Institute, Panama (https://stri.si.edu/)
* Strategic Environmental Archaeology Database (https://www.sead.se/)
* University of Arizona, School of Anthropology (https://anthropology.arizona.edu/)
* University of Georgia Center for Applied Isotopes Studies (https://cais.uga.edu/)
* University of Georgia Department of Anthropology (https://anthropology.uga.edu/)
* University of Oregon Department of Anthropology (https://anthropology.uoregon.edu/)
* Western Carolina University History Department (https://www.wcu.edu)

# References
[1] https://www.tdwg.org/community/esp/chrono/ \
[2] https://github.com/tdwg/vocab/blob/master/vms/maintenance-specification.md \
[3] http://rs.gbif.org/schema/extension.xsd \
[4] http://ipt.vertnet.org/ \
[5] https://tools.gbif.org/dwca-validator/extension.do?id=http://zooarchnet.org/dwc/terms/ChronometricDate \
[6] https://github.com/gbif/rs.gbif.org/tree/master/extension/zooarchnet \
[7]https://tools.gbif.org/dwca-validator/extensions.do \
[8] http://ipt.vertnet.org:8080/ipt/resource?r=baptizing_springs \
[9] http://ipt.vertnet.org:8080/ipt/resource?r=north_midden \
[10] http://ipt.vertnet.org:8080/ipt/resource?r=tick_island_zooarchaeological_data \
[11] http://ipt.vertnet.org:8080/ipt/resource?r=flarch_zooarch_parnell_feature1 \
[12] Brenskelle L, Wieczorek J, Guralnick R, Emery K, LeFebvre M (2017) Extending Darwin Core to incorporate data about material condition and absolute deep time. Proceedings of TDWG 1: e20126. https://doi.org/10.3897/tdwgproceedings.1.20126 \
[13] https://github.com/tdwg/esp \
[14] Brenskelle, L. (2018) TDWG Presentation: Published examples using the new Chronometric extension to Darwin Core. https://biss.pensoft.net/articles.php?id=25694&journal_name=biss https://spnhctdwg18.sched.com/event/G4Wy/s06-published-examples-using-the-new-chronometric-extension-to-darwin-core \
[15] Brenskelle, L. (2018) Darwin Core Hour: The Problem of Time - Dealing with Paleontological and Zooarchaeological Specimens in Darwin Core. https://www.idigbio.org/content/darwin-core-hour-problem-time-dealing-paleontological-and-zooarchaeological-specimens-darwin and https://docs.google.com/presentation/d/1OBcXXuETlzQ_FnHgo2Oc34ADAuAYvcRei_KBQ-V6mds \
[16] https://github.com/tdwg/chrono, moved from https://github.com/vertnet/chrono for the purpose of making the vocabulary part of the TDWG standards. Issues addressed can be seen at https://github.com/tdwg/chrono/issues?q=is%3Aissue+is%3Aclosed \
[17] https://tools.gbif.org/dwca-validator/extension.do?id=http://zooarchnet.org/dwc/terms/ChronometricAge \
[18] http://ipt.vertnet.org:8080/ipt/resource?r=uomnh-cfc \
[19] https://www.tdwg.org/community/dwc/ \
[20] https://github.com/tdwg/chrono/blob/master/dist/ChronometricAge_2020-10-06.xml \
[21] https://github.com/gbif/rs.gbif.org/tree/master/extension/dwc \
[22] https://dwc.tdwg.org/rdf/ \
[23] https://tdwg.github.io/chrono/terms/ \
[24] https://tdwg.github.io/chrono/list/ \
[25] https://www.tdwg.org/community/esp/chrono/ \
[26] https://zooarchnet.org/ \
[27] http://vertnet.org/