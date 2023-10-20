## Checklist

- [ ] When you start making changes to the specification package after a release, open a new [Release Note Tracking](<INSERT URL TO RELEASE NOTE TEMPLATE>) issue.
- [ ] If you know what your release version will be, update the `#.#.#` accordingly. Otherwise leave it be for now (see "Repository Release" protocol for versioning information).
- [ ] Log all Updated / Template Fixes:
- [ ] Log all Specification / Reference Guide / Protocol Changes
- [ ] Right before release:
  - [ ] Update the issue release note `#.#.#` (see "Repository Release" protocol for versioning information).
  - [ ] Make sure the issue #number is mentioned in the new release notes
- [ ] After release:
  - [ ] Close the release note issue thread. It will remain linked to the release.

## Tips/Tricks

### Getting Started

Start with recording the changes in the release notes and updating the DataHarmonizer template. This will likely help you iron out the release version number which you can label the GitHub branch as when you go about update the Excel template.

### Reference Guide Class Level Tracking

You'll want to track the changes in the reference guide as you go. I.e. update the "Version Tracking" information within the sheet and in the release notes issue. If you are updating this after integrating all template changes, you can immediately put whatever the expected release number will be. If you aren't sure what the final release number is yet, use a placeholder of some sort (that doesn't appear anywhere else in these columns) and then use "Find and replace" to update it to the final value before final release preparation.

![replacing empty cells with "UPDATE"](https://github.com/cidgoh/GRDI_AMR_One_Health/assets/48695054/694c1df5-b2c2-414c-8b56-a8d65c1cac9b)

Select the three version columns as your range, and then open `Edit > Find and replace (Ctrl+H)`
Find your placeholder term (e.g. "UPDATE") and then replace with the release number (e.g. "7.7.5").

![using find and replace to replace "UPDATE" with "7.7.5"](https://github.com/cidgoh/GRDI_AMR_One_Health/assets/48695054/994e344b-d8c2-4136-8f0a-c638720b9f59)

![showing the cell change from "UPDATE" to "7.7.5"](https://github.com/cidgoh/GRDI_AMR_One_Health/assets/48695054/80b8efd8-9e54-43c9-9745-3c5613ed1321)

