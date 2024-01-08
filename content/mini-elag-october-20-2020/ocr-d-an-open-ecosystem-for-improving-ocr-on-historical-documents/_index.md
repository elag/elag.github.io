---
title: 'OCR-D: An open ecosystem for improving OCR on historical documents'
date: 2020-10-24
layout: single
---

{{< youtube OkUyO5mcV9U >}}

Clemens Neudecker, Berlin State Library 

OCR for historical documents remains a tricky challenge. The German OCR-D project and community have in recent years created a fully open source framework and ecosystem for historical document OCR (https://ocr-d.de). Now the solutions developed will have to demonstrate their effectiveness in real-world implementation scenarios. In this lightning talk we want to introduce the OCR-D stack and its features and discuss the open and participative development strategy of OCR-D in order to encourage others to experiment with OCR-D, engage with its community and contribute their own experiences and findings. 

**Extra questions** 

These questions were asked during the session chat but not answered during the session. 

_Q: How far have you tested the OCR-D tools in other languages? (by Sally Chambers)_ 

A: So far, the OCR-D tools were mainly tested on documents in (historical) German language. However, in principle, the OCR-D tools are language agnostic and should work equally well for other languages. This is clearly the case for all tools that operate purely on an image level (image optimization, binarization, segmentation asf.) but even the current OCR models (e.g. for Calamari) are independent of the language. Only the OCR post-correction tools, which employ language models, would first have to be re-trained when applied to another language, but can otherwise also be reused. We would be happy to hear from users interested to try out OCR-D for languages other than German and will be happy to assist and support this via our regular communication channels.