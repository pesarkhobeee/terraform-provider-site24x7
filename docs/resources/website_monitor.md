---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "site24x7_website_monitor Resource - terraform-provider-site24x7"
subcategory: ""
description: |-
  
---

# site24x7_website_monitor (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **display_name** (String)
- **website** (String)

### Optional

- **actions** (Map of String)
- **auth_pass** (String)
- **auth_user** (String)
- **check_frequency** (Number)
- **custom_headers** (Map of String)
- **http_method** (String)
- **id** (String) The ID of this resource.
- **location_profile_id** (String)
- **match_case** (Boolean)
- **match_regex_severity** (Number)
- **match_regex_value** (String)
- **matching_keyword_severity** (Number)
- **matching_keyword_value** (String)
- **monitor_groups** (List of String)
- **notification_profile_id** (String)
- **threshold_profile_id** (String)
- **timeout** (Number)
- **unmatching_keyword_severity** (Number)
- **unmatching_keyword_value** (String)
- **up_status_codes** (String)
- **use_name_server** (Boolean)
- **user_agent** (String)
- **user_group_ids** (List of String)

