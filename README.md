# Dental Dimension Analysis using MaskRCNN

## Problem Statement
In pediatric dentistry, ensuring the proper development of a child’s permanent teeth is critical. When a baby tooth is lost prematurely, dentists often place space maintainers to preserve the necessary space for the incoming permanent tooth. However, identifying the appropriate spaces for these maintainers — especially between premolars and primary molars — can be a labor-intensive, subjective process prone to human error. This manual segmentation of dental images requires precise identification of tooth boundaries and gaps, which is crucial to avoid future alignment issues and to make timely clinical decisions.

Given the variability in tooth size, shape, and spacing across different patients, it becomes challenging for dental professionals to consistently and efficiently perform this task. As a result, the current manual approach is time-consuming, and the lack of automation in this process can delay treatment.

## Objectives

1). Automate Dental Image Segmentation\
2). Detect Gaps Between Premolars and Molars\
3). Enhance Clinical Efficiency\
4). Improve Precision of Gap Detection\
5). Provide a Tool for Real-time Clinical Decision Support\
6). Ensure Scalability Across Various Image Types\
7). Reduce Manual Errors and Subjectivity\
8). Integrate with Existing Dental Imaging Systems

## Proposed Solution

To address this problem, we propose developing a machine learning-based solution that automates the segmentation of dental images, specifically focusing on detecting gaps between premolars and primary molars. By using advanced models such as Mask R-CNN and Detectron, we aim to create a system that can accurately and consistently identify tooth boundaries, segment each tooth, and pinpoint the gaps that require space maintainers.

