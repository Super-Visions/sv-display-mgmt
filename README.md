# Display Management

The module `sv-display-mgmt` is an [iTop][1] extension to add a new object class [Display](#display) to the [End user devices][2].
This new class can be used to document monitors, multimedia projectors, TV and smart boards.

## Installation

Place this in the `extensions` folder of your iTop instance and run iTop setup again.
Be sure to enable the extension during setup.

## Features

### Display

![Display icon](images/display.png) Parent: `PhysicalDevice`

* Size _(Integer)_ Size of the display in inches
* Type _(ExternalKey)_ [DisplayType](#displaytype)

### DisplayType

Parent: `Typology`

[1]:https://www.itophub.io/
[2]:https://www.itophub.io/wiki/page?id=latest:datamodel:itop-endusers-devices
