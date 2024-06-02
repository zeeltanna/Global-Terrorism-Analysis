# **Global-Terrorism-Analysis**
Global terrorism refers to the use of intentional violence to create fear and achieve political, religious or ideological goals. This analysis covers patterns, trends and impacts of terrorism worldwide.

### **Data Description**

The dataset used in the analysis is called Global Terrorism Dataset and it contains 181691 rows of data and a total of 23 attributes among which following are few of them:

	  1. Year: The year during which attacks occurred.

	  2. Country: The country where attacks occurred.

	  3. Region: The region of world map where in attacks occurred.

	  4. Attack Type: The type of attack that took place(Eg: Bombing, Shooting,  
                      Murder etc).

	  5. Target Type: The type of target for terrorist attack.
    
      6. Killed: Number of people killed in the particular terrorist attack.

### **Steps Involved**

    1. **Data Preprocessing**:
    	- Load and selecting the necessary columns for further evaluation.
    	- Find inconsistencies and missing values in dataset and eliminate if any.
    	- Finding null values and fill them, and identify data types of data and perform type conversion. 

	2. **Perform Statistical Calculations**:
    	- Perform value counts of each attributes
    	- Calculate correlation values between all the attributes
		  - Calculate covariance values between all the attributes

	3. **Data Visualization**:
    	- Plot Heat Map for Correlation and Covariance values for all attributes.
            - Plot Pie Charts for different types of attacks and weapons used.
            - Plot Region Wise affected areas using a World Map.
            - Plot number of attacks each year and number of terrorist activities country wise.

### **Results**
As a result of analysis the we can be come to the following 7 conclusions:

    1. Country with Highest Number of Attacks : Iraq
    2. Region with Highest Number of Terrorist Attacks : Middle East and North Africa
    3. Maximum Number of People Killed : 1570 (In Iraq)
    4. Year with Most Attacks : 2014
    5. Month with Mose Attacks : May
    6. Group that carried out most attacks : Taliban
    7. Type of Attack most carried out : Bombing / Explosion
