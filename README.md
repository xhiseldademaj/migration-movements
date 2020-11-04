# Why_Do_Populations_Move?

# General Framework

From ancient times, human history has been marked by mass migration events, often triggered by economic difficulties and poverty, by armed conflict, or political and social instabilities. ”In the first decades of our millennium the combined effect of globalization and geopolitical issues has triggered notable migration trends across a turbulent global socioeconomic landscape” (Curry et al. 2019). But what are the main reasons of this mass-migration phenomenon? 
In this work we examine some stylized facts represented by the migrant-routes which depart from north Africa with the aim of reaching final destination countries. During their journey migrants arrive in the hotspots of the European coasts. The hotspots are the centres of first reception of people arriving in Europe by land or by sea without a regular residence permit. ”The hotspot approach was introduced by the European Commission in the European Agenda on Migration in April 2015, at the height of the migration crisis, as a means of providing emergency assistance to frontline Member States that were faced with the arrival of disproportionate numbers of migrants” (European Parliament 2018). According to European Union Agency for Fundamental Rights, the states who play a crucial role in the first welcome policies are mainly Greece and Italy where indeed the hotspots are located. 
In this work we study the migrants’ pathways from their home countries to final destination countries, as well as the conditions and activities that evolve during the migration process.

# How the model works

# Entities and variables of interest

For sake of simplicity, we assume that the group of migrants we consider is made up of three different ethnic groups represented by three different colors assigned to the agents. We assume that migrants all depart from the same initial-patch, which can be assumed to be Tripoli, the Lybian port located in north Africa. Before reaching the final destination countries, migrants pass through the hotspot zones which constitute a provisional arrival and first reception area. To reach these areas they engage a journey, which is often by sea. But the arrival in the first reception areas is not always easy and linear to predict, since it is subject to many factors. We take into consideration the
stochasticity of the journey process, and we introduce three probabilities according to which the migrants reach one of the three hotspots. More specifically, we assume that q1 represents the migrants arrival in Italy, q2 their arrival in Greece and q3 the arrival in Turkey. Here the probabilities q1, q2 and q3 are assumed to be as indicators of internal welcome policies adopted by the host countries.

We also assume migrants to be rational agents who aim to maximize a determined objective function. We assume that the variables profit and sameethnicity are the variables by which the utility function depends. We also assume that, before leaving their home countries, migrants have a set of links with some agents located in the destination countries. The link represents the migrant’s connection with his community in the country of final destination and they are supposed to guide the choice of the final destination country.

We rely now on the ODD protocol in order to describe the building process of our model.

# Design Concepts

We investigate the concepts of distance and wealth. In this sense, we ”guide” our model to tell us how these functions may change when we change the parameters by which they are composed and the framework in which they are defined. The destination-patches represent the northern European countries, which are characterized by higher levels of GDP with respect to home countries. So moving to higher GDP regions is associated to the possibility of having better jobs, schools and health systems. In this sense the movement is justified by the will to achieve better life conditions. We examine the trend of the mean wealth and of the mean distance after running the Go procedure, and we wonder if the average distance traveled by agents can help us to explain variations in their average wealth. 

# Details

Through the initialisation process we describe how we set up the world at the beginning of the simulation, since the results of the model often depend on these initial conditions. We endow agents with a random color chosen from a set of three, which represents their ethnicity, with a size and an initial location. The values of environment variables are set taking into account the stylized facts. We divide the landscape into three main regions: the home, the hotspot and the destination patches. We assign a color to all of them and more specifically we endow the destination patches with the patches-owned-variables profit and failure.

# From animation to science

Our goal is to determine how migrants’ behavior changes following the reaction of the external environment. The initial point of this analysis is to investigate how host countries react to the daily arrival of thousands of migrants. In the first experiment we try to simulate this external behavior in order to understand which could be the reactive behavior of migrants to the host-countries policies. We consider Italy in this experiment since it is the nearest European country to north
Africa, and its geographical position is crucial in the attempt to determine the dynamics of migration movements. In a second experiment we analyze the relation between the number of agents which remain in the Hotspot 1 located in Italy and the probability they arrive there. 


# Conclusions and further extensions

This work tries to capture the dynamics behind the mass-migration movements that affect our times. It is important to stress how migration is a huge phenomenon and it is not easy to be elicited and understood. Since the dynamics of this phenomenon are varied, it is often difficult to identify universal features that affect all migrants. For this reason our model is quite limited and we are aware that it could be refined and improved in many ways. However the general conclusion that can be drawn from this analysis is that, if the migratory phenomenon is allowed to be governed by migrants’ self-selection mechanisms with the aim of maximizing their utilities, these mechanisms will lead to a a failure for our system. We can automatically deduce that specific policies are necessary. The intent could be to refine the objective utility function
of migrants taking into account a social planner maximization problem. This is because our final purpose is to try do give a combined solution to this crisis, which concern humanity, and humanity only.
