<!-- Default Statcounter code for Correlation Relationship
https://project-correlation-relationship.github.io/Correlation-Relationships/#/Home
-->
<script type="text/javascript">
var sc_project=12447157;
var sc_invisible=1;
var sc_security="91ac9dc3";
var sc_https=1;
var sc_remove_link=1;
</script>
<script type="text/javascript"
src="https://www.statcounter.com/counter/counter.js" async></script>
<noscript><div class="statcounter"><img class="statcounter"
src="https://c.statcounter.com/12447157/0/91ac9dc3/1/" alt="hit
counter"></div></noscript>
<!-- End of Statcounter Code -->


![Banner - Credit: Shutterstock by shin88](/_media/Banner211.png)


# Correlation Sharing Portal

This page has been created to give you the opportunity to download and engage with the correlations we've created thus far. We value your feedback so please answer the questions below and share any thoughts or suggestions you may have.
The purpose of the correlation relationships published is to demonstrate the importance of recognising correlation relationship data model for practical applications, and thus propose it to data producers, software vendors, and researchers to consider it for adoption.

Note that the Correlation Relationships produced are experimental data and fall under the Experimental Statistics category. The methodologies used to develop the correlations are under development and would require further extensive testing. 

This means that the data:
- may not be complete or fully developed;
- may contain inaccuracies; and
- could be subject to changes based on user feedback.

Note that there is no guarantee as yet on whether participating partner bodies will continue to be able to generate the correlations.

The Office for National Statistics (ONS) has a useful 
[Guide to Experimental Statistics](https://www.ons.gov.uk/methodology/methodologytopicsandstatisticalconcepts/guidetoexperimentalstatistics).

England:
<select id="mySelect">
  <option value="T013187BW7Q-F01HRFXP01F-3fd9c3364e">Apple</option>
  <option value="T013187BW7Q-F01GYGE2Y23-01421e60d7">Orange</option>
  <option value="T013187BW7Q-F01GYGE2Y23-01421e60d7">Pineapple</option>
</select>
Wales:
<select id="mySelect">
  <option value="T013187BW7Q-F01HRFXP01F-3fd9c3364e">Apple</option>
  <option value="T013187BW7Q-F01GYGE2Y23-01421e60d7">Orange</option>
  <option value="T013187BW7Q-F01GYGE2Y23-01421e60d7">Pineapple</option>
</select>
<button name="button" onclick="var x = document.getElementById('mySelect').selectedIndex; var y = document.getElementsByTagName('option')[x].value; var z= 'https:\/\/slack-files.com\/'+y; alert(z);window.open(z,'top')">Download</button>

## How you can help

We would be very grateful for any input or comments that you may have but specifically would welcome your thoughts on the following questions:

1. Is anything missing from this data model?
2. Is there anything that would need to be changed in order for your organisation to consider adopting?
3. Which aspects do you consider the most valuable to your organisation and users?
4. Do you have any suggestions for how we can maximise future engagement with this work?
5. What other correlation relationships could be of interest to you?
6. What other correlation relationship data models do you know of that we could possibly research?

Please complete our survey

<a href="https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fwww.surveymonkey.com%2Fr%2FHKYWL8S&data=04%7C01%7Csanjay.rana%40voa.gov.uk%7Cb3ef4b4875c84b81a1a808d8a1abc93a%7Cac52f73cfd1a4a9a8e7a4a248f3139e1%7C0%7C0%7C637437106469859177%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&sdata=p2mooEkMV5Bqp42%2BDEkf%2FGhopOAPjzopbm928aUbwys%3D&reserved=0">
    <button>Take the survey</button>
</a>

We encourage feedback so please contact us via this form:

<a href="form.md">
  <button>Feedback form</button>
</a>

[Feedback form](/form.md)

## So, what are Correlation Relationships and why are they so useful?

A “Correlation Relationship/Link” is defined as the linking of representations of similar, but different spatial entities. Different organisations routinely store data that contain different spatial entities with similar identifiers.
For example, an address of a property exists in records in the HM Land Registry, VOA and OS databases. Each of these records represent different information associated with an address, which are:
- HM Land Registry records would show a general extent of Title Plan. 
- VOA shows extent of ownership space. 
- OS shows the precise extent of the built structure. 

Figure 1 below is an illustrative example.

![Correlation between different entities](/_media/Correlations2.PNG)
<br>__Figure 1:__ Correlations between different (but similar) entities

We developed a correlation relationship data model which was tested against three correlation relationships. These are listed below:
- OS MasterMap Topographic Area Polygon and HM Land Registry Inspire Polygon
- Different forest representations used by Defra and OS
- VOA Property Address and OS AddressBase Property Address
## What are our goals?
- To verify that the Correlation Relationship data model effectively represents the correlation between the datasets;
- Does the Correlation Relationship data model support the FAIR (link) principles:
    - Findability – is it easy to find
    - Accessibility – was it easy to access
    - Interoperability – does the data model metadata support integration. 
    - Reusable –  ….
- Identify areas of improvement (talk about improving data governance, ethical issues in sharing, TQV).
## Related Literature
- The motivation underlying the interest in correlation relationship is similar to those of probabilistic data linkage techniques used for Master Data Management. 
- Probabilistic record linkage is widely used across the government. For example, Ministry of Justice [[2]](https://www.iso.org/standard/64242.html), ONS [[3]](https://www.agi.org.uk/agi-groups/standards-committee/bs7666-guidelines) and Home Office [[4]](https://www.ordnancesurvey.co.uk/business-government/products/addressbase-premium), where the similarity between related datasets, typically records on individuals, is derived to create a Master Data using sophisticated algorithms in open source. (e.g. See [[2]](https://www.iso.org/standard/64242.html)) and commercial off the shelf software such as IBM Big Match and Informatica R (Dan Rickman, Home Office Data Scientist, personal communication).
- The main emphasis of the probabilistic record linkage is to find the similarities and deduplicate records. However, at the time of writing this project didn’t find any evidence of any dedicated focus on the capture of the metadata behind probabilistic record links, in the elaborate and transparent manner as proposed by this project. However, it is reasonable to speculate that it would of course be possible to do so easily when needed. 

<br>
<br>
L.I.F.E : Linked Identifier Federating Environment, a name of the service that was based on popular vote.
