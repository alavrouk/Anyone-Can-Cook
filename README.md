# 🐀👨‍🍳 Anyone Can Cook: Serving Up Insights on Bias in Pre-Training Data.

This repo houses the dataset used in my paper. Each item's use and contents is listed below.

## 📊 en_ru_ar_article_stats.xlsx
This file contians every statistic for every article. More details can be found in **Section 3** of the paper.
| Column Name | Description |
| ----------- | ----------- |
| article                      | The link to the article for which we are getting the stats.       |
| language                     | The language the article is in (EN/RU/AR).                        |
| country_of_origin            | The 2 letter codes for countries of origin (ISO Alpha-2).         |
| country_of_origin_simplified | AR/RU/WEST/OTHER (to make analysis easier).                       |
| num_words                    | The number of words in the article.                               |
| num_links                    | The number of links in the article.                               |
| num_sections                 | The number of sections in the article.                            |
| num_unique                   | The number of unique words in the article.                        |
| avg_sentence_length          | The average sentence length of the article.                       |
| num_edits                    | The number of edits the article has received.                     |

## 📈 en_ru_ar_food_data.xlsx
| Column Name | Description |
| ----------- | ----------- |
| fid                      | The id of the Wikidata object for the given food.                    |
| food                     | The name of the food in English (if applicable).                     |
| food_ru                  | The name of the food in Russian (if applicable).                     |
| food_ar                  | The name of the food in Arabic (if applicable).                      |
| article_en               | The link to the Wikipedia article in English (if applicable).        |
| article_ru               | The link to the Wikipedia article in Russian (if applicable).        |
| article_ar               | The link to the Wikipedia article in Arabic (if applicable).         |
| countryofOriginList_en   | The 2 letter codes for countries of origin (ISO Alpha-2).            |

## 🌍 countries.csv
The two letter ISO Alpha-2 country codes converted to the full country name, as well as the longitude and latitude in case you need that.
