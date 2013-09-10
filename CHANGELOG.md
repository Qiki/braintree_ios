## 2.1.2

* Add approvedPaymentMethodWithCodeAndCard helper method. This is similar to approvedPaymentMethodWithCode, but returns an object that contains additional information about the card referenced by the payment method code. 

## 2.1.1

* Rename VTClient method, "+ (VTClient *)sharedClient;" to "+ (VTClient *)sharedVTClient;" to avoid Apple's newly-introduced static analysis flag.
* Fix namespacing compilation error with TTTAttributedLabel.

## 2.1.0

* Library is renamed to "braintree_ios".
* iOS 7 Support
* New framework requirement: Please add AdSupport.framework, CoreTelephony.framework and CoreText.framework to "Link Binary with Libraries" under "Build Phases".
* New VTClient initializers that include "customerEmail" parameter, please see VTClient.h

## 2.0.3

* Centers modals to fit different screen sizes.
* Sets VTCheckbox height dynamically based on locale. (default English height is 46px)

## 2.0.2

* Fixes bug where some users could not enter Maestro or Union Pay cards of variable length
* Fixes crash where non-ARC users could see a crash when using BTPaymentCardUtils
* Resolves UI discrepancy where some cards could be displayed on the same session after the user logs out
* Smooths modal entry and dismissal transitions

## 2.0.1

* Add to CocoaPods

## 2.0.0

* Adds support for Venmo Touch.
* Library is renamed to "braintree-ios".

## 1.1.0

* Library now uses ARC.

## 1.0.1

* Bugfix for encrypted string format.

## 1.0.0

* Initial release.