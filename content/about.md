+++
keywords = ["Neeraj Pradhan", "about", "contact"]
menu = "main"
type = "about"
+++
I am a software engineer, working on using data mining and machine learning for large scale personalization. My interest lies in using machine learning algorithms to build and improve products. Some of the work that I have worked on, in more recent years:


{{% insertclass class="project-container" %}}
### Query Click Analytics | Groupon
{{% insertclass class="project-text" %}}
 - Set up the data infrastructure for search query-click analytics in Hive. The resulting data has been used to improve Query Understanding and deal recall for tail queries.
 - Automated tagging of "atypical" search queries to adjust precision-recall during search retrieval.
   - Neeraj Pradhan, Vinay Deolalikar, and Kang Li. 2015. *Atypical Queries in eCommerce*. In Proceedings of the 24th ACM International Conference on Information and Knowledge Management (CIKM '15). ACM, New York, NY, USA, 1767-1770. [paper](/docs/atypical_queries).
   - [CIKM 2015 poster](/docs/cikm_poster).
 - Analyzed demand-supply gaps in real-time across different locations based on the local query-click data characteristics.
 - Built a model for computing item-item similarity based on the characteristics of their query-click distribution. This is being used as a signal to our personalization framework.
 - Query Suggestions using random walk on the query-click bipartite graph to facilitate discovery.
{{% /insertclass %}}
{{< figure src="/img/wordcloud_search.png" link="/docs/atypical_queries" class="project-img" title="Sample of search terms on Groupon : atypical queries are tagged as highly specific, ambiguous or broad." >}}
{{% /insertclass %}}


{{% insertclass class="project-container" %}}
### User Feed Personalization | Groupon
{{% insertclass class="project-text" %}}
 - Involved in setting up the Hadoop Mapreduce data pipeline for user activity based personalization.
   - Kang Li, Vinay Deolalikar, and Neeraj Pradhan. *Big Data Gathering and Mining Pipelines for CRM using Opensource*. 2015 IEEE International Conference on Big Data. [paper](/docs/big_data_crm).
 - Mining and characterizing lifestyle personas of users at scale -- Groupon has user activity across the entire spectrum from local deals to goods. How do we scalably mine 360&deg; views of user personas across Local and Goods? How can we  use this data for personalizing user experience on our website and mobile app?
   - Kang Li, Vinay Deolalikar, and Neeraj Pradhan. *Mining Lifestyle Personas at Scale in E-commerce*. 2015 IEEE International Conference on Big Data. [paper](/docs/persona_mining).

{{% /insertclass %}}
{{< figure src="/img/user_feed.png" link="/docs/persona_mining" class="project-img" title="Personalized user feed using both direct historical activity and using Collaborative Filtering. ">}}   
{{% /insertclass %}}

{{% insertclass class="project-container" %}}
### Effect of Modularity on Attractor Network Dynamics | Institute of Mathematical Sciences, Chennai
{{% insertclass class="project-text" %}}
Modular organization characterizes many complex networks. We studied the role of modular organization in increasing the global stability of certain desirable attractors of a system.

 - We observed that that the basins of attractors, corresponding to patterns that have been embedded using a learning rule, occupy maximum volume in phase space at an optimal modularity. Simultaneously, there is a decrease in convergence time to these attractors as a result of cooperative dynamics between the modules.
 - The findings may provide a clue to the evolution and ubiquity of modular networks in nature.
   - Neeraj Pradhan, Subinay Dasgupta and Sitabhra Sinha. *Modular organization enhances the robustness of attractor network dynamics*. Europhys. Lett. 94 (2011) 38004 (1-6). [paper](/docs/modular_networks).
{{% /insertclass %}}
{{< figure src="/img/Brain_network.png" link="/docs/modular_networks" class="project-img" title="Modular structure is common across  many real world networks including the human brain." attr="(Wikimedia Commons)" attrlink="https://en.wikipedia.org/wiki/Biological_neural_network#/media/File:Brain_network.png" >}}
{{% /insertclass %}}   


