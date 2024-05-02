# Economic News Classification Project

This repository hosts all materials that are used in the "Evaluating the Prevalence of Certain Economic Indicators in Media" project for the Text as Data course assignment.

Using a fine-tuned RoBERTA to classify thousands of articles pertaining to the economy from 2016 to 2014, this research study analyzes partisan differences between which topics media sources tend to focus on. Specifically looking at if sources who have been deemed as left leaningtend to discuss metrics like GDP and employment, etc more than their right-leaning counterparts or vice versa. Additionally, I evaluated differences between which topics government sources and typical media sources prioritize- possibly alluding to differing narrative agendas between these different sources when it comes to discussion on the economy.

## Structure of scripts
- data_collection_gold_standard.ipynb: collects urls and lableled article content for articles pertaining to main economic metrics of interest
- data_collection.ipynb: collects urls and unlabeled article content for articles pertaining to the broader economy
- classifyinge_econ_news.ipynb: script for fine-tuning RoBERTA model using articles collected in data_collection_gold_standard.ipynb
- fine_project.Rmd: script for building final project paper and visualizations
- fine_tuning.ipynb: script for quickly classifying new articles using saved pretrained model
