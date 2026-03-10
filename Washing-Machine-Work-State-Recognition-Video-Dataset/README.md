---
tags: video analysis, pattern recognition, machine learning, smart home, appliance monitoring, machine state detection
license: cc-by-nc-sa-4.0
task_categories: video-classification
language: en
pretty_name: Washing Machine Work State Recognition Video Dataset
size_categories: 1B<n<10B
---

# Washing Machine Work State Recognition Video Dataset

With the rapid expansion of the smart home market, consumer demands for the intelligentization of home appliances continue to rise. However, there are still challenges in the operation state recognition of many appliances, making true automation and remote monitoring difficult to achieve. Existing solutions often rely on traditional sensors, which have limitations such as installation difficulty, high cost, and insufficient effectiveness. This dataset is built to enhance the accuracy and reliability of washing machine work state recognition through video analysis technology, meeting the growing needs of the smart home market. The dataset consists of videos collected from multiple home environments, involving washing machines of different brands and models. Data collection uses high-definition camera equipment and recordings are made in real home environments to ensure data diversity and representativeness. Quality control is ensured through multiple rounds of annotation and expert review to guarantee the accuracy and consistency of data descriptions. A professional annotation team, composed of electrical engineers and data scientists, is responsible for the detailed classification of washing machine work states. Data preprocessing includes video editing, frame-by-frame processing, noise reduction, and format conversion, ultimately stored in structured MP4 format for subsequent model training and algorithm testing.

## Technical Specifications

| Field | Type | Description |
| :---  | :---  | :--- |
| file_name | string | File name |
| duration | string | Duration |
| quality | string | Resolution |
| machine_state | string | The current operating state of the washing machine in the video, such as washing, rinsing, or spinning. |
| load_type | string | The type of load inside the washing machine, such as clothes or bed linen. |
| water_level | string | The current water level in the washing machine, such as low, medium, or high. |
| time_remaining | integer | The remaining time for the current washing machine cycle, measured in minutes. |
| spin_speed | integer | The current spin speed of the washing machine, measured in revolutions per minute (RPM). |
| temperature | integer | The water temperature setting for the washing machine cycle, measured in degrees Celsius. |
| door_status | string | The open or closed status of the washing machine door, possible values: open, closed. |
| detergent_type | string | The type of detergent used in the washing machine, such as liquid detergent or powder detergent. |

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

If you need more dataset details, please visit [Mobiusi](https://www.mobiusi.com/datasets/b8d44acb9d8c199c9678cd72910a8f24?utm_source=huggingface&utm_medium=referral). or contact us via contact@mobiusi.com
