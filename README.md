# RectangleSVGComponent

![image](https://user-images.githubusercontent.com/86930618/162580500-b0d4b8e0-ad7c-4dc9-8dde-ea75f2e69d44.png)


Rectangle progress component for your canvas app!

This component has a number of input properties that you can use to customise the SVG without needing to edit the SVG code. 
It’s built of a few  controls – an image (where the SVG code is), a HTML control, and a couple of labels which means that it will not impact the loading time of your app at all. It allows you to visualise progress/utilisation of various activities – total annual leave days taken, total number of tasks completed, or items left in stock – it’s up to you and your use case!

◻ Value – this property specifies the ‘progress’ value. This could be X holidays taken, X tasks completed, X items in stock

◼ MaxValue – use this property to set the max value. This could be the total holiday allowance, total number of tasks for the project, total number of items etc.

◻ Percentage – there is already a formula in this property so you don’t need to adjust it! It will calculate the percentage of utilisation – value divided by max value and multiplied by 100.

◼ BackgroundTile – this is a boolean property (yes/no) to specify whether you would like the background tile to be visible or not,

◻ PercentageLabelColour – this property specifies the colour of the font of the percentage label.

◼ PercentageLabelFontSize – this property specifies the size of the percentage label.

◻ BorderRadius - this property specifies the border radius of the progress rectangle.

◼ LinealGradientHexValue1 and LinealGradientHexValue2 –  this property is responsible for the gradient of your progress bar, please enter hex values without ‘#’.

◻ BoxShadow – this property is another toggle. Set this to ‘on’ if you like to go the extra mile with your visuals – it will add box shadow to your SVG which will make it look more modern. Set this to off if you want your SVG to be ‘flat’.

◼ TileTitleFontSize –  this property is responsible for the font size of the tile label (e.g. 'Project Completion')

◻ Icon – this property is responsible for the logo in the component, this could be either an image within your app, or SVG code.

If you have any enhancement ideas, or experience any issues at all - please reach out to me either by raising an issue or getting in touch on my social media: LinkedIn - https://www.linkedin.com/in/kristine-kolodziejski-07b6a7212/ Twitter - @kristinekk94

Happy Power Apping 😊
