**#Assignment 01: Evaluate the GDP Dataset**

**#Import required library**

import numpy library
import numpy as np
print ("library imported")

#Manually add the dataset
array4=['Algeria','Angola','Argentina','Australia','Austria','Bahamas','Bangladesh','Belarus','Belgium','Bhutan','Brazil','Bulgaria','Cambodia','Cameroon','Chile','China','Colombia','Cyprus','Denmark','El Salvador','Estonia','Ethiopia','Fiji','Finland','France','Georgia','Ghana','Grenada','Guinea','Haiti','Honduras','Hungary','India','Indonesia','Ireland','Italy','Japan','Kenya', 'South Korea','Liberia','Malaysia','Mexico', 'Morocco','Nepal','New Zealand','Norway','Pakistan', 'Peru','Qatar','Russia','Singapore','South Africa','Spain','Sweden','Switzerland','Thailand', 'United Arab Emirates','United Kingdom','United States','Uruguay','Venezuela','Vietnam','Zimbabwe']
array5=[2255.225482,629.9553062,11601.63022,25306.82494,27266.40335,19466.99052,588.3691778,2890.345675,24733.62696,1445.760002,4803.398244,2618.876037,590.4521124,665.7982328,7122.938458,2639.54156,3362.4656,15378.16704,30860.12808,2579.115607,6525.541272,229.6769525,2242.689259,27570.4852,23016.84778,1334.646773,402.6953275,6047.200797,394.1156638,385.5793827,1414.072488,5745.981529,837.7464011,1206.991065,27715.52837,18937.24998,39578.07441,478.2194906,16684.21278,279.2204061,5345.213415,6288.25324,1908.304416,274.8728621,14646.42094,40034.85063,672.1547506,3359.517402,36152.66676,3054.727742,33529.83052,3825.093781,15428.32098,33630.24604,39170.41371,2699.123242,21058.43643,28272.40661,37691.02733,9581.05659,5671.912202,757.4009286,347.7456605]

**Find and print the name of the country with the highest GDP**
print(np.argmax(array3))

**#Print the name of the country**
print(array2[0][45])

**Find and print the name of the country with the lowest GDP**
print(np.argmin(array3))

**#Print the name of the country**
print (array2[0][21])

**Print out text ('evaluating country') and input value ('country name') iteratively**
#Use a for loop to print the required output
array4=['Algeria','Angola','Argentina','Australia','Austria','Bahamas','Bangladesh','Belarus','Belgium','Bhutan','Brazil','Bulgaria','Cambodia','Cameroon','Chile','China','Colombia','Cyprus','Denmark','El Salvador','Estonia','Ethiopia','Fiji','Finland','France','Georgia','Ghana','Grenada','Guinea','Haiti','Honduras','Hungary','India','Indonesia','Ireland','Italy','Japan','Kenya', 'South Korea','Liberia','Malaysia','Mexico', 'Morocco','Nepal','New Zealand','Norway','Pakistan', 'Peru','Qatar','Russia','Singapore','South Africa','Spain','Sweden','Switzerland','Thailand', 'United Arab Emirates','United Kingdom','United States','Uruguay','Venezuela','Vietnam','Zimbabwe']

for i in array4:
    print('countries {}'.format(i))

**** Print out the entire list of the countries with their GDPs****

array4=['Algeria','Angola','Argentina','Australia','Austria','Bahamas','Bangladesh','Belarus','Belgium','Bhutan','Brazil','Bulgaria','Cambodia','Cameroon','Chile','China','Colombia','Cyprus','Denmark','El Salvador','Estonia','Ethiopia','Fiji','Finland','France','Georgia','Ghana','Grenada','Guinea','Haiti','Honduras','Hungary','India','Indonesia','Ireland','Italy','Japan','Kenya', 'South Korea','Liberia','Malaysia','Mexico', 'Morocco','Nepal','New Zealand','Norway','Pakistan', 'Peru','Qatar','Russia','Singapore','South Africa','Spain','Sweden','Switzerland','Thailand', 'United Arab Emirates','United Kingdom','United States','Uruguay','Venezuela','Vietnam','Zimbabwe']
array5=[2255.225482,629.9553062,11601.63022,25306.82494,27266.40335,19466.99052,588.3691778,2890.345675,24733.62696,1445.760002,4803.398244,2618.876037,590.4521124,665.7982328,7122.938458,2639.54156,3362.4656,15378.16704,30860.12808,2579.115607,6525.541272,229.6769525,2242.689259,27570.4852,23016.84778,1334.646773,402.6953275,6047.200797,394.1156638,385.5793827,1414.072488,5745.981529,837.7464011,1206.991065,27715.52837,18937.24998,39578.07441,478.2194906,16684.21278,279.2204061,5345.213415,6288.25324,1908.304416,274.8728621,14646.42094,40034.85063,672.1547506,3359.517402,36152.66676,3054.727742,33529.83052,3825.093781,15428.32098,33630.24604,39170.41371,2699.123242,21058.43643,28272.40661,37691.02733,9581.05659,5671.912202,757.4009286,347.7456605]

for i in range(len(array4)):
    countries=array4[i]
    gdp=array5[i]
    print('countries {} gdp {} '.format(countries,gdp))

**Print the following:**

Highest GPD value
Lowest GDP value
Mean GDP value
Standardized GDP value
Sum of all the GDPs

**#List of countries:

#'Algeria','Angola','Argentina','Australia','Austria','Bahamas','Bangladesh','Belarus','Belgium','Bhutan','Brazil','Bulgaria','Cambodia','Cameroon','Chile','China','Colombia','Cyprus','Denmark','El Salvador','Estonia','Ethiopia','Fiji','Finland','France','Georgia','Ghana','Grenada','Guinea','Haiti','Honduras','Hungary','India','Indonesia','Ireland','Italy','Japan','Kenya', 'South Korea','Liberia','Malaysia','Mexico', 'Morocco','Nepal','New Zealand','Norway','Pakistan', 'Peru','Qatar','Russia','Singapore','South Africa','Spain','Sweden','Switzerland','Thailand', 'United Arab Emirates','United Kingdom','United States','Uruguay','Venezuela','Vietnam','Zimbabwe'


**#GDP values for each country:**

#2255.225482,629.9553062,11601.63022,25306.82494,27266.40335,19466.99052,588.3691778,2890.345675,24733.62696,1445.760002,4803.398244,2618.876037,590.4521124,665.7982328,7122.938458,2639.54156,3362.4656,15378.16704,30860.12808,2579.115607,6525.541272,229.6769525,2242.689259,27570.4852,23016.84778,1334.646773,402.6953275,6047.200797,394.1156638,385.5793827,1414.072488,5745.981529,837.7464011,1206.991065,27715.52837,18937.24998,39578.07441,478.2194906,16684.21278,279.2204061,5345.213415,6288.25324,1908.304416,274.8728621,14646.42094,40034.85063,672.1547506,3359.517402,36152.66676,3054.727742,33529.83052,3825.093781,15428.32098,33630.24604,39170.41371,2699.123242,21058.43643,28272.40661,37691.02733,9581.05659,5671.912202,757.4009286,347.7456605


[Countries with GDP.txt](https://github.com/SonamRajGupta/Analyse-GDP-of-Countries/files/8692458/Countries.with.GDP.txt)
# import numpy library
import numpy as np
print ("library imported")
library imported
#Create a 2-D array
array1=np.array([['Algeria','Angola','Argentina','Australia','Austria','Bahamas','Bangladesh','Belarus','Belgium','Bhutan','Brazil','Bulgaria','Cambodia','Cameroon','Chile','China','Colombia','Cyprus','Denmark','El Salvador','Estonia','Ethiopia','Fiji','Finland','France','Georgia','Ghana','Grenada','Guinea','Haiti','Honduras','Hungary','India','Indonesia','Ireland','Italy','Japan','Kenya', 'South Korea','Liberia','Malaysia','Mexico', 'Morocco','Nepal','New Zealand','Norway','Pakistan', 'Peru','Qatar','Russia','Singapore','South Africa','Spain','Sweden','Switzerland','Thailand', 'United Arab Emirates','United Kingdom','United States','Uruguay','Venezuela','Vietnam','Zimbabwe'


],[2255.225482,629.9553062,11601.63022,25306.82494,27266.40335,19466.99052,588.3691778,2890.345675,24733.62696,1445.760002,4803.398244,2618.876037,590.4521124,665.7982328,7122.938458,2639.54156,3362.4656,15378.16704,30860.12808,2579.115607,6525.541272,229.6769525,2242.689259,27570.4852,23016.84778,1334.646773,402.6953275,6047.200797,394.1156638,385.5793827,1414.072488,5745.981529,837.7464011,1206.991065,27715.52837,18937.24998,39578.07441,478.2194906,16684.21278,279.2204061,5345.213415,6288.25324,1908.304416,274.8728621,14646.42094,40034.85063,672.1547506,3359.517402,36152.66676,3054.727742,33529.83052,3825.093781,15428.32098,33630.24604,39170.41371,2699.123242,21058.43643,28272.40661,37691.02733,9581.05659,5671.912202,757.4009286,347.7456605]])
print(array1)
print(type(array1))
print (array1.shape)
print(array1.size)
print(np.argmax(array1))
[['Algeria' 'Angola' 'Argentina' 'Australia' 'Austria' 'Bahamas'
  'Bangladesh' 'Belarus' 'Belgium' 'Bhutan' 'Brazil' 'Bulgaria'
  'Cambodia' 'Cameroon' 'Chile' 'China' 'Colombia' 'Cyprus' 'Denmark'
  'El Salvador' 'Estonia' 'Ethiopia' 'Fiji' 'Finland' 'France' 'Georgia'
  'Ghana' 'Grenada' 'Guinea' 'Haiti' 'Honduras' 'Hungary' 'India'
  'Indonesia' 'Ireland' 'Italy' 'Japan' 'Kenya' 'South Korea' 'Liberia'
  'Malaysia' 'Mexico' 'Morocco' 'Nepal' 'New Zealand' 'Norway' 'Pakistan'
  'Peru' 'Qatar' 'Russia' 'Singapore' 'South Africa' 'Spain' 'Sweden'
  'Switzerland' 'Thailand' 'United Arab Emirates' 'United Kingdom'
  'United States' 'Uruguay' 'Venezuela' 'Vietnam' 'Zimbabwe']
 ['2255.225482' '629.9553062' '11601.63022' '25306.82494' '27266.40335'
  '19466.99052' '588.3691778' '2890.345675' '24733.62696' '1445.760002'
  '4803.398244' '2618.876037' '590.4521124' '665.7982328' '7122.938458'
  '2639.54156' '3362.4656' '15378.16704' '30860.12808' '2579.115607'
  '6525.541272' '229.6769525' '2242.689259' '27570.4852' '23016.84778'
  '1334.646773' '402.6953275' '6047.200797' '394.1156638' '385.5793827'
  '1414.072488' '5745.981529' '837.7464011' '1206.991065' '27715.52837'
  '18937.24998' '39578.07441' '478.2194906' '16684.21278' '279.2204061'
  '5345.213415' '6288.25324' '1908.304416' '274.8728621' '14646.42094'
  '40034.85063' '672.1547506' '3359.517402' '36152.66676' '3054.727742'
  '33529.83052' '3825.093781' '15428.32098' '33630.24604' '39170.41371'
  '2699.123242' '21058.43643' '28272.40661' '37691.02733' '9581.05659'
  '5671.912202' '757.4009286' '347.7456605']]
<class 'numpy.ndarray'>
(2, 63)
126
62
array2=np.array([['Algeria','Angola','Argentina','Australia','Austria','Bahamas','Bangladesh','Belarus','Belgium','Bhutan','Brazil','Bulgaria','Cambodia','Cameroon','Chile','China','Colombia','Cyprus','Denmark','El Salvador','Estonia','Ethiopia','Fiji','Finland','France','Georgia','Ghana','Grenada','Guinea','Haiti','Honduras','Hungary','India','Indonesia','Ireland','Italy','Japan','Kenya', 'South Korea','Liberia','Malaysia','Mexico', 'Morocco','Nepal','New Zealand','Norway','Pakistan', 'Peru','Qatar','Russia','Singapore','South Africa','Spain','Sweden','Switzerland','Thailand', 'United Arab Emirates','United Kingdom','United States','Uruguay','Venezuela','Vietnam','Zimbabwe'


]])
print(array2)
[['Algeria' 'Angola' 'Argentina' 'Australia' 'Austria' 'Bahamas'
  'Bangladesh' 'Belarus' 'Belgium' 'Bhutan' 'Brazil' 'Bulgaria'
  'Cambodia' 'Cameroon' 'Chile' 'China' 'Colombia' 'Cyprus' 'Denmark'
  'El Salvador' 'Estonia' 'Ethiopia' 'Fiji' 'Finland' 'France' 'Georgia'
  'Ghana' 'Grenada' 'Guinea' 'Haiti' 'Honduras' 'Hungary' 'India'
  'Indonesia' 'Ireland' 'Italy' 'Japan' 'Kenya' 'South Korea' 'Liberia'
  'Malaysia' 'Mexico' 'Morocco' 'Nepal' 'New Zealand' 'Norway' 'Pakistan'
  'Peru' 'Qatar' 'Russia' 'Singapore' 'South Africa' 'Spain' 'Sweden'
  'Switzerland' 'Thailand' 'United Arab Emirates' 'United Kingdom'
  'United States' 'Uruguay' 'Venezuela' 'Vietnam' 'Zimbabwe']]
array3=np.array([[2255.225482,629.9553062,11601.63022,25306.82494,27266.40335,19466.99052,588.3691778,2890.345675,24733.62696,1445.760002,4803.398244,2618.876037,590.4521124,665.7982328,7122.938458,2639.54156,3362.4656,15378.16704,30860.12808,2579.115607,6525.541272,229.6769525,2242.689259,27570.4852,23016.84778,1334.646773,402.6953275,6047.200797,394.1156638,385.5793827,1414.072488,5745.981529,837.7464011,1206.991065,27715.52837,18937.24998,39578.07441,478.2194906,16684.21278,279.2204061,5345.213415,6288.25324,1908.304416,274.8728621,14646.42094,40034.85063,672.1547506,3359.517402,36152.66676,3054.727742,33529.83052,3825.093781,15428.32098,33630.24604,39170.41371,2699.123242,21058.43643,28272.40661,37691.02733,9581.05659,5671.912202,757.4009286,347.7456605]])

print(array3)
array3.max()
[[ 2255.225482    629.9553062 11601.63022   25306.82494   27266.40335
  19466.99052     588.3691778  2890.345675  24733.62696    1445.760002
   4803.398244   2618.876037    590.4521124   665.7982328  7122.938458
   2639.54156    3362.4656    15378.16704   30860.12808    2579.115607
   6525.541272    229.6769525  2242.689259  27570.4852    23016.84778
   1334.646773    402.6953275  6047.200797    394.1156638   385.5793827
   1414.072488   5745.981529    837.7464011  1206.991065  27715.52837
  18937.24998   39578.07441     478.2194906 16684.21278     279.2204061
   5345.213415   6288.25324    1908.304416    274.8728621 14646.42094
  40034.85063     672.1547506  3359.517402  36152.66676    3054.727742
  33529.83052    3825.093781  15428.32098   33630.24604   39170.41371
   2699.123242  21058.43643   28272.40661   37691.02733    9581.05659
   5671.912202    757.4009286   347.7456605]]
40034.85063
print(np.argmax(array3))
45
# Name of the country with highest GDP
print(array2[0][45])
Norway
print(np.argmin(array3))
21
# Nmae of the country with lowest GDP
print (array2[0][21])
Ethiopia
array4=['Algeria','Angola','Argentina','Australia','Austria','Bahamas','Bangladesh','Belarus','Belgium','Bhutan','Brazil','Bulgaria','Cambodia','Cameroon','Chile','China','Colombia','Cyprus','Denmark','El Salvador','Estonia','Ethiopia','Fiji','Finland','France','Georgia','Ghana','Grenada','Guinea','Haiti','Honduras','Hungary','India','Indonesia','Ireland','Italy','Japan','Kenya', 'South Korea','Liberia','Malaysia','Mexico', 'Morocco','Nepal','New Zealand','Norway','Pakistan', 'Peru','Qatar','Russia','Singapore','South Africa','Spain','Sweden','Switzerland','Thailand', 'United Arab Emirates','United Kingdom','United States','Uruguay','Venezuela','Vietnam','Zimbabwe'

]
for i in array4:
    print('countries {}'.format(i))
countries Algeria
countries Angola
countries Argentina
countries Australia
countries Austria
countries Bahamas
countries Bangladesh
countries Belarus
countries Belgium
countries Bhutan
countries Brazil
countries Bulgaria
countries Cambodia
countries Cameroon
countries Chile
countries China
countries Colombia
countries Cyprus
countries Denmark
countries El Salvador
countries Estonia
countries Ethiopia
countries Fiji
countries Finland
countries France
countries Georgia
countries Ghana
countries Grenada
countries Guinea
countries Haiti
countries Honduras
countries Hungary
countries India
countries Indonesia
countries Ireland
countries Italy
countries Japan
countries Kenya
countries South Korea
countries Liberia
countries Malaysia
countries Mexico
countries Morocco
countries Nepal
countries New Zealand
countries Norway
countries Pakistan
countries Peru
countries Qatar
countries Russia
countries Singapore
countries South Africa
countries Spain
countries Sweden
countries Switzerland
countries Thailand
countries United Arab Emirates
countries United Kingdom
countries United States
countries Uruguay
countries Venezuela
countries Vietnam
countries Zimbabwe
array2.reshape(63,1)
array([['Algeria'],
       ['Angola'],
       ['Argentina'],
       ['Australia'],
       ['Austria'],
       ['Bahamas'],
       ['Bangladesh'],
       ['Belarus'],
       ['Belgium'],
       ['Bhutan'],
       ['Brazil'],
       ['Bulgaria'],
       ['Cambodia'],
       ['Cameroon'],
       ['Chile'],
       ['China'],
       ['Colombia'],
       ['Cyprus'],
       ['Denmark'],
       ['El Salvador'],
       ['Estonia'],
       ['Ethiopia'],
       ['Fiji'],
       ['Finland'],
       ['France'],
       ['Georgia'],
       ['Ghana'],
       ['Grenada'],
       ['Guinea'],
       ['Haiti'],
       ['Honduras'],
       ['Hungary'],
       ['India'],
       ['Indonesia'],
       ['Ireland'],
       ['Italy'],
       ['Japan'],
       ['Kenya'],
       ['South Korea'],
       ['Liberia'],
       ['Malaysia'],
       ['Mexico'],
       ['Morocco'],
       ['Nepal'],
       ['New Zealand'],
       ['Norway'],
       ['Pakistan'],
       ['Peru'],
       ['Qatar'],
       ['Russia'],
       ['Singapore'],
       ['South Africa'],
       ['Spain'],
       ['Sweden'],
       ['Switzerland'],
       ['Thailand'],
       ['United Arab Emirates'],
       ['United Kingdom'],
       ['United States'],
       ['Uruguay'],
       ['Venezuela'],
       ['Vietnam'],
       ['Zimbabwe']], dtype='<U20')
for i in array2.reshape(63,1):
    print('countries {}'.format(i))
countries ['Algeria']
countries ['Angola']
countries ['Argentina']
countries ['Australia']
countries ['Austria']
countries ['Bahamas']
countries ['Bangladesh']
countries ['Belarus']
countries ['Belgium']
countries ['Bhutan']
countries ['Brazil']
countries ['Bulgaria']
countries ['Cambodia']
countries ['Cameroon']
countries ['Chile']
countries ['China']
countries ['Colombia']
countries ['Cyprus']
countries ['Denmark']
countries ['El Salvador']
countries ['Estonia']
countries ['Ethiopia']
countries ['Fiji']
countries ['Finland']
countries ['France']
countries ['Georgia']
countries ['Ghana']
countries ['Grenada']
countries ['Guinea']
countries ['Haiti']
countries ['Honduras']
countries ['Hungary']
countries ['India']
countries ['Indonesia']
countries ['Ireland']
countries ['Italy']
countries ['Japan']
countries ['Kenya']
countries ['South Korea']
countries ['Liberia']
countries ['Malaysia']
countries ['Mexico']
countries ['Morocco']
countries ['Nepal']
countries ['New Zealand']
countries ['Norway']
countries ['Pakistan']
countries ['Peru']
countries ['Qatar']
countries ['Russia']
countries ['Singapore']
countries ['South Africa']
countries ['Spain']
countries ['Sweden']
countries ['Switzerland']
countries ['Thailand']
countries ['United Arab Emirates']
countries ['United Kingdom']
countries ['United States']
countries ['Uruguay']
countries ['Venezuela']
countries ['Vietnam']
countries ['Zimbabwe']
list=list(array2)
list
[array(['Algeria', 'Angola', 'Argentina', 'Australia', 'Austria',
        'Bahamas', 'Bangladesh', 'Belarus', 'Belgium', 'Bhutan', 'Brazil',
        'Bulgaria', 'Cambodia', 'Cameroon', 'Chile', 'China', 'Colombia',
        'Cyprus', 'Denmark', 'El Salvador', 'Estonia', 'Ethiopia', 'Fiji',
        'Finland', 'France', 'Georgia', 'Ghana', 'Grenada', 'Guinea',
        'Haiti', 'Honduras', 'Hungary', 'India', 'Indonesia', 'Ireland',
        'Italy', 'Japan', 'Kenya', 'South Korea', 'Liberia', 'Malaysia',
        'Mexico', 'Morocco', 'Nepal', 'New Zealand', 'Norway', 'Pakistan',
        'Peru', 'Qatar', 'Russia', 'Singapore', 'South Africa', 'Spain',
        'Sweden', 'Switzerland', 'Thailand', 'United Arab Emirates',
        'United Kingdom', 'United States', 'Uruguay', 'Venezuela',
        'Vietnam', 'Zimbabwe'], dtype='<U20')]
for i in list:
    print(i)
['Algeria' 'Angola' 'Argentina' 'Australia' 'Austria' 'Bahamas'
 'Bangladesh' 'Belarus' 'Belgium' 'Bhutan' 'Brazil' 'Bulgaria' 'Cambodia'
 'Cameroon' 'Chile' 'China' 'Colombia' 'Cyprus' 'Denmark' 'El Salvador'
 'Estonia' 'Ethiopia' 'Fiji' 'Finland' 'France' 'Georgia' 'Ghana'
 'Grenada' 'Guinea' 'Haiti' 'Honduras' 'Hungary' 'India' 'Indonesia'
 'Ireland' 'Italy' 'Japan' 'Kenya' 'South Korea' 'Liberia' 'Malaysia'
 'Mexico' 'Morocco' 'Nepal' 'New Zealand' 'Norway' 'Pakistan' 'Peru'
 'Qatar' 'Russia' 'Singapore' 'South Africa' 'Spain' 'Sweden'
 'Switzerland' 'Thailand' 'United Arab Emirates' 'United Kingdom'
 'United States' 'Uruguay' 'Venezuela' 'Vietnam' 'Zimbabwe']
# Joining the two string
array4=['Algeria','Angola','Argentina','Australia','Austria','Bahamas','Bangladesh','Belarus','Belgium','Bhutan','Brazil','Bulgaria','Cambodia','Cameroon','Chile','China','Colombia','Cyprus','Denmark','El Salvador','Estonia','Ethiopia','Fiji','Finland','France','Georgia','Ghana','Grenada','Guinea','Haiti','Honduras','Hungary','India','Indonesia','Ireland','Italy','Japan','Kenya', 'South Korea','Liberia','Malaysia','Mexico', 'Morocco','Nepal','New Zealand','Norway','Pakistan', 'Peru','Qatar','Russia','Singapore','South Africa','Spain','Sweden','Switzerland','Thailand', 'United Arab Emirates','United Kingdom','United States','Uruguay','Venezuela','Vietnam','Zimbabwe'

]
array5=[2255.225482,629.9553062,11601.63022,25306.82494,27266.40335,19466.99052,588.3691778,2890.345675,24733.62696,1445.760002,4803.398244,2618.876037,590.4521124,665.7982328,7122.938458,2639.54156,3362.4656,15378.16704,30860.12808,2579.115607,6525.541272,229.6769525,2242.689259,27570.4852,23016.84778,1334.646773,402.6953275,6047.200797,394.1156638,385.5793827,1414.072488,5745.981529,837.7464011,1206.991065,27715.52837,18937.24998,39578.07441,478.2194906,16684.21278,279.2204061,5345.213415,6288.25324,1908.304416,274.8728621,14646.42094,40034.85063,672.1547506,3359.517402,36152.66676,3054.727742,33529.83052,3825.093781,15428.32098,33630.24604,39170.41371,2699.123242,21058.43643,28272.40661,37691.02733,9581.05659,5671.912202,757.4009286,347.7456605]
for i in range(len(array4)):
    countries=array4[i]
    gdp=array5[i]
    print('countries {} gdp {} '.format(countries,gdp))
countries Algeria gdp 2255.225482 
countries Angola gdp 629.9553062 
countries Argentina gdp 11601.63022 
countries Australia gdp 25306.82494 
countries Austria gdp 27266.40335 
countries Bahamas gdp 19466.99052 
countries Bangladesh gdp 588.3691778 
countries Belarus gdp 2890.345675 
countries Belgium gdp 24733.62696 
countries Bhutan gdp 1445.760002 
countries Brazil gdp 4803.398244 
countries Bulgaria gdp 2618.876037 
countries Cambodia gdp 590.4521124 
countries Cameroon gdp 665.7982328 
countries Chile gdp 7122.938458 
countries China gdp 2639.54156 
countries Colombia gdp 3362.4656 
countries Cyprus gdp 15378.16704 
countries Denmark gdp 30860.12808 
countries El Salvador gdp 2579.115607 
countries Estonia gdp 6525.541272 
countries Ethiopia gdp 229.6769525 
countries Fiji gdp 2242.689259 
countries Finland gdp 27570.4852 
countries France gdp 23016.84778 
countries Georgia gdp 1334.646773 
countries Ghana gdp 402.6953275 
countries Grenada gdp 6047.200797 
countries Guinea gdp 394.1156638 
countries Haiti gdp 385.5793827 
countries Honduras gdp 1414.072488 
countries Hungary gdp 5745.981529 
countries India gdp 837.7464011 
countries Indonesia gdp 1206.991065 
countries Ireland gdp 27715.52837 
countries Italy gdp 18937.24998 
countries Japan gdp 39578.07441 
countries Kenya gdp 478.2194906 
countries South Korea gdp 16684.21278 
countries Liberia gdp 279.2204061 
countries Malaysia gdp 5345.213415 
countries Mexico gdp 6288.25324 
countries Morocco gdp 1908.304416 
countries Nepal gdp 274.8728621 
countries New Zealand gdp 14646.42094 
countries Norway gdp 40034.85063 
countries Pakistan gdp 672.1547506 
countries Peru gdp 3359.517402 
countries Qatar gdp 36152.66676 
countries Russia gdp 3054.727742 
countries Singapore gdp 33529.83052 
countries South Africa gdp 3825.093781 
countries Spain gdp 15428.32098 
countries Sweden gdp 33630.24604 
countries Switzerland gdp 39170.41371 
countries Thailand gdp 2699.123242 
countries United Arab Emirates gdp 21058.43643 
countries United Kingdom gdp 28272.40661 
countries United States gdp 37691.02733 
countries Uruguay gdp 9581.05659 
countries Venezuela gdp 5671.912202 
countries Vietnam gdp 757.4009286 
countries Zimbabwe gdp 347.7456605 
# Highest GDP value
array3=np.array([[2255.225482,629.9553062,11601.63022,25306.82494,27266.40335,19466.99052,588.3691778,2890.345675,24733.62696,1445.760002,4803.398244,2618.876037,590.4521124,665.7982328,7122.938458,2639.54156,3362.4656,15378.16704,30860.12808,2579.115607,6525.541272,229.6769525,2242.689259,27570.4852,23016.84778,1334.646773,402.6953275,6047.200797,394.1156638,385.5793827,1414.072488,5745.981529,837.7464011,1206.991065,27715.52837,18937.24998,39578.07441,478.2194906,16684.21278,279.2204061,5345.213415,6288.25324,1908.304416,274.8728621,14646.42094,40034.85063,672.1547506,3359.517402,36152.66676,3054.727742,33529.83052,3825.093781,15428.32098,33630.24604,39170.41371,2699.123242,21058.43643,28272.40661,37691.02733,9581.05659,5671.912202,757.4009286,347.7456605]])
array3.max()
40034.85063
# min gdp value
array3.min()
229.6769525
# gdp mean
array3.mean()
11289.409271639683
# gdp std
array3.std()
12743.828910617945
# gdp sum
array3.sum()
711232.7841133
 
