# Getting Data Class Project

## Transform and Summarize Smart Phone Accelerometer Data

### Input files:

* Train and test data subjects (2 data.frames)
* Subject activity descriptions file (1 data.fram)
* Train and test activities (2 data.frames)
* Train and test data observations (2 data.frames)

### Transformations performed:

* Merged activity descriptions into the (2) activities DFs by adding a character column via Mutate
* Merged the (2) subject DFs with the (2) activities DFs and the (2) observations DFs columns 1:6
* The two resulting data.frames were then merged into a single data.frame.
* A final data.frame was created by averaging all extracted observations, grouping by Subject and Activity

### Output files:

* wearables.txt