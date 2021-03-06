# 8.3.8 (2017-07-05)
* Upgrade `ember-cli` to `2.12.3`


# 8.3.7 (2017-05-23)
* Fix https://github.com/ciena-frost/ember-frost-info-bar/issues/69
  * Specify min-height for info-bar to prevent firefox from ignoring height

# 8.3.6 (2017-05-10)
* **Updated** the secure auth tokens in `.travis.yml`


# 8.3.5 (2017-04-21)
* **Added** blueprint check

# 8.3.4 (2017-03-23)
* **Fixed** `ember` and `ember-cli` dependencies

# 8.3.3
* **Updated** the travis scripts used for bumping and publishing

# 8.3.2

* **Updated** Travis to test Chrome as well as Firefox.
* **Updated** testem to use custom reporter from `ember-test-utils`.
* **Updated** Travis to only publish when git tags are added in preparation for non-version bump pull requests.
* **Updated** linting to use linting tools from `ember-test-utils`.


# 8.3.1
* **Updated** integration/unit tests to remove the deprecated use of `describeComponent()`



# 8.3.0

* **Updated** class names to use prefix `frost-info-bar-` so they don't have collisions with other
components not using scoped class names.
* **Updated** component to extend component from `ember-frost-core` so we have standard hook and
spread support for a Frost component.


# 8.2.1

* **Upgraded** to test against Ember 2.11.


# 8.2.0

* **Added** additional builds to CI to make sure addon works with latest versions of Ember.
* **Removed** files from npm package that aren't necessary (all of the various config files).
* **Updated** dependencies to latest versions.


# 8.1.4
* **Fixed** missing icon on demo application

# 8.1.3
* **Updated** `ember-frost-notifier` to `^4.0.0`



# 8.1.2
* Fixed missing icon in dummy app



# 8.1.1
* Fix naming of icon pack


# 8.1.0
* Add icons related to the addon


# 8.0.0
Updated Dependencies to use version ^1.0.0 of ember-frost-core. None of the existing functionality
was broken so further modification was not required.


# 7.0.2
- **Added** test to verify mixin is present


# 7.0.1
- **Added/Updated** unit/integration tests to increase test coverage
- **Removed** unused `index` from template's control `each` section
- **Added** `{{if title}}` clause around `div` for `primary-title` class and `-title` hook

<!-- Reviewable:start -->
---
This change is [<img src="https://reviewable.io/review_button.svg" height="34" align="absmiddle" alt="Reviewable"/>](https://reviewable.io/reviews/ciena-frost/ember-frost-info-bar/45)
<!-- Reviewable:end -->


# 7.0.0
**update** node version.
**update** blueprint
**remove** mirage.


# 6.0.0
No CHANGELOG section found in Pull Request description.
Use a `# CHANGELOG` section in your Pull Request description to auto-populate the `CHANGELOG.md`

# 5.0.1

* Removed the unused dependency on liquid-fire

# 5.0.0

* **Updated** interface, now `controls` will take an array of components.
* **Updated** interface, now `title` and `summary` will take either component or string.
* **Added** `array` helper and `type-of` helper




# 4.0.1
- Call super init in index.js with applying context.

# 4.0.0
- Switched from block-slots to `(component)` helper.

# 3.1.1

* **Updated** `ember-hook` dependency in blueprint to latest version
* **Removed** unneeded configuration object for `ember-hook` since it will now work correctly
in the development environment.

<!-- Reviewable:start -->
---
This change is [<img src="https://reviewable.io/review_button.svg" height="34" align="absmiddle" alt="Reviewable"/>](https://reviewable.io/reviews/ciena-frost/ember-frost-info-bar/36)
<!-- Reviewable:end -->


# 3.1.0

* **Updated** Ember, Ember-CLI and Ember data to ~2.6.0
* **Updated** npm and bower dependencies
* **Added** `ember-prop-types` to the frost-info-bar component
* **Added** a default hook name for the frost-info-bar component
* **Added** hook names for different block-slot sections in the frost-info-bar component
* **Added** tests to validate the new hook names in the frost-info-bar component
* **Updated** README to explain usage of the hooks for the frost-info-bar component


# 3.0.2

- Updated ember-block-slots, fixed up icon css and fixed broken demo app

# 3.0.1
No CHANGELOG section found in Pull Request description.
Use a `# CHANGELOG` section in your Pull Request description to auto-populate the `CHANGELOG.md`

# 3.0.0
* **Fixed** upgrading repo to use block-slots >=1.0.0

# 2.1.1
* **Fixed** Usage of single quotes was updated to double quotes when setting a class in a div

<!-- Reviewable:start -->
---
This change is [<img src="https://reviewable.io/review_button.svg" height="35" align="absmiddle" alt="Reviewable"/>](https://reviewable.io/reviews/ciena-frost/ember-frost-info-bar/20)
<!-- Reviewable:end -->


# 2.1.0
No CHANGELOG section found in Pull Request description.
Use a `# CHANGELOG` section in your Pull Request description to auto-populate the `CHANGELOG.md`
