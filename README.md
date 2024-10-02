**Project Overview:** A brief summary of the Titanic dataset analysis, focusing on the survival rates and factors that influenced them.

# Dataset	Description
**PassengerId:**	A unique identifier for each passenger.     
**Survived:**	The survival status of the passenger: 0 = Did not survive, 1 = Survived.      
**Pclass:**	The class of the passenger: 1 = First Class, 2 = Second Class, 3 = Third Class. Reflects socio-economic status, with 1 being the highest.    
**Name:**	Full name of the passenger. Includes titles such as Mr., Mrs., Miss, Master, which can indicate age, marital status, or gender.     
**Sex:**	Gender of the passenger: male or female.      
**Age:**	Age of the passenger in years. If the age is unknown, it might be left as NaN (Not a Number).      
**SibSp:**	The number of siblings or spouses aboard the Titanic with the passenger.       
**Parch:**	The number of parents or children aboard the Titanic with the passenger.          
**Ticket:**	The ticket number assigned to the passenger. This can include alphanumeric characters.          
**Fare:**	The amount of money the passenger paid for the ticket, in British pounds.           
**Cabin:**	The cabin number where the passenger was staying. Many entries are marked as Unknown due to missing data.           
**Embarked:**	The port where the passenger boarded the Titanic: C = Cherbourg, Q = Queenstown, S = Southampton.          


# Key Insights
**1) Survival Count by Passenger Class**      
There is a significant class-based survival disparity, where the survival rate is higher in the first and second class, and much lower in the third class. This suggests that social and economic factors played a role in survival likelihood.

**2)Survival Count by Gender**      
The plot shows that females had a significantly higher survival rate compared to males.

**3)Proportion of Survivors by Age Group**        
The pie chart shows the proportion of survivors across different age groups. children (0-5) had higher survival rate and adults (16-30) had lowest survival rate compared to other age groups.

**4)Survival Rate by Embarkation Port**          
The count plot for Embarked vs. Survived shows that passengers who embarked at 'C' (Cherbourg) had the highest survival rate, while those who embarked at 'S' (Southampton) had the lowest survival rate.Passengers embarking from Cherbourg were more likely to survive, possibly due to differences in class composition and socio-economic factors.

**5)Survival Rate by Family Size**         
 Family size appears to affect survival likelihood. Individuals traveling alone or with smaller families had a better chance of survival, while those with larger families faced greater challenges.
