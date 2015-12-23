# Fuelphp \Image::crop_dim($x,$y,$w,$h)
This version of FuelPHP Image class have a new method for cropping images.

# How to use:

> \Image::crop_dim() accepts 4 params.

	 - @param   integer  $x   X-Coordinate for first set.
	 - @param   integer  $y   Y-Coordinate for first set.
	 - @param   integer  $w   W-Width for cropping.
	 - @param   integer  $h   H-Height for cropping.

### Installation

  > Copy the Fuel\Core\Image Folder from this repository and replace your existing Fuelphp project folder. (or clone it)

### Usage
	<!-- Load the image first, then call crop_dim() function in order to crop your image with your specific cords and dimensions -->
	
	$driver = \Image::load("Path/to/Image")
	->crop_dim($x,$y,$w,$h) //crop_dim($x,$y,$w,$h)
	
	<!-- Save the cropped image using save() fuelphp function (check the fuelphp DOCS:#/method_save) -->
	->save("FILENAME", "755"); //save($filename = null, $permissions = null);
	

	 
