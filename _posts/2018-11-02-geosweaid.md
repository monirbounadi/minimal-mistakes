---
layout: posts
title: "Mapping Swedish Aid Data"
last_modified_at: 2018-11-02
---

During my work on geocoding the Swedish aid data, I made a Shiny app. The app shows the spatial distribution of Swedish aid activities and aid disbursements at the national level by year. To the best of my knowledge, this is the first presentation of this kind. 

*Note:* The definition of an aid activity is a value on the variable [iati-identifier][iati-identifier] from the International Aid  Transparency Initiative (IATI) standard. Total aid disbursement is in USD and is not inflation-adjusted. I plan to make an update explaining the measurement of disbursement.  

<iframe src="https://monirbounadi.shinyapps.io/geoaidswe/" style="border:none;width:600px;height:700px;"></iframe>

[iati-identifier]: http://reference.iatistandard.org/202/activity-standard/iati-activities/iati-activity/iati-identifier/