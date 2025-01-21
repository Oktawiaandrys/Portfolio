## ✨ Project: adding a new feature for setting the order of catalogs in the admin panel
### Overview: 
A new section with functionality needs to be added to the admin panel.
The functionality should allow manual management of the order of catalogs displayed in the mobile app's store view. During implementation, the existing and overarching "pinning" functionality should be considered, which remains unchanged.

- #### Current Functionality:
  * Catalogs are currently sorted by default from the newest to the oldest, without the ability to change their order, but with the option to pin a maximum of 5 catalogs in slots 1 to 5.
  * The catalog limit is 20.
  * Pinning a catalog overwrites its (default) order, and this behavior remains unchanged. This means that if, after implementing the new functionality, the order is different from the default, pinning the catalog should still overwrite that order.
  * Pinning a catalog excludes the ability to manually manage the order of catalogs, but manually setting the order does not exclude the option of pinning catalogs.
 
- #### New Functionality – Manual Order Setting:
   * If no catalogs are pinned, the user will be able to manually set the order of the catalogs.
   * When managing the order, the user will see a list of catalogs sorted from newest to oldest (default order) or according to the manually set order (custom order).
   * After making changes to the order, the user must save them by clicking the “Save order” button.

- #### Default Order:
    * If no catalog has been pinned, the default order will be sorted from the newest to the oldest.

- #### Custom Order:
   * Custom order will be available after the new functionality is implemented.
   * If no catalog has been pinned, the user will initially see the default order, and any order other than the default will be considered a custom order.

### Acceptance criteria and test plan 
* [This document](https://drive.google.com/file/d/1SGFOp4JpKDVWT8OdnoX8MIv393rdJfWx/view?usp=sharing) outlines the purpose, scope, and approach for testing.
It defines the acceptance criteria, testing strategies to ensure the feature meets the required standards.

### Test cases 
*  Test cases for the [new feature](https://drive.google.com/file/d/1_K6bmKztZoZFwznyxe38dsmWO7w7Itf7/view?usp=sharing)

## 🐛 Bug report
<b>Issue Summary:</b> a contact form message was received via email, but it is not dispalyed correctly and contains content errors.
 * [Reported bug ](https://drive.google.com/file/d/1djsoN9irGKnp7Ly22Q5aFSTFmwx9CJOE/view?usp=sharing) of a contact form that has been recieved via mail.



