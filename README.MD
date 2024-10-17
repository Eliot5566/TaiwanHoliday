# TaiwanHoliday 檔案說明

此檔案用於透過 API 擷取台灣的國定假日資料，並以 JSON 格式返回。

要擷取台灣的假日資料，您可以發送 API 請求，並以 JSON 格式接收回應。API 應提供必要的端點和參數，以指定台灣為國家，並指定所需的假日日期範圍。

一旦收到 JSON 回應，您可以解析並根據需要在應用程式中使用資料。

請記得在 API 請求和回應過程中處理可能發生的任何錯誤或異常情況。

有關如何使用 API 和 JSON 回應的具體格式的更多詳細資訊，請參閱 API 文件。

## API 文件

要擷取台灣的假日資料，您可以使用以下端點發送 API 請求：

- `/api/holidays/{date}`：擷取特定日期的假日資料。將 `{date}` 替換為所需日期，格式為 `YYYYMMDD`。例如，`/api/holidays/20221218` 將擷取 2022 年 12 月 18 日的假日資料。

- `/api/holidays/{year}`：擷取特定年份的假日資料。將 `{year}` 替換為所需年份。例如，`/api/holidays/2024` 將擷取 2024 年的假日資料。

API 將以 JSON 格式回應假日資料。您可以解析並根據需要在應用程式中使用資料。

請記得在 API 請求和回應過程中處理可能發生的任何錯誤或異常情況。

有關如何使用 API 和 JSON 回應的更多詳細資訊，請參閱 API 文件。

## 授權資訊

此檔案中使用的原始資料根據政府開放資料授權條款 - 版本 1.0 授權。根據第 3 條第 2 款的要求，請將來源標註為政府開放資料平台。此外，根據第 4 條第 2 款的規定，該資料以創用 CC 姓名標示 4.0 國際 (CC BY 4.0) 授權釋出。

在使用資料時，請確保遵守授權條款。

有關授權條款的更多詳細資訊，請參閱相應的授權條款。


# TaiwanHoliday File Description

This file is used to retrieve national holiday data in JSON format through an API.

To retrieve the holiday data for Taiwan, you can make an API request and receive the response in JSON format. The API should provide the necessary endpoints and parameters to specify Taiwan as the country and the desired date range for the holidays you want to retrieve.

Once you receive the JSON response, you can parse and use the data in your application as needed.

Remember to handle any errors or exceptions that may occur during the API request and response process.

Please refer to the API documentation for more details on how to use the API and the specific format of the JSON response.


## API Documentation

To retrieve the holiday data for Taiwan, you can make an API request using the following endpoints:

- `/api/holidays/{date}`: Retrieves the holiday data for a specific date. Replace `{date}` with the desired date in the format `YYYYMMDD`. For example, `/api/holidays/20221218` will retrieve the holiday data for December 18, 2022.

- `/api/holidays/{year}`: Retrieves the holiday data for a specific year. Replace `{year}` with the desired year. For example, `/api/holidays/2024` will retrieve the holiday data for the year 2024.

The API will respond with the holiday data in JSON format. You can parse and use the data in your application as needed.

Remember to handle any errors or exceptions that may occur during the API request and response process.

For more details on how to use the API and the specific format of the JSON response, please refer to the API documentation.



## Licensing Information

The original data used in this file is licensed under the Government Open Data License - Version 1.0. As per the requirements stated in Article 3, Section 2, please attribute the source as the Government Open Data Platform. Additionally, the data is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) license, as explained in Article 4, Section 2.

Please ensure that you comply with the licensing terms when using the data.

For more details on the licensing terms, please refer to the respective licenses.
