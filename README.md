# Dashboard Mockups

This repository aims to gather the tools and instructions to create Mockups for Dashboards and Visualizations. Bitergia is using Kidash, a version of ElasticSearch's Kibana, to produce dashboards and visualizations.

## Kibana Mockups

This is a shape library for [Diagrams app](https://app.diagrams.net/) to create Mock-ups of Kibana visualizations and dashboards.

It contains most of the visualizations and elements we commonly use from Kibana interface, using shapes from Mockup library and other Diagram shape libraries. This library includes an empty panel shape where other visualization shapes can be arranged to create a mock-up for a panel.

![Shape library](docs/imgs/visualizations.png)

Together with this shape library, there is a template which layout contains the
panel mock-up itself along with empty text boxes to detail information about the panel, such as:

* Panel description (Title + general goal or use case the panel is meant to answer).
* Goals, Questions & Metrics covered on this panel (links to the Metrics Strategy documents).
* How to use this panel (Where and what to look at, specific details about how it works)
* About filters (Global filters applied to the dashboard, any other filter that would be +needed).
* About time-picker (default date range, which date field is used, etc.)
* Comments and limitations (other specific comments about the panel, known limitations if it is the case).

![Panel description template](docs/imgs/template.png)

### How to import the shape library

1. Go to [Diagrams tool](https://app.diagrams.net/) and create a new diagram.
1. Then, at the top bar menu, click on **File** -> **Open Library From**. There are two ways of importing the shape library:
  * **From the Device**: Clone this repository locally and select the file of this shape library, located in `libraries/diagrams/panel-mockups.xml`.
  * **URL**: On GitHub, go to the path where the library is located (`libraries/diagrams`) and click on the library file (`panel-mockups.xml`). Click on `Raw` and copy the URL of the raw file from your browser. Then paste the URL on Diagrams.

![Library: Import instructions](docs/imgs/instructions-import.png)

![Library: Import from URL instructions](docs/imgs/instructions-import-url.png)

### How to import the template

1. Go to [Diagrams tool](https://app.diagrams.net/) to create a new diagram.
1. Click on `From Template URL`.
1. On GitHub, go to the path where the template is located (`templates/diagrams`) and click on the library file (`panel-description-template.xml`). Click on `Raw` and copy the URL of the raw file from your browser.
1. Then paste the URL on Diagrams.

![Template: Create Diagram from template](docs/imgs/instructions-create-diagram-from-template.png)

![Template: Import from URL instructions](docs/imgs/instructions-import-template-url.png)

### Mock-up process

The process to produce a mock-up would consist on:

* Define the objective (use-case from a goal, sets of questions).
* Start from a copy of the main template.
* Arrange the visualizations that could form the panel using the custom shape library.
* Fill the text boxes with the appropriate description and details.
