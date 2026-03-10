---
tags: event recognition, image classification, process analysis, language culture research, smart recognition, ritual activity analysis
license: cc-by-nc-sa-4.0
task_categories: image-classification
language: en
pretty_name: Smart Recognition Event Dataset of Home Small-Scale Ritual Activities and Supplies
size_categories: 1B<n<10B
---

# Smart Recognition Event Dataset of Home Small-Scale Ritual Activities and Supplies

Currently, with the development of modern society and the gradual fading of traditional culture, the cultural customs of many family ritual activities are at risk of being lost. Existing research and recognition mainly rely on human experience, and the application of modern technology is not deep and comprehensive enough. This dataset primarily aims to solve the problem of identifying supplies and recording processes in rituals through smart recognition technology, meeting the needs of language culture research and intelligent recognition system development. The data collection process includes capturing celebration processes and supplies images in a home ritual environment through cameras and sensors, with data quality ensured by multiple rounds of labeling and expert review. The labeling team consists of individuals with a language culture background and data analysis experts. The preprocessing process covers steps like data cleaning, format conversion, and label unification, finally stored and structured in JSON format. The data collection and labeling process ensures a high level of data quality and usability. Its core advantage lies in the high accuracy and consistency of data labeling, with an average labeling accuracy of over 95%, employing novel labeling standards and data enhancement strategies. On the application level, this dataset can significantly improve the accuracy of ritual supplies recognition and provide reliable data support for process automation. Compared to similar datasets, our data is more in-depth in the cultural subdivision field, with higher scarcity and extensibility, making it widely applicable to application research under different cultural backgrounds.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| file_name | string | File name |
| ritual_step_id | integer | Unique identifier for a specific ritual step. |
| ritual_step_name | string | Name of the step in the ritual process. |
| duration_of_step | integer | Duration in seconds for which the ritual step is performed. |
| supply_item_id | integer | Unique identifier for a specific ritual supply. |
| supply_item_name | string | Name of the supplies used in the ritual. |
| location_of_ritual | string | Location where the small-scale ritual activity takes place. |
| participant_count | integer | Total number of participants involved in the ritual. |
| sound_presence | boolean | Indicates whether there is sound present during the ritual. |
| lighting_condition | string | Record the lighting conditions of the ritual activity, such as bright or dim. |
| gesture_recognition | string | Recognition of gestures or body movements used in the ritual. |

## Compliance Statement

<table>
  <tr>
    <td>Authorization Type</td>
    <td>CC-BY-NC-SA 4.0 (Attribution–NonCommercial–ShareAlike)</td>
  </tr>
  <tr>
    <td>Commercial Use</td>
    <td>Requires exclusive subscription or authorization contract (monthly or per-invocation charging)</td>
  </tr>
  <tr>
    <td>Privacy and Anonymization</td>
    <td>No PII, no real company names, simulated scenarios follow industry standards</td>
  </tr>
  <tr>
    <td>Compliance System</td>
    <td>Compliant with China's Data Security Law / EU GDPR / supports enterprise data access logs</td>
  </tr>
</table>

## Source & Contact

If you need more dataset details, please visit [Mobiusi](https://www.mobiusi.com/datasets/51dc2ffde974e5b826b08873cbb88033?utm_source=huggingface&utm_medium=referral). or contact us via contact@mobiusi.com
