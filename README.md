**Federal Budget visualizations**

These are federal budget visualizations prepared for Mike Holland's [NYU CUSP](http://cusp.nyu.edu/) lecture on the inner works of the US federal budget committees.

The visualizations are root trees in the style of the famous [NY Times 2012 visualization by Shan Carter and Amanda Cox](http://www.nytimes.com/packages/html/newsgraphics/2011/0119-budget).
Visualizations are made for the 2012 budget compared to the 2010 and the 2017 budget compared to the 2016. 
In each visuzlization the size of the money allocated for a department/agency/program is represented as the size of the corresponding box. 
Funds are aggregated wither by *Account* or by *Super Function* (what is a super function?? the SuperFunction categories are shown below).
One last set of visualizations has the mandatory budget grayed out, so one can focus on the discretionary budget decisions. 

All plots are aggregates in [this](http://cosmo.nyu.edu/~fb55/budgetTree/) webpage.

The visualizations are created in D3, the code that parses the original budget excell spreadsheet to prepare json files for the visualization is in [budgetParser.ipynb](budgetParser.ipynb).

Super Functions : 

50 National Defense (=051+053+054)

150 Intl Affairs (=151+152+153+154+155)

500 Education, training, employment, and social services (=501+502+503+504+505+506)

550 Health (=551+552+554+570+571)

600 Income Security (=601+602+603+604+605+609)

650 Social Security (651)

700 Veterans Benefits (=701+702+703+704+705)

270 Energy (=271+272+274+276)

300 Natural Resources, Environment (=301+302+303+304+306)

370 Commerce and housing credit (=371+372+373+376)

400 Transportation (=401+402+403+407)

450 Community and regional development (=451+452+453)

250 S&T, Space (=251+252)

350 Agriculture (=351+352)

750 Justice (=751+752+753+754)

800 General Govt (=801+802+803+804+805+806+808)

900 Net interest (=901+902+903+908+909)
