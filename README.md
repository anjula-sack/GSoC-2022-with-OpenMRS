# GSoC '22 - OpenMRS 3.0 Cohort Builder

This repository contains my weekly work done and updates regarding Google Summer of Code 2022 OpenMRS 3.0 Cohort Builder.

<br>

## What is Cohort Builder?

The Cohort Builder is a tool in OpenMRS 1.0 in the Reporting Compatibility module (included with most OpenMRS installations) that lets the user perform ad-hoc queries for patients with defined characteristics, and combines multiple queries into more complex ones.

GSoC project link: https://summerofcode.withgoogle.com/programs/2022/projects/8EksU68Y

<br>

## Community Discussion

- Community discussion thread for the project on OpenMRS Talk is [here](https://talk.openmrs.org/t/gsoc-2022-redo-legacy-ui-cohort-builder-project-updates/36847).

<br>

## Medium Articles (Weekly Updates)

| Week    | Article Link                                                                           |
| ------- | -------------------------------------------------------------------------------------- |
| Week 0  | https://medium.com/nerd-for-tech/community-bonding-gsoc-2022-with-openmrs-8c8cd17353af |
| Week 1  | https://anjulashanaka.medium.com/coding-week-01-gsoc-2022-with-openmrs-ba85dc087f6c    |
| Week 2  | https://anjulashanaka.medium.com/coding-week-02-gsoc-2022-with-openmrs-fc66cc0f9990    |
| Week 3  | https://anjulashanaka.medium.com/coding-week-03-gsoc-2022-with-openmrs-f7d674ff572c    |
| Week 4  | https://anjulashanaka.medium.com/coding-week-04-gsoc-2022-with-openmrs-a38a002b4bf5    |
| Week 5  | https://anjulashanaka.medium.com/coding-week-05-gsoc-2022-with-openmrs-85c440a9be87    |
| Week 6  | https://anjulashanaka.medium.com/coding-week-06-gsoc-2022-with-openmrs-c7930428e6d2    |
| Week 7  | https://anjulashanaka.medium.com/coding-week-07-gsoc-2022-with-openmrs-79e503231767    |
| Week 8  | https://anjulashanaka.medium.com/coding-week-08-gsoc-2022-with-openmrs-165f88c13a97    |
| Week 9  | https://anjulashanaka.medium.com/coding-week-09-gsoc-2022-with-openmrs-e8bb1b5d5357    |
| Week 10 | https://anjulashanaka.medium.com/coding-week-10-gsoc-2022-with-openmrs-2277ba6f2e45    |
| Week 11 | https://anjulashanaka.medium.com/coding-week-11-gsoc-2022-with-openmrs-5ca7f2503d82    |
| Week 12 | https://anjulashanaka.medium.com/coding-week-12-gsoc-2022-with-openmrs-6e3ee5f8d7cf    |

## JIRA Tickets

Epic link: https://issues.openmrs.org/browse/O3-1299

| Issue Number | Issue Link                                   | Pull Request                                                                                                                                | Status           |
| ------------ | -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| O3-1311      | https://issues.openmrs.org/browse/O3-1311    | [O3-1311: Initial setup of the project](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/1)                                        | Merged           |
| O3-1300      | https://issues.openmrs.org/browse/O3-1028    | [O3-1300: Implement search by concept component](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/2)                               | Merged           |
| O3-1385      | https://issues.openmrs.org/browse/O3-1385    | [O3-1385: Write unit tests to test the components](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/7)                             | Merged           |
| O3-1302      | https://issues.openmrs.org/browse/O3-1302    | [O3-1302: Implement the Search History component](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/8)                              | Merged           |
| O3-1394      | https://issues.openmrs.org/browse/O3-1394    | [O3-1394: Update the UI according to the new design](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/9)                           | Merged           |
| O3-1303      | https://issues.openmrs.org/browse/O3-1303    | [O3-1303: Implement the search by demographics and person attributes feature](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/10) | Merged           |
| O3-1304      | https://issues.openmrs.org/browse/O3-1304    | [O3-1304: Implement the search by encounters and search by location feature](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/11)  | Merged           |
| O3-1417      | https://issues.openmrs.org/browse/O3-1417    | [O3-1417: Use SWR for data fetching](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/12)                                          | Merged           |
| O3-1305      | https://issues.openmrs.org/browse/O3-1305    | [O3-1305: Implement the search by enrollments feature](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/14)                        | Merged           |
| O3-1427      | https://issues.openmrs.org/browse/O3-1427    | [O3-1427: Add the deploy job to the workflow](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/15)                                 | Merged           |
| REPORT-890   | https://issues.openmrs.org/browse/REPORT-890 | [REPORT-890: Add the missing api module dependency](https://github.com/openmrs/openmrs-module-reporting/pull/236)                           | Merged           |
| O3-1309      | https://issues.openmrs.org/browse/O3-1309    | [O3-1309: Implement the search definitions feature](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/16)                           | Merged           |
| O3-1443      | https://issues.openmrs.org/browse/O3-1443    | [O3-1443: Improve the tablet and small desktop layout](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/17)                        | Merged           |
| O3-1306      | https://issues.openmrs.org/browse/O3-1306    | [O3-1306: Implement the search by drug order feature](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/19)                         | Merged           |
| O3-1445      | https://issues.openmrs.org/browse/O3-1445    | [O3-1445: Add search composition feature](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/20)                                     | Merged           |
| O3-1471      | https://issues.openmrs.org/browse/O3-1471    | [O3-1471: Add css to fix the broken UI layout](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/22)                                | Merged           |
| O3-1472      | https://issues.openmrs.org/browse/O3-1472    | [O3-1472: Fix the tests that were skipped due to the migration](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/22)               | Merged |
| O3-1482 | https://issues.openmrs.org/browse/O3-1482 | [O3-1482: Wrap the global selectors with a custom class](https://github.com/openmrs/openmrs-esm-cohortbuilder/pull/24) | Merged |

## Resources

- [Cohort Builder Repository](https://github.com/openmrs/openmrs-esm-cohortbuilder)
- [Wiki page](https://wiki.openmrs.org/display/projects/GSoC+2022%3A+Redo+Legacy+UI+Cohort+Builder)
