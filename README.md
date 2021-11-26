## rawdata

The **rawdata folder** contains image files transfered from the **crb folder** in the smartphone. I transferred these by removing the microSD card from the phone. Might be able to do this without removing the card (USB connection to phone) but it is likely to be much slower.

## extracting GPS coordinates

Used **code/extract_gps_data.ipynb** to do this.

```bash
papermill extract_gps_data.ipynb \
'../output/extract_gps_data_output.ipynb' \
-p IMAGE_FILE_PATH '../rawdata/*.jpg' \
-p CSV_OUTPUT_FILE '../rawdata/gps-data.csv'
```
Completed in only 1 minute 18 seconds

## Damage detection

Could not perform this step om n my main computer. Moved everything over to side computer

Ran **detect_crb_damage.ipynb**. Took 1d 10h to complete.

## Create DB

Ran **create_db.ipynb**. Took 8m 27s.

## Make Map
# Guam05
