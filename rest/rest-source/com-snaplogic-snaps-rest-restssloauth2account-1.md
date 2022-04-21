# Configure your REST In-memory OAuth2 account

Enter the following details for your REST In-memory OAuth2 account:

* **Label:** Enter a unique name to help identify your REST In-memory OAuth2 account in Flows. For example, _rest\_sales\_account_, if you are part of the sales team.
* **Client ID:** Enter the client ID associated with your account. You can create the client ID as advised by your application provider. For example, _88a731111-07k1-4714-xz5a-de111aaa9a5e_
* **Client Secret**: Enter the client secret associated with your account. You can create the client secret as advised by your application provider.
* **Header authenticated**: Select this checkbox to indicate that the endpoint uses bearer authentication in the header.
* **OAuth2 Endpoint**: Enter the URL of the endpoint that authorizes the application.
* **OAuth2 Token**: Enter the URL of the endpoint that retrieves the token for an authenticated account.
* **Grant Type**: By default, this account uses **Client Credentials** Grant Type to obtain an access token using the Client ID and Client secret through the token endpoint URL.
* **Token endpoint config**: Use this fieldset to provide custom properties for the OAuth2 token endpoint. Click the + or - icons to respectively add or remove configuration rows:&#x20;
  * **Token endpoint parameter**: Defines an optional token endpoint parameter.
  * **Token endpoint parameter value**: The value associated with the optional endpoint parameter defined above.
* **Auth endpoint config**: Use this fieldset to provide custom properties for the OAuth2 auth endpoint. Click the + or - icons to respectively add or remove configuration rows. This fieldset comprises the following fields:
  * **Authentication parameter**: Defines an optional authorization endpoint parameter.
  * **Authentication parameter value**: The value associated with the optional authorization endpoint parameter defined above.
* **Auto-refresh token**: Select this checkbox to refresh the token automatically using the refresh token, if the property is enabled. If this property is deselected, the token expires and is not refreshed automatically.
* **Authorize:** Click it **** to authorize the REST OAuth2 SSL account using the credentials provided.
* **Send Client Data as Basic Auth header**: Select this checkbox when you want to send the client information as a header to the OAuth endpoint.
* Click any one of the following:
  * **Apply** to save your account information in Flows.
  * **Cancel** to return to the previous screen.
