GERD Optimization Code

This repository contains code for modeling and optimizing the management decisions related to the Grand Ethiopian Renaissance Dam (GERD) reservoir system and it's impacts on downstream stakeholders. This analysis uses runoff data and natural / regulated reservoir storage modeling in order to examine the relationships between the river systems, reservoirs, and stakeholders. NSGA-II (Non-dominated Sorting Genetic Algorithm) is used to optimize optimal GERD management decisions.

Repository Structure

GERD_optimization_code.ipynb: The main Jupyter Notebook containing the code for the optimization model. Detailed markdown cells within the notebook provide instructions and explanations for each step of the process.

Data: Various files are inputted into this repository for use in the notebook file.
  - Crop_water_requirements.xlsx : Water Demand for different Crops
  - Cropping_Pattern_Egypt.xlsx : Crop Land Use in Egypt
  - Nile_Stations_Historical_Discharge.xlsx : Average Disharge per month (m^3/s) in various Nile River stations
  - monthly-climatology-....xlsx: monthly average precipitation in ethiopia 1961-1990.


Instructions:

  - Clone this repository:

      git clone <repository_url>
      cd <repository_name>

      Install the required Python libraries (if not already installed):

      pip install -r requirements.txt

      Note: The requirements.txt file should contain dependencies such as numpy, pandas, matplotlib, and scipy.

Open the Jupyter Notebook:

  - jupyter notebook GERD_optimization_code.ipynb

Follow the instructions in the notebook's markdown cells. Each section provides detailed guidance on running specific parts of the model and understanding the output.

Contact

For any questions or issues, please contact Romir Anand (ra493@cornell.edu), Rose Basch (rb753@cornell.edu), or Lily Blyn (llb229@cornell.edu)

Enjoy optimizing the GERD system!

