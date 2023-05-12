## 📚 Lib-HttpPostMultipart
* Library collected in parts from the Internet for easy sending Http Post Multipart requests to Java

## Usage
```
// Set headers
Map<String, String> headers = new HashMap<>();

headers.put(/* add any headers */); 
// ex. 
// headers.put("User-Agent", "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_4) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/79.0.3945.88 Safari/537.36");

HttpPostMultipart multipart = new HttpPostMultipart(requestURL, charset, headers);

multipart.addFormField(fieldName, fieldValue);

// Print result
String response = multipart.finish();
System.out.println(response);
```
