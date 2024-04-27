# Background
Science degree earnings in Psychology and Sociology laid a solid foundation for research methods, statistics, and data handling that helped inspire my transition to data science. Prior to starting a Master's degree program with Bellevue University I dedicated my career to serving those with severe and persistent mental health diagnoses. My work quickly led me earn leadership positions where I developed a growing interest data-practices that could be used to improve service quality, impact, and outcomes. I am passionate about people, mechanisms of influence, behavior, wellness, and hope to bring my combined experience into a role these passions can serve well. 
  
## Education

---

M.S. Data Science  
B.S. Sociology   
B.S. Psychology   

&nbsp;     
## Work Experience  

---

### Data Analyst Intern @ DataNicely
*Omaha, NE ( Jan 2024 - Present)*
* Provision of ad-hoc data cleaning, transformation, and reporting to meet client needs. 
* Automated file cleaning and transformation with Power Query and Power BI to reduce labor and data redundancy.
* Repaired/reformatted existing Tableau dashboard solutions to improve performance and consistency.

### Research Analyst @ United Way of the Midlands
*Omaha, NE ( June 2023 - Oct 2023)*
* Identified Omaha area service gaps through team-based, qualitative, meta-analysis and coding of external reports.
* Analyzed internal 211 caller data to identify intersection of top needs with top unmet needs.
* Influenced grantmaking changes through reporting on post-covid philanthropic trends and non-profit feedback. 
* Co-Authorship of their 2023 Community Needs Assessment and full authorship of assigned blogs. 
* Used Excel, Python, and Power BI to perform ad hoc analysis on volunteer engagement and donation.

&nbsp;     
# Projects

 ---

## Data Mining the Workplace for Mental Health 
![workcalm](/docs/assets/img/workcalm2.jpg)  
Project aims to inform company practices/offerings that reduce work-interference due to employee mental health using machine learning classification modelings and model interpretation.   
![piechart](/docs/assets/img/workplace_q.png)  
A decision tree classifier was used to predict work interference and once a model was optimized, feature impact was analyzed using the SHAP library to highlight workplace culture and practices associated with increased or decreased work-interference. Using employee perceptions of culture and company practices, this model was able to predict wether employees experienced work-interference from mental health "never", "rarely", "sometimes", or "often" with 57% accuracy. (Over double what could be guessed by chance). 
### Key Findings 
Employees work interference from mental health appears minimized by cultures that favor an open-ness of mental health as a recognized issue. Feeling safe to discuss mental health with an employer and working somewhere that is upfront about mental health resources were associated with less work interference. One of the most important factors, appeared to be the allowance for mental health leave,       


* **Mental health consequences** Feeling safe to discuss mental health issues with your employer influenced the model to predict lower work interference values. Inversely, Feeling there would be consequences for doing this led the model to favor higher values for work interference.

* **Employer Resources** to 'Seek Help Both plots mirror the impact of offering resources to learn about and improve mental wellness. The plot above shows that those with employers that did not offer resources for mental health led the model to favor the high value of work interference. Responses of "I don't know" pulled predictions away from both target extremes, which makes sense.

Mental Health Leave" It being "very difficult" to take leave for mental health had some of the strongest shap values, pushing predictions for work interference higher. Meanwhile, "I don't know" features for being able to take leave, appeared again to lead predictions away from both target extremes.

Remote Work Remote work only appears in the plot below, for those with the lowest reports of work interference from mental health. Remote work appears to favor predictions for low work interference from mental health.

Don't know Responses In general, it is worth noting, that while these category types had subtle impacts on predictions - the impact was consistent, where people responding "I don't know" appear to pull target predictions slightly away from the most extreme categories of work interference occurring "often or "never". A reasonable adjustment.

Having Benefits and Knowing Care Options While lacking benefits did not make the top list for features impacting higher work interference, it is one of the stronger influences on the plot below. It would suggest that the model leads predictions to higher levels of work interference when a person reports not having mental health benefits, or not knowing what mental health care options are available to them.

