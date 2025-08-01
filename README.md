# RajStructure – Desktop 2-D Detailer

## Installation
1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```
   streamlit run app.py
   ```
2. Use the sidebar to configure your structural elements and generate DXF files.

## Troubleshooting
- **Coordinate Scaling Issues**: 
  If the DXF output appears incorrectly scaled, you may need to adjust the coordinate scaling in the generator:
  - If your inputs are in millimeters (mm), divide by 1000 to convert to meters (m)
  - If your inputs are in meters (m), multiply by 1000 to convert to millimeters (mm)

## Features
- Generate DXF files for various structural elements
- Support for different unit systems (mm/m)
- Interactive configuration through Streamlit interface
