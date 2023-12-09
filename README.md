# 🐀👨‍🍳 Anyone Can Cook: Multilingual, Cross-Cultural Bias in Wikipedia

## ✍️ Abstract
This study presents an analysis of the biases inherent in the training datasets of Large Language Models (LLMs), with a specific focus on food items in Wikipedia's multilingual corpus. The study explores how these biases emerge from the datasets used in pre-training, particularly in the context of culturally significant topics. Using the example of food items—a subject deeply intertwined with cultural identity—the research examines Wikipedia's representation of this topic across English, Russian and Arabic languages. The methodology encompasses an examination of the cultural significance of a language's Wikipedia, scrutinizing potential western biases, assessing culturally unique elements in terms of both their quantity and quality, and conducting a thorough comparative analysis of the quality of articles in various languages on identical topics. Evidence is observed of numerous biases, manifesting both in the quantity of articles as well as in their quality. The findings of this study are vital for understanding the challenges in developing LLMs that are culturally inclusive and unbiased. By identifying several different forms of bias in Wikipedia's multilignual corpus, the study suggests that these biases easily propagate into LLM outputs, which can cause non-alignment for various groups of users.

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
