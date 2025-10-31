# Urban-Heat-Mapping-via-Roof-Type-Classification-
Urban Heat Mapping via Roof Type Classification uses computer vision on satellite images to identify roof types and estimate their heat absorption levels. It generates an Urban Heat Sustainability Index (UHSI) to highlight heat-prone zones, supporting eco-friendly and climate-resilient city planning.

Overview

Urban Heat Mapping via Roof Type Classification is a computer vision project that leverages satellite and aerial imagery to promote sustainable urban planning.
The model classifies building roofs into categories — Green, Concrete, Metal, and Terracotta — and computes an Urban Heat Sustainability Index (UHSI) to highlight heat-prone zones in cities.

By identifying roofs with high heat absorption (e.g., metal, concrete) versus sustainable ones (e.g., green), the system supports eco-friendly infrastructure planning, energy efficiency, and climate-resilient development.

Key Features

Roof Type Classification: Deep learning model trained on satellite images.

Urban Heat Index (UHSI): Quantifies sustainability based on roof materials.

Heat Map Visualization: Interactive map/dashboard to visualize heat zones.

Sustainability Insights: Helps urban planners identify improvement areas.

Tech Stack

Languages: Python

Libraries: TensorFlow / Keras, OpenCV, NumPy, scikit-learn, Folium, Streamlit

Tools: Google Earth Pro, LabelImg / CVAT for dataset creation

Workflow

Data Collection: Capture and label aerial roof images from Google Earth.

Model Training: Fine-tune MobileNetV3 or EfficientNet for roof classification.

Heat Scoring: Assign sustainability values to each roof category.

Visualization: Generate an interactive UHSI heat map using Folium or Streamlit.

Results

Accurate roof classification using transfer learning models.

Generated sustainability heat maps for visual analysis.

Provides actionable insights for greener city planning.

Future Enhancements

Integrate live satellite or drone data for real-time analysis.

Combine with weather or temperature datasets for validation.

Extend to predict “cool roof” adoption potential across regions.

Conclusion

This project demonstrates how AI and sustainability can work together to create climate-aware urban ecosystems. By mapping roof types and heat profiles, it offers a practical, data-driven approach to building smarter and greener cities.
