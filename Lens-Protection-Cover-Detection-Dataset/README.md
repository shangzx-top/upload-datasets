---
tags:
- Object Detection
- Quality Assurance
- Camera Module Packaging Inspection
- Automatic Film Application Verification
license: cc-by-nc-sa-4.0
task_categories:
- object-detection
language:
- en
pretty_name: Lens Protection Cover Detection Dataset
size_categories:
- 1B<n<10B
---

# Lens Protection Cover Detection Dataset

In the current industrial landscape, the demand for efficient quality control systems is increasing, especially for camera module packaging. However, existing solutions often struggle with accuracy and speed in defect detection, leading to potential production losses. This dataset aims to address the need for precise inspection tools by providing high-quality images with annotations for lens protection cover detection. The dataset consists of images captured in controlled environments using high-resolution cameras. Data quality is ensured through multiple rounds of annotation and expert reviews to maintain consistency and accuracy. Images are stored in JPG format, organized into folders by categories to facilitate easy access and processing. The dataset is designed to enhance training performance for object detection algorithms.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| file_name | string | File name |
| quality | string | Resolution |
| object_count | int | The number of lens shields detected in the image. |
| reflectivity | float | The reflectance of the lens protector surface, quantifying the reflective properties. |
| object_position | string | The specific position coordinates of the lens protector in the image. |
| scratch_presence | boolean | Whether there are scratches on the lens protector (Yes: true, No: false). |
| contamination_level | string | The detected level of pollution on the lens protector, such as no pollution, slight pollution, moderate pollution, or heavy pollution. |
| material_type | string | The material type of the lens protector, for example: glass, plastic, polycarbonate, etc. |
| edge_smoothness | float | The measurement value of the smoothness of the lens protector's edges. |

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

If you need more dataset details, please visit [Mobiusi](https://www.mobiusi.com/datasets/98d1a2498268b64c9a491f9803f6db26?utm_source=huggingface&utm_medium=referral). or contact us via contact@mobiusi.com
