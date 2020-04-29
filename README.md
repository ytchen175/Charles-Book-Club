# Charles-Book-Club
Build a xgboost model to predict whether a person will purchase a book about "The Art History of Florence" based on past purchases or not.

feature_importance
![image](https://github.com/ytchen175/image/blob/master/importance.png?raw=true)

plot_tree
![image](https://github.com/ytchen175/image/blob/master/tree.png?raw=true)

shap_value
![image](https://github.com/ytchen175/image/blob/master/shap.jpg?raw=true)


Description of Variables:


Seq#: Sequence number

Gender: O=Male 1=Female

M: Monetary- Total money spent on books

R: Recency- Months since last purchase

F: Frequency - Total number of purchases

FirstPurch: Months since first purchase

ChildBks: Number of purchases from the category: Child books

YouthBks: Number of purchases from the category: Youth books

CookBks: Number of purchases from the category: Cookbooks

DoItYBks: Number of purchases from the category: Do It Yourself books

RefBks: Number of purchases from the category: Reference books (Atlases, Encyclopedias, Dictionaries)

ArtBks: Number of purchases from the category: Art books

GeoBks: Number of purchases from the category: Geography books

ItalCook: Number of purchases of book title: "Secrets of Italian Cooking"

ItalAtlas: Number of purchases of book title: "Historical Atlas of Italy"

ItalArt: Number of purchases of book title: "Italian Art"

Related purchase: Number of related books purchased 



Florence: =1 if 'The Art History of Florence" was bought, = 0 if not
