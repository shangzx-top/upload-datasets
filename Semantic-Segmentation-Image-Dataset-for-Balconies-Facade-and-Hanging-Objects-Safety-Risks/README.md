---
tags: semantic segmentation, image recognition, safety hazard detection, building safety monitoring, smart city management, home security, property management
license: cc-by-nc-sa-4.0
task_categories: image-segmentation
language: en
pretty_name: Semantic Segmentation Image Dataset for Balconies Facade and Hanging Objects Safety Risks
size_categories: 1B<n<10B
---

# Semantic Segmentation Image Dataset for Balconies Facade and Hanging Objects Safety Risks

In the context of rapid urban development, the facades and hanging objects on balconies of apartments and homes have increasingly become part of safety concerns, posing potential threats to safety in daily life. Existing manual safety inspections are not only time-consuming and prone to omissions but also unable to effectively support real-time monitoring needs. This dataset aims to improve the efficiency of identifying safety hazards on balconies and hanging objects through precise semantic segmentation, meeting intelligent monitoring business needs. Image data of balconies in urban and rural residential buildings are collected by drone equipment from different heights and angles to ensure diversity and authenticity. During the data collection process, quality is strictly controlled using multiple annotation rounds and consistency checks, with all annotation results audited by a 30-member team with architectural and safety expertise. Data preprocessing adopts advanced technologies such as denoising, cropping, and enhancement, stored in JPG format and organized by building type and region. The annotation accuracy of this dataset reaches 95%, ensuring high consistency and completeness, utilizing improved annotation techniques and quality evaluation methods to enhance monitoring efficiency and safety. Compared to similar datasets, this dataset has unique advantages in terms of data breadth and rarity, providing diverse scenarios of urban and rural areas, and supporting multi-task extension applications. Through the application of this dataset, the accuracy of risk detection for balconies façades and their hanging objects has increased by 20%, showing significant application value.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| file_name | string | File name |
| quality | string | Resolution |
| balcony_present | boolean | Indicates whether a balcony is present in the image. |
| balcony_type | string | The specific type of balcony, such as open balcony or enclosed balcony. |
| hanging_objects_present | boolean | Indicates whether hanging objects are present in the image. |
| hanging_objects_type | string | The type of hanging objects, such as clothing or flower pots. |
| risk_level | string | The safety risk level of the hanging objects in the image, such as low, moderate, or high. |
| weather_condition | string | The weather condition at the time the image was captured, such as sunny, cloudy, or rainy. |
| time_of_day | string | The time of day when the image was captured, such as morning, afternoon, or evening. |
| visible_damage | boolean | Indicates whether there is visible damage to the balcony or hanging objects in the image. |

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

If you need more dataset details, please visit [Mobiusi](https://www.mobiusi.com/datasets/a5f6349eb517d6b6cfcc5a7f0c096ee2?utm_source=huggingface&utm_medium=referral). or contact us via contact@mobiusi.com
