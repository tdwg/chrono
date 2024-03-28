# Chronometric Age Vocabulary List of Terms

Title
: Chronometric Age Vocabulary List of Terms

Namespace IRI:
: http://rs.tdwg.org/chrono/terms/

Preferred namespace abbreviation
: chrono:

Date version issued
: 2021-04-27

Date created
: 2021-04-27

Part of TDWG Standard
: <http://www.tdwg.org/standards/450>

This version
: <http://rs.tdwg.org/dwc/doc/chrono/2021-04-27>

Latest version
: <http://rs.tdwg.org/dwc/doc/chrono/>

Abstract
: The Chronometric Age Vocabulary is a standard for transmitting information about chronometric ages - the processes and results of an assay or other analysis used to determine the age of a MaterialSample. This document lists all terms in namespaces currently used in the vocabulary.

Contributors
: John Wieczorek, Laura Brenskelle, Robert Guralnick, Kitty Emery, Michelle LeFebvre, Neill Wallis, Steve Baskauf, Marie Elise Lecoq, Eric Kansa, Sarah Kansa, Denné Reed

Creator
: TDWG Darwin Core Chronometric Age Extension Task Group

Bibliographic citation
: TDWG Darwin Core Chronometric Age Extension Task Group. 2021. Chronometric Age Vocabulary. Biodiversity Information Standards (TDWG). <http://rs.tdwg.org/dwc/doc/chrono/2021-04-27>


## 1 Introduction

This document contains all versions of terms in the Chronometric Age vocabulary (<http://rs.tdwg.org/version/chrono/2021-02-21>). The vocabulary uses the namespace abbreviation `chrono:`. Earlier term versions using the `zooarchnet:` namespace are deprecated and should no longer be used. These deprecated terms can be found at <http://rs.tdwg.org/chrono/zooarchnet/>.

For a simplified list that contains only the currently recommended terms, see the Chronometric Age Quick Reference Guide (<https://tdwg.github.io/chrono/terms/>).

### 1.1 Status of the content of this document

In Section 4, the values of the `Term IRI`, and `Definition` are normative. The values of `Term Name` are non-normative, although one can expect that the namespace abbreviation prefix is one commonly used for the term namespace.  `Label` and the values of all other properties (such as `Notes` and `Examples`) are non-normative.

### 1.2 RFC 2119 key words
The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

## 2 Use of Terms

The terms in this standard are meant to provide stable definitions that can be used in a variety of contexts, but were envisioned principally to function together as an extension to Darwin Core, where each core record may be annotated by one or more chronometric ages.

## 3 Term index

### 3.1 Index By Term Name

(See also [3.2 Index By Label](#32-index-by-label))

**Classes**

[chrono:ChronometricAge](#chrono_ChronometricAge) 

**Chronometric Age**

[chrono:chronometricAgeConversionProtocol](#chrono_chronometricAgeConversionProtocol) |
[chrono:chronometricAgeDeterminedBy](#chrono_chronometricAgeDeterminedBy) |
[chrono:chronometricAgeDeterminedDate](#chrono_chronometricAgeDeterminedDate) |
[chrono:chronometricAgeID](#chrono_chronometricAgeID) |
[chrono:chronometricAgeProtocol](#chrono_chronometricAgeProtocol) |
[chrono:chronometricAgeReferences](#chrono_chronometricAgeReferences) |
[chrono:chronometricAgeRemarks](#chrono_chronometricAgeRemarks) |
[chrono:chronometricAgeUncertaintyInYears](#chrono_chronometricAgeUncertaintyInYears) |
[chrono:chronometricAgeUncertaintyMethod](#chrono_chronometricAgeUncertaintyMethod) |
[chrono:earliestChronometricAge](#chrono_earliestChronometricAge) |
[chrono:earliestChronometricAgeReferenceSystem](#chrono_earliestChronometricAgeReferenceSystem) |
[chrono:latestChronometricAge](#chrono_latestChronometricAge) |
[chrono:latestChronometricAgeReferenceSystem](#chrono_latestChronometricAgeReferenceSystem) |
[chrono:materialDated](#chrono_materialDated) |
[chrono:materialDatedID](#chrono_materialDatedID) |
[chrono:materialDatedRelationship](#chrono_materialDatedRelationship) |
[chrono:maximumChronometricAge](#chrono_maximumChronometricAge) |
[chrono:maximumChronometricAgeReferenceSystem](#chrono_maximumChronometricAgeReferenceSystem) |
[chrono:minimumChronometricAge](#chrono_minimumChronometricAge) |
[chrono:minimumChronometricAgeReferenceSystem](#chrono_minimumChronometricAgeReferenceSystem) |
[chrono:uncalibratedChronometricAge](#chrono_uncalibratedChronometricAge) |
[chrono:verbatimChronometricAge](#chrono_verbatimChronometricAge) 

**IRI-value terms**

[chronoiri:chronometricAgeConversionProtocol](#chronoiri_chronometricAgeConversionProtocol) |
[chronoiri:chronometricAgeDeterminedBy](#chronoiri_chronometricAgeDeterminedBy) |
[chronoiri:chronometricAgeProtocol](#chronoiri_chronometricAgeProtocol) |
[chronoiri:chronometricAgeUncertaintyMethod](#chronoiri_chronometricAgeUncertaintyMethod) |
[chronoiri:earliestChronometricAgeReferenceSystem](#chronoiri_earliestChronometricAgeReferenceSystem) |
[chronoiri:latestChronometricAgeReferenceSystem](#chronoiri_latestChronometricAgeReferenceSystem) |
[chronoiri:materialDated](#chronoiri_materialDated) 

### 3.2 Index By Label

(See also [3.1 Index By Term Name](#31-index-by-term-name))

**Classes**

[Chronometric Age](#chrono_ChronometricAge) 

**Chronometric Age**

[Chronometric Age Conversion Protocol](#chrono_chronometricAgeConversionProtocol) |
[Chronometric Age Determined By](#chrono_chronometricAgeDeterminedBy) |
[Chronometric Age Determined Date](#chrono_chronometricAgeDeterminedDate) |
[Chronometric Age ID](#chrono_chronometricAgeID) |
[Chronometric Age Protocol](#chrono_chronometricAgeProtocol) |
[Chronometric Age References](#chrono_chronometricAgeReferences) |
[Chronometric Age Remarks](#chrono_chronometricAgeRemarks) |
[Chronometric Age Uncertainty In Years](#chrono_chronometricAgeUncertaintyInYears) |
[Chronometric Age Uncertainty Method](#chrono_chronometricAgeUncertaintyMethod) |
[Earliest Chronometric Age](#chrono_earliestChronometricAge) |
[Earliest Chronometric Age Reference System](#chrono_earliestChronometricAgeReferenceSystem) |
[Latest Chronometric Age](#chrono_latestChronometricAge) |
[Latest Chronometric Age Reference System](#chrono_latestChronometricAgeReferenceSystem) |
[Material Dated](#chrono_materialDated) |
[Material Dated ID](#chrono_materialDatedID) |
[Material Dated Relationship](#chrono_materialDatedRelationship) |
[Maximum Chronometric Age](#chrono_maximumChronometricAge) |
[Maximum Chronometric Age Reference System](#chrono_maximumChronometricAgeReferenceSystem) |
[Minimum Chronometric Age](#chrono_minimumChronometricAge) |
[Minimum Chronometric Age Reference System](#chrono_minimumChronometricAgeReferenceSystem) |
[Uncalibrated Chronometric Age](#chrono_uncalibratedChronometricAge) |
[Verbatim Chronometric Age](#chrono_verbatimChronometricAge) 

**IRI-value terms**

[Chronometric Age Conversion Protocol (IRI)](#chronoiri_chronometricAgeConversionProtocol) |
[Chronometric Age Determined By (IRI)](#chronoiri_chronometricAgeDeterminedBy) |
[Chronometric Age Protocol (IRI)](#chronoiri_chronometricAgeProtocol) |
[Chronometric Age Uncertainty Method (IRI)](#chronoiri_chronometricAgeUncertaintyMethod) |
[Earliest Chronometric Age Reference System (IRI)](#chronoiri_earliestChronometricAgeReferenceSystem) |
[Latest Chronometric Age Reference System (IRI)](#chronoiri_latestChronometricAgeReferenceSystem) |
[Material Dated (IRI)](#chronoiri_materialDated) 

## 4 Vocabulary
<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_ChronometricAge"></a>Term Name  chrono:ChronometricAge</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/ChronometricAge">http://rs.tdwg.org/chrono/terms/ChronometricAge</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-02-21</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/ChronometricAge-2021-02-21">http://rs.tdwg.org/chrono/terms/version/ChronometricAge-2021-02-21</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>An approximation of a temporal position (in the sense conveyed by https://www.w3.org/TR/owl-time/#time:TemporalPosition) that is supported via evidence.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The age of a specimen and how this age is known, whether by a dating assay, a relative association with dated material, or legacy collections information.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><ul class="list-group list-group-flush">
  <li class="list-group-item"><code>An age range associated with a specimen derived from an AMS dating assay applied to an oyster shell in the same stratum</code></li>
  <li class="list-group-item"><code>An age range associated with a specimen derived from a ceramics analysis based on other materials found in the same stratum</code></li>
  <li class="list-group-item"><code>A maximum age associated with a specimen derived from K-Ar dating applied to a proximal volcanic tuff found stratigraphically below the specimen</code></li>
  <li class="list-group-item"><code>An age range of a specimen based on its biostratigraphic context</code></li>
  <li class="list-group-item"><code>An age of a specimen based on what is reported in legacy collections data</code>.</li>
</ul></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-RadiometricDates">https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-RadiometricDates</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Class</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_chronometricAgeConversionProtocol"></a>Term Name  chrono:chronometricAgeConversionProtocol</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeConversionProtocol">http://rs.tdwg.org/chrono/terms/chronometricAgeConversionProtocol</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-02-02</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/chronometricAgeConversionProtocol-2021-02-02">http://rs.tdwg.org/chrono/terms/version/chronometricAgeConversionProtocol-2021-02-02</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Conversion Protocol</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The method used for converting the uncalibratedChronometricAge into a chronometric age in years, as captured in the earliestChronometricAge, earliestChronometricAgeReferenceSystem, latestChronometricAge, and latestChronometricAgeReferenceSystem fields.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>For example, calibration of conventional radiocarbon age or the currently accepted age range of a cultural or geological period.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>INTCAL13</code>, <code>sequential 6 phase Bayesian model and IntCal13 calibration</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-Method">https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-Method</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chronoiri_chronometricAgeConversionProtocol"></a>Term Name  chronoiri:chronometricAgeConversionProtocol</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/chronometricAgeConversionProtocol">http://rs.tdwg.org/chrono/iri/chronometricAgeConversionProtocol</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-02-02</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/version/chronometricAgeConversionProtocol-2021-02-02">http://rs.tdwg.org/chrono/iri/version/chronometricAgeConversionProtocol-2021-02-02</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Conversion Protocol (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The method used to convert the uncalibratedChronometricAge into a chronometric age in years, as captured in earliestChronometricAge, earliestChronometricAgeReferenceSystem, latestChronometricAge, and latestChronometricAgeReferenceSystem.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Terms in the chronoiri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_chronometricAgeDeterminedBy"></a>Term Name  chrono:chronometricAgeDeterminedBy</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedBy">http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedBy</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-02-02</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/chronometricAgeDeterminedBy-2021-02-02">http://rs.tdwg.org/chrono/terms/version/chronometricAgeDeterminedBy-2021-02-02</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Determined By</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A list (concatenated and separated) of names of people, groups, or organizations who determined the ChronometricAge.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to separate the values in a list with space vertical bar space ( | ).</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>Michelle LeFebvre | Neill Wallis</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-Identifiers">https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-Identifiers</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chronoiri_chronometricAgeDeterminedBy"></a>Term Name  chronoiri:chronometricAgeDeterminedBy</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/chronometricAgeDeterminedBy">http://rs.tdwg.org/chrono/iri/chronometricAgeDeterminedBy</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/version/chronometricAgeDeterminedBy-2021-01-26">http://rs.tdwg.org/chrono/iri/version/chronometricAgeDeterminedBy-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Determined By (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A person, group, or organization that determined the ChronometricAge.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Terms in the chronoiri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_chronometricAgeDeterminedDate"></a>Term Name  chrono:chronometricAgeDeterminedDate</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedDate">http://rs.tdwg.org/chrono/terms/chronometricAgeDeterminedDate</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2020-11-17</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/chronometricAgeDeterminedDate-2020-11-17">http://rs.tdwg.org/chrono/terms/version/chronometricAgeDeterminedDate-2020-11-17</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Determined Date</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The date on which the ChronometricAge was determined.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a date that conforms to ISO 8601-1:2019.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>1963-03-08T14:07-0600</code> (8 Mar 1963 at 2:07pm in the time zone six hours earlier than UTC). <code>2009-02-20T08:40Z</code> (20 February 2009 8:40am UTC). <code>2018-08-29T15:19</code> (3:19pm local time on 29 August 2018). <code>1809-02-12</code> (some time during 12 February 1809). <code>1906-06</code> (some time in June 1906). <code>1971</code> (some time in the year 1971).</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-RadiometricDate-AnalysisDateTime">https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-RadiometricDate-AnalysisDateTime</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_chronometricAgeID"></a>Term Name  chrono:chronometricAgeID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeID">http://rs.tdwg.org/chrono/terms/chronometricAgeID</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2020-09-14</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/chronometricAgeID-2020-09-14">http://rs.tdwg.org/chrono/terms/version/chronometricAgeID-2020-09-14</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age ID</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>An identifier for the set of information associated with a ChronometricAge.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>May be a global unique identifier or an identifier specific to the dataset. This can be used to link this record to another repository where more information about the dataset is shared.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code><a href="https://www.canadianarchaeology.ca/samples/70673">https://www.canadianarchaeology.ca/samples/70673</a></code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_chronometricAgeProtocol"></a>Term Name  chrono:chronometricAgeProtocol</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeProtocol">http://rs.tdwg.org/chrono/terms/chronometricAgeProtocol</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2020-11-17</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/chronometricAgeProtocol-2020-11-17">http://rs.tdwg.org/chrono/terms/version/chronometricAgeProtocol-2020-11-17</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Protocol</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A description of or reference to the methods used to determine the chronometric age.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>radiocarbon AMS</code>, <code>K-Ar dates for the lower most marker tuff</code>, <code>historic documentation</code>, <code>ceramic seriation</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-Method">https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-Method</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chronoiri_chronometricAgeProtocol"></a>Term Name  chronoiri:chronometricAgeProtocol</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/chronometricAgeProtocol">http://rs.tdwg.org/chrono/iri/chronometricAgeProtocol</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/version/chronometricAgeProtocol-2021-01-26">http://rs.tdwg.org/chrono/iri/version/chronometricAgeProtocol-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Protocol (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A method used to determine the chronometric age.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Terms in the chronoiri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_chronometricAgeReferences"></a>Term Name  chrono:chronometricAgeReferences</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeReferences">http://rs.tdwg.org/chrono/terms/chronometricAgeReferences</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2020-11-17</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/chronometricAgeReferences-2020-11-17">http://rs.tdwg.org/chrono/terms/version/chronometricAgeReferences-2020-11-17</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age References</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A list (concatenated and separated) of identifiers (publication, bibliographic reference, global unique identifier, URI) of literature associated with the ChronometricAge.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to separate the values in a list with space vertical bar space ( | ).</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>Pluckhahn, Thomas J., Neill J. Wallis, and Victor D. Thompson. 2020  The History and Future of Migrationist Explanation in the Archaeology of the Eastern Woodlands: A Review and Case Study of the Woodland Period Gulf Coast. Journal of Archaeological Research. <a href="https://doi.org/10.1007/s10814-019-09140-x">https://doi.org/10.1007/s10814-019-09140-x</a></code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-MeasurementOrFactReference">https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-MeasurementOrFactReference</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_chronometricAgeRemarks"></a>Term Name  chrono:chronometricAgeRemarks</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeRemarks">http://rs.tdwg.org/chrono/terms/chronometricAgeRemarks</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2020-11-17</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/chronometricAgeRemarks-2020-11-17">http://rs.tdwg.org/chrono/terms/version/chronometricAgeRemarks-2020-11-17</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Remarks</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Notes or comments about the ChronometricAge.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>Beta Analytic number: 323913 | One of the Crassostrea virginica right valve specimens from North Midden Feature 17 was chosen for AMS dating, but it is unclear exactly which specimen it was.</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-DatingComment">https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-DatingComment</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_chronometricAgeUncertaintyInYears"></a>Term Name  chrono:chronometricAgeUncertaintyInYears</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyInYears">http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyInYears</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-02-02</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/chronometricAgeUncertaintyInYears-2021-02-02">http://rs.tdwg.org/chrono/terms/version/chronometricAgeUncertaintyInYears-2021-02-02</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Uncertainty In Years</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The temporal uncertainty of the earliestChronometricAge and latestChronometicAge in years.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The expected unit for this field is years. The value in this field is number of years before and after the values given in the earliest and latest chronometric age fields within which the actual values are estimated to be.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>100</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-ChronostratigraphicAttribution-Accuracy">https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-ChronostratigraphicAttribution-Accuracy</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chronoiri_chronometricAgeUncertaintyMethod"></a>Term Name  chronoiri:chronometricAgeUncertaintyMethod</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/chronometricAgeUncertaintyMethod">http://rs.tdwg.org/chrono/iri/chronometricAgeUncertaintyMethod</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/version/chronometricAgeUncertaintyMethod-2021-01-26">http://rs.tdwg.org/chrono/iri/version/chronometricAgeUncertaintyMethod-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Uncertainty Method (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The method used to generate the value of chronometricAgeUncertaintyInYears.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Terms in the chronoiri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_chronometricAgeUncertaintyMethod"></a>Term Name  chrono:chronometricAgeUncertaintyMethod</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyMethod">http://rs.tdwg.org/chrono/terms/chronometricAgeUncertaintyMethod</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2020-11-17</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/chronometricAgeUncertaintyMethod-2020-11-17">http://rs.tdwg.org/chrono/terms/version/chronometricAgeUncertaintyMethod-2020-11-17</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Chronometric Age Uncertainty Method</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The method used to generate the value of chronometricAgeUncertaintyInYears.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>2-sigma calibrated range</code>, <code>Half of 95% confidence interval</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-Method">https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-Method</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_earliestChronometricAge"></a>Term Name  chrono:earliestChronometricAge</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/earliestChronometricAge">http://rs.tdwg.org/chrono/terms/earliestChronometricAge</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/earliestChronometricAge-2021-01-26">http://rs.tdwg.org/chrono/terms/version/earliestChronometricAge-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Earliest Chronometric Age</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The maximum/earliest/oldest possible age of a specimen as determined by a dating method.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The expected unit for this field is years. This field, if populated, must have an associated earliestChronometricAgeReferenceSystem.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>100</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-UpperValue">https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-UpperValue</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chronoiri_earliestChronometricAgeReferenceSystem"></a>Term Name  chronoiri:earliestChronometricAgeReferenceSystem</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/earliestChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/iri/earliestChronometricAgeReferenceSystem</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/version/earliestChronometricAgeReferenceSystem-2021-01-26">http://rs.tdwg.org/chrono/iri/version/earliestChronometricAgeReferenceSystem-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Earliest Chronometric Age Reference System (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The reference system associated with the earliestChronometricAge.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Terms in the chronoiri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_earliestChronometricAgeReferenceSystem"></a>Term Name  chrono:earliestChronometricAgeReferenceSystem</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/earliestChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/terms/earliestChronometricAgeReferenceSystem</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/earliestChronometricAgeReferenceSystem-2021-01-26">http://rs.tdwg.org/chrono/terms/version/earliestChronometricAgeReferenceSystem-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Earliest Chronometric Age Reference System</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The reference system associated with the earliestChronometricAge.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>kya</code>,<code>mya</code>,<code>BP</code>,<code>AD</code>,<code>BCE</code>,<code>ka</code>,<code>Ma</code>,<code>Ga</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_latestChronometricAge"></a>Term Name  chrono:latestChronometricAge</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/latestChronometricAge">http://rs.tdwg.org/chrono/terms/latestChronometricAge</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/latestChronometricAge-2021-01-26">http://rs.tdwg.org/chrono/terms/version/latestChronometricAge-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Latest Chronometric Age</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The minimum/latest/youngest possible age of a specimen as determined by a dating method.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The expected unit for this field is years. This field, if populated, must have an associated latestChronometricAgeReferenceSystem.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>27</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-ChronostratigraphicAttribution-LowerValue">https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-ChronostratigraphicAttribution-LowerValue</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_latestChronometricAgeReferenceSystem"></a>Term Name  chrono:latestChronometricAgeReferenceSystem</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/latestChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/terms/latestChronometricAgeReferenceSystem</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/latestChronometricAgeReferenceSystem-2021-01-26">http://rs.tdwg.org/chrono/terms/version/latestChronometricAgeReferenceSystem-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Latest Chronometric Age Reference System</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The reference system associated with the latestChronometricAge.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>kya</code>,<code>mya</code>,<code>BP</code>,<code>AD</code>,<code>BCE</code>,<code>ka</code>,<code>Ma</code>,<code>Ga</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chronoiri_latestChronometricAgeReferenceSystem"></a>Term Name  chronoiri:latestChronometricAgeReferenceSystem</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/latestChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/iri/latestChronometricAgeReferenceSystem</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/version/latestChronometricAgeReferenceSystem-2021-01-26">http://rs.tdwg.org/chrono/iri/version/latestChronometricAgeReferenceSystem-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Latest Chronometric Age Reference System (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The reference system associated with the latestChronometricAge.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Terms in the chronoiri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chronoiri_materialDated"></a>Term Name  chronoiri:materialDated</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/materialDated">http://rs.tdwg.org/chrono/iri/materialDated</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/iri/version/materialDated-2021-01-26">http://rs.tdwg.org/chrono/iri/version/materialDated-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Material Dated (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The material on which the chronometricAgeProtocol was actually performed.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Terms in the chronoiri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_materialDated"></a>Term Name  chrono:materialDated</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/materialDated">http://rs.tdwg.org/chrono/terms/materialDated</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2020-11-17</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/materialDated-2020-11-17">http://rs.tdwg.org/chrono/terms/version/materialDated-2020-11-17</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Material Dated</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A description of the material on which the chronometricAgeProtocol was actually performed, if known.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>Double Tuff</code>, <code>Charcoal found in Stratum V</code>, <code>charred wood</code>, <code>tooth</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-MaterialDated">https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-MaterialDated</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_materialDatedID"></a>Term Name  chrono:materialDatedID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/materialDatedID">http://rs.tdwg.org/chrono/terms/materialDatedID</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-02-05</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/materialDatedID-2021-02-05">http://rs.tdwg.org/chrono/terms/version/materialDatedID-2021-02-05</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Material Dated ID</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>An identifier for the MaterialSample on which the chronometricAgeProtocol was performed, if applicable.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>dwc:materialSampleID: <a href="https://www.ebi.ac.uk/metagenomics/samples/SRS1930158">https://www.ebi.ac.uk/metagenomics/samples/SRS1930158</a></code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_materialDatedRelationship"></a>Term Name  chrono:materialDatedRelationship</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/materialDatedRelationship">http://rs.tdwg.org/chrono/terms/materialDatedRelationship</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/materialDatedRelationship-2021-01-26">http://rs.tdwg.org/chrono/terms/version/materialDatedRelationship-2021-01-26</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Material Dated Relationship</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The relationship of the materialDated to the subject of the ChronometricAge record, from which the ChronometricAge of the subject is inferred.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>sameAs</code> (cases where the subject material was completely destructively subsampled to get the ChronometricAge), <code>subsampleOf</code> (cases where part of the original specimen was extracted as the material used to determine the ChronometricAge), <code>inContextWith</code> (cases where the ChronometricAge is inferred from materialDated, such as sediments or cultural objects, in related temporal context),<code>stratigraphicallyCorrelatedWith</code> (cases where the ChronometricAge is inferred from materialDated in a stratigraphically correlated context)</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_maximumChronometricAge"></a>Term Name  chrono:maximumChronometricAge</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/maximumChronometricAge">http://rs.tdwg.org/chrono/terms/maximumChronometricAge</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Maximum Chronometric Age</td>
		</tr>
		<tr>
			<td></td>
			<td><strong>This term is deprecated and should no longer be used.</strong></td>
		</tr>
		<tr>
			<td>Is replaced by</td>
			<td><a href="#chrono_earliestChronometricAge">http://rs.tdwg.org/chrono/terms/earliestChronometricAge</a></td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Upper limit for the age of a specimen as determined by a dating method.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The expected unit for this field is years. This field, if populated, must have an associated maximumChronometricAgeReferenceSystem.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>27</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-UpperValue">https://terms.tdwg.org/wiki/abcd-efg:StratigraphicAttributions-ChronostratigraphicAttribution-UpperValue</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_maximumChronometricAgeReferenceSystem"></a>Term Name  chrono:maximumChronometricAgeReferenceSystem</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/maximumChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/terms/maximumChronometricAgeReferenceSystem</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Maximum Chronometric Age Reference System</td>
		</tr>
		<tr>
			<td></td>
			<td><strong>This term is deprecated and should no longer be used.</strong></td>
		</tr>
		<tr>
			<td>Is replaced by</td>
			<td><a href="#chrono_earliestChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/terms/earliestChronometricAgeReferenceSystem</a></td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The reference system associated with the maximumChronometricAge.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>kya</code>,<code>mya</code>,<code>BP</code>,<code>AD</code>,<code>BCE</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-TimeUnit">https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-TimeUnit</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_minimumChronometricAge"></a>Term Name  chrono:minimumChronometricAge</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/minimumChronometricAge">http://rs.tdwg.org/chrono/terms/minimumChronometricAge</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Minimum Chronometric Age</td>
		</tr>
		<tr>
			<td></td>
			<td><strong>This term is deprecated and should no longer be used.</strong></td>
		</tr>
		<tr>
			<td>Is replaced by</td>
			<td><a href="#chrono_latestChronometricAge">http://rs.tdwg.org/chrono/terms/latestChronometricAge</a></td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Lower limit for the age of a specimen as determined by a dating method.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The expected unit for this field is years. This field, if populated, must have an associated maximumChronometricAgeReferenceSystem.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>100</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-ChronostratigraphicAttribution-LowerValue">https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-ChronostratigraphicAttribution-LowerValue</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_minimumChronometricAgeReferenceSystem"></a>Term Name  chrono:minimumChronometricAgeReferenceSystem</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/minimumChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/terms/minimumChronometricAgeReferenceSystem</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-01-26</td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Minimum Chronometric Age Reference System</td>
		</tr>
		<tr>
			<td></td>
			<td><strong>This term is deprecated and should no longer be used.</strong></td>
		</tr>
		<tr>
			<td>Is replaced by</td>
			<td><a href="#chrono_latestChronometricAgeReferenceSystem">http://rs.tdwg.org/chrono/terms/latestChronometricAgeReferenceSystem</a></td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The reference system associated with the minimumChronometricAge.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>kya</code>,<code>mya</code>,<code>BP</code>,<code>AD</code>,<code>BCE</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-TimeUnit">https://terms.tdwg.org/wiki/abcd-efg:UnitStratigraphicDetermination-TimeUnit</a></td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_uncalibratedChronometricAge"></a>Term Name  chrono:uncalibratedChronometricAge</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/uncalibratedChronometricAge">http://rs.tdwg.org/chrono/terms/uncalibratedChronometricAge</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2020-09-14</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/uncalibratedChronometricAge-2020-09-14">http://rs.tdwg.org/chrono/terms/version/uncalibratedChronometricAge-2020-09-14</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Uncalibrated Chronometric Age</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The output of a dating assay before it is calibrated into an age using a specific conversion protocol.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>1510 +/- 25 14C yr BP</code>, <code>16.26 Ma +/- 0.016</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="chrono_verbatimChronometricAge"></a>Term Name  chrono:verbatimChronometricAge</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/verbatimChronometricAge">http://rs.tdwg.org/chrono/terms/verbatimChronometricAge</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2020-09-14</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/chrono/terms/version/verbatimChronometricAge-2020-09-14">http://rs.tdwg.org/chrono/terms/version/verbatimChronometricAge-2020-09-14</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Verbatim Chronometric Age</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The verbatim age for a specimen, whether reported by a dating assay, associated references, or legacy information.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>For example, this could be the radiocarbon age as given in an AMS dating report. This could also be simply what is reported as the age of a specimen in legacy collections data.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td><code>27 BC to 14 AD</code>, <code>stratigraphically pre-1104</code></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2021-04-27_33">http://rs.tdwg.org/decisions/decision-2021-04-27_33</a></td>
		</tr>
	</tbody>
</table>


