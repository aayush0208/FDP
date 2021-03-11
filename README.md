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
	        implementation 'com.github.aayush0208:FDP:0.2'
	   }


Step 3. Implement like this

     // For margin or width use _fdp
     android:layout_marginTop="@dimen/_40fdp"
     
     // For text size use _fsp
     android:textSize = "@dimen/_16fsp"
     
     
     
     
Without FDP

<img src="https://user-images.githubusercontent.com/21282839/110767682-87277e00-827c-11eb-8c3f-ce0f06e901ca.png" width="20%" height="20%">
<img src="https://user-images.githubusercontent.com/21282839/110767702-8b539b80-827c-11eb-9e27-37c25eab1216.png" width="20%" height="20%">
<img src="https://user-images.githubusercontent.com/21282839/110767716-8db5f580-827c-11eb-9e7f-210d6afb1ca8.png" width="20%" height="20%">


With FDP 
<img src="https://user-images.githubusercontent.com/21282839/110767771-9dcdd500-827c-11eb-8b2c-cf741267e317.png" width="20%" height="20%">
<img src="https://user-images.githubusercontent.com/21282839/110767780-a0302f00-827c-11eb-869d-3e78b6feafeb.png" width="20%" height="20%">
<img src="https://user-images.githubusercontent.com/21282839/110767791-a1615c00-827c-11eb-98c7-423185551b4b.png" width="20%" height="20%">

     
Happy Coding :)
