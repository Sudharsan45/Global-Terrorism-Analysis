# Global-Terrorism-Dataset-Analysis
# **Project Summary -**
The objective of this project is to conduct an exploratory data analysis (EDA) of the Global Terrorism Database (GTD). This open-source dataset contains comprehensive information on both domestic and international terrorist attacks occurring globally from 1970 through 2017. Developed and maintained by the National Consortium for the Study of Terrorism and Responses to Terrorism (START) at the University of Maryland, the database encompasses details of over 180,000 recorded terrorist incidents. The project's principal aim is to dig deep into this expansive dataset, identify significant trends, patterns, and insights about terrorism-related activities, and present these discoveries visually for an enhanced understanding.

A critical aspect of this project is the extensive use of Python libraries tailored for data analysis and visualization. The cornerstone of data manipulation, including loading the dataset, cleaning data, and executing sophisticated aggregation operations, will be the Pandas library. This powerful, high-performance tool offers efficient data structures and makes the handling of large datasets effortless.

The project employs the NumPy library to facilitate advanced numerical operations and speed up computation. Given its proficiency in handling multi-dimensional arrays and matrices, NumPy is the perfect companion for data processing operations.

The project doesn't stop at numerical data analysis; it brings the extracted insights to life through vivid, informative visualizations, courtesy of the Matplotlib and Seaborn libraries. These libraries provide an array of visualization styles, enabling the display of data in ways that are both appealing and informative. From bar plots and scatter plots to histograms and heatmaps, the project will utilize a minimum of five different visualizations to reveal relationships between variables and provide a graphical representation of the dataset's characteristics.

Exploring the GTD through this project will pave the way for an intricate understanding of terrorism patterns over the past decades. The goal is to unveil potential trends in attack frequency, most targeted countries, preferred methods of attack, types of weapons used, casualties, and the evolution of terrorist organizations, among other relevant dimensions.

By examining these factors, the project aims to provide a detailed overview of global terrorism trends, informing counter-terrorism strategies and policies. Additionally, the findings may also help understand the characteristics of regions prone to attacks and the reasons behind their vulnerability.

In conclusion, this project offers a data-driven exploration into the dark world of terrorism, aiming to shed light on the complex patterns hidden within the enormity of the GTD. The end product of this project will be an array of valuable insights that have the potential to contribute substantially to ongoing counter-terrorism efforts and inform future research in this field. The combination of data manipulation, numerical computation, and graphic visualization is expected to yield a robust and comprehensive dataset exploration, leading to substantial key findings about global terrorism.

# **Problem Statement**





1. Name the top 10 most effective terrorist groups.

2. What are the most common attack, weapon, and target types?


3. To find the comparison between the number of people killed and wounded.

4. Display the frequency of attacks per year.

5. Demonstrate the killed and wounded people using subgraphs.



6. Find the successful and unsuccessful terrorist attacks around the world.

7. Identify the hot zones of terrorism globally and discern the evolving patterns of terrorist activities.
   
# **Define Your Business Objective?**

The business objective of this project is to leverage the data contained within the Global Terrorism Database (GTD) to derive actionable insights into terrorist activities worldwide from 1970 to 2017. By conducting a comprehensive exploratory data analysis (EDA), the goal is to identify the key patterns, trends, and correlations related to global terrorism, thereby enabling better-informed decision-making for security analysts, policy-makers, and counter-terrorism agencies.

Specifically, the objectives include:

Identification of global "hot zones" for terrorist activities: By determining the most affected regions, we can better understand where resources might be best allocated to prevent future attacks.

Analysis of frequency and intensity of attacks: Understanding how these have evolved over time can provide insights into the changing dynamics of terrorism and allow for more accurate risk assessments.

Examination of methodologies and weapons used in attacks: This can shed light on the operational preferences of terrorist organizations and potentially provide early indicators of future threats.

Assessment of casualty trends: This can help identify the most devastating types of attacks and allow for targeted response planning to minimize human loss.

Unveiling patterns related to terrorist organizations: This can potentially aid in understanding their strategies, thereby supporting intelligence agencies in their counter-terrorism efforts.

# **What did you know about your dataset?**
**Dataset Size**: The dataset is quite large, containing 181,691 entries or rows.

**Feature Quantity**: The dataset contains 135 features or columns.

**Data Types**: The dataset has a mix of data types. There are 55 features with floating point numbers (float64), 22 features with integers (int64), and 58 features with objects (object). The object datatype in pandas typically means the column contains string (text) data.

**Memory Usage**: The dataset uses over 187.1 MB of memory.

**Missing Values**: There are some columns with a large number of missing values. For example, the 'approxdate' column has 172,452 missing values and the 'related' column has 156,653 missing values. However, several columns do not have any missing values, such as 'eventid', 'iyear', 'imonth', 'iday', 'INT_LOG', 'INT_IDEO', 'INT_MISC', and 'INT_ANY'.
**eventid**: Unique ID for each event or terrorist attack.

**iyear**: Year the terrorist attack occurred.

**imonth**: Month the terrorist attack occurred.

**iday**: Day the terrorist attack occurred.

**country_txt**: Name of the country where the terrorist attack occurred.

**region_txt**: Name of the region where the terrorist attack occurred.

**city**: City where the terrorist attack occurred.

**attacktype1_txt**: The general method of attack employed.

**target1**: The specific person, building, installation, etc., that was targeted.

**nkill**: Number of confirmed fatalities for the incident.

**nwound**: Number of confirmed non-fatal injuries.

**gname**: Name of the group that carried out the attack.

# **5. Solution to Business Objective**
Based on the exploratory data analysis conducted on the Global Terrorism Dataset, there are several recommendations that could be provided to a client interested in using this information to decrease the impact of terrorism, and thereby meet the stated business objective.

Focus on Hotspot Regions: The regions with the highest frequencies of terrorist activities should be prioritized for intervention efforts. These regions may need more robust security measures, targeted socio-economic programs to address root causes of terrorism or more substantial international assistance.

Understand Yearly Trends: Keeping track of the rise or fall of terrorist incidents over the years could help forecast potential future threats and adjust counter-terrorism strategies accordingly.

Prioritize Major Threat Groups: Our analysis shows that certain terrorist groups are more active than others. Intelligence efforts should be concentrated on these high-impact groups to prevent future attacks.

Target Most Common Attack Types: Understanding the most common types of attacks used by terrorists can help in developing preventive measures and response strategies. For instance, if bombings are the most common attack type, more resources could be directed towards bomb detection and disposal.

 # **Conclusion**
 The Exploratory Data Analysis (EDA) conducted on the Global Terrorism Dataset provided significant insights into trends and patterns in global terrorism from 1970 through 2017. With the help of the Python libraries Pandas, Matplotlib, Seaborn, and NumPy, we were able to handle, visualize and interpret complex data related to terrorist activities.

Through this analysis, we identified trends over time, regional hotspots, dominant terrorist groups, and preferred modes of attacks. All these findings are crucial for devising effective counter-terrorism strategies and interventions.

The process underscored the power of data-driven decision-making. By using EDA, we were able to transform raw data into meaningful insights. For instance, understanding that certain regions are more prone to terrorist attacks or that specific terrorist groups are more active allows security agencies and policymakers to allocate resources more efficiently, thereby potentially saving lives and property.

However, while this data analysis provides a robust foundation, it's important to acknowledge that addressing terrorism requires more than just understanding past data. It necessitates a comprehensive approach that includes current intelligence, geopolitical considerations, and on-the-ground realities.

To conclude, this project demonstrates the potential of data analysis in informing and shaping counter-terrorism efforts. It provides a useful starting point for further study and action, emphasizing the importance of continuous data collection, analysis, and interpretation in tackling global security challenges like terrorism.

















