# industrial_objects_dataset

> Essential tools and components for manual assemblies.

## Description ##

This dataset is a compilation of images that contain tools such as drills, hammers, pliers, scredrivers, wrenches; and complements as bolts, clamps, nuts, gears, screws, washers ; and accesories such as drill bits and sockets. The project was developed by taking pictures of each one of the elements listed and also downloading images from the internet, then the Data Augmentation for Object Detection(YOLO) (link below) was used to increase the data volume to complete the dataset.

https://github.com/srp-31/Data-Augmentation-for-Object-Detection-YOLO-

This dataset also contains videos of an operator performing the manual assembly process of a skateboard, along with the corresponding separation in frames for each one of the videos.

## Properties ##

Format: .jpg

Total number of images: 27150.

Number of images per class:
- Bolt: 1450.
- Clamp: 1100.
- Drill bit: 1600.
- Drill gun: 700.
- Drill screw: 1200.
- Gears: 1800.
- Hammer ball pein: 1150.
- Hammer claw: 1000.
- Nut: 1700.
- Nut driver: 1750.
- Diagonal pliers: 1250.
- Lineman pliers: 1000.
- Locking pliers: 950.
- Long nose pliers: 1050.
- Ratchet: 950.
- Screw: 1500.
- Electric screwdriver: 800.
- Phillips screwdriver: 1400.
- Slotted screwdriver: 1300.
- Socket: 1000.
- Washer: 1300.
- Adjustable wrench: 1350.
- Allen wrench: 1300.
- Combination wrench: 950.

Number of frames per video and tools involved (All video frames are in 640x360 px resolution):
- Seq001: 6042. Wrench, screwdriver.
- Seq002: 2752. Pliers, wrench.
- Seq003: 3108. Screwdriver, wrench.
- Seq004: 8808. Hammer, wrench.
- Seq005: 6884. Wrench, screwdriver.
- Seq006: 5640. Ratchet.
- Seq007: 4917. Wrench, screwdriver.
- Seq008: 3816. Screwdriver, pliers.
- Seq009: 0653. Pliers.
- Seq010: 2145. Pliers.
- Seq011: 1351. Pliers.
- Seq012: 0967. Pliers.
- Seq013: 1908. Hammer.
- Seq014: 0814. Drill.
- Seq015: 1339. Drill.

## Repository structure ##

The folder named AUN NO SE HA SUBIDO contains the specific folder for each one of the tools, accesories and complements.

The folder named [Real_videosframe_dataset](https://github.com/mazamorahdez/Industry-Dataset-for-MDL/tree/main/Real_videosframe_dataset) contains the folder for each video that is separated in frames.
