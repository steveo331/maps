# Riskrieg | Maps
Official Riskrieg Maps

# Submission

Never used GitHub before? Please read [this](https://guides.github.com/activities/hello-world/) first in order to gain a basic understanding of how GitHub works.
Next, you may want to use [GitHub Desktop](https://desktop.github.com/) which will allow you to easily clone this repository and make edits on your local filesystem.

Now, assuming you have a basic understanding of GitHub, the process is simple!

## Steps

1. Fork this repository.
2. Clone your fork.
3. Add your map file that you exported from the [official Riskrieg map editor](https://github.com/Riskrieg/map-editor).
4. Add your map options file to the 'options' folder.
5. Submit a pull request.

That's it! For definitions of the above terms, please read below.


# Definitions

## Rkm File / Map File
This is the file with the `.rkm` extension that you exported from the [official Riskrieg map editor](https://github.com/Riskrieg/map-editor).


## Options File
This is the file with the `.json` extension that contains information that may need to change on-the-fly.

### Availability
This defines the availability of the map. Valid values are `AVAILABLE`, `RESTRICTED`, `COMING_SOON`, and `UNAVAILABLE`.

### Alignment
This defines where the interface should show up on the map.

Valid **vertical** values are `TOP`, `MIDDLE`, and `BOTTOM`.

Valid **horizontal** values are `LEFT`, `CENTER`, and `RIGHT`.
