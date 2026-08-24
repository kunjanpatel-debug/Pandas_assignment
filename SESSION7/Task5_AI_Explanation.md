# Session 7 - Task 5: AI Learning Summary

## Topic: Calculating GST in Pandas

### What I Learned:
1. **Vectorized Operations vs Row Computation:** In Pandas, calculating column-wise math like `df['Price'] * df['Qty'] * 0.05` is done directly without needing manual `for` loops, making the code clean and fast.
2. **Dynamic Column Creation:** Simply assigning the formula to a new column name (`df['GST'] = ...`) creates the column automatically and matches every row seamlessly.
