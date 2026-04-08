# Data Identification and Understanding

The proposed system utilizes both structured and unstructured data to perform efficient product identification and price comparison. The primary source of data is obtained through web scraping from major e-commerce platforms such as Amazon and Flipkart. The extracted data includes product attributes such as product name, price, ratings, availability, and product links. This data is dynamic in nature, as it changes frequently based on market conditions and offers.

In addition to real-time scraped data, the system also makes use of a labeled image dataset for implementing the image-based search functionality. The dataset consists of footwear categories such as sneakers, sandals, and formal shoes. Each image is associated with a corresponding label stored in a structured format such as a CSV file. This labeled dataset is used to train or adapt the machine learning model (MobileNet) for recognizing product categories from user-uploaded images.

The system processes two types of user inputs: text-based input and image-based input. For text input, the system directly uses the keyword for scraping product data. For image input, the image is first preprocessed using OpenCV and then passed to the MobileNet model, which predicts the product category. Based on this prediction, a relevant keyword is generated, which is further used for scraping.

Understanding the nature of data is crucial for the system’s performance. The scraped data may contain noise, duplicate entries, or inconsistent formats, which are handled through preprocessing techniques such as data cleaning, normalization, and filtering using Pandas. Similarly, image data requires preprocessing such as resizing and normalization to ensure compatibility with the machine learning model.

By combining real-time scraped data with a structured image dataset, the system achieves both accurate product identification and effective price comparison. This hybrid data approach enhances the overall efficiency and usability of the system.
