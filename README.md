This repository contains a JavaScript function with a bug related to the handling of NaN (Not a Number) values. The original function does not correctly handle cases where one or both input parameters are NaN. The solution provided addresses this issue by explicitly checking for NaN values using the isNaN() function and returning 0 in those cases.  This ensures a more robust and reliable function.