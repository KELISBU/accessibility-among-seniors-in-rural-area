# Development of a Causal Model for Improving Rural Seniors’ Accessibility: Data Evidences
Here is the supplemental dataset and code for this paper. The aim for this paper is to use data evidence to verify the causal model of rural residency, mobility and accessibility.
## National Household Travel Model(NHTS 2017):https://nhts.ornl.gov/
We choose **'triphub'** as our main data, which contains a completed survey from 129,696 households and 923,572 person trips.    
**Codebook for the data:**  
**'URBRUR'**:1 for urban area, 2 for rural area.  
**'TRPTRANS'**:01=Walk,02=Bicycle, 03=Car, 04=SUV, 05=Van, 06=Pickup truck, 07=Golf cart / Segway, 08=Motorcycle / Moped, 09=RV (motor home, ATV, snowmobile), 10=School bus, 11=Public or commuter bus, 12=Paratransit / Dial-a-ride, 13=Private / Charter / Tour / Shuttle bus, 14=City-to-city bus (Greyhound, Megabus), 15=Amtrak / Commuter rail, 16=Subway / elevated / light rail / street car, 17=Taxi / limo (including Uber / Lyft), 18=Rental car (Including Zipcar / Car2Go), 19=Airplane, 20=Boat / ferry / water taxi  

We define transportation modes including: '01' as walking, '02' as bicycle, '03-09' as automobiles, '11-18' as transit, '10' as school bus, and '19-20' as others.  
**'WHYTRP1S'**: travel purposes. 1=Home, 2=Work 3=School 4=Medical 5=Shopping 6=Social/Recreational 7=Transport someone 8=Meals 9=Something else  
**'TRPMILAD'**: trip travel mile.  
**'TRVLCMIN'**: trip travel time.  
**'R_AGE_IMP'**: age. We define people aged from 16-64 as younger adults (Yadults), and 65 and older as seniors.  
**'WTTRDFIN'**: final trip weight.
## H1
We caculated cumulative distribution function among groups for intended purposes. Additional codes are display in [H1 code](main/H1 code)
## H2
We analyzed the distribution of trips by transportation modes and traveler groups, and travel frequency, travel speed, and time to public transit, for the three groups of travelers.  
## H3

## H4
