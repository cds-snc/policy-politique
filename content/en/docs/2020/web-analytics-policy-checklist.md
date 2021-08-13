---
title: "CDS Web Analytics Policy Checklist"
description: "The goal of this checklist is to make it easy for any CDS delivery team to make sure their service’s use of web analytics is in line with the Standard on Privacy and Web Analytics."
date: 2020-06-22
datePublished: 2021-08-10
author: "Sam Burton, Victoria Chan"
draft: false
---

**The goal of this checklist** is to make it easy for any CDS delivery team to make sure their service’s use of web analytics is in line with the [Standard on Privacy and Web Analytics (SPWA)](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=26761).

**Questions?** Ask the policy advisor on your delivery team, or anyone on the CDS policy team! #policy on Slack is a great place to start.

**IP anonymization is enabled.** The SPWA requires that we enable IP anonymization for any web analytics tool we use, so that it does not store personal information.

_Google Analytics:_

* To enable anonymization, you need to modify the product code that loads GA. The approach varies depending on how GA is integrated into the product. Google has [a site describing its IP anonymization process, with some links describing how to enable it](https://support.google.com/analytics/answer/2763052?hl=en). 
* Once anonymization is enabled, you can verify that the product is anonymizing IP addresses:
    1. Load the product’s site in either Chrome or Firefox.
    2. Right click on the page and choose “Inspect” or “Inspect element” in the menu that appears.
    3. A new window should appear. This is the developer tools window. Navigate to the “Network” tab and refresh the product site to load new data. (This tab lists all the resources loaded to display a webpage.)
    4. In the Network tab’s filter box, type “collect”. There should now be one entry in the list, something that starts like “collect?v=1&”. Select it.
    5. In Chrome, choose the “Headers” sub-tab and scroll to the “Query String Parameters” section. In Firefox, choose the “Params” sub-tab. You want to see “aip: 1” in the list. If it’s there, IP anonymization is enabled!

**All other analytics options that collect personal information are disabled**

_Google Analytics:_

* This includes disabling demographic data (eg. extrapolates and stores info re: age, gender of users). 
* Review [Best practices to avoid sending Personally Identifiable Information](https://support.google.com/analytics/answer/6366371?hl=en&ref_topic=2919631) with a developer on your team to ensure no personally identifiable information is inadvertently being transmitted to Google.

**Data retention period is set for max 6 months, or the shortest  option available**

_Google Analytics:_

* Set data retention period at 14 months. Google Analytics doesn't allow a retention period shorter than this, and most of the data collected by GA is exempt from the 6 month retention limit because it's aggregated.

**The service’s privacy notice meets all of the following requirements, as set out in Appendix B of the [Standard on Privacy and Web Analytics](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=26761):**

* A statement setting out the legislative authority for the collection of this information.
* An explanation of what Web analytics is and the purposes for use of Web analytics tools by the institution.
* A statement as to what specific personal information, including the IP address, is being automatically collected from visitors by the government institution.
* A statement advising visitors as to whether the Internet Protocol (IP) address and other data in digital markers is being collected and used internally by the institution for the purpose of Web analytics or is being disclosed or transmitted externally to a third party for that purpose.
* In cases where the IP address and other data in digital markers is disclosed or transmitted to a third party, an explanation of how the privacy of visitors to Government of Canada websites is being safeguarded through, at a minimum, the activation of the third-party anonymization feature whereby the third party depersonalizes the IP address.
* If data disclosed or transmitted for Web analytics is going outside of Canada, for example to the United States, a statement to that effect along with reference to any governing legislation that the information might be subject to, for example the[ USA Patriot Act](http://www.fincen.gov/statutes_regs/patriot/).
* A statement as to the maximum retention period for any personal information collected in relation to Web analytics. 

**Decide if/when to stop collecting data through a CDS-owned analytics platform**

* CDS may or may not continue to collect analytics data after a service is transitioned to a partner. 
* As long as CDS is collecting analytics data (eg. via a CDS-owned instance of Google Analytics), CDS' collection authority must remain in the privacy statement.
