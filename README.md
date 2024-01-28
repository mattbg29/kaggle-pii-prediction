# kaggle-pii-prediction
pii-prediction code without use of training data

kaggle competition:  https://www.kaggle.com/competitions/pii-detection-removal-from-educational-data

Welcome to my notebook. This is my first attempt at a Kaggle competition. In order to get a better sense of the data, I took a decidedly basic approach for this first attempt at this competition, where I used the training data just for my own edification, studying familiar patterns. This employs little to no contextural analysis, and instead simply evaluates each word/set of words and attempts to spot names or familiar patterns. I decided to ignore usernames and addresses as there simply was not enough training data to help me pick up on specific patterns there.

From here, I plan to examine some of the great work others have put together and hopefully, combined with my now intiminate knowledge of the training data, I will be able to add some real value on the predictions side of things.

I nevertheless feel this can be helpful for certain users, as it demonstrates a simple approach to this problem in a very digestable manner. This performance (0.66) also establishes a useful baseline, as this is achieved without using the training data (notice the training data is never referenced throughout the code), leveraging instead only patterns I spot within the data.

Feedback welcome!

