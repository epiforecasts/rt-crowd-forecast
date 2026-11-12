# rt-crowd-forecast

> **Archived.** No longer maintained; last updated January 2021. The app wrote forecasts to Google Sheets belonging to the project account, so it will not work as deployed.

A Shiny app for crowd forecasting the time-varying reproduction number (Rt), built on the `crowdforecastr` package and deployed to shinyapps.io. Participants saw recent Rt estimates by region and submitted forecasts for four weeks ahead.

- `app.R`: launches `crowdforecastr::run_app()` with the observations and the Google Sheets used to store forecasts and user data.
- `external-ressources/observations.csv`: the Rt estimates shown to forecasters, taken from the `covid-german-forecasts` Rt forecasts.
- `rsconnect/`: shinyapps.io deployment settings.
