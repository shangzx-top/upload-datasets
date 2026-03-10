---
tags: natural language processing, text classification, entity recognition, content generation, home cooking, food research, meal planning, intelligent assistants
license: cc-by-nc-sa-4.0
task_categories: text-generation
language: en
pretty_name: Practical Family Recipe Text Dataset
size_categories: 1B<n<10B
---

# Practical Family Recipe Text Dataset

The dataset features high-quality annotation accuracy, ensuring annotation consistency reaches over 95% through three rounds of expert annotation and review. Quality control and innovation are reflected in its use of cutting-edge natural language processing technology for content parsing and enhancement, significantly improving the practicality and reliability of the dataset. It offers significant application value by providing diverse recipe information that facilitates household users in achieving healthy eating goals, enhancing the accuracy of dining recommendations and automatic recipe content generation according to user needs. Compared to similar datasets, this dataset is more systematic and comprehensive, covering up to 1,000 home-style dishes, particularly suitable for complex meal planning. Its uniqueness lies in its inclusion of various seasonal ingredient information, increasing the dataset&#039;s extensibility and versatility.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| file_name | string | File name |
| recipe_title | string | The title of the recipe for easy identification and categorization. |
| ingredients | string | All ingredients needed for cooking the dish. |
| cooking_steps | text | Detailed steps and instructions for cooking. |
| cook_time | int | The approximate time needed to complete the dish, in minutes. |
| steps | int | The detailed cooking process of the dish, in array type, sorted by operation sequence |
| ingredients | Array | All ingredients needed to make the dish, in array type, sorted by core level/usage order |
| title | string | The standard name of the dish, reflecting the core ingredients/cooking method |
| category | string | Identify the cuisine/category of the dish for classification |

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

If you need more dataset details, please visit [Mobiusi](https://www.mobiusi.com/datasets/4c3d3334a8b5808cc5cad5388b610fde?utm_source=huggingface&utm_medium=referral). or contact us via contact@mobiusi.com
