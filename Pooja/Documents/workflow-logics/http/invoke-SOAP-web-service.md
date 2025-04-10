# Invoke SOAP Web Service

## Description

This interface allows users to send SOAP requests to a specified web service endpoint. It is used for integrating external systems that communicate using the SOAP protocol.

![Invoke SOAP Web Service UI](../../assests/workflow-logics/assests%20http/invoke-SOAP-web-service.png)

---

## Fields and Options

### **1. Endpoint** (Required)

- **Purpose:** The URL of the SOAP web service endpoint.
- **Example:** `https://example.com/soap/endpoint`
- **Required:** Yes

### **2. Custom Headers**

- **Purpose:** Optional HTTP headers to be included in the request.
- **Format:** JSON or plain key-value pairs.
- **Example:**

  ```json
  {
    "Content-Type": "text/xml",
    "Authorization": "Bearer token123"
  }
  ```

### 3. Request Body

Purpose: The full SOAP XML request body.

Format: Raw XML.

- **Example:**

```plaintext
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:web="http://example.com/webservice">
   <soapenv:Header/>
   <soapenv:Body>
      <web:GetData>
         <web:Id>123</web:Id>
      </web:GetData>
   </soapenv:Body>
</soapenv:Envelope>

```

### Common Use Cases

- Fetching data from legacy systems
- Performing transactions with ERP or CRM systems
- Interacting with government or financial web services
