# Racial Disparities in Traffic Stops/Citations

[Project](https://sta199-fa20-002.netlify.app/project/) for STA 199 - Fall 2020

**Summary:** According to a Pew Research Center survey (https://www.pewresearch.org/fact-tank/2020/06/03/10-things-we-know-about-race-and-policing-in-the-u-s/), "black adults are about five times as likely as whites to say they’ve been unfairly stopped by police because of their race or ethnicity." Given this information, we wish to investigate traffic stops in Durham from the Stanford Open Policing Project. We would like to see if that same kind of racial bias is evident in police stops in Durham. In doing so, we also wish to examine if other demographic characteristics (such as sex or age) influence traffic stops. Our general research question is the following: what is the relationship between a subject's demographic attributes (sex, race, or age) and the likelihood of being stopped by police in traffic in Durham? 

## Dataset

The data set is a census of individual police stops in Durham created by the Stanford Open Policing project. Each observation in the data set is an individual police stop recorded in Durham during 2001 to 2015.

## Description of variables

**date:** The date of the stop, in YYYY-MM-DD format.

**time:** The 24-hour time of the stop, in HH:MM format.

**subject_age:** The age of the stopped subject.

**subject_race:** The race of the stopped subject. Values are standardized to white, black, hispanic, asian/pacific islander, and other/unknown.

**officer_id_hash:** A unique hash of the officer id used to identify individual officers within a location. This is usually just a hash of the provided officer ID or badge number.

**citation_issued:** Indicates whether a citation was issued.

**outcome:** The strictest action taken among arrest, citation, warning, and summons.
