# Useful Codes for ZMK Firmware

Example of issues faced

### Issue 1 - Bluetooth cannot be paired or unsuccessful
You will need to clear bluetooth profile everytime you re-flash with new firmware or u2f. 
Let's say you have paired Profile 1 to desktop, and Profile 2 to Ipad. When you BT Clear, it does not clear all the two profiles you have paired. Meaning, you have to select BT1>BT Clear; and BT2>BT Clear.

|![image](https://user-images.githubusercontent.com/79617315/153982087-a283f771-8bea-47c1-b934-07eadef5324a.png)|
|:--:|
| Step 1: Bluetooth & other devices  > Remove device |

**Note that the first Reviung41 denotes you are connecting to wired Reviung41; the second one with battery and 'paired' is the wireless Reviung* 

Step 2: Select your relative BT, BTclear
Step 3: Remove your cable
Step 4: Select your desired BT profile again

|![image](https://user-images.githubusercontent.com/79617315/153982519-85bf038a-78b3-4723-a204-d3298d592b47.png)|
|:--:|
|Step 5: + Add Bluetooth or other device|

|![image](https://user-images.githubusercontent.com/79617315/153982725-f4f2d95e-78e7-48dc-890a-00c911b7b563.png)|
|:--:|
|Step 6: !!! |


### Issue 2 - Bluetooth disconnects very often
Constant disconnect and bad syncing, credit to FaizMidy

Increase the transmitting power from the nicenano.
Add this to .conf
> CONFIG_BT_CTLR_TX_PWR_PLUS_8=y
