# Data in Computer : 
> Any Data in computer is computed and stored in the form of binary Symbols/Digits (ie. 1's and 0's)
* Data is a peice of Information. 
* Everything is a data , Eg: Person Name, Phone Number, Time of the meeting, Name of the File, Sets of pull up's today, Songs, Alphabets, Numbers, Symbols.

<!--
Data
$ Data in computer hardware.
$ Representation of data in computer.
$ Input and Output Data.
$ Input and output Devices.
$ How data is stored and computed
-->
* In Computer, there are primarily two ways data is used: 
    1. Input Data.
    2. Output Data.
1. __Input Data :__
    * Any Data that used by computer (given as input) is called input data
    * Eg :  1. Voice/Songs/Music from microphone or files to computer processing.
            2. Alphabets,Numbers, Symbols, Event keys from Keybord and Mouse.
          
2. __Output Data :__
    * Any Data the Comes out of the computer is called Output Data.
    * Eg : 1. Songs, voice, Music To loudspeaker.
           2. Alphabets, Numbers, Symbols To Display screen.
    
###### How Data is stored in Computers :
* Any kind of Data is completly stored as series of Binary numbers.
* What are the Data we have in real world ? : 
    1. Numbers &nbsp; &nbsp; {0,1,2,3,4,5,6,7,8,9}
    2. Letters &nbsp; &nbsp; {A,B,C,D,E,F,G,H,I,J,K,L,M,N,O,P,Q,R,S,T,U,V,W,X,Y,Z,a,b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u,v,w,x,y,z}
    3. Symbols &nbsp; &nbsp;  {!, @, #, $, %, ^ , &, * , (, ), _, -, +, =, \, <, >, :, ;, {, }, etc }
    4. Images &nbsp; &nbsp; {img1.jpg, etc}
    5. Audio &nbsp; &nbsp; {Rec01.mp3, etc}
    6. Video &nbsp; &nbsp; {Movie.mp4. etc}
    etc. <br/>
    We will discuss each and how it stored as binary numbers in computers.<br/><br/><br/>
* __Numbers :__
    * Any kind of Whole Numbers can be stored in computer memory by converting it into Binary Numbers by process of encoding.
    * Decimal numbers to Binary Conversion : Converting a Decimals into Binary numbers is automated in computers.
    * Converting Decimal Numbers to Binary Numbers is by Encoding.
    * Converting Binary Numbers to Decimal Numbers is by Decoding.
    * Encoding is Process of converting original data from one form to another, like from Decimal to Binary.
    * Decoding is Reverse Process of Encoding, it retrieves Originl data from encoded data, like from Binary to Decimal.
    * Decimals numbers are Integers, Fractions, etc.
    > Eg : <br/>
        (int)  &nbsp;  &nbsp; &nbsp; &nbsp;  = (binary) . '=' indicates 'Equivalence' <br/>
         24    &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;    = 11000 <br/>
       2022    &nbsp; &nbsp; &nbsp;  = 11111100110 <br/>
      18.63    &nbsp;  &nbsp; &nbsp; = 10010.101 <br/>
    3.14159  &nbsp;  = 11.001001 <br/>
    * Even Negative Numbers can be Converted into Binary.
    * Its possible to Convert Decimal Back from Binary and its Known as Binary to decimal Conversion through Decoding
    * The Numbers is converted into Decimal is stored. and it retrieved back as Decimal Numbers automatically by computers.
   <br/>
 <img src="https://github.com/prashanthprabhu24/LearnPython/raw/main/Dust/file2_6.jpg" width="700" height="300"> <br/><br/>
* __Letters and Symbols :__
    * Any English Alphabets / Special symbols/greek symbols/Other languages can be converted into Binary.
    * ASCII : American Standard Code for Information Interchange. This converts(encodes) alphabets/symbols into decimal numbers and then indirectly to binary.
    > Eg : <br/>
        ASCII code of "A" is 65 and 65 is encoded in binary as 1000001.
<img src="https://github.com/prashanthprabhu24/LearnPython/raw/main/Dust/file2_7.jpg" width="700" height="300"> <br/><br/>
* __Images :__ 
    * Images are the pictures , these pictures are made up of matrix of pixels.
    * Pixel is a digital image length and is uses to measure the quality of images and camera's.
    * A single image is considered as a file, hence a image file has an file name and an extention as '.jpg', '.JPEG', '.png', '.bmp', '.gif', etc.
    > (Redmi Note 7 Pro smart phone has 48Mp(48 mega pixel) camera)<br/>
<img src="https://github.com/prashanthprabhu24/LearnPython/raw/main/Dust/file2_8.jpg" width="180" height="200"> &nbsp;&nbsp;&nbsp;<img src="https://github.com/prashanthprabhu24/LearnPython/raw/main/Dust/file2_9.jpg" width="500" height="200"> <br/><br/>
    * The person in the above pic is 16th U.S President , Abraham Lincoln. 
    * The Computer takes the Image and  makes a matrix of pixel values and stores the values in the same sequence in binary format.
    * This Encoding of image into matrix value is taken care of system softwares.
    * Images can be made of diffrent colours and shades and in diffrent intensity, all this values are represented for each and every pixels of entire image in the matrix.
    * This colour representation of an indivisual pixels are known as RGB value. R for Red, G for Green, B for Blues.
    * By this only 3 colours, we can achieve any colours by combining 2 or 3 colours in appropriate values. 
    * These values of [R,G,B] ranges from [0,0,0] to [255,255,255] and also considering Intensity(A) of Pixel we now give values for [R,G,B,A].
    * In [R,G,B,A] , if A = 0, means no intensity, which makes pixel looks black irrespective of RGB values.
    * In [R,G,B,A] , if A = 256, means Very high intensity, which makes pixel looks too bright as white irrespective of RGB values.
    * Hence, A values is always inbetween 0 to 255 unless we need black or while pixel colour. 

* __Audio :__ 
    * Musics, Songs, Call recordings, voices, noise sounds are all treated as Signals in nature.
    * Sounds in nature is a wave form, which is analog known as analog waveform.
    * In that wave form we are intrested in the value of the highest point on the wave (Crest) and Lowest point (Trough) over the time.
    * But saving all these values of the audio wave for very long time ( even for a minutes) will occupy large amount of system memory.
    * Hence to avoid this draw back, we assign a range to the wave form over amplitute and find on which range the Crest/Trough is on the perticula time.
    * This method is called Digitization.
    * Digitization is the process of converting information into a digital format.
    * Now , Audio in computers is exists in digital form. This digital form of audio is broken down into thousands of samples per second.
    * Each sound samples is stored as binary data in Computer.<br/>
* __Video :__ 
    * Videos are the sequence of images with an audio.
    * Seperating the Audio from the video and Digitizing the Audio into binary form.
    * Now the video is considered as a multiple image frames. More the frames per second (fps), more the quality of video.
    * Each and indivisual frames(images) in stored in binary format in same order of frame occurance.
    * Even this way can take lots of space, and even this was the earlier approach to store videos. 
    * But Technology has improved in storing videos with lesser space than first approach, this new method is compression.
    
    
