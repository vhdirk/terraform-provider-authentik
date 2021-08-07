---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "authentik_policy_hibp Resource - terraform-provider-authentik"
subcategory: ""
description: |-
  
---

# authentik_policy_hibp (Resource)



## Example Usage

```terraform
# Create haveibeenpwned.com policy

resource "authentik_policy_hibp" "name" {
  name = "hibp"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String)

### Optional

- **allowed_count** (Number) Defaults to `1`.
- **execution_logging** (Boolean) Defaults to `false`.
- **id** (String) The ID of this resource.
- **password_field** (String) Defaults to `password`.

