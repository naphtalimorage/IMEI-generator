# IMEI-generator

IMEI-generator helps you generate and validate IMEI numbers.

### Usage

1. Add this package to your project:
    ```sh
    npm install imei-generator
    ```

2. Import the package:
    ```javascript
    const imeiGenerator = require('imei-generator');

    // Generate IMEI
    const imei = imeiGenerator.generateIMEI();

    // Validate IMEI
    const isValidIMEI = imeiGenerator.isValidIMEI(imei);
    ```
