markdown
# Renewable Energy Generation Data in Abu Dhabi

This repository contains a dataset and accompanying code for managing renewable energy generation data in Abu Dhabi from 2010 to the present.

## Dataset

The dataset includes annual figures of renewable energy generation in megawatts (MW) from solar, wind, and other renewable sources. It is formatted as a CSV file for ease of analysis and compatibility with various tools.

### Data Columns
- **Year**: The year of data collection.
- **Solar MW**: Megawatts generated from solar energy.
- **Wind MW**: Megawatts generated from wind energy.
- **Other Renewables MW**: Megawatts generated from other renewable sources.
- **Total MW**: Total megawatts generated from all renewable sources.

## Code

The Python script provided allows users to add new data to the existing dataset. Follow the steps below to update the dataset:

1. **Load the original dataset**: Ensure the original CSV file is available at the specified path.
2. **Add new data**: Use the `add_renewable_energy_data` function to append new annual data for solar, wind, and other renewables.
3. **Save the updated dataset**: The script will save the updated data with a timestamp to ensure version control.

### Example Usage
python
add_renewable_energy_data(2023, 500, 200, 50)

This adds data for the year 2023 with 500 MW from solar, 200 MW from wind, and 50 MW from other renewables.

## Contributing

Feel free to fork the repository and submit pull requests to improve the dataset or code. Ensure all changes are well-documented and tested.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
