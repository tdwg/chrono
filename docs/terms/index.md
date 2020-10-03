---
container: fluid
---

# Chronometric Age quick reference guide

This document is intended to be an easy-to-read reference of the currently recommended terms maintained as part of the [Chronometric Age standard](https://www.tdwg.org/standards/chrono/). This page itself is not part of the standard. It draws on the term names and definitions from the normative part of the standard and combines them with comments and examples that are not normative, but that are meant to help people to use the terms consistently. The category `ChronometricAge corresponds to the parent class, which is a special category term used to group the rest of the terms for convenience. Comprehensive metadata for current and obsolete terms in human readable form are found in a [list of terms document](../list/). [Files with lists of these terms](https://github.com/tdwg/chrono/tree/master/dist) and [their full history](https://github.com/tdwg/chrono/blob/master/vocabulary/term_versions.csv) can be found in the [Chronometric Age repository](https://github.com/tdwg/chrono).


## Record-level

<div class="my-4">
    </div>




## ChronometricAge

<div class="my-4">
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:chronometricAgeID">chronometricAgeID</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:verbatimChronometricAge">verbatimChronometricAge</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:verbatimChronometricAgeConversionProtocol">verbatimChronometricAgeConversionProtocol</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:maximumChronometricAge">maximumChronometricAge</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:maximumChronometricAgeReferenceSystem">maximumChronometricAgeReferenceSystem</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:minimumChronometricAge">minimumChronometricAge</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:minimumChronometricAgeReferenceSystem">minimumChronometricAgeReferenceSystem</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:chronometricAgeUncertaintyInYears">chronometricAgeUncertaintyInYears</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:chronometricAgeUncertaintyMethod">chronometricAgeUncertaintyMethod</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:materialDated">materialDated</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:materialDatedID">materialDatedID</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:chronometricAgeProtocol">chronometricAgeProtocol</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:chronometricAgeReferences">chronometricAgeReferences</a>
        <a class="btn btn-sm btn-outline-secondary m-1" href="#zooarchnet:chronometricAgeRemarks">chronometricAgeRemarks</a>
    </div>

<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-primary"><th colspan="2">ChronometricAge <span class="badge badge-primary float-right">Class</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/ChronometricAge">http://zooarchnet.org/dwc/terms/ChronometricAge</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The age of a specimen or related materials that is generated from a dating assay.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td></td></tr>
    </tbody>
</table>

<p class="invisible">
    <a id="zooarchnet:chronometricAgeID"></a><a id="chronometricAgeID"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeID <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/chronometricAgeID">http://zooarchnet.org/dwc/terms/chronometricAgeID</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>An identifier for the set of information associated with a ChronometricAge. May be a global unique identifier or an identifier specific to the data set.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:verbatimChronometricAge"></a><a id="verbatimChronometricAge"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">verbatimChronometricAge <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/verbatimChronometricAge">http://zooarchnet.org/dwc/terms/verbatimChronometricAge</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The verbatim age for a specimen, whether reported by a dating assay, associated references, or legacy information. For example, this could be the conventional radiocarbon age as given in an AMS dating report. This could also be simply what is reported as the age of a specimen in legacy collections data.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>27 BC to 14 AD</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:verbatimChronometricAgeConversionProtocol"></a><a id="verbatimChronometricAgeConversionProtocol"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">verbatimChronometricAgeConversionProtocol <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/verbatimChronometricAgeConversionProtocol">http://zooarchnet.org/dwc/terms/verbatimChronometricAgeConversionProtocol</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The method used for converting the verbatimChronometricAge into a chronometric age in years, as captured in the maximumChronometricAge, maximumChronometricAgeReferenceSystem, minimumChronometricAge, and minimumChronometricAgeReferenceSystem fields. For example, calibration of conventional radiocarbon age or the currently accepted age range of a cultural or geological period.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:maximumChronometricAge"></a><a id="maximumChronometricAge"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">maximumChronometricAge <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/maximumChronometricAge">http://zooarchnet.org/dwc/terms/maximumChronometricAge</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>Upper limit for the age of a specimen as determined by a dating method. The expected unit for this field is years. This field, if populated, must have an associated maximumChronometricAgeReferenceSystem.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>27</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:maximumChronometricAgeReferenceSystem"></a><a id="maximumChronometricAgeReferenceSystem"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">maximumChronometricAgeReferenceSystem <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/maximumChronometricAgeReferenceSystem">http://zooarchnet.org/dwc/terms/maximumChronometricAgeReferenceSystem</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The reference system associated with the maximumChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>kya</code>, <code>mya</code>, <code>BP</code>, <code>AD</code>, <code>BCE</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:minimumChronometricAge"></a><a id="minimumChronometricAge"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">minimumChronometricAge <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/minimumChronometricAge">http://zooarchnet.org/dwc/terms/minimumChronometricAge</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>Lower limit for the age of a specimen as determined by a dating method. The expected unit for this field is years. This field, if populated, must have an associated maximumChronometricAgeReferenceSystem.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>14</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:minimumChronometricAgeReferenceSystem"></a><a id="minimumChronometricAgeReferenceSystem"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">minimumChronometricAgeReferenceSystem <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/minimumChronometricAgeReferenceSystem">http://zooarchnet.org/dwc/terms/minimumChronometricAgeReferenceSystem</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The reference system associated with the minimumChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>kya</code>, <code>mya</code>, <code>BP</code>, <code>AD</code>, <code>BCE</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:chronometricAgeUncertaintyInYears"></a><a id="chronometricAgeUncertaintyInYears"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeUncertaintyInYears <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/chronometricAgeUncertaintyInYears">http://zooarchnet.org/dwc/terms/chronometricAgeUncertaintyInYears</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The temporal uncertainty of the maximumChronometricAge and minimumChronometicAge, in years.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td><code>100</code></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:chronometricAgeUncertaintyMethod"></a><a id="chronometricAgeUncertaintyMethod"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeUncertaintyMethod <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/chronometricAgeUncertaintyMethod">http://zooarchnet.org/dwc/terms/chronometricAgeUncertaintyMethod</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>The method used to generate the reported uncertainty calculations.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:materialDated"></a><a id="materialDated"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">materialDated <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/materialDated">http://zooarchnet.org/dwc/terms/materialDated</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>A description of the material on which the chronometricAgeProtocol was actually performed, if known.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:materialDatedID"></a><a id="materialDatedID"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">materialDatedID <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/materialDatedID">http://zooarchnet.org/dwc/terms/materialDatedID</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>An identifier for the material on which the chronometricAgeProtocol was performed, if applicable.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:chronometricAgeProtocol"></a><a id="chronometricAgeProtocol"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeProtocol <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/chronometricAgeProtocol">http://zooarchnet.org/dwc/terms/chronometricAgeProtocol</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>A description of or reference to the methods used to determine the ChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:chronometricAgeReferences"></a><a id="chronometricAgeReferences"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeReferences <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/chronometricAgeReferences">http://zooarchnet.org/dwc/terms/chronometricAgeReferences</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>A list (concatenated and separated) of identifiers (publication, bibliographic reference, global unique identifier, URI) of literature associated with the ChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td></td></tr>
    </tbody>
</table>
<p class="invisible">
    <a id="zooarchnet:chronometricAgeRemarks"></a><a id="chronometricAgeRemarks"></a></p>
<table class="table table-sm table-bordered">
    <tbody>
        <tr class="table-secondary"><th colspan="2">chronometricAgeRemarks <span class="badge badge-secondary float-right">Property</span></th></tr>
        <tr><td class="theme-label">Identifier</td><td><a href="http://zooarchnet.org/dwc/terms/chronometricAgeRemarks">http://zooarchnet.org/dwc/terms/chronometricAgeRemarks</a></td></tr>
        <tr><td class="theme-label">Definition</td><td>Notes or comments about the ChronometricAge.</td></tr>
        <tr><td class="theme-label">Comments</td><td></td></tr>
        <tr><td class="theme-label">Examples</td><td></td></tr>
    </tbody>
</table>

