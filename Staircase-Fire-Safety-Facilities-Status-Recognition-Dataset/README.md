---
tags: Image Classification, Object Detection, Status Recognition, Building Safety, Fire Inspection, Facility Management
license: cc-by-nc-sa-4.0
task_categories: image-classification
language: en
pretty_name: Staircase Fire Safety Facilities Status Recognition Dataset
size_categories: 1B<n<10B
---

# Staircase Fire Safety Facilities Status Recognition Dataset

In modern building safety management, regular inspection of fire safety facilities is one of the crucial measures to ensure personnel safety. However, manual checks are inefficient and prone to errors, especially in high-rise buildings. Existing automated solutions often depend on inefficient sensor technology or non-real-time data monitoring, failing to meet both real-time and accuracy requirements. Therefore, the construction of this dataset aims to provide high-quality training data for automated fire safety facility status checks based on image recognition. The dataset captures images of the state of staircase fire safety facilities under different environmental lighting conditions through high-definition cameras, ensuring diversity and authenticity. Quality control includes multiple rounds of professional annotations, multiple consistency checks, and reviews by expert teams. The annotation team consists of fire safety management experts, numbering 50 people. Pre-processing steps include image cropping, noise reduction, and normalization. The data is stored in labeled JPG format and organized by building and floor.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| file_name | string | File name |
| quality | string | Resolution |
| facility_type | string | Identifies the type of firefighting equipment appearing in the image, such as fire extinguisher, fire hydrant, etc. |
| facility_condition | string | Identifies the condition of the firefighting equipment, such as intact, damaged, missing, etc. |
| obstruction_presence | boolean | Determines whether there is an obstruction blocking the firefighting equipment. |
| signage_visibility | boolean | Determines if the signage of the firefighting equipment is clearly visible. |
| facility_location | string | Describes the specific location of the firefighting equipment in the stairwell, such as left wall, staircase landing, etc. |
| maintenance_tag | boolean | Determines if there is a recent maintenance tag present on the firefighting equipment. |

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

If you need more dataset details, please visit [Mobiusi](https://www.mobiusi.com/datasets/7b7fdfa9107bc9986a0504ac850468be?utm_source=huggingface&utm_medium=referral). or contact us via contact@mobiusi.com
