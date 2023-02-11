## Salmon-ForecastR-Releases
Repository for major releases, feedback, and bug reports.

For details, check out the latest **[ForecastR Report](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiMi47T1rrvAhVVJjQIHQ-nCNYQFjAGegQIChAD&url=https%3A%2F%2Fwww.psc.org%2Fdownload%2F585%2Fvery-high-priority-chinook%2F11704%2Fs18-vhp15a-forecastr-tools-to-automate-forecasting-procedures-for-salmonid-terminal-run-and-escapement.pdf&usg=AOvVaw2ZHMiJb0dBhjytGgM8lgvZ)**


**What's New?**

*Version 2: 2023 Update --------------------------------------------*

This round of work focused on improving the user experience, but we
also added a new type of forecasting model to both the R package and the app:

* *NoAgeCovar*: For data sets without age classes (e.g., only have total run or escapement) that have covariates,
fit generalized linear models (GLM) and select the best combination of covariates.

App improvements since the last major release include:

* *dynamic interfaces*
   - model-specific menus for settings
   - model-specific diagnostics
   - data-specific model selections (e.g. on the model selections for comparing and ranking)
* *Tooltips*: click on/off to display short clarifications for app components, some with links to further information.
* *Sample data*: sample data sets are now integrated into the app and can be selected from drop down menu
* *Increased the number of models that can be compared*


*Version 1: 2021 Release --------------------------------------------*
Since the last major release in the spring of 2020,
the following major updates have been implemented:

* Return Rate (Mechanistic) Model added to the package code
and to the app interface.
* Explore tab options dynamically respond to data set and model selection (e.g. only show sibling regression model options
if data has age classes, menu options for model settings adapt to model selection)
*  Compare tab model selection re-design: have tabs for each model type now, with model-specific options.



*Note*: The code for the *ForecastR* package is continuously evolving. Whenever we get to a major release milestone, we make the code available here.  This repository is where the development team interacts with the End User Community.

*ForecastR* is available in 2 configurations:

* Shiny App: Interactive interface for exploring and ranking alternative forecast models.
* R Package: Command line access to the computational engine.


### What would you like to do?

Note: The links below will take you away from this page, unless you open them with "Right Click -> Open in New Tab".

#### I would like to play with the latest prototype


* Run the app on the server: Go to March 2021 version of the *ForecastR* App([SOLV server ](https://solv-code.shinyapps.io/forecastr/),[PSC server ](https://psc1.shinyapps.io/ForecastR/)), load in a data file, and explore the alternative forecast models.
* Install the package: Go to the [*ForecastR* Package](https://github.com/SalmonForecastR/ForecastR-Package), then build a custom script to automate your analyses (like this [demo script](https://github.com/SalmonForecastR/ForecastR-Releases/blob/main/1_DEMO_SCRIPT.R))
* Run the app locally: Download a [zip folder](https://github.com/SalmonForecastR/ForecastR-Releases/blob/main/Zipped_Releases/CK_ForecastR_prototype2021_03_08.zip) (Open this link in a new tab, then click the *Download* button),
	then run the *LaunchGUI.R* script.
* Examples of data input files can be found [on dropbpx](https://www.dropbox.com/sh/7pdqfmvn16v59uk/AAB52T_T8ItI0uEsjyk6PVXxa?dl=0) or [in this repo](https://github.com/SalmonForecastR/ForecastR-Releases/tree/main/SampleData).

#### I would like to find out more about *ForecastR*

The [Wiki](https://github.com/SalmonForecastR/ForecastR-Releases/wiki) describes the evolution of *ForecastR*, current developments,and planned features.

Notable pages are:

* [About](https://github.com/SalmonForecastR/ForecastR-Releases/wiki/1-About)
* [Structure](https://github.com/SalmonForecastR/ForecastR-Releases/wiki/2-Structure)



#### I would like to provide feedback

* To report a bug or request a feature, start a new issue [here](https://github.com/SalmonForecastR/ForecastR-Releases/issues) using either the *Bug* label or
the *Feature Request* label. To select a label, choose from the drop-menu on the right of the screen after you start a new issue.
* To provide feedback on the current prototype, leave a comment at [this thread](https://github.com/SalmonForecastR/ForecastR-Releases/issues/1)
* To add your system information to the "Verified Version Tracker", edit the first entry at [this thread](https://github.com/SalmonForecastR/ForecastR-Releases/issues/3)


