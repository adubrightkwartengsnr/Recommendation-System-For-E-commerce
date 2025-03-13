# Recommendation System for E-commerce

## Project Overview
This project is a **Recommendation System for E-commerce**, designed to analyze user behavior and provide personalized product recommendations. The system leverages machine learning techniques and big data processing tools to enhance the shopping experience by predicting user preferences and detecting abnormal behavior in the dataset.

## Features
- **User Behavior Analysis**: Tracks and analyzes user interactions such as product views and cart additions.
- **Personalized Recommendations**: Suggests relevant products based on past interactions.
- **Anomaly Detection**: Identifies unusual user behavior.
- **Scalability**: Handles large datasets efficiently using Dask.
- **ETL Pipeline**: Processes and transforms raw e-commerce data into structured insights.

## Technologies Used
- **Python**: Core programming language for data analysis and modeling.
- **Dask**: Distributed computing framework for handling large-scale data.
- **Pandas & NumPy**: Data manipulation and numerical analysis.
- **Scikit-learn**: Machine learning library for building recommendation models.
- **FastAPI**: API framework to serve recommendations.
- **Streamlit**: Web interface for visualization and user interaction.
- **Docker**: Containerization for seamless deployment.

## Dataset
The project utilizes an **e-commerce dataset** containing:
- **events.csv**: User activity logs (views, add-to-cart, purchases, etc.).
- **item_properties.csv**: Information about products (category, price, etc.).
- **category_tree.csv**: Hierarchical structure of product categories.

## Installation
### Prerequisites
- Python 3.8+
- Docker
- Virtual Environment (optional but recommended)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/recommendation-system
   cd recommendation-system
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the system using Docker:
   ```bash
   docker compose up --build
   ```

## Usage
1. Access the recommendation API at: `http://localhost:8000/docs`
2. Open the Streamlit dashboard: `http://localhost:8501`
3. Monitor data processing using Dask dashboard: `http://localhost:8787`

## Results
- Improved recommendation accuracy by analyzing real-time user behavior.
- Reduced processing time for large datasets using Dask.
- Enhanced product discovery for users, leading to increased engagement.

## Contributing
Contributions are welcome! Feel free to submit an issue or a pull request.

## License
This project is licensed under the MIT License.

## Contact
If you face any challenges, reach out via [LinkedIn](https://www.linkedin.com/in/your-profile).
