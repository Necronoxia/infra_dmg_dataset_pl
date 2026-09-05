# infra_dmg_dataset_pl
Encroachment and Infrastructure Damage dataset and pipeline architecture. NIT Calicut Mtech AIDA M26-group C Data Analytics project. 

## Libraries:
 - OpenCV ()
 - Pandas ()
 - Scikitlearn ()
 - Numpy ()
 - Boto3 ()

## Step 1 Data Collection:
 Day time pictures of local buildings and structures for infrastructure damage and encrouchment with geotags/gps LatLong coordinates.
## Step 2 Storage:
 On AWS S3 free tier (5Gb) data store, preferably in RAW->Preprocessed->Analytics layers (Follow Medallion Architecture for layering).
## Step 3 Setup: 
 Setup python environments and libraries.
## Step 4 Fetch raw:
 Boto3 call for pulling Raw data into the pipeline for processing.
## Step 5 Data Processing:
 Using openCV for image data transformations and separately annotation tools.

## Pending to discuss and finalize:
    1. Annotation tools.
    2. How to store geotag/gps metadata. Metadata file uniquely tagged with filename?
    3. How to store labels?

## References:
    Null
