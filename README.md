##search-by-prediction

This project serves to imitate search engine behavior by using recommender system to, hopefully, improve performance on large data by 
avoiding complex querying from DB. Dataset is picked from pixiv.com, which contains large amount of anime pictures (so less color complexity 
comparing to real image). Two methods are implemented, including search by image tag and search similar art by color feature.

## Files

Presentation Paper:
Designing_Recommendation_System_for_Search_Porpuse.pdf

search similar art by color feature:
predict_by_color.ipynb
predict_by_color_2.ipynb

search by image tag:
predict_by_tag.ipynb


## Weighted-One-Hot-Encoding

A special method of one-hot-encoding is implemented in search by image tag. Due to large amount of tags and combinational tags, weights are
 added in additional to traditional one-hot-encoding to improve tag precision. See presentation paper for detail. 
