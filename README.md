# Exoplanets

Exoplanets are planets orbiting other stars.

This repository used NASA summary data of Kepler "objects of interests" to determine if an observation indicates that an exoplanet was located.

Discovering exoplanets is approached with several techniques.  Numbers in parentheses is planets confirmed to NASA:   
* Astrometry	(1) - star wobbles compared to nearby stars  
* Disk Kinematics	(1) - looking for gaps in material around star (where it collected into an object  
* Eclipse Timing Variations	(16) - a binary star system where eclipsing has variation due to other object(s)  
* Imaging	(50) - removing the star's light from the image to find what remains  
* Microlensing	(96) - light from the star is gravitationally bent  
* Orbital Brightness Modulation	(6) - the brightness of the star changes because of reflected light off object  
* Pulsar Timing	(7) - slight regular variation in pulsar bursts due to other objects  
* Pulsation Timing Variations	(2) - Doppler shift in bursts from a pulsar  
* Radial Velocity	(810) - star's motion displays a wobble  
* Transit	(3191) - an object block some of the star's light  
* Transit Timing Variations	(21) - measuring variations in the transit times to detect other objects  

Data set used:  
https://www.kaggle.com/nasa/kepler-exoplanet-search-results

The data set used includes a preliminary classification of "False Positive" and "Candidate".  The subsequent determination categories are "False Positive", "Candidate", and "Confirmed".  For modeling building, "False Positive" and "Confirmed were included; "Candidate" was excluded.  The model was used to make determinations for objects of interest that remain categorized as "Candidate".

Other potential data sets:  
https://en.wikipedia.org/wiki/List_of_exoplanet_search_projects  
https://en.wikipedia.org/wiki/Sagittarius_Window_Eclipsing_Extrasolar_Planet_Search  
https://en.wikipedia.org/wiki/CoRoT#List_of_planets_discovered  
https://en.wikipedia.org/wiki/Transiting_Exoplanet_Survey_Satellite  
https://en.wikipedia.org/wiki/CHEOPS
