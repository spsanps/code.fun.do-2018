# code.fun.do-2018
This contains the project for Team Tilted Axis for CodeFunDo ++ 2018.

# Distributed Disaster Impact Analysis

## The issue we address
We strive to restrict the impact that a natural disaster has on the population by means of helping relief organisation better serve the distressed population. Usually NGOs and or Governments have to spend resources and time to do an initial survey of affected areas (as in the the case of kerala flood). If immediate and accurate heat map of damage and threats can be generated, it can result in better allocation of relief resources as well as immediate rescue efforts which will result in lives saved.

## Our Proposed Solution
Distributed Disaster Impact Analysis can be used by relief agencies to access the hardest hit regions. The solution needs to be accessible in order to paint an accurate picture of the impact of the disaster. This mandates an easy to use interface as well as potency in the lack of or limited availability of internet. This can be achieved by harnessing the power of the masses. People should have the ability to self report a damage/threat score in their location or that of their friends and family. This information can be used to create a heat map showcasing the extent of damage across the city/state. To prevent intentional/ unintentional misrepresentation of damage, an option to upload images in areas of high response i.e. areas with active network connections can be provided. These images can then be verified manually or automatically verified using data of disasters in the past. 
In order to make more sense of the self reported scores, other available data of the region can be presented alongside them to enhance the damage metric proposed above. This could include incorporating the existing weather data in the region, distinction of areas as urban and rural areas to judge the density of reports and the proportion of people with active network connection or power. Taking a closer look at the ratio of active users, severely affected areas will have a sparse proportion of active users indicating either damage to cell towers which in turn indicates substantial damage or power outage in the region which is also an emergency. 
In order to be accessible to the masses, the solution should be able to accommodate the technically challenged as well. To ensure equal opportunity to report damage, rural areas can be provided with the opportunity to report via sms instead of reporting using the app exclusively. 
The solution is geared towards aiding the first responders who might otherwise have a lack of information pertaining to the effects of the disaster in various regions and might have to depend on non uniform reporting that comes in from distressed phone calls from a few locations. 
## Tech we plan to use:
- Twillo API <Dial> verb to determine the number of active usres. 
- Twillo API <SMS> to urge users to self report the conditions with guidelines on scores, and use Twillo to obtain the data required for the map(https://www.twilio.com/blog/2011/05/how-to-create-a-simple-sms-voting-system-using-php.html).
- Microsoft Azure compute VM to serve as the server for the project.
