# Job transition visualization
Script and preliminary visualizations for [tailoredpath.com/transition.html](https://tailoredpath.com/transition.html).


## Purpose of this notebook:

This notebook contains the baseline for the Python script that runs on the **[interactive web app: tailoredpath.com/transition.html](https://tailoredpath.com/transition.html)**. 

The app accesses the data via an API built with [Python Flask](http://flask.pocoo.org/). The charts were developped with [Chart.js](https://www.chartjs.org/).

This notebook reproduces these visualizations with matplotlib.


## Data:

The [ONET program](https://www.onetcenter.org/overview.html) is the primary source of occupational information in the US. 

For each job, ONET rates the importance and level of all skills, knowledge and abilities, along with the required levels of education and experience. This data is available on their [resource center](https://www.onetcenter.org/database.html#individual-files).

More specifically, this notebook uses the following datasets:
- [Knowledge.xlsx](https://www.onetcenter.org/dictionary/23.3/excel/knowledge.html)
- [Skills.xlsx](https://www.onetcenter.org/dictionary/23.3/excel/skills.html)
- [Education, Training, and Experience.xlsx](https://www.onetcenter.org/dictionary/23.3/excel/education_training_experience.html)
- [Education, Training, and Experience Categories.xlsx](https://www.onetcenter.org/dictionary/23.3/excel/ete_categories.html)
- [Job Zones.xlsx](https://www.onetcenter.org/dictionary/23.3/excel/job_zones.html)
