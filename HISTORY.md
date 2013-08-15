# Changelog

## 2.0.1

* Fix to_xml_params method [bradleypriest]

## 2.0.0

* New name for the gem

## 1.4.0

* Add accessor for invoices
* Add accessor for last successful invoice

## 1.3.6

* Modernize packaging
* Improve handling of bad credentials

## 1.3.5

* Move to Spreedly repo.

## 1.3.4

* Add result body to comp validation failure. [ntalbott]

## 1.3.3

* Add support for return_url in Spreedly.edit_subscriber_url [jjthrash]
* Add support for return_url in Spreedly.subscribe_url [jjthrash]

## 1.3.2

* Added methods on subscriber: update, allow_free_trial,
  add_fee [mateuszzawisza]
* Fixing tests: generate spreedly url and edit url working with all
  site names [mateuszzawisza]
* Add support for pre-population of the subscribe page via the subscribe
  url. [davemcp]

## 1.3.1

* Handle new error reporting when creating a subscriber.
* Use a more sane way of setting attributes in the mock, and make plans have a
  plan type [seancribbs].
* Allow optional arguments to be passed when creating subscribers [jaknowlden].

## 1.3.0 / 2009-06-04

* Properly handle invalid Subscriber lookup [karnowski].
* Added support for stopping auto renew [scottmotte, dsimard].

## 1.2.2 / 2009-05-11

* Fixed an error in the README [karnowski].

## 1.2.1 / 2009-04-30

* A few documentation tweaks.

## 1.2.0 / 2009-04-30

* Added mock support for Subscriber#activate_free_trial [scottmotte].
* Added tests for Subscriber#activate_free_trial.

## 1.1.0 / 2009-04-24

* Compatibility with the latest hoe and HTTParty [seancribbs].
* Added Subscriber.delete! [scottmotte].
* Added Subscriber#activate_free_trial [scottmotte].

## 1.0.0 / 2009-03-17

* Initial release.

