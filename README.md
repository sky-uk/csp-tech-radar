# csp-tech-radar
The Content Supply Platforms department technology radar.

## Visualisation
The current Tech Radar can be viewed [here](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fraw.githubusercontent.com%2Fsky-uk%2Fcsp-tech-radar%2Fmaster%2Fcsp-tech-radar.csv) using the web application provided by ThoughtWorks.

## Goals
* Provide a succinct means for developers to view the technical opinions held by the department.
* To capture technical opinions in a collaborative and iterative way.

## Structure
All the technical opinions are captured as individual rows in a table kept in a simple [radar](csp-tech-radar.csv) CSV file.

The opinions are categorised into quadrants and rings on the radar as per the normal ThoughtWorks tech radar format.  
Opinions are only visualised as blips on a radar if they are 'in motion'. i.e. Only changed or new opinions are shown.

**Quadrants:**
* Languages & Frameworks - What we write our software in (Development)
* Platforms - What we run our software systems on and where we persist our data (Operations)
* Tools - What we use on the side to improve the way we develop and operate our systems (Dev & Ops)
* Techniques - What methods & practices we follow

**Rings:**
* Adopt - Mature and ready for use. You should be using these technologies if they are appropriate for your problem.
* Trial - Proven to be ready for use but not yet widely used. Should be carefully monitored when used in production.
* Assess - Something new that we are excited about but not yet sure it is production ready. Evidence why it solves a particular problem should be collected through some kind of POC.
* Hold - We know these are not ready for use or we are actively avoiding going forward.

For more information please see the [ThoughtWorks Tech Radar FAQ](https://www.thoughtworks.com/radar/faq).

## Contributing
Please follow the contributing guidelines [here](CONTRIBUTING.md)

## Testing Your Changes
It's best to test any changes you want to the [radar](csp-tech-radar.csv) CSV file by pushing them to github in a new branch (as per the contributing guidelines above). Navigating to the [radar](csp-tech-radar.csv) CSV file on github for your new branch (not on master!) and select the "Raw" view of the file. You can then copy the link to this file and enter it into the [ThoughtWorks radar tool](https://radar.thoughtworks.com) to render it with your changes.
