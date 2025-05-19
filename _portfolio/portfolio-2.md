---
title: "(2) Object Detection System for Fasteners Identification"
# excerpt: "* Developed an application which **automatically extracts information** from engineering PDFs and structured them for **intelligent querying**. <br/><img src='/images/mtech_proj1_excerpt.png'>"
excerpt: >
  <ul>
    <li>Developed an object detection model to detect fasteners in an image and provide its coordinates for downstream tasks (e.g. robotic disassembly).</li>
    <li>Key features of this system include:</li>
    <ol>
        <li><strong>Camera Intrinsic Calibration:</strong> OpenCV</li>
        <li><strong>Object Detection:</strong> Fine-tuned YOLOv8m</li>
        <li><strong>Object Segmentation:</strong> Fine-tuned YOLOv8s-seg</li>
    </ol>
  </ul>
  <div style="text-align: center;">
  <img src="/images/mtech_proj2_excerpt.png" alt="Project Image" width="600">
  </div>

collection: portfolio
---

The objective of **Object Detection System for Fasteners Identification** is to develop an object detection model to assist in building a robotic disassembly system. Specifically, our developed model is designed to process the image taken by the camera mounted on an industry six-axis robot arm and identify all the bolts to be removed. Thereafter, the model will provide the bolts’ physical coordinates to the robot for automated unbolting.

As a proof-of-concept, a UI has been designed for user to upload an image to be processed. Bolts in the images will be identified along with the coordinates tabulated. 

<table>
  <tr>
    <td style="background-color: white; text-align: center;">
      <img src="/images/mtech_proj2_overview.png" alt="Overall System Process Flow" style="width: 100%; padding: 10px;">
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">Fig. Architecture Overview</td>
  </tr>
</table>

The overall architecture for the application is as depicted in the figure above. The key features of the development include:
- **Camera Intrinsic Calibration:** OpenCV
- **Object Detection:** Fine-tuned YOLOv8m
- **Object Segmentation:** Fine-tuned YOLOv8s-seg

Github Repo: [Link](https://github.com/tanjm93/mtech-object-detecton-system)

## Key Results 
<img src="/images/mtech_proj2_keyresults1.png" alt="Key Result" style="border: 1px solid black;" />

<img src="/images/mtech_proj2_keyresults2.png" alt="Key Result" style="border: 1px solid black;" />

<img src="/images/mtech_proj2_keyresults3.png" alt="Key Result" style="border: 1px solid black;" />

<img src="/images/mtech_proj2_keyresults4.png" alt="Key Result" style="border: 1px solid black;" />

<img src="/images/mtech_proj2_keyresults5.png" alt="Key Result" style="border: 1px solid black;" />

<img src="/images/mtech_proj2_keyresults6.png" alt="Key Result" style="border: 1px solid black;" />