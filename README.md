# salesforeml Backend
# File upload:
The upload_File function is defined to handle the POST request sent from the frontend Angular application. It checks if the request contains a file, saves the file to the specified directory on the server, and returns a success message.

# Forecasting:
The forecast function is defined to handle the POST request sent from the frontend Angular application, which contains the selected number of steps for forecasting. It reads the uploaded file, selects the endogenous variable (in this case, the Sales column), defines a SARIMAX model, fits the model to the data, and generates a forecast for the specified number of steps. The forecast is saved to an Excel file and returned as a JSON response.

# Plotting:
The plot function is defined to plot the actual sales and forecasted sales. It loads the uploaded file, reads the Sales column, generates a forecast using the SARIMAX model, plots the actual sales and forecasted sales, saves the plot as an image, and returns a success message.

# Excel creation:
The create_excel function is defined to create an excel file and save the forecast data in it.

A simple function to calculate the square of a number:
The disp function is defined to take an integer as input, calculate its square, and return the result as a JSON response.

# Main function:
Finally, the main function runs the Flask application with debug mode enabled.






         
       








