# Avolites Titan Reaper Import Widget

## Introduction

This widget designed to work with Avolites WebAPI allows you to import a cuepoint CSV cue file into the current Titan show. The expected CSV column format is:  
  
"Track","Type","Position","Cue No","Label","Fade"
  
The first line of the CSV file should contain headers.  

This is based on someone elses code hosted here https://owaits.github.io/avolites-reaperImport, 
this is a fork of that code with some magor changes to allow me to use it in the way i need to with Cue Point, 

  
## Getting Started

We assume that you already have a working Avolites Console that is networked and accessible from this PC or another PC you run this widget on.  
  
Step 1 - Build And run this yourself. 
Step 2 - enter the IP address of the console you want to import the reaper tiecodes on and press Connect  
Step 3 - if the connection is successful you will be asked to select your cuepoint CSV file to import. Once you have selected the file click Load  
Step 4 - you will see a list of all cue lists recorded in your show, select the one you want and select Import  

