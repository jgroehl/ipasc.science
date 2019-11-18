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
| Janek Gröhl 				| German Cancer Research Center (DKFZ) 	|
| Lina Hacker 				| University of Cambridge 				|
{{% /md %}}
</div>

## Mission:

Our overarching goal is to enable intercomparison of photoacoustic imaging (PAI) data between different users (scientific groups / industries). To achieve this goal the Data Acquisition and Management (DAM) theme is conducting work towards three main goals:

<center>
<img src="../img/2019_dam_goals.png" width="280px" > </img>
</center>

Goal 1 is to define an essential list of metadata to fully characterise the format of PAI data acquired from commercial and custom-built PAI instruments and to transfer the device-specific data of instruments within the consortium to an open access database. Goal 2 is to implement an open source tool that enables conversion to the prior agreed standardized data format (HDF5). Goal 3 is to provide an open-access platform for PA reference data that can be used for comparison of processing algorithms etc.


## Progress:

A table summarizing information on the technical specifications of all PAI systems that are used within the consortium has been created and three main recommendations have been made: (1) To initially only include raw time series data into the standardization, (2) To use HDF5 as the standardized file format, and (3) To create a standardized list of metadata parameters. Furthermore, the working group has formulated a plan to create an open source conversion tool between data formats.

## Proposed deliverables:

<div class="listing">
<h3>Towards goal 1:</h3>
<ol>
	<li><p><em><b>Consensus document:</b></em> This document aims to define a comprehensive list of necessary parameters to fully characterise PAI data. IPASC consensus should be reached on:</p></li>
	<p class="sublisting">
		(1) Definitions of the required terminology.<br />
		(2) A detailed description of the metadata parameters identified as being essential to characterize PA devices. <br />
		(3) Definition of the physical units and data format of the respective parameters.
	</p>
	<li><p><em><b>Strategy document:</b></em> This document aims to describe the steps necessary to set up a PA device database. IPASC consensus should be reached on:</p></li>
	<p class="sublisting">
		(1) A device data collection strategy. <br />
		(2) A device data storage strategy (containing e.g. the database format). <br />
		(3) A tool to transfer the technical information of the PAI devices to the created database.
	</p>
</ol>
</div>
 
<div class="listing">
<h3>Towards goal 2:</h3>
<ol>
	<li><p><em><b>Software tool:</b></em> The software tool should be able to provide conversion functionality from multiple different proprietary formats to the agreed HDF5 format including all metadata. This entails:</p></li>
	<p class="sublisting">
		(1) A <em>requirement analysis:</em> Collection of all requirements for the tool. <br />
		(2) Setup of a <em>code repository:</em> A repository that contains the implementation of the converters.
	</p>
</ol>
</div>
 
<div class="listing">
<h3> Towards goal 3:</h3>
<ol>
	<li><p><em><b>Strategy document:</b></em> This document aims to describe a strategy how to create an open access data repository for the reference data sets. IPASC consensus should be reached on:</p></li>
	<p class="sublisting">
		(1) The ideal composition of a reference data set for comparison of processing algorithms. <br />
		(2) A hosting strategy (single data items; data sets; Application programming interface (API) access) <br />
		(3) A reporting strategy (referencing of raw data sets after processing; computed metrics)
	</p>
</ol>
</div>

<br />