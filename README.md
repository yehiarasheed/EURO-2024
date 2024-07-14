# EURO 2024 Player Filter

## Project Description

This project processes an Excel workbook listing all the Euro 2024 players with details such as name, citizenship, position, weight, height, date of birth, club team, and club team league. It allows users to filter the entire list and create a new workbook with a sheet named after the selected country. If "All" is chosen, it creates workbooks with sheets for each country team. If a specific country name is chosen, it creates an Excel file with a sheet that contains player data with the name of the country. The filtering process is highly efficient, taking as short as 20 seconds for all 24 countries and 12 seconds for a single country. **Essentially reducing the processing time by 80% and achieving better monitoring of overall activity using the detailed logs and validations provided by the robots.**
![StepsCompressed](https://github.com/user-attachments/assets/c2d5dabd-56f3-4196-8f0b-0015e8422668)

> [!IMPORTANT] 
> All the File Paths used in the project are now relative paths so that any user could clone the project and use it right out of the box. In the `Additional Files` folder, you will find the Excel workbook containing all the players and teams data inside the `Inputs` folder. As well as the generated outputs in the `Outputs` folder.

## How to Install

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yehiarasheed/EURO-2024.git
   cd EURO-2024
   ```

   **Alternatively, Clone the Repository in UiPath Studio:**
   - Open UiPath Studio.
   - Go to the `Team` tab.
   - Click on `Clone Repository`.
   - Enter the repository URL: https://github.com/yehiarasheed/EURO-2024.git.
   - Select the destination folder and click `Open` using your Authentication method of choice.

3. **Install UiPath Studio:**
   Download and install UiPath Studio from the [official UiPath website](https://www.uipath.com).

4. **Open the Project in UiPath Studio:**
   - Launch UiPath Studio.
   - Click on `Open` in the Start tab.
   - Navigate to the cloned repository folder and open the `.xaml` file.

5. **Install Microsoft Excel:**
   Ensure Microsoft Excel is installed on your computer, as it is required for handling Excel files in this project.

## Dependencies

This project requires the following dependencies:

- **Microsoft Excel**: Required for handling Excel files.
- **UiPath.Excel.Activities**: For interacting with Excel files.
- **UiPath.System.Activities**: For general automation tasks.

These dependencies can be managed through UiPath Studio's Package Manager. Make sure all required packages are installed and up to date.



---
