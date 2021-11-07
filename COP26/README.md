# COP26 Dataset

### Agreements

This file is available for all countries recognized by the United Nations (UN).

| Columns                         | Description                                                           |
|:---------------------------------|:----------------------------------------------------------------------|
| `state_iso`                    | ISO 3166-1 alpha-2 two-letter country code                              |
| `state_name`                      | Name of the country                                      |
| `status_deforestation`             | Status for the declaration on forests and land use, according [to the COP26 website](https://ukcop26.org/glasgow-leaders-declaration-on-forests-and-land-use/). Available statuses are `Pledged` and `NotPledged`                    |
| `status_methane`        | Status of their methane pledge, according [to the EU press release](https://ec.europa.eu/commission/presscorner/detail/en/statement_21_5766). Available statuses are `Pledged` and `NotPledged`, as well as `PledgedAsPartOfEU` for countries that did not sign the pledge individually, but are part of the EU and thus part of the pledge made by the European Commission                |
| `status_coal`          | Status of the pledge made on phasing out coal ** ADD SOURCE**. Available statuses are `Pledged` and `NotPledged`, as well as `PledgedAsPartOfEU` for countries that did not sign the pledge individually, but are part of the EU and thus part of the pledge made by the European Commission. `NoCoal` is added to countries which currently do not have active coal reserves and/or power production, according to **ADD SOURCE**                    |

## Changelog
- 07.11.2021 initial release

## License
Please refer to our [data hub](https://github.com/klimadashboard/data) for information on licensing.

## Authors
The datasets in this repository were assembled by Adrian Hiss, David Jablonski and Johannes Stangl. For questions, please write to data@klimadashboard.at.

Klimadashboard aims to collect, publish and visualise data on the climate crisis. [Read more about us.](https://klimadashboard.at)