<h1>Between death and life; brief inspection of SARS-CoV-2 in Mexico</h1>

All code available [here](https://github.com/jvelez-s/cdmx_challenge)

<h3><i>Table of contents</i></h3>
1. [Abstract](#id1)
2. [Introduction](#id2)
3. [The problem](#id3)
4. [How did we do it?](#id4)
5. [Results](#id5)
6. [The team](#id6)

<div id='#id1'>
<h3>Abstract</h3>
<div style="text-align: justify">The objective of the investigation is to link a list of comorbidities of COVID-19 shown on recent studies that make a person more prone to complications if infected. Using geospatial data to predict and identify which geographic zones have more infections, where are happening and make a prediction of future outbreaks and mortality rates.
We took the results of a recent investigation with a sample of 177, 133 subjects on May 18th, 220 where it was observed 1, 633 with SARS-CoV-2, and 5,332 deaths to make our calculations. The principal risk factors for lethality in COVID-19 include diabetes, obesity, advanced age and immunosuppression. Those factors conferred an increased risk of hospitalization and possible intubation. 
</div>

<div id='id2' />  
<h3>Introduction</h3>
<b>What did we do?</b>
<div style="text-align: justify"> Our main question was: 
What is the mortality rate in Mexico depending on comorbidities, sex, hospital of admision, if the patient was in ICU or not,etc. For this we made a big search of recent studies that investigated the principal risk factors that could lead to a complicated situation for the infected people and compare each one to identify which ones could have a bigger impact in México for its conditions and the geographic zones that are more endangered by its type of population.
After we collected the data, organized and selected it, we started to write the code that would help us to identify the endangered zones and where the last deaths and infections were.</div>

<div id='id3' />
<h3>The problem</h3>
<div class="figure">
<div style="text-align: justify"> We live in Mexico and we believe that there is not enough information about COVID-19 so we wanted to collaborate and aport information using the already existing data about coronavirus. 
COVID-19 is a virus that initiated in China in December 2019. The virus travelled fast and ended up in a global pandemic. The virus is easily spread by the air and contaminated surfaces. It is highly contagious and on average it has a high death rate.</div>

<div id='id4' />
<h3>How Did we did it?</h3>
<div style="text-align: justify"> First, we recollected geospatial data from INEGI, like sex, age, hospital of admission, etc. We combined them with the information obtained via Mexico’s government and different internet sources that together could take us to identify the main risk factors that complicate the patients with COVID-19. This all with the purpose that the two sources combined helped us generate a heatmap of Mexico. The map shows the current situation that we are living in Mexico, the death rate, the number of cases (ambulatory, confirmed and deceased), etc.
Finally, we generated six more graphs that show different and more specific data about the condition of the population in the country.</div>   
  
{% include municipalities_positive_cases.jpg %}
  
<div style="text-align: justify"> Here we mapped the results obtained from Mexico’s government about COVID-19 patients combined with data from INEGI. 
To achieve this we created a dataset to make the information more legible so that it has more friendly access in English and Spanish. The dataset is done in Spanish but our work has been translated to English, this way it has more reproducibility.</div>

Graph 1: Cases per state

<div style="text-align: justify">Here we can see the cases per state distribution, these results can be affected by the sanitary regulations, population density, etc. This allows us to compare the decisions taken by every state and their effectiveness. 
By deduction, we can see that those states with a high population density but a low number of cases have more effective sanitary regulations, compared to those who have low population density and a higher number of cases.</div>

Graph 2:

<div style="text-align: justify">Number of accumulated cases since the start of the pandemic.
This graph shows the accumulation of positive COVID-19 cases since the first case was detected in each state of Mexico.</div>

<div style="text-align: justify"> Graph 3:
 
One of the questions we asked to make our model was if the virus affects male and females equally. The next graph answers this.</div>
<div style="text-align: justify"> In the column on the left, we can see the number of deceased patients and in the right the ones that are still alive. The color blue represents the females and the red represents the males.
Here there are two things to notice: the virus has affected more the male population than the females. Second, if we concentrate on the lifetime distribution once infected by the virus we can see that there is no notorious difference. 
</div>

Graph 4:

<div style="text-align: justify">In this data, we can see that the quantity of men affected is more. Possibly because men are commonly exposed for some reason. There is no certain way for us to know.</div>

Graph 5:

<div style="text-align: justify"> We already know gender does not matter in relationship with the time of death, but age does matter, mainly to the age range 40-85. This data represents the most part of cases that presented symptoms and went to the hospital.
We discovered that the time a patient lives after contracting the virus depends on hospital care. Those who Went to the ICU (lighter colour in the graph) lived 15 days, the patients who were on normal care lived 12 days and the ambulatory patients lived 13 days. </div>

Graph 6:

<div style="text-align: justify">By now we have classified different factor. Now we want to determine which comorbidities (illnesses) will increase the risk of death when infected with COVID-19.</div>

 <div id='#id5'>
 <h3>Results</h3>
All code available <a href="https://github.com/jvelez-s/cdmx_challenge">here</a>          
<h3>The team</h3>
<div class="col-12">
        <img alt="image" class="img-fluid rounded" src="./IMG-20200814-WA0001.jpg">
        <h5><strong>Regina Olvera</strong></h5>
        
 <div class="col-12">     
        <h5><strong>Jesús Vélez</strong></h5>
       
<div class="col-12">     
        <h5><strong>Johann Baez</strong></h5>
        
<h2>Por parte del CdeCMX Challenge</h2>
  
  
## References
  
- COVID-19 Associated Hospitalization Related to Underlying Medical Conditions. (n.d.). Retrieved from https://www.cdc.gov/coronavirus/2019-ncov/covid-data/investigations-discovery/hospitalization-underlying-medical-conditions.html
 
- COVID-19 Hospitalization and Death by Age. (n.d.). Retrieved from https://www.cdc.gov/coronavirus/2019-ncov/covid-data/investigations-discovery/hospitalization-death-by-age.html
 
- COVID-19 Hospitalization and Death by Race/Ethnicity. (n.d.). Retrieved from https://www.cdc.gov/coronavirus/2019-ncov/covid-data/investigations-discovery/hospitalization-death-by-race-ethnicity.html
 
- Coronavirus: COVID-19. (n.d.). Retrieved from https://www.saludcastillayleon.es/es/farmacia-medicamentos/noticias/coronavirus-covid-19
 
- Coronavirus: ¿cuánto tiempo lleva recuperarse del Covid-19? (2020, April 20). Retrieved from https://www.eluniversal.com.mx/mundo/coronavirus-cuanto-tiempo-lleva-recuperarse-del-covid-19
 
- Giannouchos, T., Sussman, R., Mier, J. M., Poulas, K., & Farsalinos, K. (2020, January 01). Characteristics and risk factors for COVID-19 diagnosis and adverse outcomes in Mexico: An analysis of 89,756 laboratory-confirmed COVID-19 cases. Retrieved from https://www.medrxiv.org/content/10.1101/2020.06.04.20122481v2.full.pdf html
 
- Older Adults and COVID-19. (n.d.). Retrieved from https://www.cdc.gov/coronavirus/2019-ncov/need-extra-precautions/older-adults.html
 
- Preguntas y respuestas sobre la enfermedad por coronavirus (COVID-19). (n.d.). Retrieved from https://www.who.int/es/emergencies/diseases/novel-coronavirus-2019/advice-for-public/q-a-coronaviruses#:~:text=sintomas
 
- Zheng, Y., Ma, Y., Zhang, J., & Xie, X. (2020, March 05). COVID-19 and the cardiovascular system. Retrieved from https://www.nature.com/articles/s41569-020-0360-5?fbclid=IwAR3TjvxiEtYQqNkpsPuEu
 
- Bello-Chavolla, O. Y., Bahena-Lopez, J. P., Antonio-Villa, N. E., Vargas-Vázquez, A., González-Díaz, A., Márquez-Salinas, A., . . . Aguilar-Salinas, C. A. (2020, January 01). Predicting mortality due to SARS-CoV-2: A mechanistic score relating obesity and diabetes to COVID-19 outcomes in Mexico. Retrieved from https://www.medrxiv.org/content/10.1101/2020.04.20.20072223v4
