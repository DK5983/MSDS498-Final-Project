# MSDS498-Final-Project
Individual MSDS 498 Capstone Project

## Project 3 Summary

Project 3 calls for a walkthrough of chapter 16  in *Python for Programmers*, written by Paul and Harvey Deitel.  The project calls for a Hadoop MapReduce that executes a word-length summation for Shakespeare's play *Romeo and Juliet* enscribed as a .txt file.  The same task is then executed using Apache Spark.  The chapter walkthrough performs these tasks using MS Azure's HDInsight, and rather than recreate code, all files on this repository are borrowed from the text's online source code here: **https://learning.oreilly.com/library/view/python-for-programmers/9780135231364/ch16.xhtml**. For the sake of brevity, I won't elaborate on how to complete these tasks with MS Azure, but instead point to the text for step-by-step instructions.


## Replicating Word Count Tasks with GCP

Once these tasks are complete, the project then requires the same Hadoop and Spark jobs to be completed on another cloud platform.  I chose to complete these tasks on Google Cloud Platform (GCP).

## Hadoop wordcount job on GCP Dataproc Cluster

Step by step instructions found here: https://cloud.google.com/composer/docs/tutorials/hadoop-wordcount-job

Note: You'll have to establish an account and input billing information, though Google will provide you with enough start-up credits to work through both the Hadoop and Spark examples for the project.  Just ensure you delete your clusters when you're done.





