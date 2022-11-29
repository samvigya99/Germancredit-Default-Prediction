# Germancredit-Default-Prediction
**It becomes strategically crucial for the banking industry to be able to determine whether a client is going to miss a premium payment or not. It is crucial for banks to be able to identify clients who have a high tendency to default early on since failing to anticipate the default propensity can lead to revenue losses. Who is likely to miss a premium payment? We will build models to predict which customers are likely to default using Machine Learning.**

Data Definition:

**DM**-> **Deutsche Mark**

Attribute 1: checkingstatus1

Status of existing checking account 
A11 : ... < 0 DM 
A12 : 0 <= ... < 200 DM 
A13 : ... >= 200 DM / salary assignments for at least 1 year 
A14 : no checking account

Attribute 2: duration

Duration in month

Attribute 3: history

Credit history 
A30 : no credits taken/ all credits paid back duly 
A31 : all credits at this bank paid back duly 
A32 : existing credits paid back duly till now 
A33 : delay in paying off in the past 
A34 : critical account/ other credits existing (not at this bank)

Attribute 4: Purpose

A40 : car (new) 
A41 : car (used) 
A42 : furniture/equipment 
A43 : radio/television 
A44 : domestic appliances 
A45 : repairs 
A46 : education 
A47 : (vacation - does not exist?) 
A48 : retraining 
A49 : business A410 : others

Attribute 5: amount

Credit amount

Attibute 6: savings

Savings account/bonds A61 : ... < 100 DM 
A62 : 100 <= ... < 500 DM 
A63 : 500 <= ... < 1000 DM 
A64 : .. >= 1000 DM 
A65 : unknown/ no savings account

Attribute 7: employ

Present employment since 
A71 : unemployed 
A72 : ... < 1 year 
A73 : 1 <= ... < 4 years 
A74 : 4 <= ... < 7 years 
A75 : .. >= 7 years

Attribute 8: installment

Installment rate in percentage of disposable income

Attribute 9: status

Personal status and sex 
A91 : male : divorced/separated 
A92 : female : divorced/separated/married 
A93 : male : single 
A94 : male : married/widowed 
A95 : female : single

Attribute 10: others

Other debtors / guarantors 
A101 : none 
A102 : co-applicant 
A103 : guarantor

Attribute 11: residence

Attribute 12: Property

A121 : real estate 
A122 : if not A121 : building society savings agreement/ life insurance 
A123 : if not A121/A122 : car or other, not in attribute 6 
A124 : unknown / no property

Attribute 13: age

Age in years

Attribute 14: otherplans

Other installment plans 
A141 : bank 
A142 : stores 
A143 : none

Attribute 15: housing

Housing 
A151 : rent 
A152 : own 
A153 : for free

Attribute 16: cards

Number of existing credits at this bank

Attribute 17: job

A171 : unemployed/ unskilled - non-resident 
A172 : unskilled - resident 
A173 : skilled employee / official 
A174 : management/ self-employed/ highly qualified employee/ officer

Attribute 18: liable

Number of people being liable to provide maintenance for

Attribute 19: tele

Telephone 
A191 : none 
A192 : yes, registered under the customers name

Attribute 20: foreign

foreign worker 
A201 : yes 
A202 : no
