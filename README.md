# ENCE688j-Final-Project
Project Objective

Adriana Bryant, Livingstone Imonitie, Asal Mehdi Tabrizi, Behnam Tahmasbi

**Literature review**

There is plenty of literature on the general concept of eviction rates post-natural disasters. Previous studies show that evictions rise after a disaster in places with more landlord-friendly laws, regardless of whether tenant protections are also in place (Raymond, Green et al. 2021). Also in general the recovery policies are biased to the homeowners (Fussell and Harris 2014). However, eviction depends on landlord size and the access to the federal assistance (Brennan, Srini et al. 2021). Moreover, as expected the literature review shows that the low-income families are more vulnerable after disaster. There is also emerging literature on climate gentrification, but we have not been able to find literature that connects the two. This could be an interesting topic. Although, further exploration of the datasets we have access to needs to be done, as well as we need to find more data that has gentrification indicators/proxies.

**Initial data review**

We downloaded the FEMA and disaster datasets, and looked into the reports of the eviction datasets. One observation is that the eviction data is not available for all states or all counties in each state. The FEMA datasets contain nearly 500 recorded disasters and the amount of aid at the zipcode level. The attributes of the FEMA dataset are as follow:
-	Exploration of FEMA Housing Assistance Program Data - Renters 
-	Key Variables:  
-	disasterNumber: could be helpful in breaking project down by type of disaster
-	Zip: information at zipcode level
-	vaidRegistrations: shows how many people were registered for FEMA aid 
-	totalInsepcted: indicates how many properties were actually inspected for damage
-	totalInspectedWithNoDamag, totalWithModerateDamage, totalWithMajorDamage, totalWithSubstantialDamage: these variables are great indicators of the severity of the disaster 
-	approvedForFemaAssistance: important metric for finding correlation between areas approved and eviction rate 
-	totalApprovedlphAmount: important overall metric
-	approvedBetween1Aand10000, approvedBetween10001And25000, approvedBetween 25001AndMax, important for understanding different levels of FEMA funding


**Overall research goal**

This is a work in progress based on preliminary research findings. By the next group meeting on 4/11, we will have explored the relationship between eviction data and natural hazards across the United States broadly. Both FEMA and HUD data will be examined at the same spatial resolution as the hazards and evictions data to understand the relationship of the funding with the hazards.

This initial data analysis will provide both a better understanding of the issue as well as what data is available for further in depth analysis. The research goal will be defined based on what the group is most interested in looking further into. 

After a literature review, it has become apparent that people are being exploited in the aftermath of natural disasters. One of the main negative effects is the eviction of renters and then the increase in rent prices. This has led to the potential topic of the relationship between disasters, evictions, and gentrification. The following questions could be asked: 

If we look at the profile of renters pre and post-disaster, how has this changed
	Per capita income, race breakdown, homelessness	
		Is there more homelessness after a disaster? How long after?
	What is the average rent 
		Are there rent control laws
	What are tenant/landlord laws/protections/insurance 
	Is there an increase in homeownership afterwards? 
	Gentrification????
		How would you quantify 
	Can you predict if/degree of gentrification of an area based on pre existing conditions 
		As well as the type and size of disaster? 
	Where are people going if they are not staying? 
		Lit shows that many people leave region
	Looking at moments of opportunity disasters provide for city planning?
		Disaster capitalism 

This is not a final decision, but rather a general research direction that may lead to an interesting analysis. 

**References**

Brennan, M., T. Srini, J. Steil, M. Mazereeuw and L. Ovalles (2021). "A Perfect Storm? Disasters and Evictions." Housing Policy Debate: 1-32.
Fussell, E. and E. Harris (2014). "Homeownership and housing displacement after Hurricane Katrina among low‐income African‐American mothers in New Orleans." Social science quarterly 95(4): 1086-1100.
Raymond, E., T. Green and M. Kaminski (2021). "Preventing Evictions After Disasters: The Role of Landlord-Tenant Law." Housing Policy Debate: 1-17.
