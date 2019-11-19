# LocationUtils


### Developed by
[Softpal](https://www.github.com/softpal)

[![](https://jitpack.io/v/softpal/DateTimeUtils.svg)](https://jitpack.io/#softpal/DateTimeUtils)


**Features**

Used to Get the current location of mobile user.


## Installation

Add repository url and dependency in application module gradle file:
  
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
	
    
    
### Gradle
[![](https://jitpack.io/v/softpal/DateTimeUtils.svg)](https://jitpack.io/#softpal/DateTimeUtils)
```javascript
dependencies {
    implementation 'com.github.softpal:LocationUtils:1.0'
}
```


## Usage

### 1. Get Current Location

```javascript
        // Call the method by passing date in required format
       Location location = LocationUtils.getMyLocation(MainActivity.this);
       
       location.getLatitude();
       location.getLongitude();
```
