Tips:
1. Take the API keys: https://azure.microsoft.com/en-us/try/cognitive-services/?api=bing-image-search-api
2. Copy the first key for "API_KEY" variable in code.
3. Install requests package: sudo pip install requests
4. Create a folder to store the images. (ex. dataset)
5. Run the code with python3: python3 scrape.py --query "iphone" --output dataset/
6. All the images related to your given query will be stored in "dataset" folder.

Notes:
1. Images will be of varying sizes.
2. Images may have multiple objects of same category.
3. Cannot use these images directly for training a network.
