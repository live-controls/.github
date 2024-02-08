# Live Controls
Live Controls is a collection of libraries used for Laravel and Livewire. Some of the libraries won't need Laravel or Livewire, but the requirement of every library will be shown inside their own Readme.md file.

*Most of those libraries are NOT tested in a production scenario. They're made for it, but will be built while creating other projects.*

### Libraries
#### Utils (Battletested)
This library is used by some of the other libraries and will installed automatically over Composer if you install the other library, but you can use it as standalone if you want.

#### AutoAddress (Battletested)
This library automatically adds the street, city, state etc. to an areacode based on informations from CEPAberto and other libraries. This is the successor of AutoCEP and should be used instead.

#### Payment (Battletested)
This library includes helper classes for IUGU and PagSeguro. It is pretty much in alpha state and only the IUGU classes are battletested.

#### Storage (Battletested)
Simple Object Storage library, can be seen as a small extension to Laravels Storage class

#### Permissions (Battletested)
This library handles permissions from users and groups

#### Groups (Battletested)
This library handles groups of users

#### Alerts (Legacy)
This library includes a Sweet Alert implementation

#### Masks (Needs testing)
This library adds input masks based on iMask
