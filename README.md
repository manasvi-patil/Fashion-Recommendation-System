# fashion-recommender-system
A Deep Learning based Fashion Recommender System using the ResNET50
In this project, the user is requested to upload one image of any clothing item and based on that the model will recommend five similar looking images from the dataset
<br /><br />

How to run:
1. Download the dataset from kaggle
link- https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small
2. For this project I had created a virtual environment and separately downloaded the required packages (you can download the packages on IDE of your choice too).
4. Add the dataset to your app.py.
3. Run the app.py file to extract the features from the given dataset. You will get two files after extracting- embeddings.pkl and filenames.pkl
4. Run the test.py using this two pickle files to test the model.
5. Run main.py file to display the final output (For front-end I've used streamlit to display the output). <br /><br />


-->Sample file is having the sample images I had used to train my model <br />
-->Uploads file will store the image you had selected for suggestion<br /><br />


Note:
For running the files via terminal/cmd use the command "streamlit run main.py" to run the main.py file
