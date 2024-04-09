# Email Spam Detection using Mutlinomial Naive Bayes with accuracy of 98.8%
- 1 is for Yes
- 0 is for No
- using Count Vectorizer we can convert string to document-term matrix.
```
clf = Pipeline([
    ('vec',CountVectorizer()),
    ('nb',MultinomialNB())
])
```
![Screenshot 2024-04-09 175100](https://github.com/omchaudhari1107/Email-Spam-Detection/assets/90174038/193a2cdb-5d45-4b3d-b8d1-e0368fbce516)
