# AdminsApi

All URIs are relative to *https://virtserver.swaggerhub.com/kocicjelen/hier/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addInventory**](AdminsApi.md#addInventory) | **POST** /inventory | adds an inventory item




<a name="addInventory"></a>
# **addInventory**
> addInventory(inventoryitem)

adds an inventory item

Adds an item to the system

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.AdminsApi;



AdminsApi apiInstance = new AdminsApi();

InventoryItem inventoryitem = ; // InventoryItem | 

try {
    apiInstance.addInventory(inventoryitem);
} catch (ApiException e) {
    System.err.println("Exception when calling AdminsApi#addInventory");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inventoryitem** | [**InventoryItem**](.md)|  | [optional]


### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined



