---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "teampasswordmanager_group Data Source - terraform-provider-teampasswordmanager"
subcategory: ""
description: |-
  Retrieve group information.
---

# teampasswordmanager_group (Data Source)

Retrieve group information.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `id` (String) Group ID.

### Read-Only

- `created_by` (List of Object) User which created the resource. (see [below for nested schema](#nestedatt--created_by))
- `created_on` (String) Date when the resource was created.
- `group_dn` (String) LDAP group's distinguished name (DN)
- `is_ldap` (Boolean) Whether the group is a LDAP group.
- `ldap_server_id` (Number) LDAP server id
- `name` (String) Name of the group.
- `updated_by` (List of Object) User which updated the resource. (see [below for nested schema](#nestedatt--updated_by))
- `updated_on` (String) Date when resource was updated.
- `users` (List of Object) Users of the group. (see [below for nested schema](#nestedatt--users))

<a id="nestedatt--created_by"></a>
### Nested Schema for `created_by`

Read-Only:

- `email_address` (String)
- `id` (Number)
- `name` (String)
- `role` (String)
- `username` (String)


<a id="nestedatt--updated_by"></a>
### Nested Schema for `updated_by`

Read-Only:

- `email_address` (String)
- `id` (Number)
- `name` (String)
- `role` (String)
- `username` (String)


<a id="nestedatt--users"></a>
### Nested Schema for `users`

Read-Only:

- `email_address` (String)
- `id` (Number)
- `name` (String)
- `role` (String)
- `username` (String)

