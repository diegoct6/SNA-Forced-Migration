# Forced Migration Network Analysis

The journey of a refugee is often untold, and if told, it is never heard. Often in western mainstream media, the refugee journey is either termed as
a “crisis” and expand to questions on “how this will effect our economy.” However, using various social network analysis techniques, we will
debunk the stereotypical notion of a Eurocentric refugee network, and bring light to the stories of the untold.

![Blind visualization of the forced migrants network](/img/Unweighted_Migration.jpg)

This first map is a “blind” data visualization of the migrants social network. As you can see in the first map, the flows are unweighted so it gives a
misleading representation of the flow of the migrants around the globe. This is the case for most of the maps online created by famous
journalists trying to show the flow of refugees around the globe; however not depicting the reality of the refugees social network. This is why we
decided to first start by creating another map you can see below with weighted edges.

![The visualization for migration network using weighted edges](/img/Weighted_Migration.jpg)

This map still does not give very valuable insights to the reality of the migrants social network. The reason behind this is that we are trying to plot
a complex society in a simple graoh, which does not give the social network justice. This is why we are digging deeper into the analysis by
dividing our refugees into three types: Refugees,Asylum seekers,Internally Displaced People.

In the full report we presented different centrality measures to detect transitory countries and asylum safe heavens.  We also applied community detection to identify characteristics of the communities that have been broken but are subsequently rebuilt.

![Community Dynamics](/img/ComDetection.jpeg)

With this social netwrok analysis of the forced migrants, we have been able to dispell the eurocentric notion of the refugee crisis. Moreover, it is
about rethinking our humanity.

This project was made possible with the help of my colleagues Marang Mutloatse and Nisrine Ferahi. The tools used for the project are the following:

- R for data transformation, the analysis and the report in a Markdown format;
- Gephi for some of the visualizations of our networks;
- www.flowmap.blue for maping the networks on mapped backgrounds (very intuitive tool that easily allows to map in and out degrees for geographical data)

To be able to reproduce most of the work, you will just need to dowload the "edges.csv" and "nodes.csv" from the /Dataset directory. To be able to reproduce the maps on FlowMapBlue, you just need the latitudes and longitudes of the nodes, and the flows between those nodes with their respective weights.  I here attach the R markdown, as well as the final PDF report.
