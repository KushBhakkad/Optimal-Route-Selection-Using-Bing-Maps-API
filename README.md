# Optimal-Route-Selection-Using-Bing-Maps-API

## Project Overview
This project demonstrates a Python-based solution to solve the Traveling Salesperson Problem (TSP) for a set of locations using the Bing Maps API. The program calculates the optimal route for visiting all specified locations and returning to the starting point. It also provides a visual map of the route, displays the total distance, and uses text-to-speech to narrate the results.

## Features
- **Geocoding:** Convert human-readable addresses into geographic coordinates using Bing Maps API.
- **Distance Calculation:** Determine driving distances between multiple locations.
- **Optimal Route Selection:** Use Google OR-Tools to solve the TSP and find the shortest possible route.
- **Map Visualization:** Generate a Bing Maps URL to visualize the route.
- **Text-to-Speech Integration:** Narrate the route details and total distance.

## Installation
### Prerequisites
- Python 3.8 or higher
- Bing Maps API Key
- Required Python libraries: `requests`, `ortools`, `pyttsx3`

## Usage
1. Run the script:
   ```bash
   python main.py
   ```
2. Enter the number of locations to visit and their respective addresses when prompted.
3. The script will:
   - Calculate the optimal route.
   - Display the route and total distance in the console.
   - Open the route visualization in your default browser.
   - Narrate the results using text-to-speech.

## Example Output

![Output](https://github.com/user-attachments/assets/56710ac7-fd12-479a-936d-8cf6d3dcf6b5)

## Key Files
- `main.py`: Entry point for the application.
- `config.py`: Contains the Bing Maps API key.

## Technologies Used
- **Programming Language:** Python
- **APIs:** Bing Maps REST API
- **Optimization:** Google OR-Tools
- **Libraries:**
  - `requests` for API requests
  - `ortools` for solving the TSP
  - `pyttsx3` for text-to-speech
