# README
Data from this repository belong to Zetta Health Analytics.

You find one dataset in the data folder:

* _'sample__data.csv'_ comprises a claims data of a sample of 300 workers from a health company in Brazil. Claims data cover a 12-month before and 6-month after a self-reported health assessment risk.


# DATASET
Cases: 300

Each line represents a person.
Features:

* id................................................ 01.ID 
* type.............................................. 02.Primary/Dependent
* before.hra.12m.claims.total....................... 03.Total Claims in BR$ currency 
* before.hra.12m.elective.encounter.cost............ 04.Elective Appointment $ 
* before.hra.12m.elective.encounter.event........... 05.Elective Appointment count 
* before.hra.12m.er.cost............................ 06.Emergency room costs $
* before.hra.12m.er.event........................... 07.Emergency room count
* before.hra.12m.exams.cost......................... 08.Diagnoses exams $
* before.hra.12m.exams.event........................ 09.Diagnoses QT
* before.hra.12m.hospital.cost...................... 10.Hospitalization $$
* before.hra.12m.hospital.events.................... 11.Hospitalization QT
* before.hra.12m.outpatient.cost.................... 12.Outpatient and Therapies $$
* before.hra.12m.outpatient.events.................. 13.Outpatient and Therapies QT
* after.hra.12m.claims.total........................ 14.Total Claims
* after.hra.12m.elective.encounter.cost............. 15.Elective Appointment  $$
* after.hra.12m.elective.encounter.event............ 16.Elective Appointment QT
* after.hra.12m.er.cost............................. 17.Emergency room $$
* after.hra.12m.er.event............................ 18.Emergency room QT
* after.hra.12m.exams.cost.......................... 19.Diagnoses $$
* after.hra.12m.exams.event......................... 20.Diagnoses QT
* after.hra.12m.hospital.cost....................... 21.Hospitalization $$
* after.hra.12m.hospital.events..................... 22.Hospitalization QT
* after.hra.12m.outpatient.cost..................... 23.Outpatient and Therapies $$
* after.hra.12m.outpatient.events................... 25.Outpatient and Therapies QT
* time.on.company .................................. 26.Time of job
* risk.factors.sum.................................. 27.Disease risk factor QT
* gender............................................ 28.gender {0: 'female', 1: 'male'}
* age............................................... 29.Age in years
* educational level................................. 30.Educational level
* househood.members................................. 31.number of people that you live with 
* asthma.bronquitis.emphysema....................... 32.Asma, bronquite ou enfisema
* allergies......................................... 34.(Alergias) 
* migraine.headache................................. 35.(Enxaqueca ou dor de cabeça) 
* insomnia.......................................... 36.(Insônia (dificuldade para dormir)) 
* rhinitis.sinusitis................................ 37.(Rinites, sinusites) 
* colestherol....................................... 38.(Colesterol alto) 
* dyslipidemia...................................... 39.(Dislipidemia) 
* diabetes.......................................... 40.(Diabetes) 
* thyroid........................................... 42.(Problemas de tiroide) 
* hepatitis......................................... 43.(Hepatite B ou C) 
* blood.pressure.................................... 44.(Pressão alta / hipertensão) 
* heart.conditions.................................. 45.(Problemas cardíacos (angina, infarto, insuficiência cardíaca)) 
* stroke............................................ 46.(Acidente vascular cerebral (derrame cerebral)) 
* ms................................................ 47.(Esclerose múltipla) 
* kidney............................................ 48.(Problemas renais) 
* gastritits........................................ 49.(Problemas digestivos (gastrite, azia, etc.)) 
* bowelsyndrome..................................... 50.Inflamatory bowel diseaes (eg. Chron's) 
* rheumatism........................................ 51.(Reumatismo (artrose, artrite, bursite)) 
* low.back.pai...................................... 52.(Lombalgia) 
* back.pain......................................... 53.(Problemas de coluna) 
* osteoporosis...................................... 54.(Osteoporose) 
* cancer............................................ 55.(Câncer (de qualquer tipo)) 
* anxietydisorders.................................. 56.(Transtornos de ansiedade (síndrome do pânico, fobias, etc.)) 
* depression........................................ 57.(Transtornos depressivos / depressão) 
* othermentalcondition.............................. 58.(Outra doença mental (transtorno bipolar, esquizofrenia, etc.)) 
* stds.............................................. 59.(STD ) 
* hiv................................................60.(HIV - Síndrome da imunodeficiência adquirida (HIV positivo)) 
* sedentary.lifestyle................................61.risk of sedentary lifestyle (Yes or No)
* n.risk.health.risk.factors.........................62.risk of sedentary lifestyle (Level) the more you have, less risk  
* risk.alcoholism....................................63.risk of alcoholism
* mental.health.risk.................................64.risk of mental health 
* weight.risk........................................65.risk of weight risk
* smoking.risk.......................................66.risk of smoking risk
* orthopedic.risk....................................67.risk of orthopedic risk
* beans.iron.risk....................................68.risk of iron
* fruits.veggies.....................................69.fruits and vegetables
* snacks.............................................70.snacks 
* sugar.sweets.......................................71.sugar and sweets 
* Integral.milk.risk.................................72.integral milk risk
* red.meat.risk......................................73.red meat risk
* snack.time.risk....................................74.snack time risk
* salt risk..........................................75.salt risk
* disease.risk.aggregated............................76.disease risk (aggregate of diseased saw it)
* total.risk.........................................77.total risk ( total of YES per line ) The more you have, more risk are related 

