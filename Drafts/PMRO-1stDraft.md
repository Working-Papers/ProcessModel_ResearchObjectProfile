##Research Object Profiles and Process Modeling for Curation

###Abstract
Data curation is inherently collaborative  - it requires the coordination and cooperation of stakeholders with (potentially) different views on how research is conducted, and the value of the objects that are produced, and consequently what should and should not be preserved for long-term access.

Consequently, sound data management requires that we model and in some sense formalize these different views so as to develop research infrastructure that are both useful and reliable to each stakeholder group. 

Drawing on techniques from information systems management, this paper describes a method - process modeling - that can bring clarity to these issues in data curation.

Additionally, we argue that there is a need to move away from the ambiguous use of "data" as a blanket term for the many different artifacts produced in a research process; for instance,  software, executable workflows, and even physical specimens are critical components of many eScience research endeavors. Instead, we draw upon the emerging work of "research objects" and in particular the concept of of research object profiling in order to advance curation for reuse.

#Introduction 


[Talk about ambition of curation and preservation in broad sense... need to be more explicit about research processes in developing infrastructures to support this work... traditionally domain of software engineers doing requirements gathering, increasingly the work of data curators doing participatory development]

....

Basic science research is increasingly data-driven, but the valued products of contemporary research include a broad range of artifacts - reagents, specimens, physical and chemical samples, executable workflows, and software (which themselves range in complexity from 10 line scripts to 10,000 lines in an earth systems model). 

Each of these artifacts also have their own legacy of curation - biological specimens for instance are prepared and digitized using techniques that mix new informatics approaches with traditional documentary resources, such as field-notebooks (Thomer et al, 2011). Research software on the other hands has traditionally taken a laisse faire approach to preservation, in that code was assumed to "harden" over time and hence its purposeful stewardship was a by-product of its continued use (Chung et al, 2010).

Research data curation - as it has emerged over the last decade - tends to lump this range of artifacts, and their curatorial activities together under "data", making an argument that such materials are simply inputs for the "doing" of science (Gold, 2010). 

The lumping together of different research artifacts under one umbrella term may be initially convenient, but in our experience actually doing curation this introduces an unnecessary amount ambiguity between stakeholders - which in turn, can have disastrous effect on collaboration and systems development. Not the least of these negative impacts are a recursive, unproductive discussion about "what are data, really?". 

The point that we have emphasized over time is that such conversations are not productive for gaining traction on the problems of curation - namely because data are not inherently one thing or another, they are information artifacts playing an evidentiary role in a research process (Sacchi et al, 2011). As one of our collaborators likes to quip, one person's hypothesis is another person's data. But, such an emphasis on the relative nature of data requires curators to be systematic, and comprehensive in their modeling of a domain's research processes. So, while we often recognize that the context in which research artifacts are produced and used is paramount to their accurate preservation and reuse, we have been slow to operationalize this sentiment. 

In part, this is because doing so requires a conceptual shift in approaching curation activities. It requires the exploration of, and experimentation with practical techniques that are flexible enough to accommodate many different forms of data, and research artifacts. In particular, this requires that we are:

1. Specific about what roles artifacts are playing within a research process, and 

2. Meaningfully abstract to the types of artifacts that might be curated for the sake of long-term preservation, and meaningful data reuse.  

This paper presents our ongoing work on both of these problems. First, we describe a method of process modeling borrowed from information systems analysis literature. Drawing on work from three separate projects, we show how this method of inquiry can create useful, lightweight way of describing and visualizing the different activities that, when combined support a research process. 

We then go on to demonstrate how, when completed, we can use process models to create research object profiles. These domain specific profiles capture the range of formats, protocols, and standards that researchers and curators need to capture for a specific research object in order to facilitate their meaningful reuse over time. 

#Process Models

#Research Objects



