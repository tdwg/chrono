
# Chronometric Age Quick Reference Guide

This document is intended to be an easy-to-read reference the currently recommended terms that extend the [Darwin Core standard](https://www.tdwg.org/standards/dwc/) with vocabulary for chronometric ages. This document is not part of the standard. It draws on the [term names and definitions](../list/) from the normative part of the standard and combines them with comments and examples that are not normative, but that are meant to help people to use the terms consistently. The category `ChronometricAge` corresponds to the parent class, which is a special category term used to group the rest of the terms for convenience. Comprehensive metadata for current and obsolete terms in human readable form are found in a [list of terms document](../list/). CSV files with the [full history](https://github.com/tdwg/chrono/blob/master/vocabulary/term_versions.csv) of the terms, with [horizontal and vertical lists](https://github.com/tdwg/chrono/tree/master/dist) of these terms and the schema for the [Darwin Core Archive extension](https://github.com/tdwg/chrono/tree/master/dist) can be found in the [Chronometric Age repository](https://github.com/tdwg/chrono).


## ChronometricAge

<div class="my-4">
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:chronometricAgeID">chronometricAgeID</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:verbatimChronometricAge">verbatimChronometricAge</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:chronometricAgeProtocol">chronometricAgeProtocol</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:uncalibratedChronometricAge">uncalibratedChronometricAge</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:chronometricAgeConversionProtocol">chronometricAgeConversionProtocol</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:earliestChronometricAge">earliestChronometricAge</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:earliestChronometricAgeReferenceSystem">earliestChronometricAgeReferenceSystem</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:latestChronometricAge">latestChronometricAge</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:latestChronometricAgeReferenceSystem">latestChronometricAgeReferenceSystem</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:chronometricAgeUncertaintyInYears">chronometricAgeUncertaintyInYears</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:chronometricAgeUncertaintyMethod">chronometricAgeUncertaintyMethod</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:materialDated">materialDated</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:materialDatedID">materialDatedID</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:materialDatedRelationship">materialDatedRelationship</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:chronometricAgeDeterminedBy">chronometricAgeDeterminedBy</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:chronometricAgeDeterminedDate">chronometricAgeDeterminedDate</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:chronometricAgeReferences">chronometricAgeReferences</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chrono:chronometricAgeRemarks">chronometricAgeRemarks</a>
  </div>

<table class="table">
  <tbody>
    <tr class="table-primary"><th colspan="2">ChronometricAge <span class="badge bg-primary float-end">Class</span></th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/ChronometricAge">http://rs.tdwg.org/chrono/terms/ChronometricAge</a></td></tr>
    <tr><td>Definition</td><td>An approximation of a temporal position (in the sense conveyed by <a href="https://www.w3.org/TR/owl-time/#time:TemporalPosition">https://www.w3.org/TR/owl-time/#time:TemporalPosition</a>) that is supported via evidence.</td></tr>
    <tr><td>Comments</td><td>The age of a specimen and how this age is known, whether by a dating assay, a relative association with dated material, or legacy collections information.</td></tr>
    <tr><td>Examples</td><td><code>An age range associated with a specimen derived from an AMS dating assay applied to an oyster shell in the same stratum</code>; <code>An age range associated with a specimen derived from a ceramics analysis based on other materials found in the same stratum</code>; <code>A maximum age associated with a specimen derived from K-Ar dating applied to a proximal volcanic tuff found stratigraphically below the specimen</code>; <code>An age range of a specimen based on its biostratigraphic context</code>; <code>An age of a specimen based on what is reported in legacy collections data</code>.</td></tr>
  </tbody>
</table>

<p class="invisible">
  <span id="chrono:chronometricAgeID"></span>
    <span id="chronometricAgeID"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeID</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeID">http://rs.tdwg.org/chrono/terms/chronometricAgeID</a></td></tr>
    <tr><td>Definition</td><td>An identifier for the set of information associated with a chrono:ChronometricAge.</td></tr>
    <tr><td>Comments</td><td>May be a global unique identifier or an identifier specific to the dataset. This can be used to link this record to another repository where more information about the dataset is shared.</td></tr>
    <tr><td>Examples</td><td><code><a href="https://www.canadianarchaeology.ca/samples/70673">https://www.canadianarchaeology.ca/samples/70673</a></code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:verbatimChronometricAge"></span>
    <span id="verbatimChronometricAge"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">verbatimChronometricAge</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/verbatimChronometricAge">http://rs.tdwg.org/chrono/terms/verbatimChronometricAge</a></td></tr>
    <tr><td>Definition</td><td>The verbatim age for a specimen, whether reported by a dating assay, associated references, or legacy information.</td></tr>
    <tr><td>Comments</td><td>For example, this could be the radiocarbon age as given in an AMS dating report. This could also be simply what is reported as the age of a specimen in legacy collections data.</td></tr>
    <tr><td>Examples</td><td><code>27 BC to 14 AD</code>, <code>stratigraphically pre-1104</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:chronometricAgeProtocol"></span>
    <span id="chronometricAgeProtocol"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeProtocol</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeProtocol">http://rs.tdwg.org/chrono/terms/chronometricAgeProtocol</a></td></tr>
    <tr><td>Definition</td><td>A description of or reference to the methods used to determine the chrono:ChronometricAge.</td></tr>
    <tr><td>Comments</td><td> This term has an equivalent in the chronoiri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.</td></tr>
    <tr><td>Examples</td><td><code>radiocarbon AMS</code>; <code>K-Ar dates for the lower most marker tuff</code>; <code>historic documentation</code>; <code>ceramic seriation</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:uncalibratedChronometricAge"></span>
    <span id="uncalibratedChronometricAge"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">uncalibratedChronometricAge</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/uncalibratedChronometricAge">http://rs.tdwg.org/chrono/terms/uncalibratedChronometricAge</a></td></tr>
    <tr><td>Definition</td><td>The output of a dating assay before it is calibrated into an age using a specific conversion protocol.</td></tr>
    <tr><td>Comments</td><td></td></tr>
    <tr><td>Examples</td><td><code>1510 +/- 25 14C yr BP</code>, <code>16.26 Ma +/- 0.016</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:chronometricAgeConversionProtocol"></span>
    <span id="chronometricAgeConversionProtocol"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeConversionProtocol</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeConversionProtocol">http://rs.tdwg.org/chrono/terms/chronometricAgeConversionProtocol</a></td></tr>
    <tr><td>Definition</td><td>The method used for converting the chrono:uncalibratedChronometricAge into a chronometric age in years, as captured in the chrono:earliestChronometricAge, chrono:earliestChronometricAgeReferenceSystem, chrono:latestChronometricAge, and chrono:latestChronometricAgeReferenceSystem fields.</td></tr>
    <tr><td>Comments</td><td>For example, calibration of conventional radiocarbon age or the currently accepted age range of a cultural or geological period. This term has an equivalent in the chronoiri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.</td></tr>
    <tr><td>Examples</td><td><code>INTCAL13</code>; <code>sequential 6 phase Bayesian model and IntCal13 calibration</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:earliestChronometricAge"></span>
    <span id="earliestChronometricAge"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">earliestChronometricAge</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/earliestChronometricAge">http://rs.tdwg.org/chrono/terms/earliestChronometricAge</a></td></tr>
    <tr><td>Definition</td><td>The maximum/earliest/oldest possible age of a specimen as determined by a dating method.</td></tr>
    <tr><td>Comments</td><td>The expected unit for this field is years. This field, if populated, must have an associated chrono:earliestChronometricAgeReferenceSystem.</td></tr>
    <tr><td>Examples</td><td><code>100</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:earliestChronometricAgeReferenceSystem"></span>
    <span id="earliestChronometricAgeReferenceSystem"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">earliestChronometricAgeReferenceSystem</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/earliestChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/terms/earliestChronometricAgeReferenceSystem</a></td></tr>
    <tr><td>Definition</td><td>The reference system associated with the chrono:earliestChronometricAge.</td></tr>
    <tr><td>Comments</td><td>Recommended best practice is to use a controlled vocabulary. This term has an equivalent in the chronoiri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.</td></tr>
    <tr><td>Examples</td><td><code>kya</code>; <code>mya</code>; <code>BP</code>; <code>AD</code>; <code>BCE</code>; <code>ka</code>; <code>Ma</code>; <code>Ga</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:latestChronometricAge"></span>
    <span id="latestChronometricAge"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">latestChronometricAge</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/latestChronometricAge">http://rs.tdwg.org/chrono/terms/latestChronometricAge</a></td></tr>
    <tr><td>Definition</td><td>The minimum/latest/youngest possible age of a specimen as determined by a dating method.</td></tr>
    <tr><td>Comments</td><td>The expected unit for this field is years. This field, if populated, must have an associated chrono:latestChronometricAgeReferenceSystem.</td></tr>
    <tr><td>Examples</td><td><code>27</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:latestChronometricAgeReferenceSystem"></span>
    <span id="latestChronometricAgeReferenceSystem"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">latestChronometricAgeReferenceSystem</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/latestChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/terms/latestChronometricAgeReferenceSystem</a></td></tr>
    <tr><td>Definition</td><td>The reference system associated with the chrono:latestChronometricAge.</td></tr>
    <tr><td>Comments</td><td>Recommended best practice is to use a controlled vocabulary. This term has an equivalent in the chronoiri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.</td></tr>
    <tr><td>Examples</td><td><code>kya</code>; <code>mya</code>; <code>BP</code>; <code>AD</code>; <code>BCE</code>; <code>ka</code>; <code>Ma</code>; <code>Ga</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:chronometricAgeUncertaintyInYears"></span>
    <span id="chronometricAgeUncertaintyInYears"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeUncertaintyInYears</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyInYears">http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyInYears</a></td></tr>
    <tr><td>Definition</td><td>The temporal uncertainty of the chrono:earliestChronometricAge and chrono:latestChronometicAge in years.</td></tr>
    <tr><td>Comments</td><td>The expected unit for this field is years. The value in this field is number of years before and after the values given in the chrono:earliestChronometricAge and chrono:latestChronometricAge fields within which the actual values are estimated to be.</td></tr>
    <tr><td>Examples</td><td><code>100</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:chronometricAgeUncertaintyMethod"></span>
    <span id="chronometricAgeUncertaintyMethod"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeUncertaintyMethod</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyMethod">http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyMethod</a></td></tr>
    <tr><td>Definition</td><td>The method used to generate the value of chrono:chronometricAgeUncertaintyInYears.</td></tr>
    <tr><td>Comments</td><td> This term has an equivalent in the chronoiri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.</td></tr>
    <tr><td>Examples</td><td><code>2-sigma calibrated range</code>; <code>Half of 95% confidence interval</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:materialDated"></span>
    <span id="materialDated"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">materialDated</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/materialDated">http://rs.tdwg.org/chrono/terms/materialDated</a></td></tr>
    <tr><td>Definition</td><td>A description of the material on which the chrono:chronometricAgeProtocol was actually performed, if known.</td></tr>
    <tr><td>Comments</td><td> This term has an equivalent in the chronoiri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.</td></tr>
    <tr><td>Examples</td><td><code>Double Tuff</code>; <code>Charcoal found in Stratum V</code>; <code>charred wood</code>; <code>tooth</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:materialDatedID"></span>
    <span id="materialDatedID"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">materialDatedID</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/materialDatedID">http://rs.tdwg.org/chrono/terms/materialDatedID</a></td></tr>
    <tr><td>Definition</td><td>An identifier for the dwc:MaterialEntity on which the chrono:chronometricAgeProtocol was performed, if applicable.</td></tr>
    <tr><td>Comments</td><td></td></tr>
    <tr><td>Examples</td><td><code>dwc:materialEntityID: <a href="https://www.ebi.ac.uk/metagenomics/samples/SRS1930158">https://www.ebi.ac.uk/metagenomics/samples/SRS1930158</a></code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:materialDatedRelationship"></span>
    <span id="materialDatedRelationship"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">materialDatedRelationship</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/materialDatedRelationship">http://rs.tdwg.org/chrono/terms/materialDatedRelationship</a></td></tr>
    <tr><td>Definition</td><td>The relationship of the chrono:materialDated to the subject of the chrono:ChronometricAge record, from which the chrono:ChronometricAge of the subject is inferred.</td></tr>
    <tr><td>Comments</td><td>Recommended best practice is to use a controlled vocabulary.</td></tr>
    <tr><td>Examples</td><td><code>sameAs</code> (cases where the subject material was completely destructively subsampled to get the ChronometricAge); <code>subsampleOf</code> (cases where part of the original specimen was extracted as the material used to determine the ChronometricAge); <code>inContextWith</code> (cases where the ChronometricAge is inferred from materialDated, such as sediments or cultural objects, in related temporal context); <code>stratigraphicallyCorrelatedWith</code> (cases where the ChronometricAge is inferred from materialDated in a stratigraphically correlated context)</td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:chronometricAgeDeterminedBy"></span>
    <span id="chronometricAgeDeterminedBy"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeDeterminedBy</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedBy">http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedBy</a></td></tr>
    <tr><td>Definition</td><td>A list (concatenated and separated) of names of people, groups, or organizations who determined the chrono:ChronometricAge.</td></tr>
    <tr><td>Comments</td><td>Recommended best practice is to separate the values in a list with space vertical bar space ( | ). This term has an equivalent in the chronoiri: namespace that allows only an IRI as a value, whereas this term allows for any string literal value.</td></tr>
    <tr><td>Examples</td><td><code>Michelle LeFebvre | Neill Wallis</code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:chronometricAgeDeterminedDate"></span>
    <span id="chronometricAgeDeterminedDate"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeDeterminedDate</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedDate">http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedDate</a></td></tr>
    <tr><td>Definition</td><td>The date on which the chrono:ChronometricAge was determined.</td></tr>
    <tr><td>Comments</td><td>Recommended best practice is to use a date that conforms to ISO 8601-1:2019.</td></tr>
    <tr><td>Examples</td><td><code>1963-03-08T14:07-0600</code> (8 Mar 1963 at 2:07pm in the time zone six hours earlier than UTC); <code>2009-02-20T08:40Z</code> (20 February 2009 8:40am UTC); <code>2018-08-29T15:19</code> (3:19pm local time on 29 August 2018); <code>1809-02-12</code> (some time during 12 February 1809); <code>1906-06</code> (some time in June 1906); <code>1971</code> (some time in the year 1971)</td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:chronometricAgeReferences"></span>
    <span id="chronometricAgeReferences"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeReferences</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeReferences">http://rs.tdwg.org/chrono/terms/chronometricAgeReferences</a></td></tr>
    <tr><td>Definition</td><td>A list (concatenated and separated) of identifiers (publication, bibliographic reference, global unique identifier, URI) of literature associated with the chrono:ChronometricAge.</td></tr>
    <tr><td>Comments</td><td>Recommended best practice is to separate the values in a list with space vertical bar space ( | ).</td></tr>
    <tr><td>Examples</td><td><code>Pluckhahn, Thomas J., Neill J. Wallis, and Victor D. Thompson. 2020 The History and Future of Migrationist Explanation in the Archaeology of the Eastern Woodlands: A Review and Case Study of the Woodland Period Gulf Coast. Journal of Archaeological Research. <a href="https://doi.org/10.1007/s10814-019-09140-x">https://doi.org/10.1007/s10814-019-09140-x</a></code></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chrono:chronometricAgeRemarks"></span>
    <span id="chronometricAgeRemarks"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeRemarks</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeRemarks">http://rs.tdwg.org/chrono/terms/chronometricAgeRemarks</a></td></tr>
    <tr><td>Definition</td><td>Notes or comments about the chrono:ChronometricAge.</td></tr>
    <tr><td>Comments</td><td></td></tr>
    <tr><td>Examples</td><td><code>Beta Analytic number: 323913 | One of the Crassostrea virginica right valve specimens from North Midden Feature 17 was chosen for AMS dating, but it is unclear exactly which specimen it was.</code></td></tr>
  </tbody>
</table>


## UseWithIRI

For more information on `UseWithIRI`, see [Section 2.5 of the RDF Guide](https://dwc.tdwg.org/rdf/#25-terms-in-the-dwciri-namespace-normative).
<div class="my-4">
      <a class="btn btn-sm btn-outline-primary m-1" href="#chronoiri:chronometricAgeConversionProtocol">chronometricAgeConversionProtocol</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chronoiri:chronometricAgeDeterminedBy">chronometricAgeDeterminedBy</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chronoiri:chronometricAgeProtocol">chronometricAgeProtocol</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chronoiri:chronometricAgeUncertaintyMethod">chronometricAgeUncertaintyMethod</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chronoiri:earliestChronometricAgeReferenceSystem">earliestChronometricAgeReferenceSystem</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chronoiri:latestChronometricAgeReferenceSystem">latestChronometricAgeReferenceSystem</a>
      <a class="btn btn-sm btn-outline-primary m-1" href="#chronoiri:materialDated">materialDated</a>
  </div>


<p class="invisible">
  <span id="chronoiri:chronometricAgeConversionProtocol"></span>
    <span id="chronometricAgeConversionProtocol"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeConversionProtocol</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/iri/chronometricAgeConversionProtocol">http://rs.tdwg.org/chrono/iri/chronometricAgeConversionProtocol</a></td></tr>
    <tr><td>Definition</td><td>The method used to convert the chrono:uncalibratedChronometricAge into a chronometric age in years, as captured in chrono:earliestChronometricAge, chrono:earliestChronometricAgeReferenceSystem, chrono:latestChronometricAge, and chrono:latestChronometricAgeReferenceSystem.</td></tr>
    <tr><td>Comments</td><td>Terms in the chronoiri: namespace are intended to be used in RDF with non-literal objects.</td></tr>
    <tr><td>Examples</td><td></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chronoiri:chronometricAgeDeterminedBy"></span>
    <span id="chronometricAgeDeterminedBy"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeDeterminedBy</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/iri/chronometricAgeDeterminedBy">http://rs.tdwg.org/chrono/iri/chronometricAgeDeterminedBy</a></td></tr>
    <tr><td>Definition</td><td>A person, group, or organization that determined the chrono:ChronometricAge.</td></tr>
    <tr><td>Comments</td><td>Terms in the chronoiri: namespace are intended to be used in RDF with non-literal objects.</td></tr>
    <tr><td>Examples</td><td></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chronoiri:chronometricAgeProtocol"></span>
    <span id="chronometricAgeProtocol"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeProtocol</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/iri/chronometricAgeProtocol">http://rs.tdwg.org/chrono/iri/chronometricAgeProtocol</a></td></tr>
    <tr><td>Definition</td><td>A method used to determine the chrono:ChronometricAge.</td></tr>
    <tr><td>Comments</td><td>Terms in the chronoiri: namespace are intended to be used in RDF with non-literal objects.</td></tr>
    <tr><td>Examples</td><td></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chronoiri:chronometricAgeUncertaintyMethod"></span>
    <span id="chronometricAgeUncertaintyMethod"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">chronometricAgeUncertaintyMethod</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/iri/chronometricAgeUncertaintyMethod">http://rs.tdwg.org/chrono/iri/chronometricAgeUncertaintyMethod</a></td></tr>
    <tr><td>Definition</td><td>The method used to generate the value of chrono:chronometricAgeUncertaintyInYears.</td></tr>
    <tr><td>Comments</td><td>Terms in the chronoiri: namespace are intended to be used in RDF with non-literal objects.</td></tr>
    <tr><td>Examples</td><td></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chronoiri:earliestChronometricAgeReferenceSystem"></span>
    <span id="earliestChronometricAgeReferenceSystem"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">earliestChronometricAgeReferenceSystem</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/iri/earliestChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/iri/earliestChronometricAgeReferenceSystem</a></td></tr>
    <tr><td>Definition</td><td>The reference system associated with the chrono:earliestChronometricAge.</td></tr>
    <tr><td>Comments</td><td>Terms in the chronoiri: namespace are intended to be used in RDF with non-literal objects.</td></tr>
    <tr><td>Examples</td><td></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chronoiri:latestChronometricAgeReferenceSystem"></span>
    <span id="latestChronometricAgeReferenceSystem"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">latestChronometricAgeReferenceSystem</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/iri/latestChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/iri/latestChronometricAgeReferenceSystem</a></td></tr>
    <tr><td>Definition</td><td>The reference system associated with the chrono:latestChronometricAge.</td></tr>
    <tr><td>Comments</td><td>Terms in the chronoiri: namespace are intended to be used in RDF with non-literal objects.</td></tr>
    <tr><td>Examples</td><td></td></tr>
  </tbody>
</table>
<p class="invisible">
  <span id="chronoiri:materialDated"></span>
    <span id="materialDated"></span>
  </p>
<table class="table">
  <tbody>
    <tr class="table-secondary"><th colspan="2">materialDated</th></tr>
    <tr><td>Identifier</td><td><a href="http://rs.tdwg.org/chrono/iri/materialDated">http://rs.tdwg.org/chrono/iri/materialDated</a></td></tr>
    <tr><td>Definition</td><td>The material on which the chrono:chronometricAgeProtocol was actually performed.</td></tr>
    <tr><td>Comments</td><td>Terms in the chronoiri: namespace are intended to be used in RDF with non-literal objects.</td></tr>
    <tr><td>Examples</td><td></td></tr>
  </tbody>
</table>

