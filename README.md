# Lazada Product Title Quality Challenge
-- This was made as a Information Retrieval course project. 

# Problem Description: 
Lazada provided the competition’s goal, which was to identify whether the titles of its products were clear and concise amidst an increasing number of e-commerce site transactions. The specific goal of the challenge was to score the clarity and conciseness of each product title (two scores in the [0,1] interval).
One can note that these two indicators are not the same. Clarity refers to whether the content of a title is easy to understand, and whether the description is comprehensive and accurate.

An example of an unclear sentence is: “Silver Crystal Diamante Effect Evening Clutch Wedding Purse Party Prom Bag Box.” This doesn’t clarify whether the product is a “Wedding Purse” or “Party Prom Bag Box.”

While an example of a clear sentence is: “Soft-Touch Plastic Hard Case for MacBook Air 11.6 Case (Models:A1370 and A1465) with Transparent Keyboard Cover (Transparent)(Export)”
In contrast, conciseness refers to whether the content of a title is terse.

An example of a short but unconcise sentence is: “rondaful pure color window screening wedding banquet glass yarn,” because the synonyms are redundant, and it is also unclear. An example of a concise sentence is “moonmini case for iPhone 5 5s (hot pink + blue) creative melting ice cream skin hard case protective back case cover”.
To explore and solve this problem, Lazada provided a series of raw data from real scenarios, including the title, three-level category tree, description, price, and ID of the product. Lazada also provided some manually labeled information.

We were provided with standard datasets for evaluation. There were three datasets: the first was training data for training, the second was validation data for initial testing, and the third was test data for final testing.
