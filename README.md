# yolo-auto-finetuning-pipeline
This repository contains the source code for an MLOps pipeline that takes image data that has been annotated with unknown classes, run it through the existing trained inference model once, then combines the new annotations with the inferenced annotations, before using that fully-annotated data to fine tune the existing model. 
