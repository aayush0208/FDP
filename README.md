# FDP

A simple library to make your layout flexible for different screen sizes.

Step 1. Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  
Step 2. Add the dependency

     dependencies {
	        implementation 'com.github.aayush0208:FDP:v0.1'
	   }


Step 3. Implement like this

     android:layout_marginTop="@dimen/_40fdp"
     
Happy Coding :)
