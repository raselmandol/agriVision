
# AgriVision

AgriVision is an innovative web and mobile application designed to empower farmers, agronomists, and agricultural stakeholders with actionable insights derived from Earth observation data. Leveraging NASA's remote sensing assets and other environmental data, AgriVision helps users make informed decisions about crop management, planting schedules, and agricultural trends.

## Why AgriVision?

In a world facing climate change and increasing agricultural demands, AgriVision helps farmers make data-driven decisions to ensure sustainable and efficient food production. By providing critical insights and forecasts, AgriVision aims to reduce crop failures, optimize resource use, and improve overall productivity in agriculture.

## Key Features

- **Crop Yield Prediction**: Uses weather patterns, soil conditions, and satellite imagery to predict crop yields and provide insights on resource management.
- **Optimal Planting Date Identification**: Recommends the best planting windows based on Earth observation data such as temperature, rainfall, and soil moisture.
- **Agricultural Trends Forecasting**: Forecasts agricultural trends using historical and satellite data to prepare for future challenges such as droughts, pests, and changes in growing seasons.
- **Real-Time Data Integration**: Utilizes NASA’s Earth observation datasets (MODIS, Landsat, SMAP) and local weather data for real-time recommendations.
- **Mobile & Web Access**: Available as both a web and mobile application, making it accessible to users in the field and at the office.

---

## Installation

Follow the steps below to set up and run the **AgriVision** web and mobile applications locally:

### Web Application

1. **Clone the Repository**:
   Clone the project from GitHub to your local machine:
   ```bash
   git clone https://github.com/raselmandol/agriVision
   ```
   Navigate into the project directory:
   ```bash
   cd AgriVision
   ```

2. **Install**:
   Follow this if you are using aws ec2
   ```bash
   sudo apt-get update
   sudo apt-get upgrade

   ```
   Install Django and Other Deps
   ```bash
   sudo apt-get install python3-pip python3-dev libpq-dev postgresql postgresql-contrib nginx curl
   sudo apt-get upgrade
   sudo apt-get install python3-venv
   
   ```
   Navigate to your home directory or wherever you want to create your Django project:

   ```bash
   cd ~
   ```
   Create a virtual environment. Replace venv with your preferred name for the environment:

   ```bash
   python3 -m venv myenv
   ```
   Activate the virtual environment:
   ```bash
   source myenv/bin/activate
   ```
   Install Django and Requests and OLs
   ```bash
   sudo apt-get install python3-pip python3-dev libpq-dev postgresql postgresql-contrib nginx curl
   ```
   Create Django Project
   ```bash
   django-admin startproject agriVision
   cd agriVision
   python3 manage.py startapp dashboard
   ```
3. **Setup-i**:
   Follow [setup-doc](https://github.com/raselmandol/agriVision/SETUP.md) to install agriVision on aws ec2(Ubuntu).
   
---

### Additional Setup Requirements

- **APIs**: You will need API keys for services such as OpenWeatherMap and NASA Earth Observation. Add these keys to your environment variables.

---

## Technologies Used

- **Framework-web**: Django
- **Frontend-web**: HTML, CSS, Javascript
- **Backend-web**: Python (Django)
- **Machine Learning(Prediction)**: TensorFlow, Scikit-learn (for trend forecasting and yield predictions)
- **APIs**: OpenWeather, api.NASA, NASA Open APIs

---

## Contributing

Contributions are welcome! Feel free to submit pull requests or report issues on the GitHub repository.

---

## License

This project is licensed under the MIT License.

---

## Acknowledgments

- **NASA**: For providing access to Earth observation data.


---

## Authors

- [@raselmandol](https://github.com/raselmandol)
- [@shefukri](https://github.com/shefukri)
- [@koyelkalita](https://github.com/koyelkalita)

With **AgriVision**, agricultural stakeholders can harness the power of modern data technology to ensure more informed, sustainable farming practices globally.
