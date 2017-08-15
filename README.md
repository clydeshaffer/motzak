````
                                                                    
     *****   **    **                                      *        
  ******  ***** *****                                    **         
 **   *  *  ***** *****                                  **         
*    *  *   * **  * **                                   **         
    *  *    *     *        ****      ******              **         
   ** **    *     *       * ***  *  ********     ****    **  ***    
   ** **    *     *      *   ****  *      **    * ***  * ** * ***   
   ** **    *     *     **    **          *    *   ****  ***   *    
   ** **    *     *     **    **         *    **    **   **   *     
   ** **    *     **    **    **        ***   **    **   **  *      
   *  **    *     **    **    **         ***  **    **   ** **      
      *     *      **   **    **          *** **    **   ******     
  ****      *      **    ******            ** **    **   **  ***    
 *  *****           **    ****             **  ***** **  **   *** * 
*     **                                   *    ***   **  **   ***  
*                                         *                         
 **                                      *                          
                                        *                           
                                                                    

````

the DOS sound blaster tracker no one asked for

## Keyboard commands:

### All modes

|Key|Action|
|:--|-----:|
|Esc|exit the program (now with confirmation if not saved)|

### Compose mode

|Key|Action|
|:--|-----:|
|numbers 0-9|select channel|
|left/right arrows|change pitch|
|up/down arrows|move cursor backward/forward through song|
|up/down + shift|move cursor one measure at a time|
|space bar| add/remove a note under the cursor|
|V|hold while moving the cursor to select an area|
|Y| "yank" the selection to the clipboard|
|P| paste the contents of the clipboard|
|plus/minus|change duration of placed notes|
|left/right bracket|change tempo by 1 bpm|
|left/right bracket + shift|change tempo by 10 bpm|
|tab|switch to instrument edit mode|
|enter|play/pause song playback|
|shift+enter|play song from start|
|F2|save the song|



### Instrument Edit mode


|Key|Action|
|:--|-----:|
|numbers 0-9|select channel|
|left/right arrows|adjust selected byte by 0x01|
|left/right + shift|adjust selected byte by 0x10|
|up/down arrows|switch between parameters|
|spacebar | play note on current instrument|

Reading Jeffrey S. Lee's [document](http://www.shipbrook.net/jeff/sb.html) on programming the SoundBlaster/AdLib FM chip will be helpful in making sense of Instrument Edit Mode
