# Pet Insurance Cost Prediction

## Problem Statement

Currently, the premium pricing process involves a combination of manual underwriting and rule-based methods, which may not fully account for the diverse factors influencing the cost of pet insurance.

This process can lead to inaccurate pricing, resulting in either overpriced premiums that deter potential customers or underpriced policies that increase risk for the insurer.

## Business Case

By developing a machine learning algorithm to predict pet health insurance premiums, companies can leverage historical data to produce more accurate, dynamic, and fair pricing models.

Key Benefits

- Improved pricing accuracy
- Increased customer retention and acquisition
- Operational efficiency
- Scalability

## Project Objective

Develop a machine learning algorithm capable of predicting pet insurance premiums with at least 80% R-squared accuracy, providing fair pricing for customers while optimizing profitability for the business.

## Files

- [Pet Insurance Cost Prediction Notebook](https://colab.research.google.com/drive/1aqbLnUOHnnplVufDrzNPLQGRhr9UwZ5l?usp=sharing) in Google Colab
- [Pet Insurance Cost Predictor App](https://huggingface.co/spaces/bmccourt01/hugsallaround)
- [Project Presentation](https://docs.google.com/presentation/d/1Zf_LM_-rPKBLHBtBNv6AOJinaiS3vrZaKdF9hfGEqG8/edit?usp=sharing)
- [Project Proposal](https://docs.google.com/document/d/1DDW4cQqUVR0G96wklIStyyBn9HxScrRLyK1S8KAkPbw/edit?usp=sharing)
- [UK Pet Insurance Quotes Data](https://console.cloud.google.com/storage/browser/pet-insurance-data;tab=objects?forceOnBucketsSortingFiltering=true&project=pet-insurance-prediction)
- [Source Data](https://app.snowflake.com/marketplace/listing/GZTSZ2DR6BH/market-data-insightica-free-sample-uk-pet-insurance-quotes-data)

## How to interact with the files

1. The [Pet Insurance Cost Prediction Notebook](https://colab.research.google.com/drive/1aqbLnUOHnnplVufDrzNPLQGRhr9UwZ5l?usp=sharing) resides and can be run directly in **Google Colab**.
2. The [UK Pet Insurance Quotes Data](https://console.cloud.google.com/storage/browser/pet-insurance-data;tab=objects?forceOnBucketsSortingFiltering=true&project=pet-insurance-prediction) is stored in **G**oogle Cloud Storage** due to it's large size.
3. The [Pet Insurance Cost Predictor App](https://huggingface.co/spaces/bmccourt01/hugsallaround) is deployed to **Hugging Face** and is available to anyone to use simply by clicking on the link.

## Warnings

Running the following code blocks in section 5.0 Build and Test the Model of the notebook will result in either timing out or executing for a long time.  

1. Support Vector Regression (SVR) / Train the Model | Original
2. Support Vector Regression (SVR) / Train + Optimize the Model | Hyperparameter Tuning (Grid Search)
3. Random Forest

## Requirements

The following libraries are required to run the notebook.  These code snippets have already been included in the notebook for the user to run.

1. ``!pip install seaborn``
2. ``!pip install category_encoders``
3. ``!pip install gradio``
