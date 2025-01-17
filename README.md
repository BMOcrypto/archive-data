
<a href="https://githubsfdeploy.herokuapp.com">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>



# Archive Data Demo

This project is part of a series of Salesforce Platform demos.

From <https://www.platformdemos.com> you can:

- Watch a video of this demo (3 minutes or less).
- Spin up your own instance of the demo in a free scratch org.
- Find related Trailhead content.
- Get high-resolution screenshots.

___

## Installation Instructions

1. [Create your own Dev Hub and setup SFDX](https://trailhead.salesforce.com/en/content/learn/modules/sfdx_app_dev/sfdx_app_dev_setup_dx).


2. Clone this repository:

```
git clone https://github.com/gabesumner/archive-data
cd archive-data
```

3. Install **shane-sfdx-plugins** (if you don't already have it)

  ```
  sfdx plugins:install shane-sfdx-plugins
  ```


4. Install **sfdx-migration-automatic** (if you don't already have it)

  ```
  sfdx plugins:install sfdx-migration-automatic
  ```

5. Run the startup script

  ```
  sh orgInit.sh
  ```

6. Check out the demo guide on [PlatformDemos.com](https://www.platformdemos.com) for the Archive Data Solution demo.
