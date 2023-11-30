## **Σχετικά με το σύνολο δεδομένων**

Τα δεδομένα μεταφορτώθηκαν από το ***kaggle*** 

[https://www.kaggle.com/datasets/shilongzhuang/pizza-sales]: https://www.kaggle.com/datasets/shilongzhuang/pizza-sales	"δασ"



 και αφορούν τις πωλήσεις προϊόντων σε μια πιτσαρία.



**Περιεχόμενα**

Το σύνολο δεδομένων αποτελείται από 12 μεταβλητές:

- `order_id`: αριθμός (κωδικός) παραγγελίας 
- `order_details_id`: αριθμός (κωδικός) προϊόντος στην κάθε παραγγελία
- `pizza_id`: κωδικός προϊόντος
- `quantity`: ποσότητα κάθε προϊόντος στην παραγγελία
- `order_date`: Ημέρα παραγγελίας
- `order_time`: Ώρα παραγγελίας
- `unit_price`: Τιμή του προϊόντος σε USD
- `total_price`: Συνολική τιμή (`unit_price` * `quantity`)
- `pizza_size`: Μέγεθος προϊόντος (Small, Medium, Large, X-Large ή XX-Large)
- `pizza_type`: Κατηγορία στην οποία ανήκει το προϊόν (Classic, Supreme, Chicken ή Veggie)
- `pizza_ingredients`: Απαιτούμενα υλικά για την παρασκευή του προϊόντος
- `pizza_name`: Όνομα προϊόντος



**🍕** **The Pizza Challenge**

For the Maven Pizza Challenge, you’ll be playing the role of a BI Consultant hired by Plato's Pizza, a Greek-inspired pizza place in New Jersey. You've been hired to help the restaurant use data to improve operations, and just received the following note:

Welcome aboard, we're glad you're here to help!

Things are going OK here at Plato's, but there's room for improvement. We've been collecting transactional data for the past year, but really haven't been able to put it to good use. Hoping you can analyze the data and put together a report to help us find opportunities to drive more sales and work more efficiently.

Here are some questions that we'd like to be able to answer:

\1.   What days and times do we tend to be busiest?

\2.   How many pizzas are we making during peak periods?

\3.   What are our best and worst-selling pizzas?

\4.   What's our average order value?

\5.   How well are we utilizing our seating capacity? (we have 15 tables and 60 seats)

That's all I can think of for now, but if you have any other ideas I'd love to hear them – you're the expert!

Thanks in advance,

Mario Maven (Manager, Plato's Pizza)



**Colllection Methodology**

The public dataset is completely available on the Maven Analytics website platform where it stores and consolidates all available datasets for analysis in the Data Playground. The specific individual datasets at hand can be obtained at this link below: https://www.mavenanalytics.io/blog/maven-pizza-challenge

📌I set up the data model to include all the related instances in one single table so obtaining data for analysis is made easier. 

**My Inspiration**

Complete details were also provided about the challenge in the link if you are interested. The purpose of uploading here is to conduct exploratory data analysis about the dataset beforehand with the use of Pandas and data visualization libraries in order to have a comprehensive review of the data and translate my findings and insights in the form of a single page visualization.

 