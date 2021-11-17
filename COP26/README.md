# COP26 Dataset

### Agreements [klimadashboard_COP26_agreements.csv](https://klimadashboard.at/data/COP26/klimadashboard_COP26_agreements.csv)

This file is available for all countries recognized by the United Nations (UN).

| Columns                         | Description                                                           |
|:---------------------------------|:----------------------------------------------------------------------|
| `state_iso`                    | ISO 3166-1 alpha-2 two-letter country code                              |
| `state_name`                      | Name of the country                                      |
| `status_deforestation`             | Status for the declaration on forests and land use, according [to the COP26 website](https://ukcop26.org/glasgow-leaders-declaration-on-forests-and-land-use/). Available statuses are `Pledged` and `NotPledged`                    |
| `status_methane`        | Status of their methane pledge, according [to the pledge’s website](https://www.globalmethanepledge.org). Available statuses are `Pledged` and `NotPledged`, as well as `PledgedAsPartOfEU` for countries that did not sign the pledge individually, but are part of the EU and thus part of the pledge made by the European Commission                |
| `status_coal`          | Status of the pledge made on phasing out coal according to [the COP26 website](https://ukcop26.org/global-coal-to-clean-power-transition-statement/). Available statuses are `Pledged` and `NotPledged`.`PledgedPlusPPCA` countries signed the COP26 pledge and have also signed the PPCA. We do not track the PPCA status for countries that are `NotPledged` at COP26. `IncompletePledged` refers to countries that only signed up to parts of the pledge. `NoCoal` is added to countries which currently do not use coal for power generation according to [Our World In Data](https://ourworldindata.org/explorers/energy?facet=none&country=~SOM&Total+or+Breakdown=Select+a+source&Select+a+source=Coal&Energy+or+Electricity=Electricity+only&Metric=Annual+generation), [Carbon Brief](https://www.carbonbrief.org/mapped-worlds-coal-power-plants) and the [Bloomberg Coal Countdown](https://bloombergcoalcountdown.com).  `UsesCoal` refers to countries currently using or planning to use coal for power generation.                 |
| `status_cars`          | Status of the pledge on moving towards zero emission cars and vans. Available statuses are `Pledged2040` for governments of developed countries (Article A of the pledge, agreeing to phase out by 2040 and 2035 for leading markets), `PledgedAccelerated` for governments of emerging markets (Article B of the pledge, agreeing to work intensely towards accelerated proliferation and adoption of zero emission vehicles), and `NotPledged`. Source is [this press release by the UK government](https://www.gov.uk/government/publications/cop26-declaration-zero-emission-cars-and-vans/cop26-declaration-on-accelerating-the-transition-to-100-zero-emission-cars-and-vans)            |

## Changelog
- 07.11.2021 initial release

## License
Please refer to our [data hub](https://github.com/klimadashboard/data) for information on licensing.

## Authors
The datasets in this repository were assembled by Adrian Hiss, David Jablonski and Johannes Stangl. For questions, please write to data@klimadashboard.at.

Klimadashboard aims to collect, publish and visualise data on the climate crisis. [Read more about us.](https://klimadashboard.at)