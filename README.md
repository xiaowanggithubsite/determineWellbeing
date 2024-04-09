
# Determining well-being during a crisis based on Twitter data

## Introduction

In this repository, we present our implementation code and methodologies employed in determining well-being during a crisis based on Twitter data. The objective of this paper is to determine how subjective well-being (SWB) can be predicted based on Twitter (or X) data during a crisis. Generally speaking, we evaluate five different textual representation techniques over five machine learning algorithms (i.e., elastic net regression, support vector machines, random forest, artificial neural networks, and XGBoost).

The short descriptions of the contents in this  repository are as following: 

## Table of Contents:

0. ***data***  
   - **Test_results**    
    The folder for all reuslts.
   
   - **ModelData.csv**  
    The data for building models.

   - **Textual representation files**
     - 1024elmo.csv  
     - berttwitter.csv
     - glove200.csv
     - openai.csv
     - tfidf.csv
  
   - **SA.csv**  
     Sentiment analysis. 
      
   
1. ***1_Processing.ipynb***  
   Data processing for all obeservations. 

2. ***2_SA_VS_PANAS.ipynb***  
   Sentiment analysis code (VADER and TextBlob)

3. ***3_Embedding.ipynb***  
   Code for all textual representation techniques.

4. ***4_XXX_model.ipynb***  
   Build models for total SWB, PA, and NA.

5. ***6_combined_F_test.ipynb***  
   Code for compare performance by combined F test.

6. ***7_Compare_feature_rank_difference.ipynb***    
   Code for feature importance anlysis.