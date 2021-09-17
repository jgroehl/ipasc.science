+++
title = "IPASC Thematic Area: Data Acquisition and Management"
subtitle = "Test"
+++

## Leadership Team:

<div class="consortium-table">
{{% md %}}
| Name 						| Affiliation 							|
| ----------- 				| ----------- 							|
| Ben Cox					| University College London				|
| Janek Gröhl 				| University of Cambridge 	|
| Lina Hacker 				| University of Cambridge 				|
{{% /md %}}
</div>

## Mission:

Photoacoustic imaging (PAI) has shown substantial promise in a wide range of applications, but the current lack of
uniformity in PAI data formats compromises inter-device data exchange and comparison. To overcome this challenge, the goal of the
<b>Data Acquisition and Management (DAM)</b> theme is to establish a standard data format with a defined metadata structure, 
and to develop an open source software application programming interface (API) to enable conversion from proprietary file formats into the standard format. 
<br />
By unifying the variety of proprietary data and metadata definitions into a standardised format, the authors hope to facilitate exchange and 
comparison of PAI data, thereby accelerating technological advances within the field.
To achieve this goal the Data Acquisition and Management (DAM) theme is conducting work towards three main goals:

<center>
<img src="../img/2019_dam_goals.png" width="280px" > </img>
</center>

## Progress:

### Goal 1:

We compiled a table summarising information on the technical specifications of PAI systems used throughout the consortium. <br />
From 2018 to 2021, the members of the theme have worked towards a <i>consensus document</i> for photoacoustic data and device parameters. 
The <a href="../documents/20200121_Metadata_list.pdf" target="_blank"><b>[first version of the manuscript]</b></a> was agreed upon by the consortium on the 20th of January 2020 (with 75% agreement from 40 voters). After 1.5 years of continuous integration of feedback,
the <a href="../documents/20210916_IPASC_Format_V2.pdf" target="_blank"><b>[second version of the manuscript]</b></a> was agreed upon on the 14th of July 2021 (with 95% agreement from 20 voters). <br />
The final document can be subject to further changes and optimisation based on feedback from the community and a third version may be published in future.

### Goal 2:
A task force was established within the theme to develop an initial prototype of the open source software tool. The initial prototype was finalized in August 2021 and 
is <a href="https://github.com/IPASC/IPASC_DataConversionTool" target="_blank"><b>[available open source]</b></a> under the BSD 3-Clause License.


### Completed deliverables:

<div class="listing">
<ol>
	<li><p><em><b>Consensus document: Photoacoustic Data and Device Parameters</b></em> This document defines a comprehensive list of minimal and optional parameters required to fully characterise PAI data. 
	This IPASC consensus document contains information on:</p></li>
	<p class="sublisting">
		(1) Definitions of the required terminology.<br />
		(2) A detailed description of the metadata parameters essential to characterize PA devices. <br />
		(3) Definition of the physical units and data format of the respective parameters. <br />
		<br />
		You can find the <i> Agreed Proposal</i> in the <a href="../publications/"> <b>[Publications]</b> </a> section.
	</p>
	<li><p><em><b>Open Source Software Tool Prototype</b></em> The DAM theme has established a first version of a Python software tool that enables the following:</p></li>
	<p class="sublisting">
		(1) Loading and saving of PA time series data into an HDF5 container.<br />
		(2) Integration of custom adapters that allow for the conversion of proprietary formats into the IPASC format. <br />
		(3) Quality Control mechanisms that evaluate the completeness and consistency of the metadata. <br />
		<br />
		You can find the source code of the tool on <a href="https://github.com/IPASC/IPASC_DataConversionTool" target="_blank"> <b>[Github]</b></a>.
	</p>
</ol>

</div>

## Current Projects:

### IPASC Image Reconstruction Project:

The current work of the DAM theme is focused on creating a library of open source image reconstruction algorithms that are compatible with the IPASC data format.
The goal of the project is to evaluate the performance of each of these reconstruction algorithms under numerous different conditions to identify their respective strengths and weaknesses.
The project idea is outlined in the figure below. If you would like to join the project, please feel free to contact any of the DAM theme leads (Ben, Lina, or Janek).

<center>
<img src="../img/IPASC-IRP_ ConceptOverviewAndVision.png" width="1000px" > </img>
</center>