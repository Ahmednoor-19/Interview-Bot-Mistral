# Interview Bot Project

This project involves developing an Interview Bot capable of analyzing interview feedback and case data to provide insights and improve the interview process. The project utilizes a fine-tuned Mistral model to handle and analyze interview-related data.

## Project Structure

### Files in the Repository

1. **Case Data.csv**
   - Contains case study data used for training and analysis.

2. **Interview Feedback Data.csv**
   - Contains feedback data from interviews, used for evaluating the performance and responses.

3. **csv_to_json.ipynb**
   - Jupyter notebook for converting CSV files to JSON format for easier processing and analysis.

4. **training_script.ipynb**
   - Jupyter notebook for training and fine-tuning the Mistral model on the processed data to provide insights and feedback.

## Features

1. **Data Conversion**: Convert CSV files into JSON format using the provided Jupyter notebook.
   
2. **Data Processing**: Analyze and process case study and interview feedback data.

3. **Model Training**: Fine-tune the Mistral model on the processed data to derive useful insights and feedback.

4. **Insight Generation**: Generate insights based on the fine-tuned model to improve interview performance and decision-making.

## How to Run the Project

### 1. Prepare Your Environment

Ensure you have Jupyter Notebook installed and the required libraries listed in the `requirements.txt` file.

### 2. Convert CSV to JSON

Run the `csv_to_json.ipynb` notebook to convert your CSV files into JSON format. This step is crucial for preparing the data for further processing.

### 3. Train the Model

Execute the `training_script.ipynb` notebook to fine-tune the Mistral model using the processed data. This script will leverage the converted JSON data to train and enhance the model's performance.

## Libraries Used

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **scikit-learn**: For machine learning model training and evaluation.
- **transformers**: For working with Mistral and other language models.
- **json**: For handling JSON data format.

## Usage

1. **Capture Data**: Use the CSV files to input interview and case study data.
2. **Convert Data**: Run the `csv_to_json.ipynb` notebook to convert the data from CSV to JSON format.
3. **Train Model**: Execute the `training_script.ipynb` notebook to fine-tune the Mistral model and generate insights.

## Future Enhancements

1. **Advanced Models**: Experiment with additional models or techniques to further improve accuracy and insights.
2. **User Interface**: Develop a user-friendly interface for easier interaction and visualization of insights.
3. **Integration**: Integrate with other tools or platforms to enhance the functionality and usability of the Interview Bot.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

## Contact

For any questions or suggestions, please feel free to reach out to:

Sheikh Ahmed Noor: [sheikhahmednoor00@gmail.com](mailto:sheikhahmednoor00@gmail.com)
