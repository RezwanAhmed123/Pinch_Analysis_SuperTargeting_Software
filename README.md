# Pinch Analysis SuperTargeting Software

## Acknowledgments
This software was completely developed by myself, Rezwan Ahmed, with some help using AI tools such as ChatGPT. This software also depends on an excel sheet provided in Kemp's Book (Pinch Analysis and Process Integration: A User Guide on Process Integration for the Efficient Use of Energy, 2007). Feel free to use the software as desired, and make modifications as you feel fit. Unfortunately, due to copyright issues, I cannot provide that excel sheet.

However, if you are able to create the composite curve plot data yourself, it is also possible to use this software accordingly. Just keep in mind that the accuracy may not be 100% as the software was created using the excel sheet provided in Kemp's Book.

## Assumptions (not an exhaustive list)
- Stream CP is constant for all streams.
- Heat Transfer Coefficient is not temperature dependent.
- Balanced Composite Curve is used.

## User Guide
1. Copy and paste composite curve data in the correct locations in cell 2.
2. If data is processed correctly, there would be a success message printed, if not, error messages will explain what went wrong.
3. In cell 3, declare list of stream names and respective coefficients (HTC, CP) in that order.
4. In cell 4 and 6, list out the stream names (following the same names as in cell 3) and their respective temperature ranges. Examples, Hot streams: (hotter, colder) and Cold streams: (colder, hotter).
5. Cells 5 and 7 gives a summary of all the streams in each possible interval and serves as a check if calculations feel wrong later down the line.
6. Cell 15 plots the Hot and Cold Composite Curves and the number of sections created using the code.
7. In cell 20, manually adjust the hot temperature and cold temperature pinch temperatures. The number of minimum theoretical heat exchangers required above and below the pinch should be printed out accordingly.
8. In cell 21, manually adjust the costing equations for cost of utilities and capital costs based on equations that are more representative of the systems you are using.