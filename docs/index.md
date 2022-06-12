---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "teampasswordmanager Provider"
subcategory: ""
description: |-
  
---

# teampasswordmanager Provider





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `host` (String) Host of the team password manager. (ie: http://localhost:8081)
- `private_key` (String, Sensitive) Private key from http://{ host }/index.php/user_info/api_keys
- `public_key` (String, Sensitive) Public key from http://{ host }/index.php/user_info/api_keys