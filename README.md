# ApexPlanet-Task-1
Data dictionary 
### 🗂️️ Data Dictionary (ApexPlanet Sales Dataset)

| 🏷️ Column Name | ⚙️ Data Type | 📖 Meaning (Iska matlab kya hai?) | 💼 Business Relevance (Business mein kya kaam aayega?) |
| :--- | :--- | :--- | :--- |
| **Order_ID** | `Text / String` | Har ek order ka ek unique pehchan number. | Total orders ko ginne aur kisi specific order ko track karne ke liye. |
| **Order_Date** | `Date / Time` | Woh tareekh jab customer ne order place kiya. | Har mahine ya saal ki sales ka trend (badhotari/giravat) check karne ke liye. |
| **Customer_ID** | `Text / String` | Har customer ko diya gaya ek unique number. | Puraane aur naye customers ko pehchanne aur unki loyalty track karne ke liye. |
| **Customer_Name** | `Text / String` | Customer ka poora naam. | Customers ko unke naam se emails ya offers bhej kar marketing karne ke liye. |
| **Age** | `Numeric (Float)` | Customer ki umar (saalo mein). | Yeh samajhne ke liye ki kis umar ke log sabse zyada saaman kharid rahe hain (Demographics). |
| **Gender** | `Text / String` | Customer ka ling (Male ya Female). | Gender ke hisaab se product ki demand samajhne ke liye. |
| **City** | `Text / String` | Customer kis shahar se hai (jaise Bengaluru, Kolkata). | Yeh dekhne ke liye ki kis shahar mein sabse zyada sales ho rahi hai. |
| **Product** | `Text / String` | Jo saaman kharida gaya (jaise Mobile, Book, Rice). | Sabse zyada bikne wale (top-selling) products ko identify karne ke liye. |
| **Category** | `Text / String` | Product ki shreni (jaise Electronics, Grocery). | Kis category mein sabse zyada fayda (profit) hai, yeh analyze karne ke liye. |
| **Quantity** | `Numeric (Int)` | Customer ne kitne items/piece kharide. | Inventory (stock) manage karne aur product ki demand samajhne ke liye. |
| **Unit_Price** | `Numeric (Float)` | Kisi ek item (product) ki keemat. | Product ki pricing strategy set karne ke liye. |
| **Total_Sales** | `Numeric (Float)` | Kul bill ya amount (Quantity × Unit_Price). | Company ki total kamai (revenue/sales) calculate karne ke liye. |
