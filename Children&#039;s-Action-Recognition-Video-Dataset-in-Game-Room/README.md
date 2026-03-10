---
tags: Action Recognition, Behavior Analysis, Video Classification, Intelligent Security, Human-Computer Interaction, Educational Technology
license: cc-by-nc-sa-4.0
task_categories: video-classification
language: en
pretty_name: Children&#039;s Action Recognition Video Dataset in Game Room
size_categories: 1B<n<10B
---

# Children&#039;s Action Recognition Video Dataset in Game Room

In the fields of intelligent security and human-computer interaction, recognizing children&#039;s actions and behaviors is an important technical issue. However, existing solutions have limitations in recognition accuracy and adaptability, often struggling to handle complex action diversity and occlusion issues. This dataset aims to address this challenge by providing high-quality video data to support researchers in developing more accurate action recognition models. The dataset is primarily collected in various environments such as homes, kindergartens, and game rooms, using high-definition camera equipment to ensure coverage of a variety of action types. Multiple rounds of annotation and consistency checks are conducted to ensure data quality, and the annotation team is composed of experienced action research experts with more than 10 members. Preprocessing techniques such as video denoising, inter-frame alignment, and action clipping are employed to guarantee data consistency and usability. The data is stored in MP4 format and organized by time and action type.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| file_name | string | File name |
| duration | string | Duration |
| quality | string | Resolution |
| child_count | integer | The number of children identified in the video. |
| actions_detected | string | List of types of children's actions identified in the video. |
| duration_of_actions | float | The duration of each detected action, measured in seconds. |
| object_presence | string | Indicator of whether specific objects, such as toys, are present in the video. |
| interaction_type | string | Types of interactions among children or with objects (such as competition, cooperation). |

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

If you need more dataset details, please visit [Mobiusi](https://www.mobiusi.com/datasets/5b42079fdcfef2f229b9eb229981c2f7?utm_source=huggingface&utm_medium=referral). or contact us via contact@mobiusi.com
