/**********************************************************************
 *                                                  
 *  PS4b: StringSound implementation and SFML audio output 
 **********************************************************************/

Name: Michael Chagnon

Hours to complete assignment : 12 hrs

/**********************************************************************
 *  How to run program
 **********************************************************************/
To run the program make first. Then use ./KSGuitarSim to run executable. SFML window will pop up,
use keyboard to plays notes.
 

/**********************************************************************
 *  Did you complete the whole assignment?
 *  Successfully or not? 
 *  Indicate which parts you think are working, and describe
 *    how you know that they're working.
 **********************************************************************/
I was able to implement my StringSound class properly. However, I was unable to implement
KSGuitarSim.cpp in the desired way. Instead I replicated the method used in SSLite.cpp


/**********************************************************************
 *  Did you implement exseptions to check your StringSound 
 *	implementation?
 *  Indicate yes or no, and explain how you did it.
 **********************************************************************/
Yes, I created an excpetion for the constructor that made it so StringSound couldn't
be initilized with a non-positive number for frequency. This is because frequency determines the
size of the CircularBuffer wnd arrays can't be <= 0.


/**********************************************************************
 *  Did your code pass cpplint?
 *  Indicate yes or no, and explain how you did it.
 **********************************************************************/
Yes, I just ran lint on my code and fix the errors accordingly


/**********************************************************************
 *  List whatever help (if any) you received from TAs,
 *  classmates, or anyone else.
 **********************************************************************/
Went to Tutoring and a TA helped me figure out that in my CircularBuffer constructor
the size wasn't created dynamically, so I fixed that

