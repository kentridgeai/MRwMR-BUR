# MRwMR-BUR
Code for paper: Improving Mutual Information based Feature Selection by Boosting Unique Relevance

In this code, we study 5 representative feature selection algorithms via the criterion of Maximum Relevance with Minimum Redundancy(MRwMR) They are Mutual Information Maximization (MIM), Joint Mutual Inforamtion (JMI), minimal Redundancy Maximal Relevance (mRMR), Joint Mutual Information Maximisation (JMIM) and Greedy Search Algorithm (GSA). We augment all these algorithms to include the criterion of boosting unique relevance (BUR). Therefore, we have 5 new algorithms for the criterion of MRwMR. They are MIM_BUR, JMI_BUR, mRMR_BUR, JMIM_BUR and GSA_BUR. We conduct experiments to examine the effectiveness of all algorithms.

The feature selection algorithm for each of the above methods can be found in the code in the following functions, 

*MIM_selection: MIM Algorithm

*MIM_selection_UR: MIM_BUR Algorithm

*JMI_selection: JMI Algorithm

*JMI_selection_UR: JMI_BUR Algorithm

*mRMR_selection: mRMR Algorithm

*mRMR_selection_UR: mRMR_BUR Algorithm

*JMIM_selection: JMIM Algorithm

*JMIM_selection_UR: JMIM_BUR Algorithm

*GSA_selection: GSA Algorithm

*GSA_selection_UR: GSA_UR Algorithm

More comments can be found in the codes.
