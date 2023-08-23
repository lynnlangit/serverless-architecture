# GCP Serverless Applications

Serverless GCP architectures include interactive or batch data processing.  Also it's common to include machine learning evaluation and processing. Data Lake architectures are generally used when data volumes are genomic-sized.  Below are examples and also links to more information about GCP libraries that are commonly used in this type of solution.  

Of course you can build a serverless website using any number of patterns.  I shown the three most common ones in the diagram below:

<img src="https://github.com/lynnlangit/serverless-architecture/blob/main/images/gcp-serverless-web.png" width=800>

## General GCP Serverless Architectures

- See section for **Cloud Functions** --> https://cloud.google.com/architecture/serverless-functions-blueprint
- See section for **Cloud Run** --> https://cloud.google.com/architecture/serverless-functions-blueprint

## Scale Out Architecture Example for Bioinformatics

<img src="https://github.com/lynnlangit/gcp-for-bioinformatics/blob/master/images/gcp-funtctions-tools-test.png" widt=600>

This example is for genomics (bioinformatics tool / library testing) with the ability scale out if needed for size of input data.  More information [here](https://github.com/lynnlangit/gcp-for-bioinformatics/blob/master/5_Serverless_Compute_with_Functions/4_Serverless_Workflows.md)

## Multiple Processing Types Architecture Example for Bioinformatics

This example is for genomics (bioinformatics data) with multiple pipeline types and is shown below.  

- 📘 "Build a Data Lake on GCP" -- [link](https://cloud.google.com/solutions/build-a-data-lake-on-gcp)
- 📘 "Serverless Analytics and Machine Learning with Google Cloud" -- [link](https://www.leptonsoftware.com/2018/01/16/serverless-analytics-machine-learning-with-google-cloud)
- 🔨 About Knative -- [link](https://cloud.google.com/knative/) 
- 🔨 KServe for serverless ML model serving -- [link](https://github.com/kserve/kserve)

<img src="https://github.com/lynnlangit/gcp-for-bioinformatics/blob/master/images/batch-pipelines.png" width=1000>
