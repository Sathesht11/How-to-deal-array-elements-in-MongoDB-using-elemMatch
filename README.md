# How-to-deal-array-elements-in-MongoDB-using-elemMatch
When dealing with MongoDB arrays, we must show attention to how we construct queries.

We frequently make mistakes in our queries and retrieve documents that we are not looking for.

When we have two or more conditions, we receive documents in which one element of the array matches one condition and another document solely matches the other condition.

Obviously, we want one element of the array to satisfy both conditions at the same time.

The attached ipynb code file will explain how to choose only those documents in our dataset that contain fields within arrays that meet our criteria and project only the array's fields that we require.

# Data
The sample data from MongoDB was used. The database'sample_supplies' collection 'sales' has been used.
