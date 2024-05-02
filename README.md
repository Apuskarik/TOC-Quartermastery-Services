# TOC-Quartermastery-Services
A functional calculator that allows members to calculate services and cost of supply requisition..
# Brotherhood Quarter-Mastery Services

## Introduction

Brotherhood Quarter-Mastery Services is a web application designed to allow users to easily calculate the total cost of various items, including weapons, upgrades, armor, consumables, and miscellaneous items. Users can specify the quantity of each item they wish to purchase and obtain a calculated total cost.

## Features

- **Dynamically Generated UI**: The form for item selection is generated dynamically from predefined item data, ensuring that the form accurately reflects the available items and their prices.
- **Easy Quantity Adjustment**: Users can adjust the quantity of items via `+` and `-` buttons. They can also directly input quantities into the input fields.
- **Total Cost Calculation**: The app calculates the total cost based on the selected items and their quantities, providing the result in real-time.

## Technologies Used

- **HTML**: For structuring the web page.
- **JavaScript**: For dynamically generating the item form, handling user input, and calculating the total cost.
- **CSS**: For styling the page layout.

## How to Use

1. **Clone or Download** the project to your local machine.
2. Open the `index.html` file in a web browser.
3. **Select Quantities**: Adjust the quantities of items by clicking the `+` and `-` buttons or manually entering a value in the text input fields.
4. Click the **Calculate** button to see the total cost of the selected items.
5. The total cost is displayed below the Calculate button.

## Adding or Modifying Items

- The item data is defined in the `prices` object within the `<script>` tag.
- Each item category (e.g., Weapons, Upgrades) is a property of this object.
- To add or modify items, update the object with the new items and their prices. The user interface will automatically reflect the changes.

## Customization

- **Styling**: Customize the appearance of the page by modifying the `<style>` section of the HTML file.
- **Functional Enhancements**: Extend the JavaScript functions to add new features or refine existing ones.

## License

This project is open-source and available under the MIT license.

## Acknowledgments

Thanks to the Brotherhood of Steel community for inspiring this application.
