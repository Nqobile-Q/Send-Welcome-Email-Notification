 **Zoho CRM automation** written in **Zoho Deluge**.

The function automatically sends a Zoho Sign document to a new CRM Contact created through the SAPIN app.

## Overview

When a new Contact is created in Zoho CRM, the workflow:

1. Receives the CRM Contact ID.
2. Fetches the Contact record.
3. Reads the Contact's name and email address.
4. Retrieves the configured Zoho Sign template.
5. Adds the Contact as the signer.
6. Prepares the document for signature.
7. Sends the document to the Contact through Zoho Sign.

## Technology

- Zoho CRM
- Zoho Workflow Rules
- Zoho Sign
- Zoho Deluge
- SAPIN app

## Function Name

```deluge
automation.Send_SAPIN_Zoho_Sign_Document
