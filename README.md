# GCPTest
GCP Test Repo

// Running Dataflow

--project=the-dominion-290000
--inputFile=gs://apache-beam-samples/shakespeare/*
--output=gs://wordcount_20201012/output/
--gcpTempLocation=gs://wordcount_20201012/tmp
--zone=us-east1
--runner=DirectRunner
