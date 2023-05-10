# Pinguin Classifier

Pinguin Classifier is a Streamlit app that allows users to classify penguins based on their features. The app uses a decision tree model to predict the species of a penguin based on its culmen length, culmen depth, flipper length, and body mass.

## Usage

To use Pinguin Classifier, follow these steps:

1. Install the required packages by running `pip install -r requirements.txt` in the terminal.
2. Run the app by executing `streamlit run penguins_app.py` in the terminal.
3. Use the sliders to adjust the culmen length, culmen depth, flipper length, and body mass of the penguin you wish to classify.
4. The app will generate a prediction of the species of the penguin, along with the probability of the prediction.

## How it works

Pinguin Classifier uses [Streamlit](https://streamlit.io/), an open-source Python library that allows users to create interactive web applications using only Python code. The app uses a decision tree model to classify the penguin species based on their features.

The app uses the [Palmer Penguins](https://github.com/allisonhorst/palmerpenguins) dataset, which includes measurements of three penguin species: Adelie, Gentoo, and Chinstrap. The app loads the dataset into a Pandas DataFrame and trains the decision tree model using scikit-learn.

When the user adjusts the sliders to change the features of the penguin, the app uses the trained decision tree model to generate a prediction of the penguin's species. The prediction is displayed in the app, along with the probability of the prediction.

## Contributing

If you would like to contribute to Pinguin Classifier, please submit a pull request. We welcome contributions from developers of all skill levels.

## Credits

Pinguin Classifier was created by Joseph Szklar. The app uses the following libraries:

- [Streamlit](https://streamlit.io/)
- [scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
