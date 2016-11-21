# dwp-employment-support-allowance
Number of Employment and Support Allowance claimants by age, gender, and ethnicity.

This dataset contains a count of all people claiming Employment Support Allowance (ESA). Data shown here are derived from a 100% data source - the Work and Pensions Longitudinal Study (WPLS) - which is not subject to any sampling error. Breakdowns are available by benefit type, award rate, gender, duration, age, and reason for claiming. A very small number of claimants who have an unknown age/gender are included within the area total but excluded from the age/gender breakdowns as they pose a small disclosure risk.

Statistics created by Department for Work and Pensions:  http://statistics.gov.scot/data/employment-support-allowance

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/dwp-employment-support-allowance.git
```

Install npm dependencies

```
cd dwp-employment-support-allowance
npm install
```

Run the API (from the dwp-employment-support-allowance directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
