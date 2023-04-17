# Nonprofit-Cloud-Scratch
Generates a scratch org based on the shape of the Nonprofit Trial Org. It also includes a Platform license

## Development
To work on this project in a scratch org:

1. [Set up CumulusCI](https://cumulusci.readthedocs.io/en/latest/tutorial.html) (if you haven't already)
2. Run `cci flow run dev_org --org dev` to deploy this project.
3. Run `cci org browser dev` to open the org in your browser.
4. Assign your user the approriate Nonprofit Cloud permission sets (use a Nonprofit Trial Org user as a reference)
5. Manually activate features
   - Search "Program and Case Management" in Setup
   - Under that heading, you should see various features options (ex. "Care Plan Settings", etc.)
   - Click the desired feature and activate it