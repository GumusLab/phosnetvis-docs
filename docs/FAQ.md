---
layout: default
title: FAQ Page
---

FAQ
---
---
<b>1.) Does PhosNetVis require the users to login?</b>
<br>
No PhosNetVis does not require you to login.
<br>
<br>
<b>2.) What are alternative tools to fKSEA for conducting kinase-substrate enrichment analysis?</b>
<br>
Some other tools commonly used in the literature are <a href="https://casecpb.shinyapps.io/ksea/" target="_blank">KSEA</a>,<a href="https://maayanlab.cloud/kea3/" target="_blank">KEA3</a>,<a href="https://rokai.io/" target="_blank">RoKAI App</a>,<a href="https://github.com/CutillasLab/KSEA_professional" target="_blank">KSEA professional</a> and <a href="http://phosfate.com/profiler.html" target="_blank">PhosFate</a>.
<br>
<br>
<b>3.) What is phosphorylation and why is it important?</b>
<br>
Phosphorylation is a process where a phosphate group is added to a protein. This tiny modification can have major effects:<br>
·  	Turning Proteins On and Off: Phosphorylation can activate or deactivate proteins, controlling their function in cells.<br>
·  	Cell Communication: It helps cells talk to each other by regulating signals sent between them.<br>
·  	Cell Growth and Division: Phosphorylation is crucial for regulating cell growth, division, and other important processes.<br>
·  	Gene Expression: It can influence which genes are turned on or off, impacting how cells behave and respond to their environment.<br>
·  	Metabolism: Phosphorylation plays a role in how cells use energy and process nutrients.<br>
In essence, phosphorylation is a molecular switch that helps cells respond to changes in their surroundings and carry out their functions properly.
<br>
<br>
<b>4.) What is a Kinase Substrate Interaction (KSI) network?</b>
<br>
A KSI network shows how kinases (special proteins) interact with other proteins called substrates. Kinases help regulate many activities inside cells by adding a phosphate          group to substrates. These interactions are like connections in a network, where each kinase is linked to the proteins it affects. By studying this network, scientists can          understand how cells work and find new ways to treat diseases.
<br>
<br>
<b>5.) Does PhosNetVis store data on a server?</b>
<br>
PhosnetVis runs on the client browser window. All modules except fGSEA(fast gene-set enrichment algorithm) run on the local browser. For fGSEA, the data are sent to a HIPAA-compliant server at the Icahn School of Medicine, through a HTTPS protocol which is safe and secure. Once the fGSEA is run, no data is stored on the server.
<br>
<br>
<b>6.) I have my data in gene ID format instead of Protein ID format. Can I still use PhosNetvis?</b>
<br>
Yes, absolutely! For fKSEA analyses, you need to first convert the gene IDs to Protein Accession IDs using an API such as <a href="https://www.uniprot.org/id-mapping" target="_blank">UniProt</a>. Then, you can run fKSEA analysis. For Network Visualization, you can upload your data in gene ID format directly to the "Upload Data for Visualization" section.
<br>



