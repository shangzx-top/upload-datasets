---
tags: Image classification, object detection, pattern recognition, Horticultural plant identification, plant classification, agricultural production management
license: cc-by-nc-sa-4.0
task_categories: image-classification
language: en
pretty_name: Yard Flower Musella Lasiocarpa Image Recognition Dataset
size_categories: 1B<n<10B
---

# Yard Flower Musella Lasiocarpa Image Recognition Dataset

The horticulture industry involves recognizing and managing a large number of plant species, currently facing challenges in accurately identifying specific flower varieties. Existing solutions mostly rely on human expertise, which can result in poor accuracy and consistency. This dataset aims to improve classification accuracy for machine learning models by providing high-quality images of Musella Lasiocarpa, catering to horticultural management needs. Data collection used high-resolution digital cameras to capture flowers in various growth stages under natural and standard laboratory lighting. Quality control measures include multiple rounds of annotation, expert review of images, consistency checks, and manual validation by personnel with a background in botany. The annotation team consists of 10 botany experts who rigorously ensure data accuracy and consistency. Data preprocessing includes denoising, cropping, and normalization of images, organized by date and flower status, and stored as JPG format files.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| file_name | string | File name |
| quality | string | Resolution |
| flower_type | string | The specific flower species identified in the image, mainly Musella or its variants. |
| growth_stage | string | The growth stage of the flower in the image, such as seedling stage, flowering stage, etc. |
| health_status | string | The health condition of the flower in the image, such as healthy, diseased, or wilted. |
| lighting_condition | string | The lighting condition during capturing, such as natural light, shadow, or bright light. |
| image_background | string | The background environment of the image, such as outdoor, greenhouse, or laboratory. |
| presence_of_pests | boolean | Whether there are pests or signs of pest damage to the flowers in the image. |
| weather_condition | string | The weather condition during the image capture, such as sunny, cloudy, or rainy. |
| leaf_condition | string | The condition of the plant leaves in the image, such as healthy, yellowing, or spotted. |

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

If you need more dataset details, please visit [Mobiusi](https://www.mobiusi.com/datasets/526558155ba1e5c59b6e6dffc2844163?utm_source=huggingface&utm_medium=referral). or contact us via contact@mobiusi.com
