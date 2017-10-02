# Template

Brief description
## Example Usage

```java
// Java
MobileElement el = driver.findElementByAccessibilityId("SomeId");
el.click();

```
```python
# Python
el = self.driver.find_element_by_accessibility_id('SomeId')
el.click();

```
```javascript
// Javascript
// webdriver.io example
await driver.status();


// wd example
await driver.status();

```
```ruby
# Ruby
# Ruby Code here

```
```php
# PHP
// PHP Code here

```
```csharp
// C#
// CSharp Code here

```


## Description

An indepth description of what this command does


## Client Docs

* [Java](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/WebElement.html#click--)
* [Python](https://github.com/appium/python-client)
* [Javascript (WebdriverIO)](http://webdriver.io/index.html)
* [Javascript (WD)](https://github.com/admc/wd/releases)
* [Ruby](https://github.com/appium/ruby_lib/releases/latest)
* [PHP](https://github.com/appium/php-client/releases/latest-)
* [C#](https://github.com/appium/appium)

## Support

### Appium Server

|Platform|Driver|Platform Versions|Appium Version|Driver Version|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | 1.2 to 9.3 | 1.7 to 1.9 | 1.1 to 9.9 |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | 1.0 to 9.3 | All | All |
| Android | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | 8.0+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | 4.2+ | All | All |
| Mac | [Mac](/docs/en/drivers/mac.md) | ?+ | 1.6.4+ | All |

### Appium Clients 

|Language|Support|
|--------|-------|
|[Java](https://github.com/appium/java-client/releases/latest)| All |
|[Python](https://github.com/appium/python-client/releases/latest)| All |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| None |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| None |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All |
|[PHP](https://github.com/appium/php-client/releases/latest)| None |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| None |

## HTTP API Specifications

### Endpoint

`POST /wd/hub/session/:session_id/element/:element_id/click`

### URL Parameters

|name|description|
|----|-----------|
|session_id|ID of the session|
|element_id|ID of the element|

### JSON Parameters

|name|type|description|
|----|-----------|
| item | Object | Description of Item |
| item.1 | String | Item One description |

### Response

|name|type|description|
|----|----|-----------|
| build.version | string | A generic release label (i.e. "2.0rc3") |

## See Also

* [W3C Specification](https://www.w3.org/TR/webdriver/#element-click)
* [JSONWP Specification](https://github.com/SeleniumHQ/selenium/wiki/JsonWireProtocol#sessionsessionidelementidclick)
* [Google](http://www.google.com)