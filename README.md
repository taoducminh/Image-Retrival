
# Image Retrieval Project

## Overview

This project focuses on building an Image Retrieval system using traditional and advanced techniques, including deep learning models and vector databases. The system retrieves images that are visually similar to a given query image from a predefined image dataset. The project is divided into multiple phases, covering both basic and advanced methods for image retrieval.

## Project Structure

- **1_Project_Traditional.ipynb**: Contains the implementation of traditional image retrieval methods using L1, L2, Cosine Similarity, and Correlation Coefficient metrics.
- **2_Project_Embedding.ipynb**: Focuses on using pre-trained deep learning models (CLIP) to extract feature vectors from images for improved retrieval accuracy.
- **3_Project_VectorDatabase.ipynb**: Enhances the retrieval process by integrating a vector database (ChromaDB) to efficiently manage and query image embeddings.
- **Crawler.ipynb**: Implements a web crawler to collect images from the web (Flickr) and prepare the dataset for the image retrieval task.
- **Preprocessing.ipynb**: Handles data preprocessing tasks, including cleaning and organizing the dataset into training and testing sets.
- **Project_VectorDatabase_crawl.ipynb**: Extends the vector database approach by adding functionality to handle large-scale image datasets with optimized querying.

## Key Components

### 1. Traditional Image Retrieval
The project starts with implementing traditional image retrieval methods using various distance metrics:
- **L1 Distance (Manhattan Distance)**
- **L2 Distance (Euclidean Distance)**
- **Cosine Similarity**
- **Correlation Coefficient**

### 2. Advanced Image Retrieval with Deep Learning
Using the CLIP model, the project extracts feature vectors from images. These vectors are then compared using the same distance metrics to retrieve similar images more accurately.

### 3. Optimized Retrieval with Vector Database
To manage and efficiently query large sets of image embeddings, a vector database (ChromaDB) is used. This phase involves storing image embeddings in a database and querying them to retrieve the most similar images quickly.

### 4. Data Collection and Preprocessing
The project includes a web crawler that collects images from Flickr based on various search terms. The images are then processed, cleaned, and organized into a structured dataset suitable for the image retrieval tasks.

## Setup and Installation

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Necessary Python libraries as listed in `requirements.txt`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-retrieval-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd image-retrieval-project
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebooks
1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open the relevant `.ipynb` files and run the cells sequentially.

## Usage
1. **Data Collection**: Run `Crawler.ipynb` to collect images from the web.
2. **Preprocessing**: Use `Preprocessing.ipynb` to clean and organize the dataset.
3. **Image Retrieval**:
   - Run `1_Project_Traditional.ipynb` for traditional image retrieval methods.
   - Run `2_Project_Embedding.ipynb` for retrieval using the CLIP model.
   - Run `3_Project_VectorDatabase.ipynb` to use the vector database for optimized retrieval.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss any changes.

## License
This project is licensed under the MIT License.
