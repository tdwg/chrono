---
container: fluid
---

# Chronometric Age quick reference guide

NOTE: This document forms part of a proposal by the [Chronometric Age Extension Task Group](https://www.tdwg.org/community/esp/chrono/) to extend Darwin Core with vocabulary for chronometric ages. It is not yet ratified and may change as a result of recommendations received during the course of Open Public Commentary.

This document is intended to be an easy-to-read reference of the currently recommended terms maintained as part of the [Chronometric Age standard](https://www.tdwg.org/standards/chrono/). This page itself is not part of the standard. It draws on the [term names and definitions](../list/) from the normative part of the standard and combines them with comments and examples that are not normative, but that are meant to help people to use the terms consistently. The category `ChronometricAge` corresponds to the parent class, which is a special category term used to group the rest of the terms for convenience. Comprehensive metadata for current and obsolete terms in human readable form are found in a [list of terms document](../list/). [CSV files](https://github.com/tdwg/chrono/tree/master/dist) with horizontal and vertical lists of these terms and their [full history](https://github.com/tdwg/chrono/blob/master/vocabulary/term_versions.csv) can be found in the [Chronometric Age repository](https://github.com/tdwg/chrono).


## ChronometricAge

<div class="my-4">
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:chronometricAgeID">chronometricAgeID</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:verbatimChronometricAge">verbatimChronometricAge</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:chronometricAgeProtocol">chronometricAgeProtocol</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:uncalibratedChronometricAge">uncalibratedChronometricAge</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:chronometricAgeConversionProtocol">chronometricAgeConversionProtocol</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:maximumChronometricAge">maximumChronometricAge</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:maximumChronometricAgeReferenceSystem">maximumChronometricAgeReferenceSystem</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:minimumChronometricAge">minimumChronometricAge</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:minimumChronometricAgeReferenceSystem">minimumChronometricAgeReferenceSystem</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:chronometricAgeUncertaintyInYears">chronometricAgeUncertaintyInYears</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:chronometricAgeUncertaintyMethod">chronometricAgeUncertaintyMethod</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:materialDated">materialDated</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:materialDatedID">materialDatedID</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:chronometricAgeDeterminedBy">chronometricAgeDeterminedBy</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:chronometricAgeDeterminedDate">chronometricAgeDeterminedDate</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:chronometricAgeReferences">chronometricAgeReferences</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#chrono:chronometricAgeRemarks">chronometricAgeRemarks</a>
    </div>

<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-primary"><th colspan="2">ChronometricAge <span class="badge badge-primary float-right">Class</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/ChronometricAge">http://rs.tdwg.org/chrono/terms/ChronometricAge</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The age of a specimen or related materials that is generated from a dating assay.</td></tr>
        <tr><td class="theme-label">Comments</td><td>This is a categorical term (class) to organize the other chronometric age properties and does not ever have values.</td></tr>
        <tr><td class="theme-label">Examples</td><td>A radiocarbon date. A date determined through dendrochronology. A date derived using the potassium-argon method.</td></tr>
    </tbody>
</table>

<p class="invisible">
    <a id="chrono:chronometricAgeID"></a><a id="chronometricAgeID"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeID <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeID">http://rs.tdwg.org/chrono/terms/chronometricAgeID</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>An identifier for the set of information associated with a ChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td>May be a global unique identifier or an identifier specific to the dataset. This can be used to link this record to another repository where more information about the dataset is shared.</td></tr>
        <tr><td class="theme-label">Examples</td><td><code><a href="https://www.canadianarchaeology.ca/samples/70673">https://www.canadianarchaeology.ca/samples/70673</a></code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:verbatimChronometricAge"></a><a id="verbatimChronometricAge"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">verbatimChronometricAge <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/verbatimChronometricAge">http://rs.tdwg.org/chrono/terms/verbatimChronometricAge</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The verbatim age for a specimen, whether reported by a dating assay, associated references, or legacy information.</td></tr>
        <tr><td class="theme-label">Comments</td><td>For example, this could be the radiocarbon age as given in an AMS dating report. This could also be simply what is reported as the age of a specimen in legacy collections data.</td></tr>
        <tr><td class="theme-label">Examples</td><td><code>27 BC to 14 AD</code>, <code>stratigraphically pre-1104</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:chronometricAgeProtocol"></a><a id="chronometricAgeProtocol"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeProtocol <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeProtocol">http://rs.tdwg.org/chrono/terms/chronometricAgeProtocol</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>A description of or reference to the methods used to determine the chronometric age.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>radiocarbon AMS</code>, <code>K-Ar dates for the lower most marker tuff</code>, <code>historic documentation</code>, <code>ceramic seriation</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:uncalibratedChronometricAge"></a><a id="uncalibratedChronometricAge"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">uncalibratedChronometricAge <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/uncalibratedChronometricAge">http://rs.tdwg.org/chrono/terms/uncalibratedChronometricAge</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The output of a dating assay before it is calibrated into an age using a specific conversion protocol.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>1510 +/- 25 14C yr BP</code>, <code>16.26 Ma +/- 0.016</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:chronometricAgeConversionProtocol"></a><a id="chronometricAgeConversionProtocol"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeConversionProtocol <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeConversionProtocol">http://rs.tdwg.org/chrono/terms/chronometricAgeConversionProtocol</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The method used to convert the uncalibratedChronometricAge into a chronometric age in years, as captured in maximumChronometricAge, maximumChronometricAgeReferenceSystem, minimumChronometricAge, and minimumChronometricAgeReferenceSystem.</td></tr>
        <tr><td class="theme-label">Comments</td><td>For example, calibration of conventional radiocarbon age or the currently accepted age range of a cultural or geological period.</td></tr>
        <tr><td class="theme-label">Examples</td><td><code>INTCAL13</code>, <code>sequential 6 phase Bayesian model and IntCal13 calibration</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:maximumChronometricAge"></a><a id="maximumChronometricAge"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">maximumChronometricAge <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/maximumChronometricAge">http://rs.tdwg.org/chrono/terms/maximumChronometricAge</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>Upper limit for the age of a specimen as determined by a dating method.</td></tr>
        <tr><td class="theme-label">Comments</td><td>The expected unit for this field is years. This field, if populated, must have an associated maximumChronometricAgeReferenceSystem.</td></tr>
        <tr><td class="theme-label">Examples</td><td><code>27</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:maximumChronometricAgeReferenceSystem"></a><a id="maximumChronometricAgeReferenceSystem"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">maximumChronometricAgeReferenceSystem <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/maximumChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/terms/maximumChronometricAgeReferenceSystem</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The reference system associated with the maximumChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>kya</code>,<code>mya</code>,<code>BP</code>,<code>AD</code>,<code>BCE</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:minimumChronometricAge"></a><a id="minimumChronometricAge"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">minimumChronometricAge <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/minimumChronometricAge">http://rs.tdwg.org/chrono/terms/minimumChronometricAge</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>Lower limit for the age of a specimen as determined by a dating method.</td></tr>
        <tr><td class="theme-label">Comments</td><td>The expected unit for this field is years. This field, if populated, must have an associated minimumChronometricAgeReferenceSystem.</td></tr>
        <tr><td class="theme-label">Examples</td><td><code>100</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:minimumChronometricAgeReferenceSystem"></a><a id="minimumChronometricAgeReferenceSystem"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">minimumChronometricAgeReferenceSystem <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/minimumChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/terms/minimumChronometricAgeReferenceSystem</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The reference system associated with the minimumChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>kya</code>,<code>mya</code>,<code>BP</code>,<code>AD</code>,<code>BCE</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:chronometricAgeUncertaintyInYears"></a><a id="chronometricAgeUncertaintyInYears"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeUncertaintyInYears <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyInYears">http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyInYears</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The temporal uncertainty of the maximumChronometricAge and minimumChronometicAge in years.</td></tr>
        <tr><td class="theme-label">Comments</td><td>This is the +/- number for the age in years. The expected unit for this field is years.</td></tr>
        <tr><td class="theme-label">Examples</td><td><code>100</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:chronometricAgeUncertaintyMethod"></a><a id="chronometricAgeUncertaintyMethod"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeUncertaintyMethod <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyMethod">http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyMethod</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The method used to generate the value of chronometricAgeUncertaintyInYears.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>2-sigma calibrated range</code>, <code>Half of 95% confidence interval</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:materialDated"></a><a id="materialDated"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">materialDated <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/materialDated">http://rs.tdwg.org/chrono/terms/materialDated</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>A description of the material on which the chronometricAgeProtocol was actually performed, if known.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>Double Tuff</code>, <code>Charcoal found in Stratum V</code>, <code>charred wood</code>, <code>tooth</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:materialDatedID"></a><a id="materialDatedID"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">materialDatedID <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/materialDatedID">http://rs.tdwg.org/chrono/terms/materialDatedID</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>An identifier for the material on which the chronometricAgeProtocol was performed, if applicable.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>dwc:occurrenceID: 702b306d-f167-44d0-a5c9-890ece2b8839</code>, <code><a href="https://www.idigbio.org/portal/records/e1438058-c8b9-418e-998e-1e497a3bcec4">https://www.idigbio.org/portal/records/e1438058-c8b9-418e-998e-1e497a3bcec4</a></code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:chronometricAgeDeterminedBy"></a><a id="chronometricAgeDeterminedBy"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeDeterminedBy <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedBy">http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedBy</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>A list (concatenated and separated) of names of people, groups, or organizations who determined the ChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td>Recommended best practice is to separate the values in a list with space vertical bar space ( | ).</td></tr>
        <tr><td class="theme-label">Examples</td><td><code>Michelle LeFebvre | Neill Wallis</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:chronometricAgeDeterminedDate"></a><a id="chronometricAgeDeterminedDate"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeDeterminedDate <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedDate">http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedDate</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The date on which the ChronometricAge was determined.</td></tr>
        <tr><td class="theme-label">Comments</td><td>Recommended best practice is to use a date that conforms to ISO 8601-1:2019.</td></tr>
        <tr><td class="theme-label">Examples</td><td><code>1963-03-08T14:07-0600</code> (8 Mar 1963 at 2:07pm in the time zone six hours earlier than UTC). <code>2009-02-20T08:40Z</code> (20 February 2009 8:40am UTC). <code>2018-08-29T15:19</code> (3:19pm local time on 29 August 2018). <code>1809-02-12</code> (some time during 12 February 1809). <code>1906-06</code> (some time in June 1906). <code>1971</code> (some time in the year 1971).</td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:chronometricAgeReferences"></a><a id="chronometricAgeReferences"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeReferences <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeReferences">http://rs.tdwg.org/chrono/terms/chronometricAgeReferences</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>A list (concatenated and separated) of identifiers (publication, bibliographic reference, global unique identifier, URI) of literature associated with the ChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td>Recommended best practice is to separate the values in a list with space vertical bar space ( | ).</td></tr>
        <tr><td class="theme-label">Examples</td><td><code>Pluckhahn, Thomas J., Neill J. Wallis, and Victor D. Thompson. 2020  The History and Future of Migrationist Explanation in the Archaeology of the Eastern Woodlands: A Review and Case Study of the Woodland Period Gulf Coast. Journal of Archaeological Research. <a href="https://doi.org/10.1007/s10814-019-09140-x">https://doi.org/10.1007/s10814-019-09140-x</a></code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="chrono:chronometricAgeRemarks"></a><a id="chronometricAgeRemarks"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeRemarks <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeRemarks">http://rs.tdwg.org/chrono/terms/chronometricAgeRemarks</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>Notes or comments about the ChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>Beta Analytic number: 323913 | One of the Crassostrea virginica right valve specimens from North Midden Feature 17 was chosen for AMS dating, but it is unclear exactly which specimen it was.</code></td></tr>
    </tbody>
</table>

