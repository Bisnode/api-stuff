## Folder containg postman collections for easy testing


HOW TO:

Set up Postman collection for Bisnode Credit data companies 

Step by step:

1. Download and import Postman collection _bisnode-credit-data-companies.postman_collection.json_ into your Postman instance.

2. Go to https://developer.bisnode.com/store

3. Sign in with your Bisnode-id.

4. Choose Credit Information B2B API
    ![image](https://user-images.githubusercontent.com/54436429/66762071-8f239880-eea5-11e9-97c0-1531eff40cc7.png)

5. Choose 'SUBSCRIBE TO API' and following page will be shown.
    ![image](https://user-images.githubusercontent.com/54436429/66761444-53d49a00-eea4-11e9-92fc-c1faf0e32a3b.png)

6. Choose 'GET API KEY' and click on tab **'Sandbox Keys'**
    ![image](https://user-images.githubusercontent.com/54436429/66761671-c180c600-eea4-11e9-9795-ecdfd4838cfc.png)

7. Click on button 'SHOW KEYS' and your credentials will be shown as text. You will use those values to set Access Token in your Postman collection.

8. Go to Postman and click on the icon with three dots on the right side of the collection name.
    ![image](https://user-images.githubusercontent.com/54436429/66762351-1f61dd80-eea6-11e9-8855-ab0f4853143e.png)

9. Click on Edit.
    ![image](https://user-images.githubusercontent.com/54436429/66762478-5801b700-eea6-11e9-9c15-e6017aa5a285.png)

10. Set your 'Access token' for Postman collection 
 * Ensure that 'OAuth 2.0' is selected as authorization type on the left pane. 
 * Set Add auth data to: 'Request Headers'.
 * Click on button 'Get New Access Token'.
 * Fill the form with following information:
   - _Token Name: API Token_ (or whatever you want to call it)
   - _Grant Type: Client Credentials_ 
   - _Access Token URL: https://login.bisnode.com/as/token.oauth2_
   - _Client ID:_ (copy here 'Consumer Key' value from API Keys - see step 7 above.)
   - _Client Secret:_ (copy here 'Consumer Secret' value from API Keys - see step 7 above.)
   - _Scope: credit_data_companies_
   - _Client Authentication: Send as Basic Auth header_
 ![image](https://user-images.githubusercontent.com/54436429/66763772-ba5bb700-eea8-11e9-835e-ca00ed1c7f00.png)  

11. Click on button 'Request Token' and you will retrieve your access token
    ![image](https://user-images.githubusercontent.com/54436429/66764271-b714fb00-eea9-11e9-9fbe-c09d08f238c3.png)

12.Click 'Use Token'
    ![image](https://user-images.githubusercontent.com/54436429/66764210-9482e200-eea9-11e9-99dd-909d2924a8a5.png)

13. Click 'Update'

Now is your Access Token added to the Postman collection and you can start with testing of Bisnode Credit Information API in the sandbox.
    ![image](https://user-images.githubusercontent.com/54436429/66764637-808bb000-eeaa-11e9-812e-c9cda243c885.png)

Happy testing!
    
  


