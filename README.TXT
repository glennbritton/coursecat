






a. the text file codes may need updating as courses are added
    659 lines as of 24March2015
    1 line added 12Nov2015  9-EES:UTSCOMPMATH
    16Nov2015  duplicates in graduate section: 9LPR  9NUS  
    16NOV2015  removed duplicates
    16NOV2015  ESS  UTSCOMPMATH replace with ESS  UTSPHYSENVSCI SGS
	
    1-st.george
    3-UTS
    5-UTM
    9-graduate courses
   

1. run campuscourses  script
   you will be prompted for year and term code:
     20159  fall term
     20155  summer term
     20151  winter term

     -campuscourses calls the following scripts:

        campuscodes
        maketermcourses 
        fixgrads

MUST MODIFY THE HARDCODED ENGLISH WORD FOR THE SEASON...Winter, Fall, Summer
in the file named testscriptN

2. run testscriptN
   you will be prompted for year and term code:
     20159  fall term
     20155  summer term
     20151  winter term

grep -v "||" whatever > marco
(marco needs a file omitting the lines with no course catergory.)

AND delete section lables .....look for the word "COURSES" in whatever
