# Smart-Gardening-System
The Smart Trolley System, powered by Raspberry Pi 3B, revolutionizes the retail experience by integrating a barcode scanner, load cell, push buttons, and an LCD display. This system enhances efficiency, accuracy, and security in the shopping process.

## Features
- Barcode scanning for product identification.
- Load cell for real-time weight monitoring.
- Push buttons for user interaction.
- LCD display for product details and pricing.
- Raspberry Pi 3B for data processing and communication.
- Security measure using the load cell to compare scanned and actual weights.

## Components
Our system includes the following key components:
- Barcode scanner
- Load cell
- Push buttons
- LCD display
- Power supply
- Trolley frame

## Component Connections for Smart Trolley System
### Raspberry Pi 3B to Components:
- Connect barcode scanner, load cell, push buttons, and LCD display to GPIO pins on the Raspberry Pi.
- Utilize appropriate power supplies for each component.

## Block Diagram

1. **Barcode Scanning:**
   - When a user places a product in the cart, the barcode scanner reads the barcode on the product's packaging. The Raspberry Pi processes the barcode data and retrieves product information from a predefined database.

2. **Data Display:**
   - The Raspberry Pi displays the product details on an LCD display mounted on the cart, including the product name, price, and a running total of the bill.

3. **Load Cell Integration:**
   - The cart is equipped with a load cell, which measures the weight of the cart and its contents. The load cell provides real-time weight data to the Raspberry Pi.

4. **Weight Verification:**
   - The Raspberry Pi compares the total weight of the purchased items, as measured by the load cell, with the calculated weight of the scanned products, ensuring accurate billing.

5. **Data Storage on ThingSpeak:**
   - Product information, total bill, and weight data are sent to ThingSpeak, an IoT platform for data storage and visualization.

## Explanation:

- **Barcode Scanning:**
  - Real-time identification of products using the barcode scanner.
- **Load Cell Security:**
  - Compares scanned weight with actual weight; triggers alert in case of discrepancies, enhancing security.
- **Push Buttons:**
  - Allow users to interact, perhaps for confirming purchases or requesting assistance.
- **LCD Display:**
  - Shows product details, pricing, and a running total.
- **Raspberry Pi 3B:**
  - Processes data, communicates with components, and manages the overall system.

## Libraries Used in the Code:
- **RPi.GPIO Library:**
  - Utilized for interfacing Raspberry Pi GPIO pins with other components.
- **Barcode Scanner Library:**
  - Specific libraries for the barcode scanner model for efficient code integration.
- **HX711 Load Cell Library:**
  - Enables communication with the load cell for weight measurements.
- **LCD Python Library:**
  - Manages the LCD display, providing functionalities for text and data presentation.

These libraries are essential for connecting to the system, reading data from sensors. Each library serves a specific purpose in the functionality of our Smart Trolley.

## Benefits
- **Efficient Shopping:**
  - Quick product identification and billing.
- **Accurate Billing:**
  - Real-time weight monitoring ensures precise billing.
- **Enhanced Security:**
  - Load cell security feature alerts in case of discrepancies, preventing unauthorized items.

## Conclusion
The Smart Trolley System not only streamlines the retail experience but also prioritizes security. The integration of a load cell for weight verification adds an extra layer of protection against unauthorized items, ensuring a secure and efficient shopping process.

Thank you for considering our solution. We look forward to discussing how this system can be tailored to meet your specific needs.

**For any inquiries or further details, please feel free to contact us.**

**Contact Email: [campussolutions9@gmail.com](mailto:campussolutions9@gmail.com)**

**Thank You …..**
