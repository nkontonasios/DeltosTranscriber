# DeltosTranscriber

Newspapers, as historical documents, serve as invaluable sources of information, capturing a wide range of
events, trends, and societal shifts. For historians, newspapers are rich, multi-faceted resources that
provide unique insights into the daily lives of people, their concerns, and the way they perceived and responded
to events. Whether it is through detailed reports, advertisements, or personal stories, newspapers are a reflection
of the time in which they were published, offering a window into the past.

Despite their significance, the full potential of newspaper archives remains largely untapped due to the
limitations inherent in traditional methods of research. With large collections of historical newspapers spread
across various institutions, accessing and extracting meaningful data has traditionally been time-consuming,
requiring manual examination of each article or page. As these archives continue to grow, the challenge of
extracting structured, searchable information becomes even more pressing. Digital archives have already begun
to transform the accessibility of historical newspapers, but without effective tools to parse and analyse their
content, much of the potential of these valuable resources remains unrealised.

This work focuses specifically on the extraction of well-structured data from newspaper archives to support
historical research. By addressing the segmentation problem inherent in newspaper pages, we aim to implement
a robust pipeline capable of transforming raw page images into structured data that can be then analysed for
scholarly research. As a case study, we consider the extraction of ship arrivals data, such as names of ships, names
of captains, ports of origin, cargo, etc., from the regional newspaper "Le Sémaphore de Marseille" (1827-1944)
whose daily issues are preserved as scanned images by the National Library of France (BnF). This data, existing
in a specific "ARRIVALS" section in almost all newspaper issues, provides valuable insights into historical trade
routes, economic patterns, and regional interactions. The structured output of
this pipeline, a machine-readable CSV file, enables large-scale analysis, making it easier to study trends over time
and across regions.

The proposed pipeline, depicted in the Figure below, integrates layout analysis and AI-driven information extraction
methods, tailored specifically for the historical newspaper "Le Sémaphore de Marseille". While this newspaper
provides an ideal test case, the techniques and approaches developed may not generalise directly to other
newspapers, particularly those with vastly different layouts or characteristics. 
![processOverview](https://github.com/user-attachments/assets/c00bce97-14aa-446b-881f-d261b4cbb6bc)
