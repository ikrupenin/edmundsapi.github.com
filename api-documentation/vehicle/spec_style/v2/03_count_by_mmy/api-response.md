---
layout: api-documentation
title : 'Get Style Count by Car Make/Model/Year'
title_active_left_menu: "Spec: Style"
title_parent: Api documentation

amount_version: 2
title-endpoint: 'Get Style Count by Car Make/Model/Year'
spec: spec_style
version: v2
api: vehicle
dropdown-link: 'api/vehicle/v2/{make}/{model}/{year}/styles/count'


level: 4
description_edpoint: 'Get Style Count by Car Make/Model/Year'
title_md : Response format
number: 3

---

###Response format

	{
	  "stylesCount": {integer}
	}

| Property      | Description                         					| Visibility                |
|:--------------|:------------------------------------------------------|:------------------------- |
| stylesCount   | The count of styles									| Edmunds, Partners, Public |

