# DataPrepKitP
**A Python library for _data preparation_ tasks.**

## Features
> Read data from CSV, Excel, and JSON files.
> Summarize data with statistical measures.
> Handle missing values by removing or imputing.
> Encode categorical data using one-hot encoding.

## Installation
pip install DataPrepKitP
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/466aada1-17c0-441a-8487-3fe1c52e9730)

## Usage
import DataPrepKitP as dp
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/997c9c92-7407-4365-a2a8-0f15471d20e6)

### Read data from a CSV file
data = dp.read_data('data.csv')
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/3adf8aed-4859-4988-bb53-0164c7a619de)

### Summarize the data
dp.data_summary(data)
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/10d9a48d-8255-40a5-bfd2-4993e1f3454c)
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/2cfdf9f8-52b5-4d0b-9e6a-0e25a4825d11)
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/4ca80c17-b93b-4e25-bedd-691a201def23)

### Handle missing values by imputing with the strategy: {'mean', 'median', 'mode', 'drop'}, default='mean'
data = dp.handle_missing_values(data, strategy='mean')
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/c94fccc2-d0ef-48c1-ab00-8c907fa34b93)
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/0395c467-9baa-4fd8-8411-498cc7d4ee00)
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/b0bd0b1e-0128-46d2-9c16-b05b318ae6df)
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/26bff57e-d78e-42f3-8104-3b6deb1278e9)

### Encode categorical data
data = dp.encode_categorical_data(data, 'column_name')
![image](https://github.com/R0-J/DataPrepKitP/assets/80273502/edf27955-e986-44a8-90d2-e374b36ae09b)

## License
This project is licensed under the MIT License.

## Contact
If you have any questions or suggestions, please feel free to contact me at roqaiahjamil@gmail.com.
