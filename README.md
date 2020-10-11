# STP-UDGAT: Spatial-Temporal-Preference User Dimensional Graph Attention Network for Next POI Recommendation

Comments: Accepted to CIKM 2020.

Next Point-of-Interest (POI) recommendation is a longstanding problem across the domains of Location-Based Social Networks (LBSN) and transportation. Recent Recurrent Neural Network (RNN) based approaches learn POI-POI relationships in a local view based on independent user visit sequences. This limits the model's ability to directly connect and learn across users in a global view to recommend semantically trained POIs. In this work, we propose a Spatial-Temporal-Preference User Dimensional Graph Attention Network (STP-UDGAT), a novel explore-exploit model that concurrently exploits personalized user preferences and explores new POIs in global spatial-temporal-preference (STP) neighbourhoods, while allowing users to selectively learn from other users. In addition, we propose random walks as a masked self-attention option to leverage the STP graphs' structures and find new higher-order POI neighbours during exploration. Experimental results on six real-world datasets show that our model significantly outperforms baseline and state-of-the-art methods.



