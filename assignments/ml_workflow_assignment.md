# Machine Learning Workflow Assignment

## Task 1: Label & Data Leakage
- **Label:** `repeat_purchase_flag`
  - *Justification:* Ye hamara target variable hai kyunki model ko yahi predict karna hai ki customer purchase karega ya nahi.
- **Data Leakage:** `discount_used_on_repeat_order`
  - *Justification:* Ye column model ko "future" ki information de raha hai; agar discount use hua hai iska matlab purchase pehle hi ho chuki hai, jo training ke waqt galat hai.

## Task 2: Important ML Steps
1. **Exploratory Data Analysis (EDA):** Model banane se pehle data ko samajhna zaroori hai (jaise missing values ya outliers check karna) taaki model bias na ho.
2. **Data Splitting (Train-Test Split):** Data ko do hisso mein baantna zaroori hai taaki hum check kar sakein ki model anjaan data (unseen data) par kaisa perform kar raha hai.
