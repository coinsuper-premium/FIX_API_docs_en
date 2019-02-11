# **FIX API**

Introduction

```
Exchange API is an interface provided by Coinsuper for external developers.
```

------

Update log

| Version   | Modify date | Comment       | Author |
| --------- | ----------- | ------------- | ------ |
| v1.0.0(α) | 20181226    | First edition | liyong |

------------- ----------------- --------------- ------------
## [一、**General Information**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#%E4%B8%80general-information)

#### [**API Access Address**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#api-access-address)

#### [**API Specifications**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#api-specifications)

##### [**POST Body Format**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#post-body-format)

##### [**Logon Signature Generation Method**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#logon-signature-generation-method)

##### [**Signature Generation Sample**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#signature-generation-sample)

#### [FIX is requesting a standard message header.](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#fix-is-requesting-a-standard-message-header)

#### [**General Exceptions**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#general-exceptions)

------------------------ ---------------------------------------


## https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#%E4%BA%8C-api-endpoint-details

### [API Endpoint Definition](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#api-endpoint-definition)

#### [**1. Session Type**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#1-session-type)

##### [**1.1 Logon**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#11-logon)

##### [**1.2 Logout**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#12-logout)

##### [1.3 Heartbeat](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#13-heartbeat)

#### [2. Transaction Type](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#2-transaction-type)

##### [**2.1 Order Creation**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#21-order-creation)

##### [2.2 Order Cancellation](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#22-order-cancellation)

####[3. Query Type](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#3-query-type)

##### [**3.1 Queries into Unfinished Orders**](https://github.com/coinsuper-premium/FIX_API_docs_en/wiki#31-queries-into-unfinished-orders)
