# Multi-Class CNN (Fruits-262)

The following fruit types/labels/clades are included: abiu, acai, acerola, ackee, alligator apple, ambarella, 
apple, apricot, araza, avocado, bael, banana, barbadine, barberry, bayberry, beach plum, bearberry, bell pepper, betel nut, bignay, 
bilimbi, bitter gourd, black berry, black cherry, black currant, black mullberry, black sapote, blueberry, bolwarra, bottle gourd, brazil nut, bread fruit, 
buddha s hand, buffaloberry, burdekin plum, burmese grape, caimito, camu camu, canistel, cantaloupe, cape gooseberry, carambola, cardon, cashew, cedar bay cherry, 
cempedak, ceylon gooseberry, che, chenet, cherimoya, cherry, chico, chokeberry, clementine, cloudberry, cluster fig, cocoa bean, coconut, coffee, common buckthorn, 
corn kernel, cornelian cherry, crab apple, cranberry, crowberry, cupuacu, custard apple, damson, date, desert fig, desert lime, dewberry, dragonfruit, durian, eggplant, 
elderberry, elephant apple, emblic, entawak, etrog, feijoa, fibrous satinash, fig, finger lime, galia melon, gandaria, genipap, goji, gooseberry, goumi, grape,
grapefruit, greengage, grenadilla, guanabana, guarana, guava, guavaberry, hackberry, hard kiwi.... and many more.

![img](https://raw.githubusercontent.com/Hrushi11/Blogs-Repository/main/Multi-Class%20CNN%20(Fruits%20262)/Images/random%20image.png)

## Some insights from the project
![IMG1](https://raw.githubusercontent.com/Hrushi11/Blogs-Repository/main/Multi-Class%20CNN%20(Fruits%20262)/Images/pred%202.jpg)
![img](https://raw.githubusercontent.com/Hrushi11/Blogs-Repository/main/Multi-Class%20CNN%20(Fruits%20262)/Images/pred%203.jpg)

## Data set Properties
Dataset Properties
Total number of images: 225,640.

Number of classes: 262 fruits.

Number of images per label: Average: 861, Median: 1007, StDev: 276. (Initial target was 1,000 per label)

Image Width: Average: 213, Median: 209, StDev: 19.

Image Height: Average: 262, Median: 255, StDev: 30.

Missing Images from the initial 1,000 target: Average: 580, Median: 567, StDev: 258.

Format: a directory name represents a label and in each directory all the image data under the said label 
(the images are numbered but there might be missing numbers. The "renumber.py" script, if run, will fix the number gap problem).

Different varieties of the same fruit are generally stored in the same directory (Example: green, yellow and red apple).

The fruit images present in the dataset can contain the fruit in all the stages of its life and also can contain slices of the fruit.

Images contain at least 50% fruit information (according to the manual filtering selection paradigm).

The background of the images can be anything (due to the nature of the data): monochromatic backgrounds, human hands, natural habitats of the fruit, leaves etc.

There are no duplicate images but there are some images (of the same label) with a high degree of similarity.

Images can contain small watermarks.

Some fruits which had between 50-100 usable images still remain in the dataset, but can be discarded for a better balance and lesser variety. 
This is also one big reason for the high variance in the missing images statistic provided above.

![IMG](https://raw.githubusercontent.com/Hrushi11/Blogs-Repository/main/Multi-Class%20CNN%20(Fruits%20262)/Images/all%203.png)
