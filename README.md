# big-data-challenge

### Analyze two product review datasets and predict for postive vs negative ratings

##### Authors:
* John Torgerson (JohnTorgerson)
---

##### Tools & Supplies:
* data from Amazon 
* https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Watches_v1_00.tsv.gz
* https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Outdoors_v1_00.tsv.gz

* PySpark, AmazonS3, GoogleColab
---

### Guide to Repo Contents:

* In folder, `Resources` are the following 6 tables:
    1. `yelp_reviews.csv` is a datafile containing reviews from yelp
* `Outdoor_Reviews.ipynb` is a notebook file intended to be run in google colab for analyzing outdoor product reviews
* `Watch_Reviews.ipynb` is a notebook file intended to be run in google colab for analyzing watch reviews
* `working_sample.ipynb` is a notebook file intended to be run in google colab which actually works where the previous 2 do not
* `ReadME.md` is the table of contents of the repo you're currently viewing
---

### Observations:
* pyspark is powerful, though not as agile as pandas, it can do quite a bit of what pandas can do, only it can do it on much larger datasets
* after running this same code on a different dataset, I cannot figure out why it is crashing on a .fit function
* for refrence I am including another sample project containing the working code and its dataset
* I ran into an error and after editing and proofreading several times I adjusted the dataframe format to match a smaller set 
* The smaller set was from an in class example which started its pipeline with 3 columns
* I made the 3 columns for *watch* and *outdoors* match that of the smaller set, and it still did not work
* I do not know why, but it should
* I'd appreciate feedback about the error if you have an opinion so i can correct it later.
---

### Credits and Special Thanks

* amazon and vine for providing public files containing review data and comments on consumer products