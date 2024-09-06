# Turing PPL Forecasting Competition Example - Mpox

> [!Caution]
> This example competition is a work in progress and therefore some of the competition infrastructure is still being organised. The information on this page is also subject to change so please check back intermittently.

> [!note]
> This is an example competition repo for the Turing PPL forecasting events. It will have all of the information sections you will find in active competitions and will mostly follow the same rules/timelines.

## Introduction [^readme-1]

[^readme-1]: Adapted from WHO Mpox Dashboard (<https://worldhealthorg.shinyapps.io/mpx_global/>)

Mpox is an infectious disease that can cause a painful rash, enlarged lymph nodes, fever, headache, muscle ache, back pain and low energy. Most people fully recover, but some get very sick. 

Mpox is caused by the monkeypox virus (MPXV). It is an enveloped double-stranded DNA virus of the *Orthopoxvirus* genus in the *Poxviridae* family, which includes variola, cowpox, vaccinia and other viruses. There are two distinct clades of the virus: clade I (with subclades Ia and Ib) and clade II (with subclades IIa and IIb).

A global outbreak of clade IIb began in 2022 and continues to this day, including in some African countries. There are also growing outbreaks of clades Ia and Ib affecting the Democratic Republic of the Congo and other countries in Africa. As of August 2024, clade Ib has also been detected beyond Africa.

The natural reservoir of the virus is unknown, but various small mammals such as squirrels and monkeys are susceptible.

The dataset included in this forecasting competition covers the period from Jan 2022 to July 2024.

## Forecasting Outputs

This competition has its own repository with pre-prepared data (found in the data folder) and a template report (demo_analysis.qmd) which showcases how to load the data, perform analyses and then export results into the correct format. There is also be a folder for any additional scripts that are required.

For this example competition, we are looking to forecast monthly regional case numbers for the 6 WHO regions (African, Eastern Mediterranean, European, Region of the Americas, South-East Asia, Western Pacific) for the remainder of 2024 (August-December).

## Joining the Competition & Getting Started

The competition repo can be found here: [Competition-Example-Mpox](https://github.com/TuringPPL/Competition-Example-Mpox).

The simplest way to get started is to fork this repo and then clone it onto your local machine. This will allow the organisers to see the forks and keep track of entrants. Alternatively, you can download the repo manually and get started. Each entry must be uploaded to a public github repo to be considered (see Rules below)

## Rules

-   Any coding languages are allowed but all analyses must be reproducible by the panel.
-   All entries must be loaded into a public Github repo.
-   All entries must follow the submission formats outlined below.
-   All entries must include a max 1000 word report to accompany the forecast analyses. This can be as a separate PDF/hmtl or incorporated into a quarto/jupyter notebook.

## How to Submit

We are in the process of building back-end architecture to automatically find all forked repos and enter them into the competition but in the interim, please send an email to jtyler\@turing.ac.uk with a link to the public github repo.

The forecast estimates must be submitted as a csv with the name `Mpox_forecast.csv` and contain three columns: WHO region, month start date and Estimate (see example in the repo). The accompanying report should be titled `Mpox_report` and be in a format outlined in the Rules.

## Connect with the Community

This competition has a page on our TuringPPL Zulip where teams can message and get clarification/advice. We will also be monitoring the competition repo. Regular updates will be posted on both platforms.

## License

![CC-BYNCSA-4](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

Unless otherwise noted, the content in this repository is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

For the data sets in the *data/* folder, please see [*data/README.md*](data/README.md) for the applicable copyrights and licenses.
