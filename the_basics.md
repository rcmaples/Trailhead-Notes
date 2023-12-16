# Salesforce Trailhead Notes

## Use Cases:

By creating a single custom object, you can totally change how your organization collaborates. High impact, low effort. As you start building with the platform, keep your eye out for processes with:

- Heavy email collaboration
- Reliance on spreadsheets
- Shared local documents
- Time-intensive, repetitive manual steps
- Impact on only a few departments (you want to minimize the number of stakeholders while you’re still learning)

Processes with these traits are great candidates for early projects on the Salesforce platform.

### Human Resources

You could build a custom app to help HR:

- List job openings
- Store applicants
- Send automated reminders to hiring managers
- store orientation and training plans
- manage equipment offers
- track time off

### IT

When your support ticketing system is in the same place as your CRM you get a lot of bennies since all of the information is already there.

- Create reports and dashboards to aggregate and analyze requests.
- Send confirmation emails when requests are received, completed, or updated.
- Queue incoming requests.
- Create custom forms for employee requests and create a knowledge base for common issues.
- Track employee hardware assets.

**Resources**

- [Salesforce Platform App Idea Guide](https://www.salesforce.com/form/conf/platform-dept-appideaguide.jsp?leadcreated=true&chapter=&videoId=&__element=pre&DriverCampaignId=70130000000sUVq&player=&redirect=true&FormCampaignId=70130000000lcUK&playlistId=&mcloudHandlingInstructions=&landing_page=%2Fform%2Fpdf%2Fplatform-dept-appideaguide.jsp&nurture=&_gl=1*m4vlw4*_ga*MzE5NDkyMTE0LjE2OTc4OTQ4MzI.*_ga_H6M98GGB18*MTcwMjc0MzcyNS4zLjEuMTcwMjc0OTEzOS4wLjAuMA..*_gcl_au*MTE2NTA0MDc0NC4xNzAyNzM1MTQx&_ga=2.140119347.1807080116.1702735141-319492114.1697894832)

- [Salesforce Platform Customer Showcase](https://www.salesforce.com/products/platform/customer-stories/?_gl=1*75rwjm*_ga*MzE5NDkyMTE0LjE2OTc4OTQ4MzI.*_ga_H6M98GGB18*MTcwMjc0MzcyNS4zLjEuMTcwMjc0OTEzOS4wLjAuMA..*_gcl_au*MTE2NTA0MDc0NC4xNzAyNzM1MTQx&_ga=2.173040803.1807080116.1702735141-319492114.1697894832)

## The Basics:

- Orgs:

  - Short for Organization; it is a specific instance of Salesforce. Companies can have one or more orgs.

- Apps:

  - Contains a set of objects, fields, and other functionality. Waffle Menu will tell you which app you're using.

- Objects:

  - Standard:
    - Accounts
    - Contacts
    - Leads
  - Custom:

    - "property" (for real estate use case)
    - "currency"
    - etc...

      Every time you create a custom object, you automatically get something called Chatter feed tracking. Chatter feed tracking provides a way for multiple people to comment and collaborate on a particular record. The discussions and decisions are stored on the record so everyone can stay up to date on important decisions.

- Records:

  - Rows in the object database tables. The actual data associated with an object.

- Fields:

  - The columns of the object database tables.

Ex:

```
"DreamHouse" app
	- Property Object
		- Fields:
			- City
			- Price
			- Beds
			- Baths
			- Title
			- Property Name
			- Address
```

---

<br>
<br>

## Customizing Salesforce

- Declaritive Development is the "no-code" way to build and customize Salesforce. You use forms, and d-n-d tools.

- Progrmatic Development uses things like Lightning components and requires coding.
