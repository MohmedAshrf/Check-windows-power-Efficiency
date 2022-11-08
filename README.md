# Check-windows-power-Efficiency

To check the power efficiency in windows:
	1. open the cmd as an adminstrator
	2. run the following command:
  ```
		powercfg -energy
    ```
	3. wait until the energy-report.html file is created
	4. run the following command to see the result:
  ```
		type energy-report.html | Findstr efficiency
    ```
