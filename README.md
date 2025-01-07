# Populate_Sampling_Custom
Software allowing to populate a distribution (Adoption, TVL, Subscribers...)


# README.md

# Dynamic TVL Distribution Tool

This tool is designed to dynamically create and manage statistical distributions for simulating Total Value Locked (TVL) data. The application is built using Streamlit and provides a user-friendly interface for configuring parameters and visualizing distributions.

## Features
- **Configurable Parameters**: Adjust the number of values, mean deposit, standard deviation, and more.
- **Power User Options**: Include extra low and high values with specific ranges and proportions.
- **Histogram Visualization**: View a histogram of the generated distribution with range indicators.
- **Data Export**: Download the generated distribution as a CSV file.
- **Descriptive Statistics**: View statistical summaries of the generated data.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```bash
   streamlit run app.py
   ```
2. Open the application in your web browser at `http://localhost:8501`.
3. Configure parameters using the sidebar and interact with the generated data.

## Dependencies
The required Python libraries are listed in `requirements.txt`.

## File Structure
- `app.py`: Main application script.
- `requirements.txt`: List of dependencies.
- `README.md`: Project documentation.

## Contributing
Feel free to open issues or submit pull requests for new features or improvements.

## License
This project is licensed under the [MIT License](LICENSE).

---
