# Iris Dataset Explorer

This is a simple Streamlit application that allows users to explore the Iris dataset interactively.

## Features

- Displays the full Iris dataset.
- Allows filtering the dataset based on a selected feature and range.
- Provides basic statistics for the filtered data.

## Project Structure

```
├── app.py          # Main Streamlit application
├── Iris.csv        # Iris dataset
├── .gitignore      # Git ignore file
└── README.md       # Project documentation
```

## Requirements

- Python 3.7 or higher
- Streamlit
- Pandas

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd streamlit
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Dataset

The application uses the Iris dataset (`Iris.csv`), which contains the following columns:

- `Id`: Unique identifier for each record.
- `SepalLengthCm`: Sepal length in cm.
- `SepalWidthCm`: Sepal width in cm.
- `PetalLengthCm`: Petal length in cm.
- `PetalWidthCm`: Petal width in cm.
- `Species`: The species of the Iris flower.

## Usage

1. Open the application in your browser after running the `streamlit run app.py` command.
2. Use the sidebar to select a feature and filter range.
3. View the filtered dataset and its statistics.

## License

This project is licensed under the MIT License.