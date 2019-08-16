+++
title = "IPASC Thematic Area: Data Acquisition and Management"
subtitle = "Test"
+++

## Leadership Team:

<div class="consortium-table">
{{% md %}}
| Name 						| Affiliation 							|
| ----------- 				| ----------- 							|
| Lina Hacker 				| University of Cambridge 				|
| Janek Gröhl 				| German Cancer Research Center (DKFZ) 	|
| Ben Cox	 				| University College London				|
{{% /md %}}
</div>

## Mission:

Our overarching goal is to enable intercomparison of photoacoustic imaging (PAI) data between different users (scientific groups / industries). To achieve this goal the Data Acquisition and Management (DAM) theme is conducting work towards three main goals: (1) is to define an essential list of metadata to fully characterise the format of PAI data acquired from commercial and custom-built PAI instruments and to transfer the device-specific data of instruments within the consortium in an open access database. (2) is to implement an open source tool that enables conversion to the prior agreed standardized data format (HDF5). (3) is to provide a platform that enables open access of PA reference data that can be used for comparison of processing algorithms etc.

## Progress:

We have created a table in which we collect information on the technical specifications of all PAI systems that are used within the consortium.

We have made three main recommendations: (1) To initially only include raw time series data into the standardization, (2) To use HDF5 as the standardized file format, and (3) To create a standardized list of metadata parameters. Furthermore, the working group has formulated a plan to create an open source conversion tool between data formats.

## Proposed deliverables:

#### Towards goal 1:
<ul>
	<li><b>Consensus document:</b> Definition of a complete list of necessary parameters to fully characterise PAI data</li>	
		<li style="margin-left:2em">Consensus on:</li>
			<li style="margin-left:4em">- parameter list</li>
			<li style="margin-left:4em">- terminology used</li>
			<li style="margin-left:4em">- physical units</li>
		<li style="margin-left:2em">The purpose of the document is also to describe the parameters in detail</li>
	<br />
	<li><b>Strategy document:</b> Creation of a PA modality database</li>	
		<li style="margin-left:2em">Consensus on:</li>
			<li style="margin-left:4em">- data collection strategy</li>
			<li style="margin-left:4em">- data storage strategy (database format)</li>
			<li style="margin-left:4em">- Transferring the technical information of the PAI devices within the consortium to the created database</li>
</ul>
 
#### Towards goal 2:
<ul>
	<li>Planning of a software tool that can provide conversion to the agreed HDF5 format with all metadata:</li>
		<li style="margin-left:2em"><b>Requirement analysis:</b> Consensus on the requirements for the tool</li>
		<li style="margin-left:2em"><b>Code repository:</b> Demo implementation of conversions</li>
</ul>
 
#### Towards goal 3:
<ul>
	<li>Discussion of a strategy how to create an open access data repository for the reference datasets.</li>
		<li style="margin-left:2em"><b>Consensus document:</b> including</li>
			<li style="margin-left:4em">- The composition of the reference data set</li>
			<li style="margin-left:4em">- A hosting strategy (single data items; data sets; Application programming interface (API) access)</li>
			<li style="margin-left:4em">- A reporting strategy (referencing of raw datasets after processing; computed metrics)</li>
</ul>

<br />