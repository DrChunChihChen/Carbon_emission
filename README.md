# 溫室氣體盤查計算與儀表板 (GHG Emissions Calculator & Dashboard)

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.20+-red.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

A comprehensive Streamlit web application designed to calculate and visualize an organization's greenhouse gas (GHG) emissions. It provides a user-friendly interface for data entry across various emission sources and presents the results in an interactive dashboard.

## 📸 Screenshots

| Login Page                                    | Data Entry Form                               | Dashboard View                                |
| --------------------------------------------- | --------------------------------------------- | --------------------------------------------- |
| *[Insert screenshot of your login page here]* | *[Insert screenshot of your data form here]* | *[Insert screenshot of your dashboard here]* |

## 🌟 Features

- **🔒 User Authentication:** Secure login page for authorized users.
- **📅 Yearly Inventory:** Select the inventory year for data entry (from 2020 to 2050).
- **🗂️ Tabbed Data Entry:** A clean, multi-tab form for inputting data across 7 different emission categories:
    1.  **固定源 (Stationary Sources):** Fuel combustion from stationary equipment.
    2.  **移動源 (Mobile Sources):** Fuel combustion from company vehicles.
    3.  **逸散性排放源-汙水 (Fugitive Emissions - Wastewater):** Emissions from septic tank usage.
    4.  **逸散性排放源-滅火器 (Fugitive Emissions - Fire Extinguishers):** Emissions from extinguisher use or leakage.
    5.  **逸散性排放源-冷媒 (Fugitive Emissions - Refrigerants):** Emissions from refrigerant leakage.
    6.  **員工通勤 (Employee Commuting):** Indirect emissions from employee travel.
    7.  **外購電力與水力 (Purchased Utilities):** Emissions from purchased electricity and water.
- **📊 Real-time Calculations:** Instantly see the calculated emissions (in tonnes of CO2e) as you enter data.
- **📈 Interactive Dashboard:** Once data is submitted, view a detailed dashboard featuring:
    - Key Performance Indicators (KPIs) for Total, Scope 1, Scope 2, and Scope 3 emissions.
    - A pie chart showing the percentage contribution of each emission category.
    - A bar chart comparing total emissions across the three scopes.
- **🎨 Customizable Login:** Easily set a custom background image for the login screen.
- **↩️ Seamless Navigation:** Switch between the data entry form and the dashboard without losing your input data.

## 🚀 Installation & Usage

To run this application locally, follow these steps:

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```

2.  **Install Dependencies**
    Make sure you have Python 3.8+ installed. Then, install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You will need to create a `requirements.txt` file containing `streamlit`, `pandas`, and `plotly`.)*

3.  **Customize Background (Optional)**
    - Open the `app.py` file.
    - Find the `login_page()` function.
    - Locate the line: `image_path = "C:/Users/ElvisChen/Downloads/ChatGPT Image 2025年6月7日 上午11_25_17.png"`
    - **Replace the placeholder path** with the actual file path to your desired background image.

4.  **Run the Application**
    - In your terminal, run the following command:
    ```bash
    streamlit run app.py
    ```
    - The application will open automatically in your web browser.

## 🔑 Login Credentials

Use one of the following accounts to access the application:

| 帳號 (Username) | 密碼 (Password) |
| :-------------- | :-------------- |
| Elvis           | 0000            |
| Nutc1           | 0001            |
| Nutc2           | 0002            |
| Nutc3           | 0003            |

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for details.
*(Note: You will need to create a `LICENSE.md` file with the MIT License text.)*
