---
tags:
- object detection
- image classification
- agricultural monitoring
- crop management
- growth analysis
license: cc-by-nc-sa-4.0
task_categories:
- image-classification
language:
- en
pretty_name: Grass Growth Stage Monitoring Dataset
size_categories:
- 1B<n<10B
---

# Grass Growth Stage Monitoring Dataset

The agricultural sector currently faces challenges in monitoring plant growth, particularly in growth stage recognition and management. Existing solutions often rely on manual observation, which is inefficient and prone to errors. This dataset aims to assist researchers and practitioners in more accurately automating plant growth stage monitoring by providing high-quality image data. Data collection is performed using high-resolution cameras on crops at different growth stages, ensuring images are clear and representative. Each image undergoes multiple rounds of annotation and consistency checks, reviewed by experts to ensure data accuracy and reliability. Data is stored in JPEG format and organized by growth stage and shooting time for ease of use. The core advantage of this dataset is its high data quality, with annotation accuracy exceeding 95%, and through innovative multi-round annotation methods, consistency and completeness are improved. Simultaneously, the dataset provides crucial support for intelligent decision-making in agricultural production, effectively enhancing crop management efficiency, and is expected to reduce crop monitoring time by 30%.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| file_name | string | File name |
| quality | string | Resolution |
| growth_stage | string | The growth stage of grass, e.g., germination, growing stage. |
| grass_species | string | The species of grass in the image, which may include different types of grass. |
| health_status | string | The health status of the grass, such as healthy, diseased, or water deficient. |
| environment_condition | string | The environmental condition where the grass is growing, e.g., full sun, shaded, humid. |
| leaf_density | string | The leaf density of the grass, indicating the number of leaves and growth state. |

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

If you need more dataset details, please visit [Mobiusi](https://www.mobiusi.com/datasets/df2cab9b9851d7f68dd9653b955b8f33?utm_source=huggingface&utm_medium=referral). or contact us via contact@mobiusi.com
