# Address Normalization Project

## Project Overview

The **Address Normalization Project** is a Streamlit-based application that provides accurate location visualization and address correction. Users can input an address, and the system performs the following tasks:

1. Corrects spelling mistakes in the address.
2. Geocodes the address to retrieve its latitude and longitude.
3. Displays the location on a map interface using HERE API.

This project streamlines address entry and visualization, ensuring precise and user-friendly results.

---

## Features

- **Address Input**
  - Users can enter any address in a text input field.

- **Spelling Correction**
  - The system detects and corrects spelling errors in the input address.

- **Geocoding**
  - Retrieves latitude and longitude for the given address using the HERE API.

- **Map Visualization**
  - Displays the corrected address on an interactive map powered by the HERE API for better understanding and verification.

---

## Technologies Used

- **Frontend**: Streamlit
- **Backend**: Python
- **APIs**: HERE API, Geopy (optional for geocoding support)
- **Libraries**: 
  - `textblob` or `symspellpy` for spelling correction
  - `folium` or Streamlit Map for map visualization

---


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Priyuuuuu/address-normalisation
   ```

2. **Install dependencies**
   
3. **Run the application**:
   ```bash
   streamlit run app.py
   ```

---

