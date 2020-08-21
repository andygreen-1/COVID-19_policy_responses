# COVID-19 Data Dashboards: Visualizing Policy Responses and Outcomes by State and Party

This repository contains the code, final dataset, and source data files for an analysis that looks at how each state has responded to the COVID-19 pandemic, and how that may be related to the volume of cases and deaths experienced by that state. I leverage data on COVID-19 cases and deaths by state, combined with information on when each state implemented key policy decisions, to create a series of interactive dashboards that allow the user to explore these relationships further.

These dashboards, along with a short accompanying piece, were published by the Georgetown Public Policy Review in August 2020. The link to that publication can be found [here](http://gppreview.com/2020/08/20/visualizing-covid-19-policy-responses-outcomes-state-party/).

You can find a brief summary of the files available in this repository below:

* COVID_dashboard.ipynb: Jupyter Notebook containing the code used to compile the datasets
* covid_policy.csv: Final state-level compiled dataset
* covid_party.csv: Final compiled dataset aggregated by party (averages for each party)
* Source_Data: Directory containing the four source data files
	* daily.csv: Daily data on confirmed COVID-19 cases, by state
		* Source: [The COVID Tracking Project](https://covidtracking.com/api/v1/states/daily.csv)
	* policy.xlsx: Data on policy responses by state
		* Source: [COVID-19 US State Policy Database](https://github.com/USCOVIDpolicy/COVID-19-US-State-Policy-Database)
	* governors.csv: Name and party of each state's governor
	    * Source: [Ballotpedia](https://ballotpedia.org/Partisan_composition_of_governors)
	* population.xlsx: Yearly data on total population, by state
		* Source: [U.S. Census Bureau](https://www2.census.gov/programs-surveys/popest/tables/2010-2019/state/totals/nst-est2019-01.xlsx)