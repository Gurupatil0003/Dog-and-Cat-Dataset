```python
import os
import urllib
import zipfile

# Download and unzip the dataset
if not os.path.isfile('.zip'):
  urllib.request.urlretrieve("https://github.com/Gurupatil0003/Dog-and-Cat-Dataset/archive/refs/heads/main.zip", "Cat Dog Data Set.zip")

zip_filename = "Cat_Dog_Dataset.zip"
with zipfile.ZipFile("Cat Dog Data Set.zip","r") as zip_ref:
    zip_ref.extractall(".")
```    
    

    
