---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const setOrder = Content-Type: application/json
Content-length: 90

{
  newAssignmentOrder: {
    order: [
        "City",
        "extension_GUID_ShoeSize"
    ]
  }
};

let res = await client.api('/identity/b2cUserFlows/{id}/userAttributeAssignments/setOrder')
	.version('beta')
	.post(setOrder);

```