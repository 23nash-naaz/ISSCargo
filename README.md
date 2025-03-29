
# ISS Cargo Management Simulation on Kaggle

This project simulates a cargo management system for a space station (e.g., the ISS) using synthetic datasets. The simulation covers:

- **Data Generation:**  
  Generates dummy datasets for items and containers with realistic attributes (dimensions, mass, expiry dates, etc.).

- **Placement Algorithm:**  
  A greedy algorithm that places each item into an available container based on its preferred zone and available volume.

- **Retrieval Simulation:**  
  Simulates the retrieval process by calculating the number of items that need to be moved before the requested item can be retrieved.

- **Waste Management:**  
  Automatically removes items that are either expired or have exhausted their usage limit.

## Files

- **Kaggle Notebook (this cell):**  
  Contains the entire code to generate datasets, run the simulation, and print results.

- **dummy_items.csv:**  
  Generated synthetic dataset containing item data.

- **dummy_containers.csv:**  
  Generated synthetic dataset containing container data.

## How to Run on Kaggle

1. **Create a New Kaggle Notebook:**
   - Log in to your Kaggle account.
   - Click on **"New Notebook"**.

2. **Paste the Provided Code:**
   - Copy the complete Python code (as shown in the notebook cell) into a cell in the Kaggle Notebook.
   - The code will generate synthetic datasets, save them as CSV files, and run the simulation.

3. **Run the Notebook Cell:**
   - Execute the cell by clicking the "Run" button or pressing `Shift+Enter`.
   - The notebook will display:
     - Confirmation of generated datasets along with their shapes.
     - Sample placement recommendations.
     - Daily simulation results including retrieval operations and waste management events.
     - Final container states after the simulation.

4. **Review Output:**
   - The output will appear in the notebook’s output area.
   - You can also view the generated CSV files (dummy_items.csv and dummy_containers.csv) in the Kaggle Files panel.

## Customization

- **Simulation Duration:**  
  Modify the `simulation_days` variable in the code to simulate more or fewer days.

- **Retrieval Requests:**  
  The simulation randomly selects 10 items per day for retrieval. Adjust this number as needed.

- **Algorithm Enhancements:**  
  The current greedy placement algorithm can be enhanced with more sophisticated heuristics for better space optimization.

## Project Structure (if exporting to GitHub)

If you choose to export this project from Kaggle to GitHub, the structure may look like this:

